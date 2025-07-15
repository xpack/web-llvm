---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CallPromotionUtils.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callpromotionutils-h">llvm/Transforms/Utils/CallPromotionUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">llvm/Analysis/CtxProfAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loads-h">llvm/Analysis/Loads.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typemetadatautils-h">llvm/Analysis/TypeMetadataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">llvm/IR/AttributeMask.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/pgoctxprofreader-h">llvm/ProfileData/PGOCtxProfReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51ff57d75f102e980e39535df6ff00bb">fixupPHINodeForNormalDest</a> (InvokeInst *Invoke, BasicBlock *OrigBlock, BasicBlock *MergeBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fix-up phi nodes in an invoke instruction's normal destination. <a href="#a51ff57d75f102e980e39535df6ff00bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59b92d3bbd9b21b61a2afbb73c10c3b0">fixupPHINodeForUnwindDest</a> (InvokeInst *Invoke, BasicBlock *OrigBlock, BasicBlock *ThenBlock, BasicBlock *ElseBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fix-up phi nodes in an invoke instruction's unwind destination. <a href="#a59b92d3bbd9b21b61a2afbb73c10c3b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf3ba57973320bd702d3b12b0b8fa8c">createRetPHINode</a> (Instruction *OrigInst, Instruction *NewInst, BasicBlock *MergeBlock, IRBuilder&lt;&gt; &amp;Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a phi node for the returned value of a call or invoke instruction. <a href="#abdf3ba57973320bd702d3b12b0b8fa8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c9ae0be5e6bcad90cdf141962a117f3">createRetBitCast</a> (CallBase &amp;CB, Type *RetTy, CastInst **RetBitCast)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast a call or invoke instruction to the given type. <a href="#a8c9ae0be5e6bcad90cdf141962a117f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a> (CallBase &amp;CB, Value *Cond, MDNode *BranchWeights)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> and clone the given call site. <a href="#aaabc735841282ccafdf43b7c165b030e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"call-promotion-utils"</td>
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


<div class="doxySectionDef">

## Functions

### createRetBitCast() {#a8c9ae0be5e6bcad90cdf141962a117f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createRetBitCast (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> ** RetBitCast)</td>
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

<p>Cast a call or invoke instruction to the given type.</p>


<p>When promoting a call site, the return type of the call site might not match that of the callee. If this is the case, we have to cast the returned value to the correct type. The location of the cast depends on if we have a call or invoke instruction.</p>


<p>For example, if the call instruction below requires a bitcast after promotion:</p>


<p>orig_bb: t0 = call i32 @func() ...</p>


<p>The bitcast is placed after the call instruction:</p>


<p>orig_bb: ; Uses of the original return value are replaced by uses of the bitcast. t0 = call i32 @func() t1 = bitcast i32 t0 to ... ...</p>


<p>A similar transformation is performed for invoke instructions. However, since invokes are terminating, a new block is created for the bitcast. For example, if the invoke instruction below requires a bitcast after promotion:</p>


<p>orig_bb: t0 = invoke i32 @func() to label normal_dst unwind label unwind_dst</p>


<p>The edge between the original block and the invoke's normal destination is split, and the bitcast is placed there:</p>


<p>orig_bb: t0 = invoke i32 @func() to label split_bb unwind label unwind_dst</p>


<p>split_bb: ; Uses of the original return value are replaced by uses of the bitcast. t1 = bitcast i32 t0 to ... br label normal_dst</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp">CallPromotionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#acdb02479a44bbebcabf8b7b5e1baa921">llvm::CastInst::CreateBitOrPointerCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a1600c7959045cb6b6a5f5a1d427ec67e">llvm::User::replaceUsesOfWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>.</p>

</div>
</div>

### createRetPHINode() {#abdf3ba57973320bd702d3b12b0b8fa8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createRetPHINode (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * OrigInst, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * NewInst, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * MergeBlock, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder)</td>
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

<p>Create a phi node for the returned value of a call or invoke instruction.</p>


<p>After versioning a call or invoke instruction that returns a value, we have to merge the value of the original and new instructions. We do this by creating a phi node and replacing uses of the original instruction with this phi node.</p>


<p>For example, if <span class="doxyComputerOutput">OrigInst</span> is defined in "else_bb" and <span class="doxyComputerOutput">NewInst</span> is defined in "then_bb", we create the following phi node:</p>


<p>; Uses of the original instruction are replaced by uses of the phi node. t0 = phi i32 [ orig_inst, else_bb ], [ new_inst, then_bb ],</p>


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp">CallPromotionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a>.</p>

</div>
</div>

### fixupPHINodeForNormalDest() {#a51ff57d75f102e980e39535df6ff00bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fixupPHINodeForNormalDest (<a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> * Invoke, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OrigBlock, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * MergeBlock)</td>
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

<p>Fix-up phi nodes in an invoke instruction's normal destination.</p>


<p>After versioning an invoke instruction, values coming from the original block will now be coming from the "merge" block. For example, in the code below:</p>


<p>then_bb: t0 = invoke i32 ptr() to label merge_bb unwind label unwind_dst</p>


<p>else_bb: t1 = invoke i32 ptr() to label merge_bb unwind label unwind_dst</p>


<p>merge_bb: t2 = phi i32 [ t0, then_bb ], [ t1, else_bb ] br normal_dst</p>


<p>normal_dst: t3 = phi i32 [ x, orig_bb ], ...</p>


<p>"orig_bb" is no longer a predecessor of "normal_dst", so the phi nodes in "normal_dst" must be fixed to refer to "merge_bb":</p>


<p>normal_dst: t3 = phi i32 [ x, merge_bb ], ...</p>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp">CallPromotionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/invokeinst/#abefe36dd5104481a69ddd11d409abc10">llvm::InvokeInst::getNormalDest</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a>.</p>


<p>Referenced by <a href="#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a>.</p>

</div>
</div>

### fixupPHINodeForUnwindDest() {#a59b92d3bbd9b21b61a2afbb73c10c3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fixupPHINodeForUnwindDest (<a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> * Invoke, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OrigBlock, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ThenBlock, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ElseBlock)</td>
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

<p>Fix-up phi nodes in an invoke instruction's unwind destination.</p>


<p>After versioning an invoke instruction, values coming from the original block will now be coming from either the "then" block or the "else" block. For example, in the code below:</p>


<p>then_bb: t0 = invoke i32 ptr() to label merge_bb unwind label unwind_dst</p>


<p>else_bb: t1 = invoke i32 ptr() to label merge_bb unwind label unwind_dst</p>


<p>unwind_dst: t3 = phi i32 [ x, orig_bb ], ...</p>


<p>"orig_bb" is no longer a predecessor of "unwind_dst", so the phi nodes in "unwind_dst" must be fixed to refer to "then_bb" and "else_bb":</p>


<p>unwind_dst: t3 = phi i32 [ x, then_bb ], [ x, else_bb ], ...</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp">CallPromotionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/invokeinst/#a07cd85c19a9298b5a4fe2abbe29472aa">llvm::InvokeInst::getUnwindDest</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a>.</p>


<p>Referenced by <a href="#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a>.</p>

</div>
</div>

### versionCallSiteWithCond() {#aaabc735841282ccafdf43b7c165b030e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase &amp; versionCallSiteWithCond (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * BranchWeights)</td>
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

<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> and clone the given call site.</p>


<p>This function creates an if-then-else structure at the location of the call site. The "if" condition is specified by <span class="doxyComputerOutput">Cond</span>. The original call site is moved into the "else" block, and a clone of the call site is placed in the "then" block. The cloned instruction is returned.</p>


<p>For example, the call instruction below:</p>


<p>orig_bb: t0 = call i32 ptr() ...</p>


<p>Is replace by the following:</p>


<p>orig_bb: cond = Cond br i1 cond, then_bb, else_bb</p>


<p>then_bb: ; The clone of the original call instruction is placed in the "then" ; block. It is not yet promoted. t1 = call i32 ptr() br merge_bb</p>


<p>else_bb: ; The original call instruction is moved to the "else" block. t0 = call i32 ptr() br merge_bb</p>


<p>merge_bb: ; Uses of the original call instruction are replaced by uses of the phi ; node. t2 = phi i32 [ t0, else_bb ], [ t1, then_bb ] ...</p>


<p>A similar transformation is performed for invoke instructions. However, since invokes are terminating, more work is required. For example, the invoke instruction below:</p>


<p>orig_bb: t0 = invoke ptr() to label normal_dst unwind label unwind_dst</p>


<p>Is replace by the following:</p>


<p>orig_bb: cond = Cond br i1 cond, then_bb, else_bb</p>


<p>then_bb: ; The clone of the original invoke instruction is placed in the "then" ; block, and its normal destination is set to the "merge" block. It is ; not yet promoted. t1 = invoke i32 ptr() to label merge_bb unwind label unwind_dst</p>


<p>else_bb: ; The original invoke instruction is moved into the "else" block, and ; its normal destination is set to the "merge" block. t0 = invoke i32 ptr() to label merge_bb unwind label unwind_dst</p>


<p>merge_bb: ; Uses of the original invoke instruction are replaced by uses of the ; phi node, and the merge block branches to the normal destination. t2 = phi i32 [ t0, else_bb ], [ t1, then_bb ] br normal_dst</p>


<p>An indirect musttail call is processed slightly differently in that:</p>


<ol class="doxyList" type="1">
<li>No merge block needed for the orginal and the cloned callsite, since either one ends the flow. No phi node is needed either.</li>
<li>The return statement following the original call site is duplicated too and placed immediately after the cloned call site per the IR convention.</li>
</ol>

<p>For example, the musttail call instruction below:</p>


<p>orig_bb: t0 = musttail call i32 ptr() ...</p>


<p>Is replaced by the following:</p>


<p>cond_bb: cond = Cond br i1 cond, then_bb, orig_bb</p>


<p>then_bb: ; The clone of the original call instruction is placed in the "then" ; block. It is not yet promoted. t1 = musttail call i32 ptr() ret t1</p>


<p>orig_bb: ; The original call instruction stays in its original block. t0 = musttail call i32 ptr() ret t0</p>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp">CallPromotionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0a4d51e372293abe5e5f6dac133e80a6">llvm::Instruction::clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="#abdf3ba57973320bd702d3b12b0b8fa8c">createRetPHINode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="#a51ff57d75f102e980e39535df6ff00bb">fixupPHINodeForNormalDest</a>, <a href="#a59b92d3bbd9b21b61a2afbb73c10c3b0">fixupPHINodeForUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a50426b12f4acb3d9f74d0778948e9597">llvm::CallBase::isMustTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af67d1f3a518964d80a109bb3d9d5cf1e">llvm::Instruction::moveBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7ac00229d8c59902686f52ed061cdc80">llvm::SplitBlockAndInsertIfThenElse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae529107c3b550f7e2fe6128a26c8f1da">llvm::promoteCallWithVTableCmp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a84163d559062da6b736ab943644e0a16">llvm::versionCallSite</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"call-promotion-utils"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp">CallPromotionUtils.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
