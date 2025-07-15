---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-perfsupportplugin-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{PerfSupportPlugin.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{PerfSupportPlugin.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f7e0099c6134ab100f80300b710e41">createX64EHFrameHeader</a> (Section &amp;EHFrame, llvm::endianness endianness, bool absolute)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeloadrecord">PerfJITCodeLoadRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d41cae6559f87a6e26f2db6c30f24d">getCodeLoadRecord</a> (const Symbol &amp;Sym, std::atomic&lt; uint64_t &gt; &amp;CodeIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitdebuginforecord">PerfJITDebugInfoRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac931ae3a09278d920ebb024da87edf2e">getDebugInfoRecord</a> (const Symbol &amp;Sym, DWARFContext &amp;DC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord">PerfJITCodeUnwindingInfoRecord</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68574bf3a1f3cabcb89adaf75a2e51b3">getUnwindingRecord</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitrecordbatch">PerfJITRecordBatch</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55e3f6a5c003de75eabd889a24709857">getRecords</a> (ExecutionSession &amp;ES, LinkGraph &amp;G, std::atomic&lt; uint64_t &gt; &amp;CodeIndex, bool EmitDebugInfo, bool EmitUnwindInfo)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9be268f91eb48f7ea90632838a0afb1">RegisterPerfStartSymbolName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937eb14957f5735e32eaa7cb854e994c">RegisterPerfEndSymbolName</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa9c8f4d6b70fbff649debfea585968">RegisterPerfImplSymbolName</a> = ...</td>
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

### createX64EHFrameHeader() {#a16f7e0099c6134ab100f80300b710e41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; anonymous{PerfSupportPlugin.cpp}::createX64EHFrameHeader (<a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; EHFrame, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> endianness, bool absolute)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/perfsupportplugin-cpp">PerfSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab8bb265a153372d87860f6a33d858f3e">llvm::dwarf::DW_EH_PE_absptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a0e91cc214494d9c9f9c8adcf03be6e51">llvm::dwarf::DW_EH_PE_datarel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255af88641d07cb5fdb688ad0d4e78314222">llvm::dwarf::DW_EH_PE_omit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a68bcc7d64ea60cf76503e913360e0b01">llvm::dwarf::DW_EH_PE_sdata4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab4f228eae8e91cb5eb218c4372d2cd75">llvm::dwarf::DW_EH_PE_sdata8</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/sectionrange/#ab7bd439fefcb561d029d76b2ca9bc500">llvm::jitlink::SectionRange::getStart</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamwriter/#a344647bc1c4a4b53334296eba145d408">llvm::BinaryStreamWriter::writeInteger</a>.</p>


<p>Referenced by <a href="#a68574bf3a1f3cabcb89adaf75a2e51b3">getUnwindingRecord</a>.</p>

</div>
</div>

### getCodeLoadRecord() {#ac0d41cae6559f87a6e26f2db6c30f24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerfJITCodeLoadRecord anonymous{PerfSupportPlugin.cpp}::getCodeLoadRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Sym, std::atomic&lt; uint64_t &gt; &amp; CodeIndex)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/perfsupportplugin-cpp">PerfSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a37941163af977712e6ae68591327a0ad">llvm::jitlink::Symbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#ab790ccf24d158f2933ef1c6cf153fb62">llvm::jitlink::Symbol::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a5e084b9b417ae456b128ee1f6506b41d">llvm::Record::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a58aef37a030d9c1e56eaa6ee5bef47a4a7cc9e41b90a35d5cb26e9fbb0cd0a8b0">llvm::orc::JIT_CODE_LOAD</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a55e3f6a5c003de75eabd889a24709857">getRecords</a>.</p>

</div>
</div>

### getDebugInfoRecord() {#ac931ae3a09278d920ebb024da87edf2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; PerfJITDebugInfoRecord &gt; anonymous{PerfSupportPlugin.cpp}::getDebugInfoRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Sym, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; DC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/perfsupportplugin-cpp">PerfSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3a7e2c85add6bbb98ae5b91471b11fd9a2">llvm::DILineInfoSpecifier::AbsoluteFilePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a55f204d9568a58fbc54ad04343452904">llvm::DWARFContext::getLineInfoForAddressRange</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a37941163af977712e6ae68591327a0ad">llvm::jitlink::Symbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section/#a46c35148a73ab51b69108948f0361d52">llvm::jitlink::Section::getOrdinal</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a99c40db3f91fad3db60ba33e9fe93977">llvm::jitlink::Symbol::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#ab790ccf24d158f2933ef1c6cf153fb62">llvm::jitlink::Symbol::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a5e084b9b417ae456b128ee1f6506b41d">llvm::Record::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a58aef37a030d9c1e56eaa6ee5bef47a4ae494e6a50a57d80f1dfad853e3c7cee9">llvm::orc::JIT_CODE_DEBUG_INFO</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a55e3f6a5c003de75eabd889a24709857">getRecords</a>.</p>

</div>
</div>

### getRecords() {#a55e3f6a5c003de75eabd889a24709857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerfJITRecordBatch anonymous{PerfSupportPlugin.cpp}::getRecords (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, std::atomic&lt; uint64_t &gt; &amp; CodeIndex, bool EmitDebugInfo, bool EmitUnwindInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/perfsupportplugin-cpp">PerfSupportPlugin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitrecordbatch/#aed5c2092464488662d58242c310db140">llvm::orc::PerfJITRecordBatch::CodeLoadRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a9ecb3cb1036963ce01100bfddac5791f">llvm::orc::createDWARFContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitrecordbatch/#a55770d4a7181cf614f005f4fb62a2e62">llvm::orc::PerfJITRecordBatch::DebugInfoRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#ac0d41cae6559f87a6e26f2db6c30f24d">getCodeLoadRecord</a>, <a href="#ac931ae3a09278d920ebb024da87edf2e">getDebugInfoRecord</a>, <a href="#a68574bf3a1f3cabcb89adaf75a2e51b3">getUnwindingRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitcodeunwindinginforecord/#af2e7b4e4f8057abfa680eaaece56a449">llvm::orc::PerfJITCodeUnwindingInfoRecord::Prefix</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a1c47ed6ddfb6770f1a432af1c9acdc44">llvm::orc::ExecutionSession::reportError</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitrecordprefix/#a04ad3002e4d48b2dfdb8c830cce5d0fb">llvm::orc::PerfJITRecordPrefix::TotalSize</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/perfjitrecordbatch/#a8cff396945130f0d41bcca7bd88bc513">llvm::orc::PerfJITRecordBatch::UnwindingRecord</a>.</p>

</div>
</div>

### getUnwindingRecord() {#a68574bf3a1f3cabcb89adaf75a2e51b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; PerfJITCodeUnwindingInfoRecord &gt; anonymous{PerfSupportPlugin.cpp}::getUnwindingRecord (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/perfsupportplugin-cpp">PerfSupportPlugin.cpp</a>.</p>


<p>References <a href="#a16f7e0099c6134ab100f80300b710e41">createX64EHFrameHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a5e084b9b417ae456b128ee1f6506b41d">llvm::Record::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a58aef37a030d9c1e56eaa6ee5bef47a4abf17deed25fa2105a9053029e46aa615">llvm::orc::JIT_CODE_UNWINDING_INFO</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="#a55e3f6a5c003de75eabd889a24709857">getRecords</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### RegisterPerfEndSymbolName {#a937eb14957f5735e32eaa7cb854e994c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{PerfSupportPlugin.cpp}::RegisterPerfEndSymbolName</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm_orc_registerJITLoaderPerfEnd"
</div>
</dd>
</dl>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/perfsupportplugin-cpp">PerfSupportPlugin.cpp</a>.</p>

</div>
</div>

### RegisterPerfImplSymbolName {#a5fa9c8f4d6b70fbff649debfea585968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{PerfSupportPlugin.cpp}::RegisterPerfImplSymbolName</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm_orc_registerJITLoaderPerfImpl"
</div>
</dd>
</dl>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/perfsupportplugin-cpp">PerfSupportPlugin.cpp</a>.</p>

</div>
</div>

### RegisterPerfStartSymbolName {#ac9be268f91eb48f7ea90632838a0afb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{PerfSupportPlugin.cpp}::RegisterPerfStartSymbolName</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    "llvm_orc_registerJITLoaderPerfStart"
</div>
</dd>
</dl>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/perfsupportplugin-cpp">PerfSupportPlugin.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/debugging/perfsupportplugin-cpp">PerfSupportPlugin.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
