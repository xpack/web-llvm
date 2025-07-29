---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/sampleprofutil
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `sampleprofutil` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::sampleprofutil { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprofutil/samplecoveragetracker">SampleCoverageTracker</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6789a9522443425d339fa34c25f89d5">callsiteIsHot</a> (const FunctionSamples *CallsiteFS, ProfileSummaryInfo *PSI, bool ProfAccForSymsInList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given callsite is hot wrt to hot cutoff threshold. <a href="#ab6789a9522443425d339fa34c25f89d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9495513e04a8f797cc8723887bdbd13c">createFSDiscriminatorVariable</a> (Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a global variable to flag FSDiscriminators are used. <a href="#a9495513e04a8f797cc8723887bdbd13c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### callsiteIsHot() {#ab6789a9522443425d339fa34c25f89d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprofutil::callsiteIsHot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * CallsiteFS, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, bool ProfAccForSymsInList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given callsite is hot wrt to hot cutoff threshold.</p>


<p>Functions that were inlined in the original binary will be represented in the inline stack in the sample profile. If the profile shows that the original inline decision was "good" (i.e., the callsite is executed frequently), then we will recreate the inline decision and apply the profile from the inlined callsite.</p>


<p>To decide whether an inlined callsite is hot, we compare the callsite sample count with the hot cutoff computed by <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a>, it is regarded as hot if the count is above the cutoff value.</p>


<p>When ProfileAccurateForSymsInList is enabled and profile symbol list is present, functions in the profile symbol list but without profile will be regarded as cold and much less inlining will happen in CGSCC inlining pass, so we tend to lower the hot criteria here to allow more early inlining to happen for warm callsites and it is helpful for performance.</p>


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileloaderbaseutil-cpp">SampleProfileLoaderBaseUtil.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adb2786061d3e569b42b7d661ccc57484">llvm::sampleprof::FunctionSamples::getTotalSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a5f58eb949321536363605ac9920a95cb">llvm::ProfileSummaryInfo::isColdCount</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#ac46d4d55dd867977ba88d57a170e31de">llvm::ProfileSummaryInfo::isHotCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprofutil/samplecoveragetracker/#a115955d2509b80c7c2c435899404b086">llvm::sampleprofutil::SampleCoverageTracker::countBodyRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofutil/samplecoveragetracker/#a982cd37395d6c62bb2030d3e1b09b4d0">llvm::sampleprofutil::SampleCoverageTracker::countBodySamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofutil/samplecoveragetracker/#a3dd722b8bbc4b043fd9a360f68aead04">llvm::sampleprofutil::SampleCoverageTracker::countUsedRecords</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>.</p>

</div>
</div>

### createFSDiscriminatorVariable() {#a9495513e04a8f797cc8723887bdbd13c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprofutil::createFSDiscriminatorVariable (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a global variable to flag FSDiscriminators are used.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileloaderbaseutil-cpp">SampleProfileLoaderBaseUtil.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae879dd14ccc28696f3d8c7b484df3c9a">llvm::appendToUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/adddiscriminators-cpp/#a6201294406f0d7ffae87b86d867045f8">addDiscriminators</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileloaderbaseutil-cpp">SampleProfileLoaderBaseUtil.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
