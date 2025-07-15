---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/samplecontexttrimmer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleContextTrimmer` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontexttrimmer">SampleContextTrimmer</a> impelements helper functions to trim, merge cold context profiles. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleContextTrimmer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">llvm/ProfileData/SampleProf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a37a2a94d7c0bbd82687e3b7854b46">SampleContextTrimmer</a> (SampleProfileMap &amp;Profiles)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab47fa20fa1c0dd43ae044963ee59049c">trimAndMergeColdContextProfiles</a> (uint64_t ColdCountThreshold, bool TrimColdContext, bool MergeColdContext, uint32_t ColdContextFrameLength, bool TrimBaseProfileOnly)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9a259e05c328dee793000b98d8bc07">ProfileMap</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontexttrimmer">SampleContextTrimmer</a> impelements helper functions to trim, merge cold context profiles.</p>


<p>It also supports context profile canonicalization to make sure ProfileMap's key is consistent with FunctionSample's name/context.</p>


<p>Definition at line 1375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SampleContextTrimmer() {#a70a37a2a94d7c0bbd82687e3b7854b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleContextTrimmer::SampleContextTrimmer (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; Profiles)</td>
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



<p>Definition at line 1377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### trimAndMergeColdContextProfiles() {#ab47fa20fa1c0dd43ae044963ee59049c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleContextTrimmer::trimAndMergeColdContextProfiles (uint64_t ColdCountThreshold, bool TrimColdContext, bool MergeColdContext, uint32_t ColdContextFrameLength, bool TrimBaseProfileOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>, definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp/#a17e9acf4f2e3f412e4af1da184beac9a">ColdCountThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap/#a21711def0b8514183a4394a50e525e81">llvm::sampleprof::SampleProfileMap::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adb2786061d3e569b42b7d661ccc57484">llvm::sampleprof::FunctionSamples::getTotalSamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adfcf1b41d1251eac2f16312eec52b45a">llvm::sampleprof::FunctionSamples::merge</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca341f13af8fa5d6c42e361bcf419abcff">llvm::sampleprof::MergedContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ProfileMap {#a2d9a259e05c328dee793000b98d8bc07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleProfileMap&amp; llvm::sampleprof::SampleContextTrimmer::ProfileMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprof-cpp">SampleProf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
