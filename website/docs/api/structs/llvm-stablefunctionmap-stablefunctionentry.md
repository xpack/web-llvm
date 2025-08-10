---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/stablefunctionmap/stablefunctionentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `StableFunctionEntry` Struct

<p>An efficient form of <a href="/web-llvm/docs/api/structs/llvm/stablefunction">StableFunction</a> for fast look-up. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::StableFunctionMap::StableFunctionEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">llvm/CGData/StableFunctionMap.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d001ebb0fcffa6159e36969e8f8970c">StableFunctionEntry</a> (stable_hash Hash, unsigned FunctionNameId, unsigned ModuleNameId, unsigned InstCount, std::unique_ptr&lt; IndexOperandHashMapType &gt; IndexOperandHashMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c87e877e9c2a12f5f30eac26a5e404">Hash</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The combined stable hash of the function. <a href="#ac1c87e877e9c2a12f5f30eac26a5e404">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee8ba9de42071872ee9e955ba6f0102f">FunctionNameId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Id of the function name. <a href="#aee8ba9de42071872ee9e955ba6f0102f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55624d86c11b9f6a7954a6ac1a433c3">ModuleNameId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Id of the module name. <a href="#af55624d86c11b9f6a7954a6ac1a433c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58d1d29df5e4fa13146441c05a4ed5e">InstCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of instructions. <a href="#ad58d1d29df5e4fa13146441c05a4ed5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a84743af686727e503a41a7cc9e590820">IndexOperandHashMapType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad440cf342552f1e5995767fa2d7e5adb">IndexOperandHashMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map from an <a href="/web-llvm/docs/api/namespaces/llvm/#aac5c174796045b79a15a2bd17ced0d6f">IndexPair</a> to a <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> which was skipped. <a href="#ad440cf342552f1e5995767fa2d7e5adb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An efficient form of <a href="/web-llvm/docs/api/structs/llvm/stablefunction">StableFunction</a> for fast look-up.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StableFunctionEntry() {#a4d001ebb0fcffa6159e36969e8f8970c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StableFunctionMap::StableFunctionEntry::StableFunctionEntry (<a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> Hash, unsigned FunctionNameId, unsigned ModuleNameId, unsigned InstCount, std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a84743af686727e503a41a7cc9e590820">IndexOperandHashMapType</a> &gt; IndexOperandHashMap)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>References <a href="#aee8ba9de42071872ee9e955ba6f0102f">FunctionNameId</a>, <a href="#ac1c87e877e9c2a12f5f30eac26a5e404">Hash</a>, <a href="#ad440cf342552f1e5995767fa2d7e5adb">IndexOperandHashMap</a>, <a href="#ad58d1d29df5e4fa13146441c05a4ed5e">InstCount</a>, <a href="#af55624d86c11b9f6a7954a6ac1a433c3">ModuleNameId</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FunctionNameId {#aee8ba9de42071872ee9e955ba6f0102f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StableFunctionMap::StableFunctionEntry::FunctionNameId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Id of the function name.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="#a4d001ebb0fcffa6159e36969e8f8970c">StableFunctionEntry</a>.</p>

</div>
</div>

### Hash {#ac1c87e877e9c2a12f5f30eac26a5e404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">stable_hash llvm::StableFunctionMap::StableFunctionEntry::Hash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The combined stable hash of the function.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="#a4d001ebb0fcffa6159e36969e8f8970c">StableFunctionEntry</a>.</p>

</div>
</div>

### IndexOperandHashMap {#ad440cf342552f1e5995767fa2d7e5adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;IndexOperandHashMapType&gt; llvm::StableFunctionMap::StableFunctionEntry::IndexOperandHashMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map from an <a href="/web-llvm/docs/api/namespaces/llvm/#aac5c174796045b79a15a2bd17ced0d6f">IndexPair</a> to a <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> which was skipped.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp/#a282266673aa65393e018d96acf69a211">getStableIndexOperandHashes</a> and <a href="#a4d001ebb0fcffa6159e36969e8f8970c">StableFunctionEntry</a>.</p>

</div>
</div>

### InstCount {#ad58d1d29df5e4fa13146441c05a4ed5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StableFunctionMap::StableFunctionEntry::InstCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of instructions.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="#a4d001ebb0fcffa6159e36969e8f8970c">StableFunctionEntry</a>.</p>

</div>
</div>

### ModuleNameId {#af55624d86c11b9f6a7954a6ac1a433c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StableFunctionMap::StableFunctionEntry::ModuleNameId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Id of the module name.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a>.</p>


<p>Referenced by <a href="#a4d001ebb0fcffa6159e36969e8f8970c">StableFunctionEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/stablefunctionmap-h">StableFunctionMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
