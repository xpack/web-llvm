---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprofilesummarybuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleProfileSummaryBuilder` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SampleProfileSummaryBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">llvm/ProfileData/ProfileCommon.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder">ProfileSummaryBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbfb3ab120a9cd59c8404b7065230d55">SampleProfileSummaryBuilder</a> (std::vector&lt; uint32_t &gt; Cutoffs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20d61c84972c3e0c411adb569076d78">addRecord</a> (const sampleprof::FunctionSamples &amp;FS, bool isCallsiteSample=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/profilesummary">ProfileSummary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa77c45e5b6c316812092a7e8a1e30143">computeSummaryForProfiles</a> (const sampleprof::SampleProfileMap &amp;Profiles)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/profilesummary">ProfileSummary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1398195ea49701192f046b104172c2db">getSummary</a> ()</td>
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


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SampleProfileSummaryBuilder() {#abbfb3ab120a9cd59c8404b7065230d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SampleProfileSummaryBuilder::SampleProfileSummaryBuilder (std::vector&lt; uint32_t &gt; Cutoffs)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ab24fb220148ef06233b2609976f3da9e">llvm::ProfileSummaryBuilder::ProfileSummaryBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRecord() {#ab20d61c84972c3e0c411adb569076d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileSummaryBuilder::addRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">sampleprof::FunctionSamples</a> &amp; FS, bool isCallsiteSample=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a28089a7d5a36c764dfe33f9f44b47d87">llvm::ProfileSummaryBuilder::addCount</a>, <a href="#ab20d61c84972c3e0c411adb569076d78">addRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa2ccdadcef66b2fc9b3f0fe60045c32c8">llvm::sampleprof::ContextDuplicatedIntoBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a72a11c11194d7fa532931fa9421c7021">llvm::ProfileSummaryBuilder::MaxFunctionCount</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ac145bd9c0722766b91ad79062cb1028f">llvm::ProfileSummaryBuilder::NumFunctions</a>.</p>


<p>Referenced by <a href="#ab20d61c84972c3e0c411adb569076d78">addRecord</a> and <a href="#aa77c45e5b6c316812092a7e8a1e30143">computeSummaryForProfiles</a>.</p>

</div>
</div>

### computeSummaryForProfiles() {#aa77c45e5b6c316812092a7e8a1e30143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ProfileSummary &gt; SampleProfileSummaryBuilder::computeSummaryForProfiles (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">sampleprof::SampleProfileMap</a> &amp; Profiles)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="#ab20d61c84972c3e0c411adb569076d78">addRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profileconverter/#aa3ffda78d2adde5ff1916294f9fe3488">llvm::sampleprof::ProfileConverter::flattenProfile</a>, <a href="#a1398195ea49701192f046b104172c2db">getSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ac145bd9c0722766b91ad79062cb1028f">llvm::ProfileSummaryBuilder::NumFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirsampleprofile-cpp/#a009775794ead70aa23c76df46ab4ed8a">Profile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a37af40e7dd3519c08eae50c32e923b36">llvm::UseContextLessSummary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a862a85fc052e3da0f7109bc54ef4998d">llvm::sampleprof::SampleProfileReader::computeSummary</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a4f8b2ab39ae70cd859c323fd97219c23">llvm::sampleprof::SampleProfileWriter::computeSummary</a>.</p>

</div>
</div>

### getSummary() {#a1398195ea49701192f046b104172c2db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ProfileSummary &gt; SampleProfileSummaryBuilder::getSummary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a0cf99f7dc09e330137cb10a3a42c12b3">llvm::ProfileSummaryBuilder::computeDetailedSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ad028b48e4b5b572a4d192042c467ac80">llvm::ProfileSummaryBuilder::DetailedSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a1680e5f0b03a6e19ab4b9043a2db4c56">llvm::ProfileSummaryBuilder::MaxCount</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a72a11c11194d7fa532931fa9421c7021">llvm::ProfileSummaryBuilder::MaxFunctionCount</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#adf42bc6121e00b01b160019b4761c546">llvm::ProfileSummaryBuilder::NumCounts</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ac145bd9c0722766b91ad79062cb1028f">llvm::ProfileSummaryBuilder::NumFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#aa5aa682b3904e88749fa973b3da370c2a0c86eaeebf5b6120b601ecc93a1c2e3a">llvm::ProfileSummary::PSK_Sample</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a9f4b516c5122d851880c9e1f2cf59520">llvm::ProfileSummaryBuilder::TotalCount</a>.</p>


<p>Referenced by <a href="#aa77c45e5b6c316812092a7e8a1e30143">computeSummaryForProfiles</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/profilecommon-h">ProfileCommon.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/profilesummarybuilder-cpp">ProfileSummaryBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
