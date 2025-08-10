---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-liveinterval-cpp-/calcliverangeutilset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CalcLiveRangeUtilSet` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{LiveInterval.cpp}::CalcLiveRangeUtilSet { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase">CalcLiveRangeUtilBase&lt;ImplT, IteratorT, CollectionT&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1639a7069961542330e9a34418a0c98c">CalcLiveRangeUtilSet</a> (LiveRange *LR)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LiveRange::SegmentSet &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe7e9edf4a4248829dc896b56f91dfc4">segmentsColl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f68fd080191fff4094dac3be6d9fe3">insertAtEnd</a> (const Segment &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#accfe22239af4a58bae19776418098990">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2bf651cafe04fd52ee95969471f619e">find</a> (SlotIndex Pos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#accfe22239af4a58bae19776418098990">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abba3ba3543e23494b91ca95866f9fae0">findInsertPos</a> (Segment S)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbb5de3066c0547599351b146a65faf7">CalcLiveRangeUtilSetBase</a></td>
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


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CalcLiveRangeUtilSet() {#a1639a7069961542330e9a34418a0c98c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilSet::CalcLiveRangeUtilSet (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> * LR)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#af12aab56d99752297b059f2ab36e65f4">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; CalcLiveRangeUtilSet, LiveRange::SegmentSet::iterator, LiveRange::SegmentSet &gt;::LR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### find() {#ad2bf651cafe04fd52ee95969471f619e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator anonymous{LiveInterval.cpp}::CalcLiveRangeUtilSet::find (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

### findInsertPos() {#abba3ba3543e23494b91ca95866f9fae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator anonymous{LiveInterval.cpp}::CalcLiveRangeUtilSet::findInsertPos (<a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#a4314e0cad331c51b65a005c7c8f685e0">Segment</a> S)</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

### insertAtEnd() {#ab0f68fd080191fff4094dac3be6d9fe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LiveInterval.cpp}::CalcLiveRangeUtilSet::insertAtEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#a4314e0cad331c51b65a005c7c8f685e0">Segment</a> &amp; S)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

### segmentsColl() {#afe7e9edf4a4248829dc896b56f91dfc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange::SegmentSet &amp; anonymous{LiveInterval.cpp}::CalcLiveRangeUtilSet::segmentsColl ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CalcLiveRangeUtilSetBase {#adbb5de3066c0547599351b146a65faf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend anonymous{LiveInterval.cpp}::CalcLiveRangeUtilSet::CalcLiveRangeUtilSetBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp">LiveInterval.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
