---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-promotememorytoregister-cpp-/allocainfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AllocaInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af92bd826e452bca7dd9a17645b0a9c86">DbgUserVec</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a> *, 1 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bda92b1076ceabc0f7dc0026215bca8">DPUserVec</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *, 1 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a> (AllocaInst *AI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan the uses of the specified alloca, filling in the <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/allocainfo">AllocaInfo</a> used by the rest of the pass to reason about the uses of this alloca. <a href="#aed57a9dd738a483f6ac02904b981c94d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38629ecb438041843cbb54c99392af7d">DefiningBlocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ccb40a621418ae685d490be9a883cd6">UsingBlocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e4a8667412a4827dafe780069e672a9">OnlyStore</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85738eb1a501216794d170a273c68309">OnlyBlock</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb70e236519f5b4e4896c60610b175e">OnlyUsedInOneBlock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af92bd826e452bca7dd9a17645b0a9c86">DbgUserVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef169a6a4e10355b9647a624f28f79c1">DbgUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug users of the alloca - does not include dbg.assign intrinsics. <a href="#aef169a6a4e10355b9647a624f28f79c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7bda92b1076ceabc0f7dc0026215bca8">DPUserVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47fd4faf1faf8974cb0e7873a01894d8">DPUsers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/assignmenttrackinginfo">AssignmentTrackingInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba65788ec2b9209b64ebe06e3109c318">AssignmentTracking</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to update assignment tracking debug info. <a href="#aba65788ec2b9209b64ebe06e3109c318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DbgUserVec {#af92bd826e452bca7dd9a17645b0a9c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::DbgUserVec =  SmallVector&lt;DbgVariableIntrinsic *, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### DPUserVec {#a7bda92b1076ceabc0f7dc0026215bca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::DPUserVec =  SmallVector&lt;DbgVariableRecord *, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AnalyzeAlloca() {#aed57a9dd738a483f6ac02904b981c94d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::AnalyzeAlloca (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI)</td>
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

<p>Scan the uses of the specified alloca, filling in the <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/allocainfo">AllocaInfo</a> used by the rest of the pass to reason about the uses of this alloca.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>References <a href="#aba65788ec2b9209b64ebe06e3109c318">AssignmentTracking</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a>, <a href="#aef169a6a4e10355b9647a624f28f79c1">DbgUsers</a>, <a href="#a38629ecb438041843cbb54c99392af7d">DefiningBlocks</a>, <a href="#a47fd4faf1faf8974cb0e7873a01894d8">DPUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26bad0f6e5435a5a4dc50850c5b8f628">llvm::findDbgUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#a85738eb1a501216794d170a273c68309">OnlyBlock</a>, <a href="#a2e4a8667412a4827dafe780069e672a9">OnlyStore</a>, <a href="#a5fb70e236519f5b4e4896c60610b175e">OnlyUsedInOneBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a> and <a href="#a1ccb40a621418ae685d490be9a883cd6">UsingBlocks</a>.</p>

</div>
</div>

### clear() {#a4cbb30bd3251ea3883b81430e81ced46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::clear ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>References <a href="#aba65788ec2b9209b64ebe06e3109c318">AssignmentTracking</a>, <a href="#aef169a6a4e10355b9647a624f28f79c1">DbgUsers</a>, <a href="#a38629ecb438041843cbb54c99392af7d">DefiningBlocks</a>, <a href="#a47fd4faf1faf8974cb0e7873a01894d8">DPUsers</a>, <a href="#a85738eb1a501216794d170a273c68309">OnlyBlock</a>, <a href="#a2e4a8667412a4827dafe780069e672a9">OnlyStore</a>, <a href="#a5fb70e236519f5b4e4896c60610b175e">OnlyUsedInOneBlock</a> and <a href="#a1ccb40a621418ae685d490be9a883cd6">UsingBlocks</a>.</p>


<p>Referenced by <a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AssignmentTracking {#aba65788ec2b9209b64ebe06e3109c318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssignmentTrackingInfo anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::AssignmentTracking</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to update assignment tracking debug info.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a> and <a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a>.</p>

</div>
</div>

### DbgUsers {#aef169a6a4e10355b9647a624f28f79c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgUserVec anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::DbgUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug users of the alloca - does not include dbg.assign intrinsics.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a> and <a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a>.</p>

</div>
</div>

### DefiningBlocks {#a38629ecb438041843cbb54c99392af7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *, 32&gt; anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::DefiningBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a> and <a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a>.</p>

</div>
</div>

### DPUsers {#a47fd4faf1faf8974cb0e7873a01894d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DPUserVec anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::DPUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a> and <a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a>.</p>

</div>
</div>

### OnlyBlock {#a85738eb1a501216794d170a273c68309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::OnlyBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a> and <a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a>.</p>

</div>
</div>

### OnlyStore {#a2e4a8667412a4827dafe780069e672a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StoreInst* anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::OnlyStore</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a> and <a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a>.</p>

</div>
</div>

### OnlyUsedInOneBlock {#a5fb70e236519f5b4e4896c60610b175e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::OnlyUsedInOneBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a> and <a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a>.</p>

</div>
</div>

### UsingBlocks {#a1ccb40a621418ae685d490be9a883cd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *, 32&gt; anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::UsingBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#aed57a9dd738a483f6ac02904b981c94d">AnalyzeAlloca</a> and <a href="#a4cbb30bd3251ea3883b81430e81ced46">clear</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
