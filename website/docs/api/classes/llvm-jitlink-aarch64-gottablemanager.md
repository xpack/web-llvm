---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/aarch64/gottablemanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GOTTableManager` Class

<p>Global Offset Table Builder. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::aarch64::GOTTableManager { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec47232ce52399a1c1ccfb402102d3b">GOTTableManager</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e4d2cd843e5d5ee929ca4de9e8fb63">visitEdge</a> (LinkGraph &amp;G, Block *B, Edge &amp;E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f864b0c47abab716508e5683d3e82a">createEntry</a> (LinkGraph &amp;G, Symbol &amp;Target)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af645fbd5c4995e38e9fabc580ee99dfe">getGOTSection</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912826b93fe0e445adcd7343c684fcf7">registerExistingEntries</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67131189a73eab3084c597efb3dd1183">GOTSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe47786c96f8d84c7de1c705fd587cf">getSectionName</a> ()</td>
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

<p>Global Offset Table Builder.</p>

<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GOTTableManager() {#a3ec47232ce52399a1c1ccfb402102d3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::aarch64::GOTTableManager::GOTTableManager (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#afbe47786c96f8d84c7de1c705fd587cf">getSectionName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createEntry() {#a59f864b0c47abab716508e5683d3e82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::aarch64::GOTTableManager::createEntry (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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



<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#ab246c2fa3507148bda940a4f0f680f68">llvm::jitlink::aarch64::createAnonymousPointer</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>

</div>
</div>

### visitEdge() {#ae9e4d2cd843e5d5ee929ca4de9e8fb63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch64::GOTTableManager::visitEdge (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> * B, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043a8d7dc75674b3fc58ba929cbef0217e4b">llvm::jitlink::aarch64::Delta32</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager/#aa7e3f0047da154572ebef76ceee273d3">llvm::jitlink::TableManager&lt; GOTTableManager &gt;::getEntryForTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043ab6bafbc8841c3ff8d19e709ef4b71609">llvm::jitlink::aarch64::GotPageOffset15</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#aa21629cef4aed37ffc47ef8681c46a99a5ac566a913119de4e29b016756ce6e9f">llvm::jitlink::Edge::Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043a69369335041eac416a42ce8fd039d38e">llvm::jitlink::aarch64::Page21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043af73aef9a424551ef1049e0bcb3e71ac1">llvm::jitlink::aarch64::PageOffset12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043ae6ed0aefe60a60c482de8fde088bba9b">llvm::jitlink::aarch64::RequestGOTAndTransformToDelta32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043acdbf75e478b336cc041c86d8c4ec2a81">llvm::jitlink::aarch64::RequestGOTAndTransformToPage21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043ad9a0f2806d0a2a90cd99edc0e54caf10">llvm::jitlink::aarch64::RequestGOTAndTransformToPageOffset12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043a10e93e2b017fdd1a792986be9fec69f4">llvm::jitlink::aarch64::RequestGOTAndTransformToPageOffset15</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043ab08a3e147eb8472939a6ee86abecbdd5">llvm::jitlink::aarch64::RequestTLVPAndTransformToPage21</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043a5c427ef98778eb60400f10d3d9cdccfd">llvm::jitlink::aarch64::RequestTLVPAndTransformToPageOffset12</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getGOTSection() {#af645fbd5c4995e38e9fabc580ee99dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section &amp; llvm::jitlink::aarch64::GOTTableManager::getGOTSection (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>

</div>
</div>

### registerExistingEntries() {#a912826b93fe0e445adcd7343c684fcf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::aarch64::GOTTableManager::registerExistingEntries ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch64-cpp">aarch64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GOTSection {#a67131189a73eab3084c597efb3dd1183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Section* llvm::jitlink::aarch64::GOTTableManager::GOTSection = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getSectionName() {#afbe47786c96f8d84c7de1c705fd587cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::jitlink::aarch64::GOTTableManager::getSectionName ()</td>
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



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch64-h">aarch64.h</a>.</p>


<p>Referenced by <a href="#a3ec47232ce52399a1c1ccfb402102d3b">GOTTableManager</a>.</p>

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
