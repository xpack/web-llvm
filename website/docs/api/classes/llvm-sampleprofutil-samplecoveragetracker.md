---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprofutil/samplecoveragetracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SampleCoverageTracker` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sampleprofutil::SampleCoverageTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">llvm/Transforms/Utils/SampleProfileLoaderBaseUtil.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada2e5c1756c734b14655435629546d54">BodySampleCoverageMap</a> = std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a>, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a275c12b6d9409c5d92e8fa4a6d99f026">FunctionSamplesCoverageMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *, BodySampleCoverageMap &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb303c9c849d1db014aac9dc66d344c8">markSamplesUsed</a> (const FunctionSamples *FS, uint32_t LineOffset, uint32_t Discriminator, uint64_t Samples)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark as used the sample record for the given function samples at (LineOffset, Discriminator). <a href="#adb303c9c849d1db014aac9dc66d344c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a794d2f372a7bc1e5f5f90bd2bc5ca8d3">computeCoverage</a> (unsigned Used, unsigned Total) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the fraction of sample records used in this profile. <a href="#a794d2f372a7bc1e5f5f90bd2bc5ca8d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd722b8bbc4b043fd9a360f68aead04">countUsedRecords</a> (const FunctionSamples *FS, ProfileSummaryInfo *PSI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of sample records that were applied from this profile. <a href="#a3dd722b8bbc4b043fd9a360f68aead04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a115955d2509b80c7c2c435899404b086">countBodyRecords</a> (const FunctionSamples *FS, ProfileSummaryInfo *PSI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of sample records in the body of this profile. <a href="#a115955d2509b80c7c2c435899404b086">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87f6aca2c16e499ae62a681c9afe9ad8">getTotalUsedSamples</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982cd37395d6c62bb2030d3e1b09b4d0">countBodySamples</a> (const FunctionSamples *FS, ProfileSummaryInfo *PSI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of samples collected in the body of this profile. <a href="#a982cd37395d6c62bb2030d3e1b09b4d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba883bb7e12f0e55cc6739a33ade0044">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaed3f5a638013e8a62cf5e15d4770133">setProfAccForSymsInList</a> (bool V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">FunctionSamplesCoverageMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac33a61e71320f900a0e25e05fb51821d">SampleCoverage</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Coverage map for sampling records. <a href="#ac33a61e71320f900a0e25e05fb51821d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3920b32e680c8d6b70bfabe0d80bae6c">TotalUsedSamples</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of samples used from the profile. <a href="#a3920b32e680c8d6b70bfabe0d80bae6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab4339f8a6226476034e6477007648e6">ProfAccForSymsInList</a> = false</td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BodySampleCoverageMap {#ada2e5c1756c734b14655435629546d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprofutil::SampleCoverageTracker::BodySampleCoverageMap =  std::map&lt;LineLocation, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>.</p>

</div>
</div>

### FunctionSamplesCoverageMap {#a275c12b6d9409c5d92e8fa4a6d99f026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sampleprofutil::SampleCoverageTracker::FunctionSamplesCoverageMap = 
      DenseMap&lt;const FunctionSamples *, BodySampleCoverageMap&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#aba883bb7e12f0e55cc6739a33ade0044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprofutil::SampleCoverageTracker::clear ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>.</p>

</div>
</div>

### computeCoverage() {#a794d2f372a7bc1e5f5f90bd2bc5ca8d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sampleprofutil::SampleCoverageTracker::computeCoverage (unsigned Used, unsigned Total)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the fraction of sample records used in this profile.</p>


<p>The returned value is an unsigned integer in the range 0-100 indicating the percentage of sample records that were used while applying this profile to the associated function.</p>


<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileloaderbaseutil-cpp">SampleProfileLoaderBaseUtil.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>

</div>
</div>

### countBodyRecords() {#a115955d2509b80c7c2c435899404b086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sampleprofutil::SampleCoverageTracker::countBodyRecords (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * FS, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of sample records in the body of this profile.</p>


<p>This count does not include records from cold inlined callsites.</p>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileloaderbaseutil-cpp">SampleProfileLoaderBaseUtil.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprofutil/#ab6789a9522443425d339fa34c25f89d5">llvm::sampleprofutil::callsiteIsHot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a115955d2509b80c7c2c435899404b086">countBodyRecords</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a115955d2509b80c7c2c435899404b086">countBodyRecords</a>.</p>

</div>
</div>

### countBodySamples() {#a982cd37395d6c62bb2030d3e1b09b4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprofutil::SampleCoverageTracker::countBodySamples (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * FS, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of samples collected in the body of this profile.</p>


<p>This count does not include samples from cold inlined callsites.</p>


<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileloaderbaseutil-cpp">SampleProfileLoaderBaseUtil.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprofutil/#ab6789a9522443425d339fa34c25f89d5">llvm::sampleprofutil::callsiteIsHot</a>, <a href="#a982cd37395d6c62bb2030d3e1b09b4d0">countBodySamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>


<p>Referenced by <a href="#a982cd37395d6c62bb2030d3e1b09b4d0">countBodySamples</a>.</p>

</div>
</div>

### countUsedRecords() {#a3dd722b8bbc4b043fd9a360f68aead04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sampleprofutil::SampleCoverageTracker::countUsedRecords (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * FS, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of sample records that were applied from this profile.</p>


<p>This count does not include records from cold inlined callsites.</p>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileloaderbaseutil-cpp">SampleProfileLoaderBaseUtil.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprofutil/#ab6789a9522443425d339fa34c25f89d5">llvm::sampleprofutil::callsiteIsHot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a3dd722b8bbc4b043fd9a360f68aead04">countUsedRecords</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a3dd722b8bbc4b043fd9a360f68aead04">countUsedRecords</a>.</p>

</div>
</div>

### getTotalUsedSamples() {#a87f6aca2c16e499ae62a681c9afe9ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprofutil::SampleCoverageTracker::getTotalUsedSamples ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>.</p>

</div>
</div>

### markSamplesUsed() {#adb303c9c849d1db014aac9dc66d344c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprofutil::SampleCoverageTracker::markSamplesUsed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * FS, uint32_t LineOffset, uint32_t Discriminator, uint64_t Samples)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark as used the sample record for the given function samples at (LineOffset, Discriminator).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this is the first time we mark the given record.</p></dd>
</dl>


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileloaderbaseutil-cpp">SampleProfileLoaderBaseUtil.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>.</p>

</div>
</div>

### setProfAccForSymsInList() {#aaed3f5a638013e8a62cf5e15d4770133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprofutil::SampleCoverageTracker::setProfAccForSymsInList (bool V)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ProfAccForSymsInList {#aab4339f8a6226476034e6477007648e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprofutil::SampleCoverageTracker::ProfAccForSymsInList = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>.</p>

</div>
</div>

### SampleCoverage {#ac33a61e71320f900a0e25e05fb51821d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSamplesCoverageMap llvm::sampleprofutil::SampleCoverageTracker::SampleCoverage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Coverage map for sampling records.</p>


<p>This map keeps a record of sampling records that have been matched to an IR instruction. This is used to detect some form of staleness in profiles (see flag -sample-profile-check-coverage).</p>


<p>Each entry in the map corresponds to a <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> instance. This is another map that counts how many times the sample record at the given location has been used.</p>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>.</p>

</div>
</div>

### TotalUsedSamples {#a3920b32e680c8d6b70bfabe0d80bae6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprofutil::SampleCoverageTracker::TotalUsedSamples = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of samples used from the profile.</p>


<p>When a sampling record is used for the first time, the samples from that record are added to this accumulator. Coverage is later computed based on the total number of samples available in this function and its callsites.</p>


<p>Note that this accumulator tracks samples used from a single function and all the inlined callsites. Strictly, we should have a map of counters keyed by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> pointers, but these stats are cleared after every function, so we just need to keep a single counter.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">SampleProfileLoaderBaseUtil.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sampleprofileloaderbaseutil-cpp">SampleProfileLoaderBaseUtil.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
