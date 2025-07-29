---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CalcLiveRangeUtilBase` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;
class anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt;ImplT, IteratorT, CollectionT&gt; { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4314e0cad331c51b65a005c7c8f685e0">Segment</a> = LiveRange::Segment</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#accfe22239af4a58bae19776418098990">iterator</a> = IteratorT</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a789fa8e3f5dd1e276f35ff360abe2681">CalcLiveRangeUtilBase</a> (LiveRange *LR)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acc30e10385342c3caf14a3bf391bc72b">createDeadDef</a> (SlotIndex Def, VNInfo::Allocator *VNInfoAllocator, VNInfo *ForVNI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A counterpart of LiveRange::createDeadDef: Make sure the range has a value defined at <span class="doxyComputerOutput">Def</span>. <a href="#acc30e10385342c3caf14a3bf391bc72b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a410add664cc1a9f7e755a2403d98be2d">extendInBlock</a> (SlotIndex StartIdx, SlotIndex Use)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b2743be1e1697ec787bef3e34831135">extendInBlock</a> (ArrayRef&lt; SlotIndex &gt; Undefs, SlotIndex StartIdx, SlotIndex Use) -&gt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7db5339e5b286123ec7187d5b6d9529">extendSegmentEndTo</a> (iterator I, SlotIndex NewEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used when we want to extend the segment specified by I to end at the specified endpoint. <a href="#ae7db5339e5b286123ec7187d5b6d9529">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#accfe22239af4a58bae19776418098990">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75072b79a016b1751f08ec1a1980ee3a">extendSegmentStartTo</a> (iterator I, SlotIndex NewStart)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used when we want to extend the segment specified by I to start at the specified endpoint. <a href="#a75072b79a016b1751f08ec1a1980ee3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#accfe22239af4a58bae19776418098990">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a865f64acaeffe1157bb42b90eb532370">addSegment</a> (Segment S)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ImplT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2bf0b6867ff55b5b69908ffa36419f2c">impl</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">CollectionT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb782f255cb4812b38e3709f7e75313b">segments</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a4314e0cad331c51b65a005c7c8f685e0">Segment</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a56f9a5520296aa8c691b60876dbd3209">segmentAt</a> (iterator I)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af12aab56d99752297b059f2ab36e65f4">LR</a></td>
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


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#accfe22239af4a58bae19776418098990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::iterator =  IteratorT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

### Segment {#a4314e0cad331c51b65a005c7c8f685e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::Segment =  LiveRange::Segment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### CalcLiveRangeUtilBase() {#a789fa8e3f5dd1e276f35ff360abe2681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::CalcLiveRangeUtilBase (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> * LR)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSegment() {#a865f64acaeffe1157bb42b90eb532370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::addSegment (<a href="#a4314e0cad331c51b65a005c7c8f685e0">Segment</a> S)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverange/#a0b73c8d5ae32ca13dd02ddde86ffd0a2">llvm::LiveRange::addSegment</a>.</p>

</div>
</div>

### createDeadDef() {#acc30e10385342c3caf14a3bf391bc72b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::createDeadDef (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Def, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a> * VNInfoAllocator, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * ForVNI)</td>
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

<p>A counterpart of LiveRange::createDeadDef: Make sure the range has a value defined at <span class="doxyComputerOutput">Def</span>.</p>


<p>If <span class="doxyComputerOutput">ForVNI</span> is null, and there is no value defined at <span class="doxyComputerOutput">Def</span>, a new value will be allocated using <span class="doxyComputerOutput">VNInfoAllocator</span>. If <span class="doxyComputerOutput">ForVNI</span> is null, the return value is the value defined at <span class="doxyComputerOutput">Def</span>, either a pre-existing one, or the one newly created. If <span class="doxyComputerOutput">ForVNI</span> is not null, then <span class="doxyComputerOutput">Def</span> should be the location where <span class="doxyComputerOutput">ForVNI</span> is defined. If the range does not have a value defined at <span class="doxyComputerOutput">Def</span>, the value <span class="doxyComputerOutput">ForVNI</span> will be used instead of allocating a new one. If the range already has a value defined at <span class="doxyComputerOutput">Def</span>, it must be same as <span class="doxyComputerOutput">ForVNI</span>. In either case, <span class="doxyComputerOutput">ForVNI</span> will be the return value.</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverange/#a4258d794235c7a408b3f52e5e4ef7159">llvm::LiveRange::createDeadDef</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#adbfe0544c5d2588941c44827f801e64b">llvm::LiveRange::createDeadDef</a>.</p>

</div>
</div>

### extendInBlock() {#a410add664cc1a9f7e755a2403d98be2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo * anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::extendInBlock (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> StartIdx, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Use)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverange/#a81f9d3d0b958e57c0c0f24982230885d">llvm::LiveRange::extendInBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#acc063bb08668434f0df98f4230901d10">llvm::LiveRange::extendInBlock</a>.</p>

</div>
</div>

### extendInBlock() {#a5b2743be1e1697ec787bef3e34831135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; VNInfo *, bool &gt; anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::extendInBlock (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; Undefs, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> StartIdx, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Use)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

### extendSegmentEndTo() {#ae7db5339e5b286123ec7187d5b6d9529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::extendSegmentEndTo (<a href="#accfe22239af4a58bae19776418098990">iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> NewEnd)</td>
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

<p>This method is used when we want to extend the segment specified by I to end at the specified endpoint.</p>


<p>To do this, we should merge and eliminate all segments that this will overlap with. The iterator is not invalidated.</p>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

### extendSegmentStartTo() {#a75072b79a016b1751f08ec1a1980ee3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::extendSegmentStartTo (<a href="#accfe22239af4a58bae19776418098990">iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> NewStart)</td>
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

<p>This method is used when we want to extend the segment specified by I to start at the specified endpoint.</p>


<p>To do this, we should merge and eliminate all segments that this will overlap with.</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### impl() {#a2bf0b6867ff55b5b69908ffa36419f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImplT &amp; anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::impl ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

### segmentAt() {#a56f9a5520296aa8c691b60876dbd3209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Segment * anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::segmentAt (<a href="#accfe22239af4a58bae19776418098990">iterator</a> I)</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

### segments() {#aeb782f255cb4812b38e3709f7e75313b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CollectionT &amp; anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::segments ()</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### LR {#af12aab56d99752297b059f2ab36e65f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImplT, typename IteratorT, typename CollectionT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange* anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; ImplT, IteratorT, CollectionT &gt;::LR</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
