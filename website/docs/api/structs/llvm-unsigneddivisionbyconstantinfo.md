---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/unsigneddivisionbyconstantinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `UnsignedDivisionByConstantInfo` Struct Reference

<p>Magic data for optimising unsigned division by a constant. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::UnsignedDivisionByConstantInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">llvm/Support/DivisionByConstantInfo.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890b63a18fc3e328809c691b17c776ed">Magic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>magic number <a href="#a890b63a18fc3e328809c691b17c776ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8b2eee90075caf0407679fb780f5c9">IsAdd</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>add indicator <a href="#a1b8b2eee90075caf0407679fb780f5c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadab71767738ad10ccb7600fa732fd96">PostShift</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>post-shift amount <a href="#aadab71767738ad10ccb7600fa732fd96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fe2f52cb1640befcb5c3da7d3e37c6d">PreShift</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>pre-shift amount <a href="#a1fe2f52cb1640befcb5c3da7d3e37c6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/unsigneddivisionbyconstantinfo">UnsignedDivisionByConstantInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7ecd0f6bb250280a31e56173931e31">get</a> (const APInt &amp;D, unsigned LeadingZeros=0, bool AllowEvenDivisorOptimization=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the magic numbers required to implement an unsigned integer division by a constant as a sequence of multiplies, adds and shifts. <a href="#a6a7ecd0f6bb250280a31e56173931e31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Magic data for optimising unsigned division by a constant.</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### IsAdd {#a1b8b2eee90075caf0407679fb780f5c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::UnsignedDivisionByConstantInfo::IsAdd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>add indicator</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a> and <a href="#a6a7ecd0f6bb250280a31e56173931e31">get</a>.</p>

</div>
</div>

### Magic {#a890b63a18fc3e328809c691b17c776ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::UnsignedDivisionByConstantInfo::Magic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>magic number</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a> and <a href="#a6a7ecd0f6bb250280a31e56173931e31">get</a>.</p>

</div>
</div>

### PostShift {#aadab71767738ad10ccb7600fa732fd96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::UnsignedDivisionByConstantInfo::PostShift</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>post-shift amount</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a> and <a href="#a6a7ecd0f6bb250280a31e56173931e31">get</a>.</p>

</div>
</div>

### PreShift {#a1fe2f52cb1640befcb5c3da7d3e37c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::UnsignedDivisionByConstantInfo::PreShift</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>pre-shift amount</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a> and <a href="#a6a7ecd0f6bb250280a31e56173931e31">get</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a6a7ecd0f6bb250280a31e56173931e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnsignedDivisionByConstantInfo UnsignedDivisionByConstantInfo::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; D, unsigned LeadingZeros=0, bool AllowEvenDivisorOptimization=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Calculate the magic numbers required to implement an unsigned integer division by a constant as a sequence of multiplies, adds and shifts.</p>


<p>Requires that the divisor not be 0. Taken from "Hacker's Delight", Henry S. Warren, Jr., chapter 10. LeadingZeros can be used to simplify the calculation if the upper bits of the divided value are known zero.</p>


<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/divisionbyconstantinfo-h">DivisionByConstantInfo.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/divisionbyconstantinfo-cpp">DivisionByConstantInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a421c6b20238e6e6585270538188f15b9">llvm::AllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a6a7ecd0f6bb250280a31e56173931e31">get</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#a1b8b2eee90075caf0407679fb780f5c9">IsAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="#a890b63a18fc3e328809c691b17c776ed">Magic</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#a1fa2460e32327ade49189c95740bc1b5">NC</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#aadab71767738ad10ccb7600fa732fd96">PostShift</a>, <a href="#a1fe2f52cb1640befcb5c3da7d3e37c6d">PreShift</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h/#a9211f62d8e1e6de999eaa63ec0f6ae02">R2</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a0f0a665210e453bb16b4bf1861dbdd58">llvm::APInt::udivrem</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a545e8d5dfa1688acea0d0e275b03682f">llvm::APInt::ult</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a> and <a href="#a6a7ecd0f6bb250280a31e56173931e31">get</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
