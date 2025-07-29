---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/weaktrackingvh
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WeakTrackingVH` Class

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle that is nullable, but tries to track the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::WeakTrackingVH { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d4a282d9ddbd93893e1ada30288b53">WeakTrackingVH</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a421d63a2896eceee540facd015e92bfa">WeakTrackingVH</a> (Value *P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f01a47cccf213d6f8cb9589bbb47ca1">WeakTrackingVH</a> (const WeakTrackingVH &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85bc1aeabca5a017a462cf5e60fe5b2a">operator=</a> (const WeakTrackingVH &amp;RHS)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b586f93a1a0fd3328324b19db83ab3">operator=</a> (Value *RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a95341d529e6347a7a48294d548ca77">operator=</a> (const ValueHandleBase &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8002fceeab805b1789ea1feae48cd640">operator Value *</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed2f94ba7ecd4983f2c811f0d01f1398">pointsToAliveValue</a> () const</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle that is nullable, but tries to track the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>This is a value handle that tries hard to point to a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, even across RAUW operations, but will null itself out if the value is destroyed. this is useful for advisory sorts of information, but should not be used as the key of a map (since the map would have to rearrange itself when the pointer changes).</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WeakTrackingVH() {#a27d4a282d9ddbd93893e1ada30288b53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WeakTrackingVH::WeakTrackingVH ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#ae2f1a12c55f1c06acc38407b8627cb4dad057ff89faba8a9c0566aabcbf3f8fce">llvm::ValueHandleBase::WeakTracking</a>.</p>


<p>Referenced by <a href="#a85bc1aeabca5a017a462cf5e60fe5b2a">operator=</a> and <a href="#a4f01a47cccf213d6f8cb9589bbb47ca1">WeakTrackingVH</a>.</p>

</div>
</div>

### WeakTrackingVH() {#a421d63a2896eceee540facd015e92bfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WeakTrackingVH::WeakTrackingVH (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * P)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#ae2f1a12c55f1c06acc38407b8627cb4dad057ff89faba8a9c0566aabcbf3f8fce">llvm::ValueHandleBase::WeakTracking</a>.</p>

</div>
</div>

### WeakTrackingVH() {#a4f01a47cccf213d6f8cb9589bbb47ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WeakTrackingVH::WeakTrackingVH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &amp; RHS)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#ae2f1a12c55f1c06acc38407b8627cb4dad057ff89faba8a9c0566aabcbf3f8fce">llvm::ValueHandleBase::WeakTracking</a> and <a href="#a27d4a282d9ddbd93893e1ada30288b53">WeakTrackingVH</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator Value \*() {#a8002fceeab805b1789ea1feae48cd640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WeakTrackingVH::operator Value * ()</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">llvm::ValueHandleBase::getValPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>

</div>
</div>

### operator=() {#a85bc1aeabca5a017a462cf5e60fe5b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeakTrackingVH &amp; llvm::WeakTrackingVH::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &amp; RHS)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a27d4a282d9ddbd93893e1ada30288b53">WeakTrackingVH</a>.</p>

</div>
</div>

### operator=() {#a80b586f93a1a0fd3328324b19db83ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::WeakTrackingVH::operator= (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a700177b68c18b9e00893b747d3de1453">llvm::ValueHandleBase::operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>

</div>
</div>

### operator=() {#a6a95341d529e6347a7a48294d548ca77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::WeakTrackingVH::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> &amp; RHS)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a700177b68c18b9e00893b747d3de1453">llvm::ValueHandleBase::operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### pointsToAliveValue() {#aed2f94ba7ecd4983f2c811f0d01f1398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WeakTrackingVH::pointsToAliveValue ()</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">llvm::ValueHandleBase::getValPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a567c4f57a2f3aaeb6daee72ec39fb073">llvm::ValueHandleBase::isValid</a>.</p>

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
