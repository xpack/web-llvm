---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/sizeoffsetvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SizeOffsetValue` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::SizeOffsetValue { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab03cf3f5fe1d0ee32b5e1196a981963">SizeOffsetValue</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674405026caacebe0aba990bafc75723">SizeOffsetValue</a> (Value *Size, Value *Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab416ff783f375309cc1078439bf0cdbc">SizeOffsetValue</a> (const SizeOffsetWeakTrackingVH &amp;SOT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac06af12e6b6b84b208fd36f639e3d5c0">known</a> (Value *V)</td>
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


<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SizeOffsetValue() {#aab03cf3f5fe1d0ee32b5e1196a981963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SizeOffsetValue::SizeOffsetValue ()</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a680eba2d2f3d92d2f8330d45a527462b">llvm::SizeOffsetType&lt; Value *, SizeOffsetValue &gt;::SizeOffsetType</a>.</p>

</div>
</div>

### SizeOffsetValue() {#a674405026caacebe0aba990bafc75723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SizeOffsetValue::SizeOffsetValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Size, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Offset)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a8859bafd8bfb3cd956d6490367ffe3eb">llvm::SizeOffsetType&lt; Value *, SizeOffsetValue &gt;::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a06605ec689995010ade897ee0ebd3023">llvm::SizeOffsetType&lt; Value *, SizeOffsetValue &gt;::Size</a> and <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a680eba2d2f3d92d2f8330d45a527462b">llvm::SizeOffsetType&lt; Value *, SizeOffsetValue &gt;::SizeOffsetType</a>.</p>

</div>
</div>

### SizeOffsetValue() {#ab416ff783f375309cc1078439bf0cdbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SizeOffsetValue::SizeOffsetValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sizeoffsetweaktrackingvh">SizeOffsetWeakTrackingVH</a> &amp; SOT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>, definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a8859bafd8bfb3cd956d6490367ffe3eb">llvm::SizeOffsetType&lt; Value *, SizeOffsetValue &gt;::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a06605ec689995010ade897ee0ebd3023">llvm::SizeOffsetType&lt; Value *, SizeOffsetValue &gt;::Size</a> and <a href="/web-llvm/docs/api/structs/llvm/sizeoffsettype/#a680eba2d2f3d92d2f8330d45a527462b">llvm::SizeOffsetType&lt; Value *, SizeOffsetValue &gt;::SizeOffsetType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### known() {#ac06af12e6b6b84b208fd36f639e3d5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SizeOffsetValue::known (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
