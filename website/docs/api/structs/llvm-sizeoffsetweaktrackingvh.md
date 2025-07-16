---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sizeoffsetweaktrackingvh
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SizeOffsetWeakTrackingVH` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/sizeoffsetweaktrackingvh">SizeOffsetWeakTrackingVH</a> - Used by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator">ObjectSizeOffsetEvaluator</a></span> in a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a></span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SizeOffsetWeakTrackingVH { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype">SizeOffsetType&lt;T, C&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype">SizeOffsetType</a> - A base template class for the object size visitors. <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26befa0d38f2d3b33596eb4a366cc9ff">SizeOffsetWeakTrackingVH</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc93189c9fe59ba05dec48d559795d0c">SizeOffsetWeakTrackingVH</a> (Value *Size, Value *Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f268ed5222f795788a17f6bb04401de">SizeOffsetWeakTrackingVH</a> (const SizeOffsetValue &amp;SOV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceeb39e971b3ccf1f8f691d6d4f2c5cb">known</a> (WeakTrackingVH V)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/sizeoffsetweaktrackingvh">SizeOffsetWeakTrackingVH</a> - Used by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator">ObjectSizeOffsetEvaluator</a></span> in a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a></span>.</p>

<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SizeOffsetWeakTrackingVH() {#a26befa0d38f2d3b33596eb4a366cc9ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SizeOffsetWeakTrackingVH::SizeOffsetWeakTrackingVH ()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a680eba2d2f3d92d2f8330d45a527462b">llvm::SizeOffsetType&lt; WeakTrackingVH, SizeOffsetWeakTrackingVH &gt;::SizeOffsetType</a>.</p>

</div>
</div>

### SizeOffsetWeakTrackingVH() {#adc93189c9fe59ba05dec48d559795d0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SizeOffsetWeakTrackingVH::SizeOffsetWeakTrackingVH (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Size, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset)</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a8859bafd8bfb3cd956d6490367ffe3eb">llvm::SizeOffsetType&lt; WeakTrackingVH, SizeOffsetWeakTrackingVH &gt;::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a06605ec689995010ade897ee0ebd3023">llvm::SizeOffsetType&lt; WeakTrackingVH, SizeOffsetWeakTrackingVH &gt;::Size</a> and <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a680eba2d2f3d92d2f8330d45a527462b">llvm::SizeOffsetType&lt; WeakTrackingVH, SizeOffsetWeakTrackingVH &gt;::SizeOffsetType</a>.</p>

</div>
</div>

### SizeOffsetWeakTrackingVH() {#a5f268ed5222f795788a17f6bb04401de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SizeOffsetWeakTrackingVH::SizeOffsetWeakTrackingVH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sizeoffsetvalue">SizeOffsetValue</a> &amp; SOV)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a8859bafd8bfb3cd956d6490367ffe3eb">llvm::SizeOffsetType&lt; WeakTrackingVH, SizeOffsetWeakTrackingVH &gt;::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a06605ec689995010ade897ee0ebd3023">llvm::SizeOffsetType&lt; WeakTrackingVH, SizeOffsetWeakTrackingVH &gt;::Size</a> and <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a680eba2d2f3d92d2f8330d45a527462b">llvm::SizeOffsetType&lt; WeakTrackingVH, SizeOffsetWeakTrackingVH &gt;::SizeOffsetType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### known() {#aceeb39e971b3ccf1f8f691d6d4f2c5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SizeOffsetWeakTrackingVH::known (<a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> V)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
