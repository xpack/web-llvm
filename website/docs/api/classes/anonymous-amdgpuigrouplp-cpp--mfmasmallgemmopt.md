---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmopt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MFMASmallGemmOpt` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy">IGLPStrategy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6499f74637e6a433bf9311d355f95f01">MFMASmallGemmOpt</a> (ScheduleDAGInstrs *DAG, const SIInstrInfo *TII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d621f8332bffbbc223f439b35f4300e">applyIGLPStrategy</a> (DenseMap&lt; int, SUnitsToCandidateSGsMap &gt; &amp;SyncedInstrs, DenseMap&lt; int, SmallVector&lt; SchedGroup, 4 &gt; &gt; &amp;SyncedSchedGroups, AMDGPU::SchedulingPhase Phase) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add SchedGroups to <span class="doxyComputerOutput">SyncedSchedGroups</span> to implement this Strategy. <a href="#a1d621f8332bffbbc223f439b35f4300e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f98bf828f8ed01ce8ba066b17677a96">shouldApplyStrategy</a> (ScheduleDAGInstrs *DAG, AMDGPU::SchedulingPhase Phase) override</td>
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


<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MFMASmallGemmOpt() {#a6499f74637e6a433bf9311d355f95f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::MFMASmallGemmOpt (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII)</td>
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



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#aa732d05ffff7be6cbcdcc3895d2524c8">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::DAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a3d3ed8371fe5d64a747693292effab0a">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::IGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a4e5b84c5ed9425486daec9a8a96368b7">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::IsBottomUp</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a787d4f8409dfc44376a67ab93559b671">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyIGLPStrategy() {#a1d621f8332bffbbc223f439b35f4300e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::applyIGLPStrategy (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a37453daec809dace88b09dcab3ffccca">SUnitsToCandidateSGsMap</a> &gt; &amp; SyncedInstrs, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup">SchedGroup</a>, 4 &gt; &gt; &amp; SyncedSchedGroups, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08">AMDGPU::SchedulingPhase</a> Phase)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add SchedGroups to <span class="doxyComputerOutput">SyncedSchedGroups</span> to implement this Strategy.</p>

<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#aa732d05ffff7be6cbcdcc3895d2524c8">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::DAG</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fa47b79bd259e22596ffc4be2ffbbe5c5a">anonymous{AMDGPUIGroupLP.cpp}::DS</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a0c0110e7049326bfe58cc58bc023a76e">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::getSyncID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a4aea1667f25dae0657fb81502aa11e29">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::initSchedGroup</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fafad0f3826ff232c44b55c89c333e115a">anonymous{AMDGPUIGroupLP.cpp}::MFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a787d4f8409dfc44376a67ab93559b671">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::TII</a>.</p>

</div>
</div>

### shouldApplyStrategy() {#a8f98bf828f8ed01ce8ba066b17677a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::shouldApplyStrategy (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08">AMDGPU::SchedulingPhase</a> Phase)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#aa732d05ffff7be6cbcdcc3895d2524c8">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::DAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
