---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/schedulemetrics
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ScheduleMetrics` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ScheduleMetrics { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">Target/AMDGPU/GCNSchedStrategy.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ac41974715c02e74a8fdff68a93639">ScheduleMetrics</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69fea409ec9aa1f1e05906ce964aca6c">ScheduleMetrics</a> (unsigned L, unsigned BC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac07f29240f3967d26791b50b3b4f65c7">getLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28790352c7a40e4fd495a603949968ba">getBubbles</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae07936418f440db324ca02542a0fa200">getMetric</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583c978528cff6ba4178a3b0ed08d0e0">ScheduleLength</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a085a6e98ee11ad58a3703af952da3cc2">BubbleCycles</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad737e526fab5f750adfdbdd427a014fb">ScaleFactor</a> = 100</td>
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


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScheduleMetrics() {#a16ac41974715c02e74a8fdff68a93639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScheduleMetrics::ScheduleMetrics ()</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>

</div>
</div>

### ScheduleMetrics() {#a69fea409ec9aa1f1e05906ce964aca6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScheduleMetrics::ScheduleMetrics (unsigned L, unsigned BC)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBubbles() {#a28790352c7a40e4fd495a603949968ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleMetrics::getBubbles ()</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af74adad07b4aa8e19894b9d480c6d364">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getLength() {#ac07f29240f3967d26791b50b3b4f65c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleMetrics::getLength ()</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af74adad07b4aa8e19894b9d480c6d364">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getMetric() {#ae07936418f440db324ca02542a0fa200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleMetrics::getMetric ()</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Reference <a href="#ad737e526fab5f750adfdbdd427a014fb">ScaleFactor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af74adad07b4aa8e19894b9d480c6d364">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BubbleCycles {#a085a6e98ee11ad58a3703af952da3cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleMetrics::BubbleCycles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>

</div>
</div>

### ScheduleLength {#a583c978528cff6ba4178a3b0ed08d0e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleMetrics::ScheduleLength</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ScaleFactor {#ad737e526fab5f750adfdbdd427a014fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned ScheduleMetrics::ScaleFactor = 100</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a>.</p>


<p>Referenced by <a href="#ae07936418f440db324ca02542a0fa200">getMetric</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a35ad2560fecc16262b15e21c9375cf3d">llvm::GCNSchedStage::getScheduleMetrics</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a741c05e011507c0982568e68fa599a8c">llvm::GCNSchedStage::getScheduleMetrics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74adad07b4aa8e19894b9d480c6d364">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/unclusteredhighrpstage/#a6a4f926bc4da7d151b71ea78aa07f2e6">llvm::UnclusteredHighRPStage::shouldRevertScheduling</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-h">GCNSchedStrategy.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
