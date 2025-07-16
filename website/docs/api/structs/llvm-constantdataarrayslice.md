---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/constantdataarrayslice
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ConstantDataArraySlice` Struct Reference

<p>Represents offset+length into a <a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ConstantDataArraySlice { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3bdd208a57384d8b4a6778e55497f3e">operator[]</a> (unsigned I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience accessor for elements in the slice. <a href="#ab3bdd208a57384d8b4a6778e55497f3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ef1356f1ed5348d1f0326f3ae5224d">move</a> (uint64_t Delta)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Moves the Offset and adjusts Length accordingly. <a href="#ab9ef1356f1ed5348d1f0326f3ae5224d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac259d8d452474b84269b58dd573ed291">Array</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a> pointer. <a href="#ac259d8d452474b84269b58dd573ed291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa521d739527c924cc3d0c7b40936ea45">Offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Slice starts at this Offset. <a href="#aa521d739527c924cc3d0c7b40936ea45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87f5d145b113af758f48fb50f6ea92b9">Length</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Length of the slice. <a href="#a87f5d145b113af758f48fb50f6ea92b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents offset+length into a <a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a>.</p>

<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#ab3bdd208a57384d8b4a6778e55497f3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ConstantDataArraySlice::operator[] (unsigned I)</td>
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

<p>Convenience accessor for elements in the slice.</p>

<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="#ac259d8d452474b84269b58dd573ed291">Array</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aa521d739527c924cc3d0c7b40936ea45">Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### move() {#ab9ef1356f1ed5348d1f0326f3ae5224d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ConstantDataArraySlice::move (uint64_t Delta)</td>
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

<p>Moves the Offset and adjusts Length accordingly.</p>

<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a87f5d145b113af758f48fb50f6ea92b9">Length</a> and <a href="#aa521d739527c924cc3d0c7b40936ea45">Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Array {#ac259d8d452474b84269b58dd573ed291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantDataArray* llvm::ConstantDataArraySlice::Array</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a> pointer.</p>


<p>nullptr indicates a zeroinitializer (a valid initializer, it just doesn't fit the <a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a> interface).</p>


<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bcd261c0da622d37e1c5aeb02496e12">llvm::getConstantStringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a5abc0c0977f5f87b0e30e784a3d487bc">GetStringLengthH</a> and <a href="#ab3bdd208a57384d8b4a6778e55497f3e">operator[]</a>.</p>

</div>
</div>

### Length {#a87f5d145b113af758f48fb50f6ea92b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ConstantDataArraySlice::Length</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Length of the slice.</p>

<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bcd261c0da622d37e1c5aeb02496e12">llvm::getConstantStringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a2e8d18b52d32049f8c9ed560d20341b8">getMemsetStringVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a5abc0c0977f5f87b0e30e784a3d487bc">GetStringLengthH</a> and <a href="#ab9ef1356f1ed5348d1f0326f3ae5224d">move</a>.</p>

</div>
</div>

### Offset {#aa521d739527c924cc3d0c7b40936ea45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ConstantDataArraySlice::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Slice starts at this Offset.</p>

<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bcd261c0da622d37e1c5aeb02496e12">llvm::getConstantStringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a5abc0c0977f5f87b0e30e784a3d487bc">GetStringLengthH</a>, <a href="#ab9ef1356f1ed5348d1f0326f3ae5224d">move</a> and <a href="#ab3bdd208a57384d8b4a6778e55497f3e">operator[]</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">ValueTracking.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
