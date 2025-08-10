---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-trace-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{Trace.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{Trace.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12a9d7c65de7b4e040ca540157bf373">loadNaiveFormatLog</a> (StringRef Data, bool IsLittleEndian, XRayFileHeader &amp;FileHeader, std::vector&lt; XRayRecord &gt; &amp;Records)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4f89ac434c992939934e78f19cd33e">loadFDRLog</a> (StringRef Data, bool IsLittleEndian, XRayFileHeader &amp;FileHeader, std::vector&lt; XRayRecord &gt; &amp;Records)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reads a log in FDR mode for version 1 of this binary format. <a href="#a6b4f89ac434c992939934e78f19cd33e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7782cd0e983ec47c2ebde56b05575ecb">loadYAMLLog</a> (StringRef Data, XRayFileHeader &amp;FileHeader, std::vector&lt; XRayRecord &gt; &amp;Records)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### loadFDRLog() {#a6b4f89ac434c992939934e78f19cd33e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{Trace.cpp}::loadFDRLog (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, bool IsLittleEndian, <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader">XRayFileHeader</a> &amp; FileHeader, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/xray/xrayrecord">XRayRecord</a> &gt; &amp; Records)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reads a log in FDR mode for version 1 of this binary format.</p>


<p>FDR mode is defined as part of the compiler-rt project in xray_fdr_logging.h, and such a log consists of the familiar 32 bit XRayHeader, followed by sequences of of interspersed 16 byte <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Records and 8 byte <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Records.</p>


<p>The following is an attempt to document the grammar of the format, which is parsed by this function for little-endian machines. Since the format makes use of BitFields, when we support big-endian architectures, we will need to adjust not only the endianness parameter to llvm's RecordExtractor, but also the bit twiddling logic, which is consistent with the little-endian convention that BitFields within a struct will first be packed into the least significant bits the address they belong to.</p>


<p>We expect a format complying with the grammar in the following pseudo-EBNF in Version 1 of the FDR log.</p>


<p>FDRLog: <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader">XRayFileHeader</a> ThreadBuffer* <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader">XRayFileHeader</a>: 32 bytes to identify the log as FDR with machine metadata. Includes BufferSize ThreadBuffer: NewBuffer WallClockTime NewCPUId FunctionSequence EOB BufSize: 8 byte unsigned integer indicating how large the buffer is. NewBuffer: 16 byte metadata record with Thread Id. WallClockTime: 16 byte metadata record with human readable time. Pid: 16 byte metadata record with Pid NewCPUId: 16 byte metadata record with CPUId and a 64 bit TSC reading. EOB: 16 byte record in a thread buffer plus mem garbage to fill BufSize. FunctionSequence: NewCPUId | TSCWrap | <a href="/web-llvm/docs/api/classes/llvm/xray/functionrecord">FunctionRecord</a> TSCWrap: 16 byte metadata record with a full 64 bit TSC reading. <a href="/web-llvm/docs/api/classes/llvm/xray/functionrecord">FunctionRecord</a>: 8 byte record with <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, entry/exit, and TSC delta.</p>


<p>In Version 2, we make the following changes:</p>


<p>ThreadBuffer: <a href="/web-llvm/docs/api/classes/llvm/xray/bufferextents">BufferExtents</a> NewBuffer WallClockTime NewCPUId FunctionSequence <a href="/web-llvm/docs/api/classes/llvm/xray/bufferextents">BufferExtents</a>: 16 byte metdata record describing how many usable bytes are in the buffer. This is measured from the start of the buffer and must always be at least 48 (bytes).</p>


<p>In Version 3, we make the following changes:</p>


<p>ThreadBuffer: <a href="/web-llvm/docs/api/classes/llvm/xray/bufferextents">BufferExtents</a> NewBuffer WallClockTime Pid NewCPUId FunctionSequence EOB: <em>deprecated</em></p>


<p>In Version 4, we make the following changes:</p>


<p><a href="/web-llvm/docs/api/classes/llvm/xray/customeventrecord">CustomEventRecord</a> now includes the CPU data.</p>


<p>In Version 5, we make the following changes:</p>


<p><a href="/web-llvm/docs/api/classes/llvm/xray/customeventrecord">CustomEventRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/xray/typedeventrecord">TypedEventRecord</a> now use TSC delta encoding similar to what <a href="/web-llvm/docs/api/classes/llvm/xray/functionrecord">FunctionRecord</a> instances use, and we no longer need to include the CPU id in the <a href="/web-llvm/docs/api/classes/llvm/xray/customeventrecord">CustomEventRecord</a>.</p>


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/trace-cpp">Trace.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/blockindexer/#a6b7ee8c19837fb7c4c10a3bdf9d8667f">llvm::xray::BlockIndexer::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/traceexpander/#adcb69ec17bb48e6c745866009f2829e5">llvm::xray::TraceExpander::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad7e3a2f9134fa59a38cc0a86acaaf351">llvm::DataExtractor::isValidOffsetForDataOfSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#ae91b89e3dbb8e36d143a6efcc4d5d85a">Verifier</a> and <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader/#acc34b30bb2aa2eb255188095f98c755f">llvm::xray::XRayFileHeader::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a170f5d8b013bd6c97daa83c36c7b4c82">llvm::xray::loadTrace</a>.</p>

</div>
</div>

### loadNaiveFormatLog() {#ab12a9d7c65de7b4e040ca540157bf373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{Trace.cpp}::loadNaiveFormatLog (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, bool IsLittleEndian, <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader">XRayFileHeader</a> &amp; FileHeader, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/xray/xrayrecord">XRayRecord</a> &gt; &amp; Records)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/trace-cpp">Trace.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a97b00c8e300bcf67f4473baf957f1892a331b3100a485d8cacff1d3df8e9b0c13">llvm::xray::ENTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a97b00c8e300bcf67f4473baf957f1892a88c8a800b3fe4ea6c2fc2524f7ee2645">llvm::xray::ENTER_ARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a97b00c8e300bcf67f4473baf957f1892aa42b2fb0e720a080e79a92f4ca97d927">llvm::xray::EXIT</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a5cc53bb122d7af1e40b77867d080114d">llvm::DataExtractor::getSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a98923ce73981e5171ef246bdcc6fde60">llvm::DataExtractor::getU16</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a0eb55ea3f585f9c8a2619fe7250e56f4">llvm::DataExtractor::getU32</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ac7c91465e0d075f5fc1bdc895c8a5f07">llvm::DataExtractor::getU64</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a45ee696c4102751e0194a0210c07dac0">llvm::DataExtractor::getU8</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad6c780b958be0ededd6a525ce67206bb">llvm::DataExtractor::isValidOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad7e3a2f9134fa59a38cc0a86acaaf351">llvm::DataExtractor::isValidOffsetForDataOfSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a13f08bc0715c6ccbe15c82f2fc9e61ca">llvm::DataExtractor::size</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a97b00c8e300bcf67f4473baf957f1892af1f3009e38d66163f03975af148bb8fa">llvm::xray::TAIL_EXIT</a> and <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader/#acc34b30bb2aa2eb255188095f98c755f">llvm::xray::XRayFileHeader::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a170f5d8b013bd6c97daa83c36c7b4c82">llvm::xray::loadTrace</a>.</p>

</div>
</div>

### loadYAMLLog() {#a7782cd0e983ec47c2ebde56b05575ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{Trace.cpp}::loadYAMLLog (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader">XRayFileHeader</a> &amp; FileHeader, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/xray/xrayrecord">XRayRecord</a> &gt; &amp; Records)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/trace-cpp">Trace.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/trace/#a34c57d0fd50b64f970f9682a03cbcb8f">llvm::Trace::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader/#a1a8d6c9691e5b509b0eac7c88653ab35">llvm::xray::XRayFileHeader::ConstantTSC</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader/#a339e015c9be8d198e2920293112f2d9a">llvm::xray::XRayFileHeader::CycleFrequency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/trace/#abf32f4a825e8b5433eb3403925620b4d">llvm::Trace::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader/#ab54f9934a050863d45df8afeb1822faa">llvm::xray::XRayFileHeader::NonstopTSC</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader/#a2278020c11cb76aed417e370aafd4469">llvm::xray::XRayFileHeader::Type</a> and <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader/#acc34b30bb2aa2eb255188095f98c755f">llvm::xray::XRayFileHeader::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a170f5d8b013bd6c97daa83c36c7b4c82">llvm::xray::loadTrace</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/xray/trace-cpp">Trace.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
