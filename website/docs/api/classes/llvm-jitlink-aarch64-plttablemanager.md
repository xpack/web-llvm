---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/aarch64/plttablemanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PLTTableManager` Class

<p>Procedure <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> Table Builder. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::aarch64::PLTTableManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">llvm/ExecutionEngine/JITLink/aarch64.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager">TableManager&lt;TableManagerImplT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP base for tables that are built on demand, e.g. <a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a503eb986072430b75795af01d53da049">PLTTableManager</a> (LinkGraph &amp;G, GOTTableManager &amp;GOT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d6737c0b7f6e8d47539355cb58a5afc">visitEdge</a> (LinkGraph &amp;G, Block *B, Edge &amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa15da2c9de13f9495f443216bcbd8991">createEntry</a> (LinkGraph &amp;G, Symbol &amp;Target)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24e7db7f75290f1fc7938cd2a3e21bf">getStubsSection</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab972ff81b88020277c87ce2ee74401a8">registerExistingEntries</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch64/gottablemanager">GOTTableManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52862e323d369cac7a1ca5a2296fda56">GOT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc6e87693a33de7c296acec16d746f8a">StubsSection</a> = nullptr</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de8894d87bd248ac39fec4ecc5d64df">getSectionName</a> ()</td>
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

<p>Procedure <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> Table Builder.</p>

<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PLTTableManager() {#a503eb986072430b75795af01d53da049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::aarch64::PLTTableManager::PLTTableManager (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch64/gottablemanager">GOTTableManager</a> &amp; GOT)</td>
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



<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a0de8894d87bd248ac39fec4ecc5d64df">getSectionName</a>, <a href="#a52862e323d369cac7a1ca5a2296fda56">GOT</a>, <a href="#ab972ff81b88020277c87ce2ee74401a8">registerExistingEntries</a> and <a href="#adc6e87693a33de7c296acec16d746f8a">StubsSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createEntry() {#aa15da2c9de13f9495f443216bcbd8991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::aarch64::PLTTableManager::createEntry (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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



<p>Definition at line 884 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#afea59b722159d204506a5a02667bdfe8">llvm::jitlink::aarch64::createAnonymousPointerJumpStub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#af24e7db7f75290f1fc7938cd2a3e21bf">getStubsSection</a> and <a href="#a52862e323d369cac7a1ca5a2296fda56">GOT</a>.</p>

</div>
</div>

### getStubsSection() {#af24e7db7f75290f1fc7938cd2a3e21bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section &amp; llvm::jitlink::aarch64::PLTTableManager::getStubsSection (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a953feeff1e20f40677fb7f77c073b3be">llvm::orc::Exec</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a0de8894d87bd248ac39fec4ecc5d64df">getSectionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2fbb59fad28934f72ede7ddc316dfc89a7a1a5f3e79fdc91edf2f5ead9d66abb4">llvm::orc::Read</a> and <a href="#adc6e87693a33de7c296acec16d746f8a">StubsSection</a>.</p>


<p>Referenced by <a href="#aa15da2c9de13f9495f443216bcbd8991">createEntry</a>.</p>

</div>
</div>

### registerExistingEntries() {#ab972ff81b88020277c87ce2ee74401a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::aarch64::PLTTableManager::registerExistingEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager/#ace7f4ad413507742c3a483f951e357cf">llvm::jitlink::TableManager&lt; PLTTableManager &gt;::registerPreExistingEntry</a> and <a href="#adc6e87693a33de7c296acec16d746f8a">StubsSection</a>.</p>


<p>Referenced by <a href="#a503eb986072430b75795af01d53da049">PLTTableManager</a>.</p>

</div>
</div>

### visitEdge() {#a8d6737c0b7f6e8d47539355cb58a5afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch64::PLTTableManager::visitEdge (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> * B, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043a71c601f1339f93bc2c5fea1e3a225985">llvm::jitlink::aarch64::Branch26PCRel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager/#aa7e3f0047da154572ebef76ceee273d3">llvm::jitlink::TableManager&lt; PLTTableManager &gt;::getEntryForTarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### GOT {#a52862e323d369cac7a1ca5a2296fda56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GOTTableManager&amp; llvm::jitlink::aarch64::PLTTableManager::GOT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#aa15da2c9de13f9495f443216bcbd8991">createEntry</a> and <a href="#a503eb986072430b75795af01d53da049">PLTTableManager</a>.</p>

</div>
</div>

### StubsSection {#adc6e87693a33de7c296acec16d746f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section* llvm::jitlink::aarch64::PLTTableManager::StubsSection = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#af24e7db7f75290f1fc7938cd2a3e21bf">getStubsSection</a>, <a href="#a503eb986072430b75795af01d53da049">PLTTableManager</a> and <a href="#ab972ff81b88020277c87ce2ee74401a8">registerExistingEntries</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getSectionName() {#a0de8894d87bd248ac39fec4ecc5d64df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::jitlink::aarch64::PLTTableManager::getSectionName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#af24e7db7f75290f1fc7938cd2a3e21bf">getStubsSection</a> and <a href="#a503eb986072430b75795af01d53da049">PLTTableManager</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
