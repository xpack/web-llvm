---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dotgraphtraits-98588480f432ad6b5e85a9f166846cbf
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DOTGraphTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
struct llvm::DOTGraphTraits&lt;MachineBlockFrequencyInfo *&gt; { ... }
</div>

## Base structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits">DefaultDOTGraphTraits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits">DefaultDOTGraphTraits</a> - This class provides the default implementations of all of the <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits">DOTGraphTraits</a> methods. <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase">BFIDOTGraphTraitsBase&lt;BlockFrequencyInfoT, BranchProbabilityInfoT&gt;</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b7e1fb61c18343612e21a0b0d718c1e">DOTGraphTraits</a> (bool isSimple=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56d02d80b27a2c753565bf7da9ae566">getNodeLabel</a> (const MachineBasicBlock *Node, const MachineBlockFrequencyInfo *Graph)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a934f1ea7fb1cb2c5e560f4f889bacfa1">getNodeAttributes</a> (const MachineBasicBlock *Node, const MachineBlockFrequencyInfo *Graph)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4682aefa53640aef6e5282a0c9a24b">getEdgeAttributes</a> (const MachineBasicBlock *Node, EdgeIter EI, const MachineBlockFrequencyInfo *MBFI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b71ece81825a64fb2e43119677f71f">CurFunc</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab370c09ed64dc024bffc107b89e48e6d">LayoutOrderMap</a></td>
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


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DOTGraphTraits() {#a7b7e1fb61c18343612e21a0b0d718c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DOTGraphTraits&lt; MachineBlockFrequencyInfo * &gt;::DOTGraphTraits (bool isSimple=false)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#ae8629cdc360910256304238ca5db1a45">llvm::DefaultDOTGraphTraits::isSimple</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEdgeAttributes() {#a0f4682aefa53640aef6e5282a0c9a24b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; MachineBlockFrequencyInfo * &gt;::getEdgeAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Node, <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#a6899d11b3abe21eebd9130ff4b30b6a4">EdgeIter</a> EI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> * MBFI)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#ac3fd4c945029b6ece24a347676056f86">llvm::BFIDOTGraphTraitsBase&lt; MachineBlockFrequencyInfo, MachineBranchProbabilityInfo &gt;::getEdgeAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo/#a6c773188891ca194070345ab04799109">llvm::MachineBlockFrequencyInfo::getMBPI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a48f48d64f6377621c4154440165c087f">llvm::ViewHotFreqPercent</a>.</p>

</div>
</div>

### getNodeAttributes() {#a934f1ea7fb1cb2c5e560f4f889bacfa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; MachineBlockFrequencyInfo * &gt;::getNodeAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> * Graph)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#a1c78d4d6544b97f0fb4219ec8a99c54b">llvm::BFIDOTGraphTraitsBase&lt; MachineBlockFrequencyInfo, MachineBranchProbabilityInfo &gt;::getNodeAttributes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a48f48d64f6377621c4154440165c087f">llvm::ViewHotFreqPercent</a>.</p>

</div>
</div>

### getNodeLabel() {#ae56d02d80b27a2c753565bf7da9ae566}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; MachineBlockFrequencyInfo * &gt;::getNodeLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> * Graph)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="#aa8b71ece81825a64fb2e43119677f71f">CurFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10bea33dd12f792987bcd7a4252a7446">llvm::getGVDT</a>, <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#a9684914352e5ac4e24c9d5d1f6002862">llvm::BFIDOTGraphTraitsBase&lt; MachineBlockFrequencyInfo, MachineBranchProbabilityInfo &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3ca9742688618517cc4690fb947fb609">isSimple</a> and <a href="#ab370c09ed64dc024bffc107b89e48e6d">LayoutOrderMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurFunc {#aa8b71ece81825a64fb2e43119677f71f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction* llvm::DOTGraphTraits&lt; MachineBlockFrequencyInfo * &gt;::CurFunc = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="#ae56d02d80b27a2c753565bf7da9ae566">getNodeLabel</a>.</p>

</div>
</div>

### LayoutOrderMap {#ab370c09ed64dc024bffc107b89e48e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineBasicBlock *, int&gt; llvm::DOTGraphTraits&lt; MachineBlockFrequencyInfo * &gt;::LayoutOrderMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a>.</p>


<p>Referenced by <a href="#ae56d02d80b27a2c753565bf7da9ae566">getNodeLabel</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockfrequencyinfo-cpp">MachineBlockFrequencyInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
