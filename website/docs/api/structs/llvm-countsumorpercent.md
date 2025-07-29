---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/countsumorpercent
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CountSumOrPercent` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::CountSumOrPercent { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343ec15617ac4850fa7833685fb5c34b">CountSumOrPercent</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4c5de0fc261ffb52e7bf28489ccb16">reset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ee8e5f865571103ec74dd37837b70e">NumEntries</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa86b18bf848839782dee252ea6871d00">CountSum</a> = 0.0f</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; double, IPVK_Last - IPVK_First+1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65910538ca9fe224414a15b68bdcf33">ValueCounts</a> = {}</td>
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


<p>Definition at line 746 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CountSumOrPercent() {#a343ec15617ac4850fa7833685fb5c34b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CountSumOrPercent::CountSumOrPercent ()</td>
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



<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### reset() {#a5c4c5de0fc261ffb52e7bf28489ccb16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CountSumOrPercent::reset ()</td>
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



<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="#aa86b18bf848839782dee252ea6871d00">CountSum</a>, <a href="#ac6ee8e5f865571103ec74dd37837b70e">NumEntries</a> and <a href="#aa65910538ca9fe224414a15b68bdcf33">ValueCounts</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CountSum {#aa86b18bf848839782dee252ea6871d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::CountSumOrPercent::CountSum = 0.0f</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 748 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a394f37e06a6020180554dbe4a23bb3b8">llvm::InstrProfRecord::accumulateCounts</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a0890bbfe709e212efce84003c8fb9469">llvm::OverlapStats::addOneMismatch</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a813dbcd2d37d971f1962238891728d87">llvm::OverlapStats::addOneUnique</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ac9be35ce19db0a3b6de2350b5c2820f3">llvm::InstrProfRecord::overlap</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2882c6d2a257083c160385fe493c0cf2">llvm::InstrProfWriter::overlapRecord</a> and <a href="#a5c4c5de0fc261ffb52e7bf28489ccb16">reset</a>.</p>

</div>
</div>

### NumEntries {#ac6ee8e5f865571103ec74dd37837b70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CountSumOrPercent::NumEntries = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofreader/#af8e0c59b9bcc7888f39284b3fc417834">llvm::InstrProfReader::accumulateCounts</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a394f37e06a6020180554dbe4a23bb3b8">llvm::InstrProfRecord::accumulateCounts</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#ac9be35ce19db0a3b6de2350b5c2820f3">llvm::InstrProfRecord::overlap</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2882c6d2a257083c160385fe493c0cf2">llvm::InstrProfWriter::overlapRecord</a> and <a href="#a5c4c5de0fc261ffb52e7bf28489ccb16">reset</a>.</p>

</div>
</div>

### ValueCounts {#aa65910538ca9fe224414a15b68bdcf33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;double, IPVK_Last - IPVK_First + 1&gt; llvm::CountSumOrPercent::ValueCounts = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a394f37e06a6020180554dbe4a23bb3b8">llvm::InstrProfRecord::accumulateCounts</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a0890bbfe709e212efce84003c8fb9469">llvm::OverlapStats::addOneMismatch</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a813dbcd2d37d971f1962238891728d87">llvm::OverlapStats::addOneUnique</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord/#abb70319c5b094f62ab7ad31eb00cec10">llvm::InstrProfValueSiteRecord::overlap</a> and <a href="#a5c4c5de0fc261ffb52e7bf28489ccb16">reset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
