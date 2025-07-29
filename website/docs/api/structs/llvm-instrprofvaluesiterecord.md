---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/instrprofvaluesiterecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InstrProfValueSiteRecord` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::InstrProfValueSiteRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79f6a3ee49c597f8d466ccbf7d6579d5">InstrProfValueSiteRecord</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63aafc0b59104c275696ec77eb97bb65">InstrProfValueSiteRecord</a> (std::vector&lt; InstrProfValueData &gt; &amp;&amp;VD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eef97183ed097cb2c34f96885db4b48">sortByTargetValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort ValueData ascending by <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a9eef97183ed097cb2c34f96885db4b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ada73e7701e1a244045e42ac76e4ddc">sortByCount</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort ValueData Descending by Count. <a href="#a1ada73e7701e1a244045e42ac76e4ddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6f26ab27f38303ef9d00f91b2b63d64">merge</a> (InstrProfValueSiteRecord &amp;Input, uint64_t Weight, function_ref&lt; void(instrprof_error)&gt; Warn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge data from another <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord">InstrProfValueSiteRecord</a> Optionally scale merged counts by <span class="doxyComputerOutput">Weight</span>. <a href="#aa6f26ab27f38303ef9d00f91b2b63d64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0859657dd371b027ded06a77e2e75e">scale</a> (uint64_t N, uint64_t D, function_ref&lt; void(instrprof_error)&gt; Warn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scale up value profile data counts by N (Numerator) / D (Denominator). <a href="#afd0859657dd371b027ded06a77e2e75e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb70319c5b094f62ab7ad31eb00cec10">overlap</a> (InstrProfValueSiteRecord &amp;Input, uint32_t ValueKind, OverlapStats &amp;Overlap, OverlapStats &amp;FuncLevelOverlap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the overlap b/w this record and <a href="/web-llvm/docs/api/classes/input">Input</a> record. <a href="#abb70319c5b094f62ab7ad31eb00cec10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; InstrProfValueData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa40cf6a32a17ecd1e62a3cd3494416f4">ValueData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> profiling data pairs at a given value site. <a href="#aa40cf6a32a17ecd1e62a3cd3494416f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrProfValueSiteRecord() {#a79f6a3ee49c597f8d466ccbf7d6579d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfValueSiteRecord::InstrProfValueSiteRecord ()</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#aa6f26ab27f38303ef9d00f91b2b63d64">merge</a> and <a href="#abb70319c5b094f62ab7ad31eb00cec10">overlap</a>.</p>

</div>
</div>

### InstrProfValueSiteRecord() {#a63aafc0b59104c275696ec77eb97bb65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrProfValueSiteRecord::InstrProfValueSiteRecord (std::vector&lt; InstrProfValueData &gt; &amp;&amp; VD)</td>
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



<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Reference <a href="#aa40cf6a32a17ecd1e62a3cd3494416f4">ValueData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### merge() {#aa6f26ab27f38303ef9d00f91b2b63d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfValueSiteRecord::merge (<a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord">InstrProfValueSiteRecord</a> &amp; Input, uint64_t Weight, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086">instrprof_error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge data from another <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord">InstrProfValueSiteRecord</a> Optionally scale merged counts by <span class="doxyComputerOutput">Weight</span>.</p>

<p>Declaration at line 825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a5e8bae22cbd37f66c813d8a3749bda1c">llvm::counter_overflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a79f6a3ee49c597f8d466ccbf7d6579d5">InstrProfValueSiteRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84836a719cdf82a516d556ae66cc8dc0">llvm::SaturatingMultiplyAdd</a>, <a href="#a9eef97183ed097cb2c34f96885db4b48">sortByTargetValues</a> and <a href="#aa40cf6a32a17ecd1e62a3cd3494416f4">ValueData</a>.</p>

</div>
</div>

### overlap() {#abb70319c5b094f62ab7ad31eb00cec10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfValueSiteRecord::overlap (<a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord">InstrProfValueSiteRecord</a> &amp; Input, uint32_t ValueKind, <a href="/web-llvm/docs/api/structs/llvm/overlapstats">OverlapStats</a> &amp; Overlap, <a href="/web-llvm/docs/api/structs/llvm/overlapstats">OverlapStats</a> &amp; FuncLevelOverlap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the overlap b/w this record and <a href="/web-llvm/docs/api/classes/input">Input</a> record.</p>

<p>Declaration at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a439f69d2f637d33a29889fef95c7f0ec">llvm::OverlapStats::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a79f6a3ee49c597f8d466ccbf7d6579d5">InstrProfValueSiteRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a3427e5f987ace470105d11ad6c7a89a1">llvm::OverlapStats::Overlap</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a0e9a9f58836064e628e42236939edbeb">llvm::OverlapStats::score</a>, <a href="#a9eef97183ed097cb2c34f96885db4b48">sortByTargetValues</a>, <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#aeacf37b436c25b1af9f22712417fef6c">llvm::OverlapStats::Test</a>, <a href="/web-llvm/docs/api/structs/llvm/countsumorpercent/#aa65910538ca9fe224414a15b68bdcf33">llvm::CountSumOrPercent::ValueCounts</a> and <a href="#aa40cf6a32a17ecd1e62a3cd3494416f4">ValueData</a>.</p>

</div>
</div>

### scale() {#afd0859657dd371b027ded06a77e2e75e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfValueSiteRecord::scale (uint64_t N, uint64_t D, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086">instrprof_error</a>)&gt; Warn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scale up value profile data counts by N (Numerator) / D (Denominator).</p>

<p>Declaration at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>, definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa218f6b22c8e271f5f9e92aa1fe51086a5e8bae22cbd37f66c813d8a3749bda1c">llvm::counter_overflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6c35ac16c3c23e443f27a025d7a1597">llvm::SaturatingMultiply</a> and <a href="#aa40cf6a32a17ecd1e62a3cd3494416f4">ValueData</a>.</p>

</div>
</div>

### sortByCount() {#a1ada73e7701e1a244045e42ac76e4ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfValueSiteRecord::sortByCount ()</td>
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

<p>Sort ValueData Descending by Count.</p>

<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h/#a308dac27348f416d34602317b56297fb">INSTR_PROF_MAX_NUM_VAL_PER_SITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a> and <a href="#aa40cf6a32a17ecd1e62a3cd3494416f4">ValueData</a>.</p>

</div>
</div>

### sortByTargetValues() {#a9eef97183ed097cb2c34f96885db4b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrProfValueSiteRecord::sortByTargetValues ()</td>
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

<p>Sort ValueData ascending by <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="#aa40cf6a32a17ecd1e62a3cd3494416f4">ValueData</a>.</p>


<p>Referenced by <a href="#aa6f26ab27f38303ef9d00f91b2b63d64">merge</a> and <a href="#abb70319c5b094f62ab7ad31eb00cec10">overlap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ValueData {#aa40cf6a32a17ecd1e62a3cd3494416f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;InstrProfValueData&gt; llvm::InstrProfValueSiteRecord::ValueData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> profiling data pairs at a given value site.</p>

<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a>.</p>


<p>Referenced by <a href="#a63aafc0b59104c275696ec77eb97bb65">InstrProfValueSiteRecord</a>, <a href="#aa6f26ab27f38303ef9d00f91b2b63d64">merge</a>, <a href="#abb70319c5b094f62ab7ad31eb00cec10">overlap</a>, <a href="#afd0859657dd371b027ded06a77e2e75e">scale</a>, <a href="#a1ada73e7701e1a244045e42ac76e4ddc">sortByCount</a> and <a href="#a9eef97183ed097cb2c34f96885db4b48">sortByTargetValues</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">InstrProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprof-cpp">InstrProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
