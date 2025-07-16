---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/misexpect
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `misexpect` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::misexpect { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62ecd68a608ec120263975c279ae3dab">checkBackendInstrumentation</a> (Instruction &amp;I, const llvm::ArrayRef&lt; uint32_t &gt; RealWeights)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkBackendInstrumentation - compares PGO counters to the thresholds used for llvm.expect and warns if the PGO counters are outside of the expected range. <a href="#a62ecd68a608ec120263975c279ae3dab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21de4796e674d8dabcea69242abe5005">checkFrontendInstrumentation</a> (Instruction &amp;I, const ArrayRef&lt; uint32_t &gt; ExpectedWeights)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkFrontendInstrumentation - compares PGO counters to the thresholds used for llvm.expect and warns if the PGO counters are outside of the expected range. <a href="#a21de4796e674d8dabcea69242abe5005">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8677c5d2618fcf52eda43f5530decb6b">verifyMisExpect</a> (Instruction &amp;I, ArrayRef&lt; uint32_t &gt; RealWeights, const ArrayRef&lt; uint32_t &gt; ExpectedWeights)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>veryifyMisExpect - compares RealWeights to the thresholds used for llvm.expect and warns if the PGO counters are outside of the expected range. <a href="#a8677c5d2618fcf52eda43f5530decb6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c52059f91406714507309d168ff95b8">checkExpectAnnotations</a> (Instruction &amp;I, const ArrayRef&lt; uint32_t &gt; ExistingWeights, bool IsFrontend)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkExpectAnnotations - compares PGO counters to the thresholds used for llvm.expect and warns if the PGO counters are outside of the expected range. <a href="#a4c52059f91406714507309d168ff95b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### checkBackendInstrumentation() {#a62ecd68a608ec120263975c279ae3dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::misexpect::checkBackendInstrumentation (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; uint32_t &gt; RealWeights)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>checkBackendInstrumentation - compares PGO counters to the thresholds used for llvm.expect and warns if the PGO counters are outside of the expected range.</p>


<p>It extracts the expected weights from the MD_prof weights attached to the instruction, which are assumed to come from lowered llvm.expect intrinsics. The RealWeights parameter and the extracted expected weights are then passed to verifyMisexpect() for verification</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> being checked</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RealWeights</td>
<td class="doxyParamItemDescription"><p>A vector of profile weights for each target block</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/misexpect-cpp">MisExpect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac19cbbc4935a23e1d44f65e1eaba6b1d">llvm::extractBranchWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4a3bd60427b33355559566bdec3c9f90">llvm::hasBranchWeightOrigin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a8677c5d2618fcf52eda43f5530decb6b">verifyMisExpect</a>.</p>


<p>Referenced by <a href="#a4c52059f91406714507309d168ff95b8">checkExpectAnnotations</a>.</p>

</div>
</div>

### checkExpectAnnotations() {#a4c52059f91406714507309d168ff95b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::misexpect::checkExpectAnnotations (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; ExistingWeights, bool IsFrontend)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>checkExpectAnnotations - compares PGO counters to the thresholds used for llvm.expect and warns if the PGO counters are outside of the expected range.</p>


<p>It extracts the expected weights from the MD_prof weights attached to the instruction, which are assumed to come from lowered llvm.expect intrinsics. The RealWeights parameter and the extracted expected weights are then passed to verifyMisexpect() for verification. It is a thin wrapper around the checkFrontendInstrumentation and checkBackendInstrumentation APIs</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> being checked</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExistingWeights</td>
<td class="doxyParamItemDescription"><p>A vector of profile weights for each target block</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsFrontend</td>
<td class="doxyParamItemDescription"><p>A boolean describing if this is Frontend instrumentation</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/misexpect-cpp">MisExpect.cpp</a>.</p>


<p>References <a href="#a62ecd68a608ec120263975c279ae3dab">checkBackendInstrumentation</a>, <a href="#a21de4796e674d8dabcea69242abe5005">checkFrontendInstrumentation</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#ab61a60817533b84f369d2623e0593ec7">handleSwitchExpect</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad272ce4631595e235e560baf59dc1ffd">llvm::setProfMetadata</a>.</p>

</div>
</div>

### checkFrontendInstrumentation() {#a21de4796e674d8dabcea69242abe5005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::misexpect::checkFrontendInstrumentation (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; ExpectedWeights)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>checkFrontendInstrumentation - compares PGO counters to the thresholds used for llvm.expect and warns if the PGO counters are outside of the expected range.</p>


<p>It extracts the expected weights from the MD_prof weights attached to the instruction, which are assumed to come from profiling data attached by the frontend prior to llvm.expect intrinsic lowering. The ExpectedWeights parameter and the extracted real weights are then passed to verifyMisexpect() for verification</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> being checked</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExpectedWeights</td>
<td class="doxyParamItemDescription"><p>A vector of the expected weights for each target block, this determines the threshold values used when emitting diagnostics</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/misexpect-cpp">MisExpect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac19cbbc4935a23e1d44f65e1eaba6b1d">llvm::extractBranchWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a8677c5d2618fcf52eda43f5530decb6b">verifyMisExpect</a>.</p>


<p>Referenced by <a href="#a4c52059f91406714507309d168ff95b8">checkExpectAnnotations</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a6ac9067dc7c125cd83855df3e480e04c">handleBrSelExpect</a>.</p>

</div>
</div>

### verifyMisExpect() {#a8677c5d2618fcf52eda43f5530decb6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::misexpect::verifyMisExpect (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; RealWeights, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; ExpectedWeights)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>veryifyMisExpect - compares RealWeights to the thresholds used for llvm.expect and warns if the PGO counters are outside of the expected range.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">I</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> being checked</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RealWeights</td>
<td class="doxyParamItemDescription"><p>A vector of profile weights from the profile data</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExpectedWeights</td>
<td class="doxyParamItemDescription"><p>A vector of the weights attatch by llvm.expect</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/misexpect-cpp">MisExpect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a0333345669e75a54c7de3d5fe0f6e746">llvm::BranchProbability::getBranchProbability</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aae93c90b6047163d33af8cc1bd57a193">LikelyBranchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a351a1280d0bfece4f72e806eba12d284">UnlikelyBranchWeight</a>.</p>


<p>Referenced by <a href="#a62ecd68a608ec120263975c279ae3dab">checkBackendInstrumentation</a> and <a href="#a21de4796e674d8dabcea69242abe5005">checkFrontendInstrumentation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/misexpect-cpp">MisExpect.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
