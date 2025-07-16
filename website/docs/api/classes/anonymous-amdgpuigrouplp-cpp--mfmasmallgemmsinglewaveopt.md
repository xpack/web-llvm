---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MFMASmallGemmSingleWaveOpt` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af484a3f232aeafc63da8565792d2c4aa">MFMASmallGemmSingleWaveOpt</a> (ScheduleDAGInstrs *DAG, const SIInstrInfo *TII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a568501d2ea6d5786f4981de195297020">applyIGLPStrategy</a> (DenseMap&lt; int, SUnitsToCandidateSGsMap &gt; &amp;SyncedInstrs, DenseMap&lt; int, SmallVector&lt; SchedGroup, 4 &gt; &gt; &amp;SyncedSchedGroups, AMDGPU::SchedulingPhase Phase) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add SchedGroups to <span class="doxyComputerOutput">SyncedSchedGroups</span> to implement this Strategy. <a href="#a568501d2ea6d5786f4981de195297020">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0acfeb2a36ba66fea1fd046a1bf3da21">shouldApplyStrategy</a> (ScheduleDAGInstrs *DAG, AMDGPU::SchedulingPhase Phase) override</td>
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


<p>Definition at line 1873 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MFMASmallGemmSingleWaveOpt() {#af484a3f232aeafc63da8565792d2c4aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::MFMASmallGemmSingleWaveOpt (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII)</td>
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



<p>Definition at line 2073 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#aa732d05ffff7be6cbcdcc3895d2524c8">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::DAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a3d3ed8371fe5d64a747693292effab0a">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::IGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a4e5b84c5ed9425486daec9a8a96368b7">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::IsBottomUp</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a787d4f8409dfc44376a67ab93559b671">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::TII</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyIGLPStrategy() {#a568501d2ea6d5786f4981de195297020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a37453daec809dace88b09dcab3ffccca">SUnitsToCandidateSGsMap</a> &gt; &amp; SyncedInstrs, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup">SchedGroup</a>, 4 &gt; &gt; &amp; SyncedSchedGroups, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08">AMDGPU::SchedulingPhase</a> Phase)</td>
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

<p>Definition at line 2063 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#aac3fdb37ad3151631a0ac14614e11a53">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::addRule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#aa732d05ffff7be6cbcdcc3895d2524c8">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::DAG</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fad0bc65265d9dde1af1c3346f6e178c79">anonymous{AMDGPUIGroupLP.cpp}::DS_READ</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fa7d48961954d9bc0dcdecbe2136562aec">anonymous{AMDGPUIGroupLP.cpp}::DS_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#ab94792180e18c6902c5fe46bd3e59555">anonymous{AMDGPUIGroupLP.cpp}::DSWCount</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a9207d782b07bb5fb9218efbf8cd7a655">anonymous{AMDGPUIGroupLP.cpp}::DSWWithPermCount</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#ae5595bdd5cfa571b472a6695ae1f09f1">anonymous{AMDGPUIGroupLP.cpp}::DSWWithSharedVMEMCount</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a95219a47b481f6ac62ed85fa7d595b39">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::getSGID</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a0c0110e7049326bfe58cc58bc023a76e">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::getSyncID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08a4f2a91e15af2631ff9424564b8a45fb2">llvm::AMDGPU::Initial</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup/#a4aea1667f25dae0657fb81502aa11e29">anonymous{AMDGPUIGroupLP.cpp}::SchedGroup::initSchedGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fafad0f3826ff232c44b55c89c333e115a">anonymous{AMDGPUIGroupLP.cpp}::MFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy/#a787d4f8409dfc44376a67ab93559b671">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::TII</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1a245b31aced1374f28f45d2b297f402">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::try_emplace</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fa4832099d4d5fd99d291138b0a0a2bd70">anonymous{AMDGPUIGroupLP.cpp}::VALU</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a09279cda31d6b1b9fb748d7f45d1345fa464bf116f77dbad1433016cc9125d2cd">anonymous{AMDGPUIGroupLP.cpp}::VMEM_READ</a>.</p>

</div>
</div>

### shouldApplyStrategy() {#a0acfeb2a36ba66fea1fd046a1bf3da21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::shouldApplyStrategy (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08">AMDGPU::SchedulingPhase</a> Phase)</td>
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



<p>Definition at line 2068 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
