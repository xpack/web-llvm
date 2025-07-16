---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/raw-string-ostream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `raw_string_ostream` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to an std::string. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::raw_string_ostream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class implements an extremely fast bulk output stream that can <em>only</em> output to a stream. <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1532c60ac358982e83c080469611061">raw_string_ostream</a> (std::string &amp;O)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6732e8d3ff8100a662ce73634840b990">str</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the string's reference. <a href="#a6732e8d3ff8100a662ce73634840b990">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6404e90b84bda345a98539075706232">reserveExtraSpace</a> (uint64_t ExtraSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If possible, pre-allocate <span class="doxyComputerOutput">ExtraSize</span> bytes for stream data. <a href="#ab6404e90b84bda345a98539075706232">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a282d4765fc440ebca83c76bacc45fa74">write_impl</a> (const char *Ptr, size_t Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See raw_ostream::write_impl. <a href="#a282d4765fc440ebca83c76bacc45fa74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3ef122bb6e8fe48d9c33a2a8f9c867">current_pos</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current position within the stream, not counting the bytes currently in the buffer. <a href="#adb3ef122bb6e8fe48d9c33a2a8f9c867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9272421623b84aed6fd21605959a918f">OS</a></td>
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

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to an std::string.</p>


<p>This is a simple adaptor class. This class does not encounter output errors. <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> operates without a buffer, delegating all memory management to the std::string. Thus the std::string is always up-to-date, may be used directly and there is no need to call <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">flush()</a>.</p>


<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### raw\_string\_ostream() {#ac1532c60ac358982e83c080469611061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_string_ostream::raw_string_ostream (std::string &amp; O)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a75860636a752bc2592f6e4185e63efdc">llvm::raw_ostream::SetUnbuffered</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### reserveExtraSpace() {#ab6404e90b84bda345a98539075706232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_string_ostream::reserveExtraSpace (uint64_t ExtraSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If possible, pre-allocate <span class="doxyComputerOutput">ExtraSize</span> bytes for stream data.</p>


<p>i.e. it extends internal buffers to keep additional ExtraSize bytes. So that the stream could keep at least <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">tell()</a> + ExtraSize bytes without re-allocations. <a href="#ab6404e90b84bda345a98539075706232">reserveExtraSpace()</a> does not change the size/data of the stream.</p>


<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>

</div>
</div>

### str() {#a6732e8d3ff8100a662ce73634840b990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string &amp; llvm::raw_string_ostream::str ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the string's reference.</p>


<p>In most cases it is better to simply use the underlying std::string directly. TODO: Consider removing this API.</p>


<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/anonymous-elfobjhandler-cpp-/#addbdfe8987613dd5333f796f9cfcaf6c">llvm::ifs::anonymous{ELFObjHandler.cpp}::appendToError</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#ab42803a7054d1210223d0e72ec575d22">constructTriples</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a6e3f70a5f3d1222550716fb9db632c6a">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a66aa742680260d77ebab20536c828c17">llvm::AMDGPUDisassembler::decodeKernelDescriptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a297d9aa8e26c1d3497ef90fc8ea95be2">emitFakeUse</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#a3ea71f46259463a2379530358a02d372">llvm::AMDGPUTargetAsmStreamer::EmitHSAMetadata</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ad436403de744b37b7517d0a7efd891e3">llvm::remarks::BitstreamRemarkSerializerHelper::emitMetaStrTab</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a3275b7a3457510661d5af13a82bb48ca">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitModuleCommandLines</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#aa6bd85a0e2d2b53c2f59708830ba3c6b">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/dia/diasession-cpp/#a07bfb89b80e6e5f6236d958d2b463d2a">ErrorFromHResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae591509c81d00090bde300a897e12d82">llvm::formatCallSiteLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/irchangedprinter/#ab0ea023a570b1c06ae878cfef19ef84d">llvm::IRChangedPrinter::generateIRRepresentation</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#abcfc043f77cf8dca5b9a3eebc653621f">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#a8250331613b40f4b0045323c5c3aaecd">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a6cca267d184aa0f88f69f9423e2bd573">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::getAsStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a99e318973960e60410de509ea46c00bc">llvm::memprof::anonymous{MemProfReader.cpp}::getBuildIdString</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendata-cpp/#a2467dd4bd3f2da739d104b355ed6d362">getCGDataErrString</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp/#ae85542bd8c97b8543e8c41db037340cf">getInstrProfErrString</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-6d84867e0ca5367d344863bb152df797/#a51fde136cfecc90dfede7499db803192">llvm::DOTGraphTraits&lt; MachineGadgetGraph * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#a6e3d7579887f71bf2b4cf7def5a3d77b">llvm::logicalview::LVDWARFReader::getRegisterName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a6c8fb36f87b49a215040e2943af69e99">getSignature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a5b3a962dc6532bf208fdccf1055119f0">getTypeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp/#af31297e70271da82249db4e0d3ccdd66">getTypeString</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gaf98e23b38443db6fa6876aababd108a5">LLVMGetSymbolAddress</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gace82127e9d25bb0a018ea2d621fda00a">LLVMGetSymbolName</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gab7faf1f46a7fb022e21e792e0250709d">LLVMMoveToContainingSection</a>, <a href="/web-llvm/docs/api/groups/llvmcanalysis/#ga5645aec2d95116c0432a676db77b2cb0">LLVMVerifyModule</a>, <a href="/web-llvm/docs/api/groups/llvmcbitwriter/#ga43cccd6ab4fe5c042fc59d972430c97f">LLVMWriteBitcodeToMemoryBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#ae09841830258172ba68866f0376898eb">llvm::LockFileManager::LockFileManager</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a46543fe277b38905b31e0d2ec607abf5">llvm::object::makeDuplicateResourceError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a118561073f002f6ae486efadc46e04d3">llvm::object::makeDuplicateResourceError</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/cgdataostream/#a1d951f57be86b30e864740019b41f0f2">llvm::CGDataOStream::patch</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#a52299b07451a31e9fc5a62e305d5fe21">llvm::ProfOStream::patch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a5bd11f377f141eaca592b06fff653370">printBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a60061d374eb7273d11025f881472a4d8">printExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4f1b2d2935f76d035678dfafa7d458b3">llvm::AsmPrinter::PrintSpecial</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#adf508d7280c5a6d9fb7d0e2cf2f426c4">printZeroExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a6132fb3423ce0d8846f93102d9658bc4">printZeroUpperMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#a54f0a58c66ed5816ddf1c3f461f6b9c7">raise_relocation_error</a>, <a href="/web-llvm/docs/api/classes/false/chain/#ad3bc2dfe7381ebca7db8684a3857dc70">false::Chain::str</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a098fa2a14ccb2f871b1c97c2080c3e84">stringify</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid/#ae9ec355054ee6400df6ba242dd3cb032">llvm::AMDGPU::IsaInfo::AMDGPUTargetID::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/docnode/#ab9126e4f825db5a1bb881098b9159279">llvm::msgpack::DocNode::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#a407dbc4127c54c6a0482293b115fac89">llvm::RISCVISAInfo::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#ab08f2a767eab0b5eb8db953d35d80b03">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::verify</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a901080a7f2755abf0fc90c2d0d9da87f">llvm::dwarf_linker::parallel::DWARFLinkerImpl::verifyInput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### current\_pos() {#adb3ef122bb6e8fe48d9c33a2a8f9c867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::raw_string_ostream::current_pos ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the current position within the stream, not counting the bytes currently in the buffer.</p>

<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### write\_impl() {#a282d4765fc440ebca83c76bacc45fa74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_string_ostream::write_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See raw_ostream::write_impl.</p>

<p>Declaration at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OS {#a9272421623b84aed6fd21605959a918f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string&amp; llvm::raw_string_ostream::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
