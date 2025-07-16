---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MFMAExpInterleaveOpt` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f405c4de8708db5a8a032f1df2f800a">MFMAExpInterleaveOpt</a> (ScheduleDAGInstrs *DAG, const SIInstrInfo *TII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6408fc489174e716ac25f42b8237203f">applyIGLPStrategy</a> (DenseMap&lt; int, SUnitsToCandidateSGsMap &gt; &amp;SyncedInstrs, DenseMap&lt; int, SmallVector&lt; SchedGroup, 4 &gt; &gt; &amp;SyncedSchedGroups, AMDGPU::SchedulingPhase Phase) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add SchedGroups to <span class="doxyComputerOutput">SyncedSchedGroups</span> to implement this Strategy. <a href="#a6408fc489174e716ac25f42b8237203f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae198d40c5758c4e0f18a7467c0d4151">shouldApplyStrategy</a> (ScheduleDAGInstrs *DAG, AMDGPU::SchedulingPhase Phase) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedb7d27d08102accb77cd0556cec561f">analyzeDAG</a> (const SIInstrInfo *TII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af77524829414a6d5914432c091cdb4">MFMAChainSeeds</a></td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaafc5440b7bf74f295fb3a91da382afc">TransPipeCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504d138a1a3e5570adfcdf0433028e02">MFMAPipeCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a089565407d957858abe9074a3f351">AddPipeCount</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa16740874621d47fbbd860166c5c1eb">MFMAEnablement</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ddb1fd80b287b3a235cec2b38e6b0e">ExpRequirement</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae803e893ad5a76f04c0cec9a3c46f3">MFMAChains</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560cfc61e34fbf1594304b647d10e8a4">MFMAChainLength</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bbf3987ed80f53db7abb48ba2ebafcb">HasCvt</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8883c058b286a0d4215b2ebfe3ea5ab3">HasChainBetweenCvt</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2abc8ab7f0705993d15c403eacaaebf">FirstPipeDSR</a> = std::nullopt</td>
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


<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MFMAExpInterleaveOpt() {#a9f405c4de8708db5a8a032f1df2f800a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAExpInterleaveOpt (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII)</td>
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



<p>Definition at line 1328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#aa732d05ffff7be6cbcdcc3895d2524c8">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::DAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a3d3ed8371fe5d64a747693292effab0a">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::IGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a4e5b84c5ed9425486daec9a8a96368b7">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::IsBottomUp</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a787d4f8409dfc44376a67ab93559b671">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyIGLPStrategy() {#a6408fc489174e716ac25f42b8237203f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::applyIGLPStrategy (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a37453daec809dace88b09dcab3ffccca">SUnitsToCandidateSGsMap</a> &gt; &amp; SyncedInstrs, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup">SchedGroup</a>, 4 &gt; &gt; &amp; SyncedSchedGroups, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08">AMDGPU::SchedulingPhase</a> Phase)</td>
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

<p>Definition at line 1320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#aac3fdb37ad3151631a0ac14614e11a53">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::addRule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#aa732d05ffff7be6cbcdcc3895d2524c8">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::DAG</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fad0bc65265d9dde1af1c3346f6e178c79">anonymous{AMDGPUIGroupLP.cpp}::DS_READ</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a95219a47b481f6ac62ed85fa7d595b39">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::getSGID</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a0c0110e7049326bfe58cc58bc023a76e">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::getSyncID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a4aea1667f25dae0657fb81502aa11e29">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::initSchedGroup</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fafad0f3826ff232c44b55c89c333e115a">anonymous{AMDGPUIGroupLP.cpp}::MFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08a352cc1831da7694e67bfa9c7fdfa3e7f">llvm::AMDGPU::PostRA</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a787d4f8409dfc44376a67ab93559b671">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::TII</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fad48c2c30968608d3e45c9beb0433a062">anonymous{AMDGPUIGroupLP.cpp}::TRANS</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fa4832099d4d5fd99d291138b0a0a2bd70">anonymous{AMDGPUIGroupLP.cpp}::VALU</a>.</p>

</div>
</div>

### shouldApplyStrategy() {#aae198d40c5758c4e0f18a7467c0d4151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::shouldApplyStrategy (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08">AMDGPU::SchedulingPhase</a> Phase)</td>
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



<p>Definition at line 1325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#aa732d05ffff7be6cbcdcc3895d2524c8">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08a352cc1831da7694e67bfa9c7fdfa3e7f">llvm::AMDGPU::PostRA</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a787d4f8409dfc44376a67ab93559b671">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyzeDAG() {#aedb7d27d08102accb77cd0556cec561f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::analyzeDAG (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 918 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MFMAChainSeeds {#a1af77524829414a6d5914432c091cdb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SUnit *, 4&gt; anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAChainSeeds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 915 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AddPipeCount {#a72a089565407d957858abe9074a3f351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::AddPipeCount = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

### ExpRequirement {#a39ddb1fd80b287b3a235cec2b38e6b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::ExpRequirement = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

### FirstPipeDSR {#ad2abc8ab7f0705993d15c403eacaaebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::FirstPipeDSR = std::nullopt</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

### HasChainBetweenCvt {#a8883c058b286a0d4215b2ebfe3ea5ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::HasChainBetweenCvt = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

### HasCvt {#a9bbf3987ed80f53db7abb48ba2ebafcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::HasCvt = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

### MFMAChainLength {#a560cfc61e34fbf1594304b647d10e8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAChainLength = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

### MFMAChains {#aeae803e893ad5a76f04c0cec9a3c46f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAChains = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

### MFMAEnablement {#afa16740874621d47fbbd860166c5c1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAEnablement = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

### MFMAPipeCount {#a504d138a1a3e5570adfcdf0433028e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAPipeCount = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 896 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

### TransPipeCount {#aaafc5440b7bf74f295fb3a91da382afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::TransPipeCount = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 894 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
