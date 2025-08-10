---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dotgraphtraits-41d1cb9c371ec31b99ac20773a2bc6fb
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
struct llvm::DOTGraphTraits&lt;BlockFrequencyInfo *&gt; { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f50393d84c80146cddcdef76439033">DOTGraphTraits</a> (bool isSimple=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa43be9b92de2ac1de389d8c7adc995f9">getNodeLabel</a> (const BasicBlock *Node, const BlockFrequencyInfo *Graph)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dec2aede5f760703a48fd93841d4b38">getNodeAttributes</a> (const BasicBlock *Node, const BlockFrequencyInfo *Graph)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dbf58a0744a235cbe747d9bf064967a">getEdgeAttributes</a> (const BasicBlock *Node, EdgeIter EI, const BlockFrequencyInfo *BFI)</td>
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


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DOTGraphTraits() {#a28f50393d84c80146cddcdef76439033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DOTGraphTraits&lt; BlockFrequencyInfo * &gt;::DOTGraphTraits (bool isSimple=false)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/defaultdotgraphtraits/#ae8629cdc360910256304238ca5db1a45">llvm::DefaultDOTGraphTraits::isSimple</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEdgeAttributes() {#a7dbf58a0744a235cbe747d9bf064967a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; BlockFrequencyInfo * &gt;::getEdgeAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#a6899d11b3abe21eebd9130ff4b30b6a4">EdgeIter</a> EI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#ac3fd4c945029b6ece24a347676056f86">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getEdgeAttributes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a48f48d64f6377621c4154440165c087f">llvm::ViewHotFreqPercent</a>.</p>

</div>
</div>

### getNodeAttributes() {#a1dec2aede5f760703a48fd93841d4b38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; BlockFrequencyInfo * &gt;::getNodeAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * Graph)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#a1c78d4d6544b97f0fb4219ec8a99c54b">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getNodeAttributes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a48f48d64f6377621c4154440165c087f">llvm::ViewHotFreqPercent</a>.</p>

</div>
</div>

### getNodeLabel() {#aa43be9b92de2ac1de389d8c7adc995f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DOTGraphTraits&lt; BlockFrequencyInfo * &gt;::getNodeLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * Graph)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a10bea33dd12f792987bcd7a4252a7446">llvm::getGVDT</a> and <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#a9684914352e5ac4e24c9d5d1f6002862">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getNodeLabel</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp">BlockFrequencyInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
