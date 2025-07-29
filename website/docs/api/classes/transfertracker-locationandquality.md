---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/transfertracker/locationandquality
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LocationAndQuality` Class



## Declaration

<div class="doxyDeclaration">
class TransferTracker::LocationAndQuality { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b8f6f7382ed160594fea63e8341c5e">LocationAndQuality</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088495756a3cd53da4efab38c8050a53">LocationAndQuality</a> (LocIdx L, LocationQuality Q)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafbc8ed2fac417ad446be5834b07a1cc">getLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/transfertracker/#aa5d994f6e3b0b93e697c85ca2002834d">LocationQuality</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14fc47dd260079d24f239d40e88f0371">getQuality</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb178c08bc77adce5c52045faeca87b4">isIllegal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc6ac95ebdfc8629136cea7fa61e3041">isBest</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae16b2b9c8cf7565a34651ca390fd12f3">Location</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3129c87c6baa0853e0f5be60615e1cd8">Quality</a></td>
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


<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LocationAndQuality() {#af0b8f6f7382ed160594fea63e8341c5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TransferTracker::LocationAndQuality::LocationAndQuality ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### LocationAndQuality() {#a088495756a3cd53da4efab38c8050a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TransferTracker::LocationAndQuality::LocationAndQuality (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> L, <a href="/web-llvm/docs/api/classes/transfertracker/#aa5d994f6e3b0b93e697c85ca2002834d">LocationQuality</a> Q)</td>
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



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getLoc() {#aafbc8ed2fac417ad446be5834b07a1cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocIdx TransferTracker::LocationAndQuality::getLoc ()</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx/#a8567f7c20eae6b2f5beabaa440df1097">LiveDebugValues::LocIdx::MakeIllegalLoc</a>.</p>

</div>
</div>

### getQuality() {#a14fc47dd260079d24f239d40e88f0371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationQuality TransferTracker::LocationAndQuality::getQuality ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#adc6ac95ebdfc8629136cea7fa61e3041">isBest</a>.</p>

</div>
</div>

### isBest() {#adc6ac95ebdfc8629136cea7fa61e3041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TransferTracker::LocationAndQuality::isBest ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/transfertracker/#aa5d994f6e3b0b93e697c85ca2002834da68ef004de6166492c1d668eb8efe09bd">TransferTracker::Best</a> and <a href="#a14fc47dd260079d24f239d40e88f0371">getQuality</a>.</p>

</div>
</div>

### isIllegal() {#aeb178c08bc77adce5c52045faeca87b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TransferTracker::LocationAndQuality::isIllegal ()</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Location {#ae16b2b9c8cf7565a34651ca390fd12f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TransferTracker::LocationAndQuality::Location</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### Quality {#a3129c87c6baa0853e0f5be60615e1cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned TransferTracker::LocationAndQuality::Quality</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
