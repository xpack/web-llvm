---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/signeddivisionbyconstantinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SignedDivisionByConstantInfo` Struct Reference

<p>Magic data for optimising signed division by a constant. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SignedDivisionByConstantInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">llvm/Support/DivisionByConstantInfo.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa54b0543973a6ef974f769d0e9383850">Magic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>magic number <a href="#aa54b0543973a6ef974f769d0e9383850">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfbfc736687e2b99cd2cc6cd2d208c4">ShiftAmount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>shift amount <a href="#a4cfbfc736687e2b99cd2cc6cd2d208c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/signeddivisionbyconstantinfo">SignedDivisionByConstantInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affa10b6ac03585fea6d8f1832071ebd5">get</a> (const APInt &amp;D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the magic numbers required to implement a signed integer division by a constant as a sequence of multiplies, adds and shifts. <a href="#affa10b6ac03585fea6d8f1832071ebd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Magic data for optimising signed division by a constant.</p>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Magic {#aa54b0543973a6ef974f769d0e9383850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::SignedDivisionByConstantInfo::Magic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>magic number</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>.</p>


<p>Referenced by <a href="#affa10b6ac03585fea6d8f1832071ebd5">get</a>.</p>

</div>
</div>

### ShiftAmount {#a4cfbfc736687e2b99cd2cc6cd2d208c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SignedDivisionByConstantInfo::ShiftAmount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>shift amount</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>.</p>


<p>Referenced by <a href="#affa10b6ac03585fea6d8f1832071ebd5">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#affa10b6ac03585fea6d8f1832071ebd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SignedDivisionByConstantInfo SignedDivisionByConstantInfo::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; D)</td>
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

<p>Calculate the magic numbers required to implement a signed integer division by a constant as a sequence of multiplies, adds and shifts.</p>


<p>Requires that the divisor not be 0, 1, or -1. Taken from "Hacker's Delight", Henry S. Warren, Jr., Chapter 10.</p>


<p>Declaration at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/divisionbyconstantinfo-cpp">DivisionByConstantInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="#aa54b0543973a6ef974f769d0e9383850">Magic</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8376734f311508662dd7e737752e5953">llvm::APInt::negate</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>, <a href="#a4cfbfc736687e2b99cd2cc6cd2d208c4">ShiftAmount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a0f0a665210e453bb16b4bf1861dbdd58">llvm::APInt::udivrem</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/divisionbyconstantinfo-cpp">DivisionByConstantInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
