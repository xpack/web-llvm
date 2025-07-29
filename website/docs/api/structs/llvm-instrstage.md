---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/instrstage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InstrStage` Struct

<p>These values represent a non-pipelined step in the execution of an instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::InstrStage { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">llvm/MC/MCInstrItineraries.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uint64_t <a href="#a28207c85d95c7a0d901b2d8dbc37b6e3">FuncUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitmask representing a set of functional units. <a href="#a28207c85d95c7a0d901b2d8dbc37b6e3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ReservationKinds { <a href="#a0c36089f8d92b1bcb9c0a582d42aa106">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf0765776840275f39418c68660b53a">getCycles</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of cycles the stage is occupied. <a href="#aebf0765776840275f39418c68660b53a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a28207c85d95c7a0d901b2d8dbc37b6e3">FuncUnits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8142eb541d0907bee0312e4b5421f62a">getUnits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the choice of FUs. <a href="#a8142eb541d0907bee0312e4b5421f62a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0c36089f8d92b1bcb9c0a582d42aa106">ReservationKinds</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe8e670a185825427da4f9566bc7639">getReservationKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa7dea955d1ca8ddc402be471a188af">getNextCycles</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of cycles from the start of this stage to the start of the next stage in the itinerary. <a href="#a5aa7dea955d1ca8ddc402be471a188af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8614d31923c695646f6e53413e25aca">Cycles_</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Length of stage in machine cycles. <a href="#aa8614d31923c695646f6e53413e25aca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a28207c85d95c7a0d901b2d8dbc37b6e3">FuncUnits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91dae4825b72bebff6c096e43cf4323b">Units_</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Choice of functional units. <a href="#a91dae4825b72bebff6c096e43cf4323b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3857eab7c0ff1a4733397f8d0f8b18e">NextCycles_</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of machine cycles to next stage. <a href="#af3857eab7c0ff1a4733397f8d0f8b18e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0c36089f8d92b1bcb9c0a582d42aa106">ReservationKinds</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5320a11af396a0abeddfce816e119ac">Kind_</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kind of the FU reservation. <a href="#af5320a11af396a0abeddfce816e119ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>These values represent a non-pipelined step in the execution of an instruction.</p>


<p>Cycles represents the number of discrete time slots needed to complete the stage. Units represent the choice of functional units that can be used to complete the stage. Eg. IntUnit1, IntUnit2. NextCycles indicates how many cycles should elapse from the start of this stage to the start of the next stage in the itinerary. A value of -1 indicates that the next stage should start immediately after the current one. For example:</p>


<p>{ 1, x, -1 } indicates that the stage occupies FU x for 1 cycle and that the next stage starts immediately after this one.</p>


<p>{ 2, x|y, 1 } indicates that the stage occupies either FU x or FU y for 2 consecutive cycles and that the next stage starts one cycle after this stage starts. That is, the stage requirements overlap in time.</p>


<p>{ 1, x, 0 } indicates that the stage occupies FU x for 1 cycle and that the next stage starts in this same cycle. This can be used to indicate that the instruction requires multiple stages at the same time.</p>


<p>FU reservation can be of two different kinds:</p>


<ul class="doxyList ">
<li>FUs which instruction actually requires</li>
<li>FUs which instruction just reserves. Reserved unit is not available for execution of other instruction. However, several instructions can reserve the same unit several times. Such two types of units reservation is used to model instruction domain change stalls, FUs using the same resource (e.g. same register file), etc.</li>
</ul>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FuncUnits {#a28207c85d95c7a0d901b2d8dbc37b6e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uint64_t llvm::InstrStage::FuncUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bitmask representing a set of functional units.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ReservationKinds {#a0c36089f8d92b1bcb9c0a582d42aa106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::InstrStage::ReservationKinds </td>
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
<td class="doxyEnumItemName">Required<a id="a0c36089f8d92b1bcb9c0a582d42aa106a7774578153e4ca5a7299d1f42395ae6e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Reserved<a id="a0c36089f8d92b1bcb9c0a582d42aa106adb675fc15885dfb7a1666cc046ac7ba5"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCycles() {#aebf0765776840275f39418c68660b53a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InstrStage::getCycles ()</td>
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

<p>Returns the number of cycles the stage is occupied.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Reference <a href="#aa8614d31923c695646f6e53413e25aca">Cycles_</a>.</p>

</div>
</div>

### getNextCycles() {#a5aa7dea955d1ca8ddc402be471a188af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InstrStage::getNextCycles ()</td>
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

<p>Returns the number of cycles from the start of this stage to the start of the next stage in the itinerary.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>References <a href="#aa8614d31923c695646f6e53413e25aca">Cycles_</a> and <a href="#af3857eab7c0ff1a4733397f8d0f8b18e">NextCycles_</a>.</p>

</div>
</div>

### getReservationKind() {#a8fe8e670a185825427da4f9566bc7639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReservationKinds llvm::InstrStage::getReservationKind ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Reference <a href="#af5320a11af396a0abeddfce816e119ac">Kind_</a>.</p>

</div>
</div>

### getUnits() {#a8142eb541d0907bee0312e4b5421f62a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncUnits llvm::InstrStage::getUnits ()</td>
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

<p>Returns the choice of FUs.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Reference <a href="#a91dae4825b72bebff6c096e43cf4323b">Units_</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a911f1ee40a3e0bc91eeef55e7903586e">llvm::HexagonInstrInfo::getUnits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Cycles\_ {#aa8614d31923c695646f6e53413e25aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InstrStage::Cycles_</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Length of stage in machine cycles.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Referenced by <a href="#aebf0765776840275f39418c68660b53a">getCycles</a> and <a href="#a5aa7dea955d1ca8ddc402be471a188af">getNextCycles</a>.</p>

</div>
</div>

### Kind\_ {#af5320a11af396a0abeddfce816e119ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReservationKinds llvm::InstrStage::Kind_</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kind of the FU reservation.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Referenced by <a href="#a8fe8e670a185825427da4f9566bc7639">getReservationKind</a>.</p>

</div>
</div>

### NextCycles\_ {#af3857eab7c0ff1a4733397f8d0f8b18e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InstrStage::NextCycles_</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of machine cycles to next stage.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Referenced by <a href="#a5aa7dea955d1ca8ddc402be471a188af">getNextCycles</a>.</p>

</div>
</div>

### Units\_ {#a91dae4825b72bebff6c096e43cf4323b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncUnits llvm::InstrStage::Units_</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Choice of functional units.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a>.</p>


<p>Referenced by <a href="#a8142eb541d0907bee0312e4b5421f62a">getUnits</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">MCInstrItineraries.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
