---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ModuleBitcodeWriterBase` Class

<p>Base class to manage the module bitcode writing, currently subclassed for <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter">ModuleBitcodeWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter">ThinLinkBitcodeWriter</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase">BitcodeWriterBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract class to manage the bitcode writing, subclassed for each bitcode file type. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter">ModuleBitcodeWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage the bitcode writing for a module. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter">ThinLinkBitcodeWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage the bitcode writing for a thin link bitcode file. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75538db633297fb9c0b91ea5a16c5b72">ModuleBitcodeWriterBase</a> (const Module &amp;M, StringTableBuilder &amp;StrtabBuilder, BitstreamWriter &amp;Stream, bool ShouldPreserveUseListOrder, const ModuleSummaryIndex *Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase">ModuleBitcodeWriterBase</a> object for the given <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, writing to the provided <span class="doxyComputerOutput">Buffer</span>. <a href="#a75538db633297fb9c0b91ea5a16c5b72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b12ebb23f57815dfdaa7a14562aa5f">writePerModuleGlobalValueSummary</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the per-module summary section alongside the rest of the module's bitcode. <a href="#ad8b12ebb23f57815dfdaa7a14562aa5f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a8decac21a63b246518180d05d1646">writePerModuleFunctionSummaryRecord</a> (SmallVector&lt; uint64_t, 64 &gt; &amp;NameVals, GlobalValueSummary *Summary, unsigned ValueID, unsigned FSCallsAbbrev, unsigned FSCallsProfileAbbrev, unsigned CallsiteAbbrev, unsigned AllocAbbrev, unsigned ContextIdAbbvId, const Function &amp;F, DenseMap&lt; CallStackId, LinearCallStackId &gt; &amp;CallStackPos, CallStackId &amp;CallStackCount)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e19c6ac1ef16447809aad3812761237">writeModuleLevelReferences</a> (const GlobalVariable &amp;V, SmallVector&lt; uint64_t, 64 &gt; &amp;NameVals, unsigned FSModRefsAbbrev, unsigned FSModVTableRefsAbbrev)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238937e71288a10ee4ce9cd5fecbff50">assignValueId</a> (GlobalValue::GUID ValGUID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a763ac36f8ca200aa7aa9e4a23450d920">getValueId</a> (GlobalValue::GUID ValGUID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea144f2e1e59d658c6bc375c1ebb6db3">getValueId</a> (ValueInfo VI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, unsigned &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac37ccb28c7f65a60cd8d81f613140cb3">valueIds</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bef003929632eb31a4722c4dab0e372">M</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to write to bitcode. <a href="#a8bef003929632eb31a4722c4dab0e372">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valueenumerator">ValueEnumerator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad06babe1d15aa19778741cb5ce634dd7">VE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates ids for all values in the module. <a href="#ad06babe1d15aa19778741cb5ce634dd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa544254679c186f7ec1b8a75c13bc30a">Index</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional per-module index to write for ThinLTO. <a href="#aa544254679c186f7ec1b8a75c13bc30a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86e62ef5b9ef1b72a2e6547a65cf2e30">GUIDToValueIdMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map that holds the correspondence between GUIDs in the summary index, that came from indirect call profiles, and a value id generated by this class to use in the VST and summary block records. <a href="#a86e62ef5b9ef1b72a2e6547a65cf2e30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f7a3f136aadcb92281250f8f2a9b40">GlobalValueId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks the last value id recorded in the GUIDToValueMap. <a href="#aa0f7a3f136aadcb92281250f8f2a9b40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a067e0380d8c4ebb24000dcb4bfe919fd">VSTOffsetPlaceholder</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Saves the offset of the VSTOffset record that must eventually be backpatched with the offset of the actual VST. <a href="#a067e0380d8c4ebb24000dcb4bfe919fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class to manage the module bitcode writing, currently subclassed for <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter">ModuleBitcodeWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter">ThinLinkBitcodeWriter</a>.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ModuleBitcodeWriterBase() {#a75538db633297fb9c0b91ea5a16c5b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::ModuleBitcodeWriterBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrtabBuilder, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream, bool ShouldPreserveUseListOrder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * Index)</td>
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

<p>Constructs a <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase">ModuleBitcodeWriterBase</a> object for the given <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, writing to the provided <span class="doxyComputerOutput">Buffer</span>.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#ad88d45a4534c867c5b0fab73d70f176f">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::BitcodeWriterBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aa0f7a3f136aadcb92281250f8f2a9b40">GlobalValueId</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="#aa544254679c186f7ec1b8a75c13bc30a">Index</a>, <a href="#a8bef003929632eb31a4722c4dab0e372">M</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#a31291fbb3033f9d35b27cc4cd51c90c2">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::Stream</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#a25c3139775b4aef5f6a1cb287f304430">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::StrtabBuilder</a> and <a href="#ad06babe1d15aa19778741cb5ce634dd7">VE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#ab776cf27f2a3afc4627ca879136a9377">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::ModuleBitcodeWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#a22a9b53882754492e326c9b7b2f5f4d5">anonymous{BitcodeWriter.cpp}::ThinLinkBitcodeWriter::ThinLinkBitcodeWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### writePerModuleGlobalValueSummary() {#ad8b12ebb23f57815dfdaa7a14562aa5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the per-module summary section alongside the rest of the module's bitcode.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ac45cef5b964b589fb0741ccc577eaf2c">llvm::BitCodeAbbrevOp::Array</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#ab5fe84ff4ac7b25ec8f7542ad3ad850b">llvm::ModuleSummaryIndex::BitcodeSummaryVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a1871554e8a3734782e7f7a145cc17491">collectMemProfCallStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a8da97c44f514ad1ae9ccf4518b0f88aa">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a86397deb1d9d25f7a17ce22c4d66482f">llvm::mdconst::extract_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672abfdef4054ace82e3ddb8794bc5ca471c">llvm::BitCodeAbbrevOp::Fixed</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a29b16689ea7e5d0827e58cbd386661a1">llvm::GlobalValueSummary::flags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba711d24e5a54cc4b6d0f0f026c6dea25b">llvm::bitc::FS_ALIAS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba52dd969c2b5e24add5ca2516ed0f200d">llvm::bitc::FS_ALLOC_CONTEXT_IDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba18ac0246f06475392afb5a095d7cc887">llvm::bitc::FS_BLOCK_COUNT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba0b88f487f51959e29f9a30be85640735">llvm::bitc::FS_CONTEXT_RADIX_TREE_ARRAY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001bab8c67884cc3a90c02a0a6916d896dd83">llvm::bitc::FS_FLAGS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001bae00c1b00b0336f5f501530553eb51324">llvm::bitc::FS_PERMODULE_ALLOC_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001badeba38c1dfee61f7d2dac12d39046937">llvm::bitc::FS_PERMODULE_CALLSITE_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba7eed6dde835daccb38574b36fb17ba32">llvm::bitc::FS_PERMODULE_GLOBALVAR_INIT_REFS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001bac9d1b09e39f4a5cce9548cdecd7d01fc">llvm::bitc::FS_PERMODULE_PROFILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba40d4866bc945500aef3ea87a8c509f06">llvm::bitc::FS_PERMODULE_RELBF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba5d8354b96ed844da9b633e551c4b9bf7">llvm::bitc::FS_PERMODULE_VTABLE_GLOBALVAR_INIT_REFS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001babeb8f3e136c6d5b652c79eba7d2ac9df">llvm::bitc::FS_STACK_IDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba5d7d125d00b7735770b5376070b7ede6">llvm::bitc::FS_TYPE_ID_METADATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba3950f7c2a51d13d881e4796aec4fcd4d">llvm::bitc::FS_VALUE_GUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001baf03cc9df6c5e873d398960808be1f1db">llvm::bitc::FS_VERSION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933daca3afe4e93910906ab7d0c2e3bd2b90e">llvm::bitc::FULL_LTO_GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a8a4f77790cdf2a3857c91b5547743ea8">getEncodedGVSummaryFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da642102503aff012fc2975f165138b454">llvm::bitc::GLOBALVAL_SUMMARY_BLOCK_ID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa544254679c186f7ec1b8a75c13bc30a">Index</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a8bef003929632eb31a4722c4dab0e372">M</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#a31291fbb3033f9d35b27cc4cd51c90c2">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::Stream</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#a25c3139775b4aef5f6a1cb287f304430">anonymous{BitcodeWriter.cpp}::BitcodeWriterBase::StrtabBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ade2457e8051855ad2911d62202458e20">llvm::BitCodeAbbrevOp::VBR</a>, <a href="#ad06babe1d15aa19778741cb5ce634dd7">VE</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a6ddafba4af9c27c785a0d873fd3cb661">writeMemoryProfileRadixTree</a> and <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a0fcb5b0c8740137c1ba7ea67bc4e1986">writeTypeIdCompatibleVtableSummaryRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#a3ad01919d5d625704d2d69f86d3136b2">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::write</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#a2cf0ff7f0ad397fc8d9799b9e0747b90">anonymous{BitcodeWriter.cpp}::ThinLinkBitcodeWriter::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assignValueId() {#a238937e71288a10ee4ce9cd5fecbff50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::assignValueId (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> ValGUID)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### getValueId() {#a763ac36f8ca200aa7aa9e4a23450d920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::getValueId (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> ValGUID)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### getValueId() {#aea144f2e1e59d658c6bc375c1ebb6db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::getValueId (<a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> VI)</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### valueIds() {#ac37ccb28c7f65a60cd8d81f613140cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt; GlobalValue::GUID, unsigned &gt; &amp; anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::valueIds ()</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeModuleLevelReferences() {#a2e19c6ac1ef16447809aad3812761237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleBitcodeWriterBase::writeModuleLevelReferences (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 64 &gt; &amp; NameVals, unsigned FSModRefsAbbrev, unsigned FSModVTableRefsAbbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### writePerModuleFunctionSummaryRecord() {#af6a8decac21a63b246518180d05d1646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleBitcodeWriterBase::writePerModuleFunctionSummaryRecord (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 64 &gt; &amp; NameVals, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> * Summary, unsigned ValueID, unsigned FSCallsAbbrev, unsigned FSCallsProfileAbbrev, unsigned CallsiteAbbrev, unsigned AllocAbbrev, unsigned ContextIdAbbvId, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a271f954222d61bd5dc7f5cb5dd836b52">LinearCallStackId</a> &gt; &amp; CallStackPos, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a> &amp; CallStackCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### GlobalValueId {#aa0f7a3f136aadcb92281250f8f2a9b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::GlobalValueId</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tracks the last value id recorded in the GUIDToValueMap.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Referenced by <a href="#a75538db633297fb9c0b91ea5a16c5b72">ModuleBitcodeWriterBase</a>.</p>

</div>
</div>

### GUIDToValueIdMap {#a86e62ef5b9ef1b72a2e6547a65cf2e30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;GlobalValue::GUID, unsigned&gt; anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::GUIDToValueIdMap</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map that holds the correspondence between GUIDs in the summary index, that came from indirect call profiles, and a value id generated by this class to use in the VST and summary block records.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### Index {#aa544254679c186f7ec1b8a75c13bc30a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleSummaryIndex* anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::Index</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optional per-module index to write for ThinLTO.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#ab776cf27f2a3afc4627ca879136a9377">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::ModuleBitcodeWriter</a>, <a href="#a75538db633297fb9c0b91ea5a16c5b72">ModuleBitcodeWriterBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#a22a9b53882754492e326c9b7b2f5f4d5">anonymous{BitcodeWriter.cpp}::ThinLinkBitcodeWriter::ThinLinkBitcodeWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#a3ad01919d5d625704d2d69f86d3136b2">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::write</a> and <a href="#ad8b12ebb23f57815dfdaa7a14562aa5f">writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### M {#a8bef003929632eb31a4722c4dab0e372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module&amp; anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::M</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to write to bitcode.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#ab776cf27f2a3afc4627ca879136a9377">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::ModuleBitcodeWriter</a>, <a href="#a75538db633297fb9c0b91ea5a16c5b72">ModuleBitcodeWriterBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#a22a9b53882754492e326c9b7b2f5f4d5">anonymous{BitcodeWriter.cpp}::ThinLinkBitcodeWriter::ThinLinkBitcodeWriter</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#a3ad01919d5d625704d2d69f86d3136b2">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::write</a> and <a href="#ad8b12ebb23f57815dfdaa7a14562aa5f">writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### VE {#ad06babe1d15aa19778741cb5ce634dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueEnumerator anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::VE</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enumerates ids for all values in the module.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Referenced by <a href="#a75538db633297fb9c0b91ea5a16c5b72">ModuleBitcodeWriterBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#a3ad01919d5d625704d2d69f86d3136b2">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::write</a> and <a href="#ad8b12ebb23f57815dfdaa7a14562aa5f">writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### VSTOffsetPlaceholder {#a067e0380d8c4ebb24000dcb4bfe919fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::VSTOffsetPlaceholder = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Saves the offset of the VSTOffset record that must eventually be backpatched with the offset of the actual VST.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
