---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpuigrouplp-cpp-/iglpstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IGLPStrategy` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt">MFMAExpInterleaveOpt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpsimpleinterleaveopt">MFMAExpSimpleInterleaveOpt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmopt">MFMASmallGemmOpt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt">MFMASmallGemmSingleWaveOpt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d3ed8371fe5d64a747693292effab0a">IGLPStrategy</a> (ScheduleDAGInstrs *DAG, const SIInstrInfo *TII)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdbe9c5a8b008a22c160b943b670555f">~IGLPStrategy</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c63b86fbe06daa2eb7ca61011412065">applyIGLPStrategy</a> (DenseMap&lt; int, SUnitsToCandidateSGsMap &gt; &amp;SyncedInstrs, DenseMap&lt; int, SmallVector&lt; SchedGroup, 4 &gt; &gt; &amp;SyncedSchedGroups, AMDGPU::SchedulingPhase Phase)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add SchedGroups to <span class="doxyComputerOutput">SyncedSchedGroups</span> to implement this Strategy. <a href="#a7c63b86fbe06daa2eb7ca61011412065">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d513e8bff8fea793f7b40765cb895e">shouldApplyStrategy</a> (ScheduleDAGInstrs *DAG, AMDGPU::SchedulingPhase Phase)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e5b84c5ed9425486daec9a8a96368b7">IsBottomUp</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa732d05ffff7be6cbcdcc3895d2524c8">DAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787d4f8409dfc44376a67ab93559b671">TII</a></td>
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


<p>Definition at line 822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IGLPStrategy() {#a3d3ed8371fe5d64a747693292effab0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::IGLPStrategy (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII)</td>
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



<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="#aa732d05ffff7be6cbcdcc3895d2524c8">DAG</a> and <a href="#a787d4f8409dfc44376a67ab93559b671">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt/#a9f405c4de8708db5a8a032f1df2f800a">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAExpInterleaveOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpsimpleinterleaveopt/#acf43edfcb3e4993e10aaf76edf4a102c">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpSimpleInterleaveOpt::MFMAExpSimpleInterleaveOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmopt/#a6499f74637e6a433bf9311d355f95f01">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::MFMASmallGemmOpt</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#af484a3f232aeafc63da8565792d2c4aa">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::MFMASmallGemmSingleWaveOpt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~IGLPStrategy() {#acdbe9c5a8b008a22c160b943b670555f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::~IGLPStrategy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyIGLPStrategy() {#a7c63b86fbe06daa2eb7ca61011412065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::applyIGLPStrategy (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuigrouplp-cpp-/#a37453daec809dace88b09dcab3ffccca">SUnitsToCandidateSGsMap</a> &gt; &amp; SyncedInstrs, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup">SchedGroup</a>, 4 &gt; &gt; &amp; SyncedSchedGroups, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08">AMDGPU::SchedulingPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add SchedGroups to <span class="doxyComputerOutput">SyncedSchedGroups</span> to implement this Strategy.</p>

<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>.</p>

</div>
</div>

### shouldApplyStrategy() {#ae0d513e8bff8fea793f7b40765cb895e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::shouldApplyStrategy (<a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22192a079456492c7a2421c54f749a08">AMDGPU::SchedulingPhase</a> Phase)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>References <a href="#aa732d05ffff7be6cbcdcc3895d2524c8">DAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsBottomUp {#a4e5b84c5ed9425486daec9a8a96368b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::IsBottomUp = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt/#a9f405c4de8708db5a8a032f1df2f800a">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAExpInterleaveOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpsimpleinterleaveopt/#acf43edfcb3e4993e10aaf76edf4a102c">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpSimpleInterleaveOpt::MFMAExpSimpleInterleaveOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmopt/#a6499f74637e6a433bf9311d355f95f01">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::MFMASmallGemmOpt</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#af484a3f232aeafc63da8565792d2c4aa">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::MFMASmallGemmSingleWaveOpt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DAG {#aa732d05ffff7be6cbcdcc3895d2524c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs* anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::DAG</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt/#a6408fc489174e716ac25f42b8237203f">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpsimpleinterleaveopt/#a788937a024c500ad30ebddebf897fc27">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpSimpleInterleaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmopt/#a1d621f8332bffbbc223f439b35f4300e">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="#a3d3ed8371fe5d64a747693292effab0a">IGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt/#a9f405c4de8708db5a8a032f1df2f800a">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAExpInterleaveOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpsimpleinterleaveopt/#acf43edfcb3e4993e10aaf76edf4a102c">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpSimpleInterleaveOpt::MFMAExpSimpleInterleaveOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmopt/#a6499f74637e6a433bf9311d355f95f01">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::MFMASmallGemmOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#af484a3f232aeafc63da8565792d2c4aa">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::MFMASmallGemmSingleWaveOpt</a>, <a href="#ae0d513e8bff8fea793f7b40765cb895e">shouldApplyStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt/#aae198d40c5758c4e0f18a7467c0d4151">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::shouldApplyStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpsimpleinterleaveopt/#a4e3d4b20ab52cf9140ea81156f30eb35">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpSimpleInterleaveOpt::shouldApplyStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmopt/#a8f98bf828f8ed01ce8ba066b17677a96">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::shouldApplyStrategy</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a0acfeb2a36ba66fea1fd046a1bf3da21">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::shouldApplyStrategy</a>.</p>

</div>
</div>

### TII {#a787d4f8409dfc44376a67ab93559b671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* anonymous{AMDGPUIGroupLP.cpp}::IGLPStrategy::TII</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt/#a6408fc489174e716ac25f42b8237203f">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpsimpleinterleaveopt/#a788937a024c500ad30ebddebf897fc27">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpSimpleInterleaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmopt/#a1d621f8332bffbbc223f439b35f4300e">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="#a3d3ed8371fe5d64a747693292effab0a">IGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt/#a9f405c4de8708db5a8a032f1df2f800a">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::MFMAExpInterleaveOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpsimpleinterleaveopt/#acf43edfcb3e4993e10aaf76edf4a102c">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpSimpleInterleaveOpt::MFMAExpSimpleInterleaveOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmopt/#a6499f74637e6a433bf9311d355f95f01">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmOpt::MFMASmallGemmOpt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#af484a3f232aeafc63da8565792d2c4aa">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::MFMASmallGemmSingleWaveOpt</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmaexpinterleaveopt/#aae198d40c5758c4e0f18a7467c0d4151">anonymous{AMDGPUIGroupLP.cpp}::MFMAExpInterleaveOpt::shouldApplyStrategy</a>.</p>

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
