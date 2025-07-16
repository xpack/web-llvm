---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/codemetrics
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CodeMetrics` Struct Reference

<p>Utility to calculate the size and a few similar metrics for a set of basic blocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::CodeMetrics { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">llvm/Analysis/CodeMetrics.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a> (const BasicBlock *BB, const TargetTransformInfo &amp;TTI, const SmallPtrSetImpl&lt; const Value * &gt; &amp;EphValues, bool PrepareForLTO=false, const Loop *L=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add information about a block to the current state. <a href="#a994ac02d488546e86aeb825e0ea88059">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c6a7050c8f07e7d2ddfde7324754722">exposesReturnsTwice</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function contains a call to setjmp or other functions with attribute "returns twice" without having the attribute itself. <a href="#a8c6a7050c8f07e7d2ddfde7324754722">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a8bf935dacd4be0013bb19cc13abdea">isRecursive</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function calls itself. <a href="#a6a8bf935dacd4be0013bb19cc13abdea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61cad01cfbfee0f1ac885df62557c708">notDuplicatable</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function cannot be duplicated. <a href="#a61cad01cfbfee0f1ac885df62557c708">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a177a8536e97483817917ecaa40ca1b69">ConvergenceKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a539f0ecccbdde5c9d4e77a46be69e6d1">Convergence</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a177a8536e97483817917ecaa40ca1b69a6adf97f83acf6453d4a6a4b1070f3754">ConvergenceKind::None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of convergence specified in this function. <a href="#a539f0ecccbdde5c9d4e77a46be69e6d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a128bf8afd69f289270e52c2a0d16af7f">usesDynamicAlloca</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if this function calls alloca (in the C sense). <a href="#a128bf8afd69f289270e52c2a0d16af7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c34d2d9e5ea7c30caf329b1477054a">NumInsts</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Code size cost of the analyzed blocks. <a href="#ae0c34d2d9e5ea7c30caf329b1477054a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3187063809f27321f9126b0aa0086ce7">NumBlocks</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of analyzed blocks. <a href="#a3187063809f27321f9126b0aa0086ce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905cd2deb038f9e0d10ee4a708470943">NumBBInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of basic block code size estimates. <a href="#a905cd2deb038f9e0d10ee4a708470943">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc8cc96b8c58c8515b74daec66c3a072">NumCalls</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the number of calls to 'big' functions. <a href="#abc8cc96b8c58c8515b74daec66c3a072">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698507b39819ac7f07dac62cdf0f78ab">NumInlineCandidates</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of calls to internal functions with a single caller. <a href="#a698507b39819ac7f07dac62cdf0f78ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad02b6db39016732659bee3efde1f9510">NumVectorInsts</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How many instructions produce vector values. <a href="#ad02b6db39016732659bee3efde1f9510">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8510fa518cbd0c195328d2fc8dbb5318">NumRets</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How many 'ret' instructions the blocks contain. <a href="#a8510fa518cbd0c195328d2fc8dbb5318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e174506b52ad46ea1f746a7f727d999">collectEphemeralValues</a> (const Loop *L, AssumptionCache *AC, SmallPtrSetImpl&lt; const Value * &gt; &amp;EphValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect a loop's ephemeral values (those used only by an assume or similar intrinsics in the loop). <a href="#a7e174506b52ad46ea1f746a7f727d999">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fe141dcc45d0acb90cd466649ae556">collectEphemeralValues</a> (const Function *L, AssumptionCache *AC, SmallPtrSetImpl&lt; const Value * &gt; &amp;EphValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect a functions's ephemeral values (those used only by an assume or similar intrinsics in the function). <a href="#a12fe141dcc45d0acb90cd466649ae556">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Utility to calculate the size and a few similar metrics for a set of basic blocks.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### analyzeBasicBlock() {#a994ac02d488546e86aeb825e0ea88059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeMetrics::analyzeBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; EphValues, bool PrepareForLTO=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add information about a block to the current state.</p>


<p>Fill in the current structure with information gleaned from the specified block.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp">CodeMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a177a8536e97483817917ecaa40ca1b69a809610cf3fb9575e6966b37f32d31d51">llvm::Controlled</a>, <a href="#a539f0ecccbdde5c9d4e77a46be69e6d1">Convergence</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a177a8536e97483817917ecaa40ca1b69aa7c5f55ac8484c6e11762713f5478488">llvm::ExtendedLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp/#a89081a9a2d006acd5d4b3c762ba19adb">extendsConvergenceOutsideLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a6a8bf935dacd4be0013bb19cc13abdea">isRecursive</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a177a8536e97483817917ecaa40ca1b69a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="#a61cad01cfbfee0f1ac885df62557c708">notDuplicatable</a>, <a href="#a905cd2deb038f9e0d10ee4a708470943">NumBBInsts</a>, <a href="#a3187063809f27321f9126b0aa0086ce7">NumBlocks</a>, <a href="#abc8cc96b8c58c8515b74daec66c3a072">NumCalls</a>, <a href="#a698507b39819ac7f07dac62cdf0f78ab">NumInlineCandidates</a>, <a href="#ae0c34d2d9e5ea7c30caf329b1477054a">NumInsts</a>, <a href="#a8510fa518cbd0c195328d2fc8dbb5318">NumRets</a>, <a href="#ad02b6db39016732659bee3efde1f9510">NumVectorInsts</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba737cfc93e5a2ff961677d57186167e7c">llvm::TargetTransformInfo::TCK_CodeSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a177a8536e97483817917ecaa40ca1b69a3cbc75230c11ca34e25123273980f413">llvm::Uncontrolled</a> and <a href="#a128bf8afd69f289270e52c2a0d16af7f">usesDynamicAlloca</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Convergence {#a539f0ecccbdde5c9d4e77a46be69e6d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConvergenceKind llvm::CodeMetrics::Convergence = <a href="/web-llvm/docs/api/namespaces/llvm/#a177a8536e97483817917ecaa40ca1b69a6adf97f83acf6453d4a6a4b1070f3754">ConvergenceKind::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The kind of convergence specified in this function.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### exposesReturnsTwice {#a8c6a7050c8f07e7d2ddfde7324754722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeMetrics::exposesReturnsTwice = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function contains a call to setjmp or other functions with attribute "returns twice" without having the attribute itself.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>

</div>
</div>

### isRecursive {#a6a8bf935dacd4be0013bb19cc13abdea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeMetrics::isRecursive = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function calls itself.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### notDuplicatable {#a61cad01cfbfee0f1ac885df62557c708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeMetrics::notDuplicatable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function cannot be duplicated.</p>


<p>True if this function contains one or more indirect branches, or it contains one or more 'noduplicate' instructions.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### NumBBInsts {#a905cd2deb038f9e0d10ee4a708470943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, InstructionCost&gt; llvm::CodeMetrics::NumBBInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of basic block code size estimates.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### NumBlocks {#a3187063809f27321f9126b0aa0086ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CodeMetrics::NumBlocks = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of analyzed blocks.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### NumCalls {#abc8cc96b8c58c8515b74daec66c3a072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CodeMetrics::NumCalls = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the number of calls to 'big' functions.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### NumInlineCandidates {#a698507b39819ac7f07dac62cdf0f78ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CodeMetrics::NumInlineCandidates = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of calls to internal functions with a single caller.</p>


<p>These are likely targets for future inlining, likely exposed by interleaved devirtualization.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### NumInsts {#ae0c34d2d9e5ea7c30caf329b1477054a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::CodeMetrics::NumInsts = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Code size cost of the analyzed blocks.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### NumRets {#a8510fa518cbd0c195328d2fc8dbb5318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CodeMetrics::NumRets = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How many 'ret' instructions the blocks contain.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### NumVectorInsts {#ad02b6db39016732659bee3efde1f9510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CodeMetrics::NumVectorInsts = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How many instructions produce vector values.</p>


<p>The inliner is more aggressive with inlining vector kernels.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

### usesDynamicAlloca {#a128bf8afd69f289270e52c2a0d16af7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeMetrics::usesDynamicAlloca = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if this function calls alloca (in the C sense).</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>.</p>


<p>Referenced by <a href="#a994ac02d488546e86aeb825e0ea88059">analyzeBasicBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### collectEphemeralValues() {#a7e174506b52ad46ea1f746a7f727d999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeMetrics::collectEphemeralValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; EphValues)</td>
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

<p>Collect a loop's ephemeral values (those used only by an assume or similar intrinsics in the loop).</p>

<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp">CodeMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp/#ada13d2155f1d7c672e7b7134819fc847">appendSpeculatableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache/#a6bc4a01d7ae02545172aaee110d4a01c">llvm::AssumptionCache::assumptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp/#aef97e4d556598a7e91419873352ed1ba">completeEphemeralValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a75514cc4632af88b58a31912c8bd9ecc">anonymous{InlineCost.cpp}::CallAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a8f40b270f64be7a9b63bc9cfb3b2977a">llvm::slpvectorizer::BoUpSLP::BoUpSLP</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ae46906a076a2ec35cf6a38e433b48219">llvm::PPCTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/ivusers/#a37e4d7bb727910e7d12a2439a6c069ca">llvm::IVUsers::IVUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-dfajumpthreading-cpp-/dfajumpthreading/#a858489f4cff24516d6ac192f2165dce2">anonymous{DFAJumpThreading.cpp}::DFAJumpThreading::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionspecializer/#a27893e2167969de71fd88771382a93ad">llvm::FunctionSpecializer::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### collectEphemeralValues() {#a12fe141dcc45d0acb90cd466649ae556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeMetrics::collectEphemeralValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * L, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; EphValues)</td>
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

<p>Collect a functions's ephemeral values (those used only by an assume or similar intrinsics in the function).</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp">CodeMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp/#ada13d2155f1d7c672e7b7134819fc847">appendSpeculatableOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache/#a6bc4a01d7ae02545172aaee110d4a01c">llvm::AssumptionCache::assumptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp/#aef97e4d556598a7e91419873352ed1ba">completeEphemeralValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">CodeMetrics.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp">CodeMetrics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
