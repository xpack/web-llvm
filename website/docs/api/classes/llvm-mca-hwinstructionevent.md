---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/hwinstructionevent
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HWInstructionEvent` Class



## Declaration

<div class="doxyDeclaration">
class llvm::mca::HWInstructionEvent { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">llvm/MCA/HWEventListener.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructiondispatchedevent">HWInstructionDispatchedEvent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionissuedevent">HWInstructionIssuedEvent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionretiredevent">HWInstructionRetiredEvent</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">GenericEventType { <a href="#a8169c917f54cc2624dd536acdc5c5e52">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a171b37ee53c5f563af010cdc3ebb47a3">HWInstructionEvent</a> (unsigned type, const InstRef &amp;Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b3225865abfc2dca5f32db28be5a1d2">Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c3610b731525a11cec3d4e9472291c">IR</a></td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### GenericEventType {#a8169c917f54cc2624dd536acdc5c5e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::mca::HWInstructionEvent::GenericEventType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invalid<a id="a8169c917f54cc2624dd536acdc5c5e52aaa80bddd08ae7c72421d29f73cd9cb38"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Retired<a id="a8169c917f54cc2624dd536acdc5c5e52a8de8de8d10772f11d7f1388dc019dd30"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pending<a id="a8169c917f54cc2624dd536acdc5c5e52ac3ea03c95905cfc942bc51170efcd248"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ready<a id="a8169c917f54cc2624dd536acdc5c5e52adb5217b7a234dc05fdea6bce972cd859"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Issued<a id="a8169c917f54cc2624dd536acdc5c5e52aa8c210f2b743c3f94bd79e510de2c2c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Executed<a id="a8169c917f54cc2624dd536acdc5c5e52a4d10e4fc3ead3a12ec1a142ba118e4a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dispatched<a id="a8169c917f54cc2624dd536acdc5c5e52a1bb71e665c2978dc4d3c02da2f9bcbc3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastGenericEventType<a id="a8169c917f54cc2624dd536acdc5c5e52a104af9dfdd0f1b1a4221b2d283f5c0b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HWInstructionEvent() {#a171b37ee53c5f563af010cdc3ebb47a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::HWInstructionEvent::HWInstructionEvent (unsigned type, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &amp; Inst)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>References <a href="#a17c3610b731525a11cec3d4e9472291c">IR</a> and <a href="#a2b3225865abfc2dca5f32db28be5a1d2">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructiondispatchedevent/#a9a25c436ad489dba4a1e2b008905cfa3">llvm::mca::HWInstructionDispatchedEvent::HWInstructionDispatchedEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionissuedevent/#a74418a125c3b0b8ea3626a99976ca16c">llvm::mca::HWInstructionIssuedEvent::HWInstructionIssuedEvent</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionretiredevent/#a11d7f5edac24c0496068791fa4999ba0">llvm::mca::HWInstructionRetiredEvent::HWInstructionRetiredEvent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IR {#a17c3610b731525a11cec3d4e9472291c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstRef&amp; llvm::mca::HWInstructionEvent::IR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructiondispatchedevent/#a9a25c436ad489dba4a1e2b008905cfa3">llvm::mca::HWInstructionDispatchedEvent::HWInstructionDispatchedEvent</a>, <a href="#a171b37ee53c5f563af010cdc3ebb47a3">HWInstructionEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionissuedevent/#a74418a125c3b0b8ea3626a99976ca16c">llvm::mca::HWInstructionIssuedEvent::HWInstructionIssuedEvent</a> and <a href="/web-llvm/docs/api/classes/llvm/mca/hwinstructionretiredevent/#a11d7f5edac24c0496068791fa4999ba0">llvm::mca::HWInstructionRetiredEvent::HWInstructionRetiredEvent</a>.</p>

</div>
</div>

### Type {#a2b3225865abfc2dca5f32db28be5a1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::mca::HWInstructionEvent::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>Referenced by <a href="#a171b37ee53c5f563af010cdc3ebb47a3">HWInstructionEvent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
