---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/weakvh
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WeakVH` Class

<p>A nullable <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle that is nullable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::WeakVH { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the common base class of value handles. <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83fa1665a8e540abe92497e0bb8b5ea9">WeakVH</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2121b8e4d72b2a1d68ffc347eb66395c">WeakVH</a> (Value *P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ccc76585513b1836598518e5afd0540">WeakVH</a> (const WeakVH &amp;RHS)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7784ad5abdaf8017393055c043aaa719">operator=</a> (const WeakVH &amp;RHS)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79a6674a38f02a9a6852e7105654980">operator=</a> (Value *RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ab87f5dbdcfddbcf7f89dd968affcd8">operator=</a> (const ValueHandleBase &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c49cdae7ce889f3126e047b81ad7bee">operator Value *</a> () const</td>
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

<p>A nullable <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle that is nullable.</p>


<p>This is a value handle that points to a value, and nulls itself out if that value is deleted.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WeakVH() {#a83fa1665a8e540abe92497e0bb8b5ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WeakVH::WeakVH ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#ae2f1a12c55f1c06acc38407b8627cb4da3c970eedf4f533d381b99e2b5c73ad77">llvm::ValueHandleBase::Weak</a>.</p>


<p>Referenced by <a href="#a7784ad5abdaf8017393055c043aaa719">operator=</a> and <a href="#a2ccc76585513b1836598518e5afd0540">WeakVH</a>.</p>

</div>
</div>

### WeakVH() {#a2121b8e4d72b2a1d68ffc347eb66395c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WeakVH::WeakVH (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * P)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#ae2f1a12c55f1c06acc38407b8627cb4da3c970eedf4f533d381b99e2b5c73ad77">llvm::ValueHandleBase::Weak</a>.</p>

</div>
</div>

### WeakVH() {#a2ccc76585513b1836598518e5afd0540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WeakVH::WeakVH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a> &amp; RHS)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#ae2f1a12c55f1c06acc38407b8627cb4da3c970eedf4f533d381b99e2b5c73ad77">llvm::ValueHandleBase::Weak</a> and <a href="#a83fa1665a8e540abe92497e0bb8b5ea9">WeakVH</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator Value \*() {#a3c49cdae7ce889f3126e047b81ad7bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WeakVH::operator Value * ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">llvm::ValueHandleBase::getValPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>

</div>
</div>

### operator=() {#a7784ad5abdaf8017393055c043aaa719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeakVH &amp; llvm::WeakVH::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a83fa1665a8e540abe92497e0bb8b5ea9">WeakVH</a>.</p>

</div>
</div>

### operator=() {#af79a6674a38f02a9a6852e7105654980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::WeakVH::operator= (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a700177b68c18b9e00893b747d3de1453">llvm::ValueHandleBase::operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>

</div>
</div>

### operator=() {#a9ab87f5dbdcfddbcf7f89dd968affcd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::WeakVH::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> &amp; RHS)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a700177b68c18b9e00893b747d3de1453">llvm::ValueHandleBase::operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
