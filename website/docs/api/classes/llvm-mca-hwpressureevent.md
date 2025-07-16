---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/hwpressureevent
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HWPressureEvent` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::mca::HWPressureEvent { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">llvm/MCA/HWEventListener.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">GenericReason { <a href="#adfb26ed742fb9cba9a339e39472afdba">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5372282b8b63061ee40dc07f912e3f80">HWPressureEvent</a> (GenericReason reason, ArrayRef&lt; InstRef &gt; Insts, uint64_t Mask=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adfb26ed742fb9cba9a339e39472afdba">GenericReason</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2d3340467f189c00cf40997c7c6c3c">Reason</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9516a5609ea77251c447ee212791459">AffectedInstructions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb98e7099e8e67edaad5194c9eb37913">ResourceMask</a></td>
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


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### GenericReason {#adfb26ed742fb9cba9a339e39472afdba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::mca::HWPressureEvent::GenericReason </td>
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
<td class="doxyEnumItemName">INVALID<a id="adfb26ed742fb9cba9a339e39472afdbaa2d558492a78876e05f930cde529cdb7c"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RESOURCES<a id="adfb26ed742fb9cba9a339e39472afdbaa9ab49687d8ecc311352f6bee677180c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REGISTER_DEPS<a id="adfb26ed742fb9cba9a339e39472afdbaa2d42b099c4456a336bb28534905732fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MEMORY_DEPS<a id="adfb26ed742fb9cba9a339e39472afdbaa3fd83fe28075165ab270763c5c098da3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HWPressureEvent() {#a5372282b8b63061ee40dc07f912e3f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::HWPressureEvent::HWPressureEvent (<a href="#adfb26ed742fb9cba9a339e39472afdba">GenericReason</a> reason, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/instref">InstRef</a> &gt; Insts, uint64_t Mask=0)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>References <a href="#aa9516a5609ea77251c447ee212791459">AffectedInstructions</a>, <a href="#a4b2d3340467f189c00cf40997c7c6c3c">Reason</a> and <a href="#abb98e7099e8e67edaad5194c9eb37913">ResourceMask</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AffectedInstructions {#aa9516a5609ea77251c447ee212791459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;InstRef&gt; llvm::mca::HWPressureEvent::AffectedInstructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>Referenced by <a href="#a5372282b8b63061ee40dc07f912e3f80">HWPressureEvent</a>.</p>

</div>
</div>

### Reason {#a4b2d3340467f189c00cf40997c7c6c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericReason llvm::mca::HWPressureEvent::Reason</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>Referenced by <a href="#a5372282b8b63061ee40dc07f912e3f80">HWPressureEvent</a>.</p>

</div>
</div>

### ResourceMask {#abb98e7099e8e67edaad5194c9eb37913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::mca::HWPressureEvent::ResourceMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a>.</p>


<p>Referenced by <a href="#a5372282b8b63061ee40dc07f912e3f80">HWPressureEvent</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/hweventlistener-h">HWEventListener.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
