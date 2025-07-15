---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/hwinstructionissuedevent
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HWInstructionIssuedEvent` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::mca::HWInstructionIssuedEvent { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">llvm/MCA/HWEventListener.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionevent">HWInstructionEvent</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74418a125c3b0b8ea3626a99976ca16c">HWInstructionIssuedEvent</a> (const InstRef &amp;IR, ArrayRef&lt; ResourceUse &gt; UR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ab534e0b15e46245fd0eb31e7e7c2e863">ResourceUse</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6849a21bb102f66188e6ff54cf723b16">UsedResources</a></td>
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


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HWInstructionIssuedEvent() {#a74418a125c3b0b8ea3626a99976ca16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::HWInstructionIssuedEvent::HWInstructionIssuedEvent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; IR, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ab534e0b15e46245fd0eb31e7e7c2e863">ResourceUse</a> &gt; UR)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionevent/#a171b37ee53c5f563af010cdc3ebb47a3">llvm::mca::HWInstructionEvent::HWInstructionEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionevent/#a17c3610b731525a11cec3d4e9472291c">llvm::mca::HWInstructionEvent::IR</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionevent/#a8169c917f54cc2624dd536acdc5c5e52aa8c210f2b743c3f94bd79e510de2c2c8">llvm::mca::HWInstructionEvent::Issued</a> and <a href="#a6849a21bb102f66188e6ff54cf723b16">UsedResources</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### UsedResources {#a6849a21bb102f66188e6ff54cf723b16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;ResourceUse&gt; llvm::mca::HWInstructionIssuedEvent::UsedResources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>Referenced by <a href="#a74418a125c3b0b8ea3626a99976ca16c">HWInstructionIssuedEvent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
