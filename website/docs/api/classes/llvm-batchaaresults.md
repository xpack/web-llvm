---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/batchaaresults
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BatchAAResults` Class

<p>This class is a wrapper over an <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a>, and it is intended to be used only when there are no IR changes inbetween queries. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BatchAAResults { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d71ed97284d930cf65f86bdc35c1dce">BatchAAResults</a> (AAResults &amp;AAR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9678b5a4526dd6fc9d3ad3fe8ac144ed">BatchAAResults</a> (AAResults &amp;AAR, CaptureAnalysis *CA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aliasresult">AliasResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2afd85d1ce874e1dd6391c967101d3b8">alias</a> (const MemoryLocation &amp;LocA, const MemoryLocation &amp;LocB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeab639d4ce23039f7777ba26b24cb77">pointsToConstantMemory</a> (const MemoryLocation &amp;Loc, bool OrLocal=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1cf15d168b6004e6bd3fe53edfc4c48">pointsToConstantMemory</a> (const Value *P, bool OrLocal=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2a774dba86bfeea3d8843822a974fe2">getModRefInfoMask</a> (const MemoryLocation &amp;Loc, bool IgnoreLocals=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa0be41805b25d9577d6f15d148a0d7">getModRefInfo</a> (const Instruction *I, const std::optional&lt; MemoryLocation &gt; &amp;OptLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb141d4c096a2e09647ae1b9f316007c">getModRefInfo</a> (const Instruction *I, const CallBase *Call2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf5c46dea9d1817b16f69b7173ed352">getArgModRefInfo</a> (const CallBase *Call, unsigned ArgIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13f9609022db240b25a69c0390efc03">getMemoryEffects</a> (const CallBase *Call)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ba3a606a0299b684755f56b1d2f1c7">isMustAlias</a> (const MemoryLocation &amp;LocA, const MemoryLocation &amp;LocB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5fc7dbdc17cdbefcd19aaa4026796fb">isMustAlias</a> (const Value *V1, const Value *V2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd4f3646c99afe025bb56fe416326c59">isNoAlias</a> (const MemoryLocation &amp;LocA, const MemoryLocation &amp;LocB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa44555b5242035c9df7941911186c44">callCapturesBefore</a> (const Instruction *I, const MemoryLocation &amp;MemLoc, DominatorTree *DT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb2b91dc90c5216adf731e436eedf5a">enableCrossIterationMode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assume that values may come from different cycle iterations. <a href="#a9cb2b91dc90c5216adf731e436eedf5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a939798bd527ba3029bf75f2671b815ac">disableDominatorTree</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable the use of the dominator tree during alias analysis queries. <a href="#a939798bd527ba3029bf75f2671b815ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c894be0e9ced3f5048926bb28720402">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82003efc7184d7a933bb6123e169af55">AAQI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simplecaptureanalysis">SimpleCaptureAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a907f29235a1e09ae8cb8e217105b45ff">SimpleCA</a></td>
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

<p>This class is a wrapper over an <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a>, and it is intended to be used only when there are no IR changes inbetween queries.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> is reusing the same <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/aaqueryinfo">AAQueryInfo</a></span> to preserve the state across queries, esentially making <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> work in "batch mode". The internal state cannot be cleared, so to go "out-of-batch-mode", the user must either use <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a>, or create a new <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a>.</p>


<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BatchAAResults() {#a3d71ed97284d930cf65f86bdc35c1dce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BatchAAResults::BatchAAResults (<a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AAR)</td>
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



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### BatchAAResults() {#a9678b5a4526dd6fc9d3ad3fe8ac144ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BatchAAResults::BatchAAResults (<a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp; AAR, <a href="/web-llvm/docs/api/structs/llvm/captureanalysis">CaptureAnalysis</a> * CA)</td>
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



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### alias() {#a2afd85d1ce874e1dd6391c967101d3b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasResult llvm::BatchAAResults::alias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocB)</td>
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



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#ac33670a87c023e6ae45daf3df0a4cd1e">canSkipClobberingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>, <a href="#ab9ba3a606a0299b684755f56b1d2f1c7">isMustAlias</a>, <a href="#ad5fc7dbdc17cdbefcd19aaa4026796fb">isMustAlias</a> and <a href="#acd4f3646c99afe025bb56fe416326c59">isNoAlias</a>.</p>

</div>
</div>

### callCapturesBefore() {#afa44555b5242035c9df7941911186c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::BatchAAResults::callCapturesBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; MemLoc, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
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



<p>Definition at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### disableDominatorTree() {#a939798bd527ba3029bf75f2671b815ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BatchAAResults::disableDominatorTree ()</td>
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

<p>Disable the use of the dominator tree during alias analysis queries.</p>

<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>.</p>

</div>
</div>

### enableCrossIterationMode() {#a9cb2b91dc90c5216adf731e436eedf5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BatchAAResults::enableCrossIterationMode ()</td>
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

<p>Assume that values may come from different cycle iterations.</p>

<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### getArgModRefInfo() {#a8cf5c46dea9d1817b16f69b7173ed352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::BatchAAResults::getArgModRefInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call, unsigned ArgIdx)</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### getMemoryEffects() {#ad13f9609022db240b25a69c0390efc03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects llvm::BatchAAResults::getMemoryEffects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call)</td>
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



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### getModRefInfo() {#adfa0be41805b25d9577d6f15d148a0d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::BatchAAResults::getModRefInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &gt; &amp; OptLoc)</td>
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



<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a5c0193fe229d9129ff3f641345ea0066">llvm::sandboxir::Utils::aliasAnalysisGetModRefInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#ac33670a87c023e6ae45daf3df0a4cd1e">canSkipClobberingStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#aa62aa7b8aa53a4cc57ee4397a5221e64">findDominatingValue</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### getModRefInfo() {#abb141d4c096a2e09647ae1b9f316007c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::BatchAAResults::getModRefInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Call2)</td>
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



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getModRefInfoMask() {#af2a774dba86bfeea3d8843822a974fe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModRefInfo llvm::BatchAAResults::getModRefInfoMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, bool IgnoreLocals=false)</td>
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



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### isMustAlias() {#ab9ba3a606a0299b684755f56b1d2f1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BatchAAResults::isMustAlias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocB)</td>
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



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>References <a href="#a2afd85d1ce874e1dd6391c967101d3b8">alias</a> and <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57ac1a99a1af9a4778a61e5cc3e1d622180">llvm::AliasResult::MustAlias</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### isMustAlias() {#ad5fc7dbdc17cdbefcd19aaa4026796fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BatchAAResults::isMustAlias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2)</td>
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



<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>References <a href="#a2afd85d1ce874e1dd6391c967101d3b8">alias</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57ac1a99a1af9a4778a61e5cc3e1d622180">llvm::AliasResult::MustAlias</a> and <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a131715ceeb92fb803a329d6b76d14e0d">llvm::LocationSize::precise</a>.</p>

</div>
</div>

### isNoAlias() {#acd4f3646c99afe025bb56fe416326c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BatchAAResults::isNoAlias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; LocB)</td>
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



<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>References <a href="#a2afd85d1ce874e1dd6391c967101d3b8">alias</a> and <a href="/web-llvm/docs/api/classes/llvm/aliasresult/#a8d3de277fb70fa515efac2db2cfe9d57a863ee317b92588eb2d6878af9fc98922">llvm::AliasResult::NoAlias</a>.</p>

</div>
</div>

### pointsToConstantMemory() {#abeab639d4ce23039f7777ba26b24cb77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BatchAAResults::pointsToConstantMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc, bool OrLocal=false)</td>
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



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae96dbd1485a431400525ca17896ec48e">llvm::isNoModRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a8eaaa1b4edc9934bfea0469269f3d869">getMemCmpLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a> and <a href="#ae1cf15d168b6004e6bd3fe53edfc4c48">pointsToConstantMemory</a>.</p>

</div>
</div>

### pointsToConstantMemory() {#ae1cf15d168b6004e6bd3fe53edfc4c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BatchAAResults::pointsToConstantMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * P, bool OrLocal=false)</td>
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



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46815b7f69bb96eddd2e1e01bec6120c">llvm::MemoryLocation::getBeforeOrAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#abeab639d4ce23039f7777ba26b24cb77">pointsToConstantMemory</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a0c894be0e9ced3f5048926bb28720402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults&amp; llvm::BatchAAResults::AA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### AAQI {#a82003efc7184d7a933bb6123e169af55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAQueryInfo llvm::BatchAAResults::AAQI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

### SimpleCA {#a907f29235a1e09ae8cb8e217105b45ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimpleCaptureAnalysis llvm::BatchAAResults::SimpleCA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">AliasAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
