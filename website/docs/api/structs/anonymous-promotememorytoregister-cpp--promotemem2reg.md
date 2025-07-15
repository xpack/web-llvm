---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PromoteMem2Reg` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a721c66ae31a226c5f4244f7827ddbba2">PromoteMem2Reg</a> (ArrayRef&lt; AllocaInst * &gt; Allocas, DominatorTree &amp;DT, AssumptionCache *AC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31d32412508ee492e69d8695f88e6dcf">run</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5716f3a33bef514c8d2e235395274a5">RemoveFromAllocasList</a> (unsigned &amp;AllocaIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae60551be3b8cd1f59dd7de7549a39bf">getNumPreds</a> (const BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061daec9de0d6f8cc82bd1ece8cc0236">ComputeLiveInBlocks</a> (AllocaInst *AI, AllocaInfo &amp;Info, const SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;DefBlocks, SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;LiveInBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine which blocks the value is live in. <a href="#a061daec9de0d6f8cc82bd1ece8cc0236">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14961f923cd9f63240af6877ae2a83ce">RenamePass</a> (BasicBlock *BB, BasicBlock *Pred, RenamePassData::ValVector &amp;IncVals, RenamePassData::LocationVector &amp;IncLocs, std::vector&lt; RenamePassData &gt; &amp;Worklist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively traverse the CFG of the function, renaming loads and stores to the allocas which we are promoting. <a href="#a14961f923cd9f63240af6877ae2a83ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf99e1c950952113ea8c785344636986">QueuePhiNode</a> (BasicBlock *BB, unsigned AllocaIdx, unsigned &amp;Version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Queue a phi-node to be added to a basic-block for a specific Alloca. <a href="#aaf99e1c950952113ea8c785344636986">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa72b4540c74be94ca22e5e5ceacc0ed">cleanUpDbgAssigns</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete dbg.assigns that have been demoted to dbg.values. <a href="#aaa72b4540c74be94ca22e5e5ceacc0ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764c3a6c9b85fb9e84283d4f21ff4bd2">Allocas</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The alloca instructions being promoted. <a href="#a764c3a6c9b85fb9e84283d4f21ff4bd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5654e9ce725c1e004e3c581755edbd8c">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32428cc1cd9368e86984af8c7da8d55">DIB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df7a2d6c0b51ace59a4ac48bcec8b6a">AC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A cache of @llvm.assume intrinsics used by SimplifyInstruction. <a href="#a2df7a2d6c0b51ace59a4ac48bcec8b6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0fce47906b1b2760ab7e533c04b864c">SQ</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f3f320b61b0e000301e831da872a16">AllocaLookup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverse mapping of Allocas. <a href="#a80f3f320b61b0e000301e831da872a16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; unsigned, unsigned &gt;, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a87b539cedba599f6314d804374737">NewPhiNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The PhiNodes we're adding. <a href="#a97a87b539cedba599f6314d804374737">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f0b91643b65c8761c9eeeadc64492dc">PhiToAllocaMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each PHI node, keep track of which entry in Allocas it corresponds to. <a href="#a4f0b91643b65c8761c9eeeadc64492dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/allocainfo/#af92bd826e452bca7dd9a17645b0a9c86">AllocaInfo::DbgUserVec</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80bb056010ea690822b298854c4c4e1f">AllocaDbgUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each alloca, we keep track of the dbg.declare intrinsic that describes it, if any, so that we can convert it to a dbg.value intrinsic if the alloca gets promoted. <a href="#a80bb056010ea690822b298854c4c4e1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/allocainfo/#a7bda92b1076ceabc0f7dc0026215bca8">AllocaInfo::DPUserVec</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8827ceeac0aefbbd0f0b75b0a25917bb">AllocaDPUsers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/assignmenttrackinginfo">AssignmentTrackingInfo</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef98790a823ccff8c29fbe3364b40172">AllocaATInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each alloca, keep an instance of a helper class that gives us an easy way to update assignment tracking debug info if the alloca is promoted. <a href="#aef98790a823ccff8c29fbe3364b40172">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic">DbgAssignIntrinsic</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ec6009a3fa3761c566d7a3f23cd2dd">DbgAssignsToDelete</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of dbg.assigns to delete because they've been demoted to dbg.values. <a href="#a67ec6009a3fa3761c566d7a3f23cd2dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51cdfe53983ad12fef31954127d7930">DVRAssignsToDelete</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d9b4f8f4591430966fdde73d6c3dfe">Visited</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of basic blocks the renamer has already visited. <a href="#a19d9b4f8f4591430966fdde73d6c3dfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b28cf56cd977cfcc409819a699db01">BBNumPreds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lazily compute the number of predecessors a block has, indexed by block number. <a href="#ad3b28cf56cd977cfcc409819a699db01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6407cb982fe1adb61f80dc780208d79">NoSignedZeros</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the function has the no-signed-zeros-fp-math attribute set. <a href="#ad6407cb982fe1adb61f80dc780208d79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PromoteMem2Reg() {#a721c66ae31a226c5f4244f7827ddbba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::PromoteMem2Reg (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; Allocas, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC)</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>References <a href="#a2df7a2d6c0b51ace59a4ac48bcec8b6a">AC</a>, <a href="#a764c3a6c9b85fb9e84283d4f21ff4bd2">Allocas</a>, <a href="#af32428cc1cd9368e86984af8c7da8d55">DIB</a>, <a href="#a5654e9ce725c1e004e3c581755edbd8c">DT</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp/#ab590661425ca60ca82edfdb4cf22233d">getRoot</a> and <a href="#ad0fce47906b1b2760ab7e533c04b864c">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1a4cac84457299517e69ff9764fed2db">llvm::PromoteMemToReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a31d32412508ee492e69d8695f88e6dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PromoteMem2Reg::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a2df7a2d6c0b51ace59a4ac48bcec8b6a">AC</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="#aef98790a823ccff8c29fbe3364b40172">AllocaATInfo</a>, <a href="#a80bb056010ea690822b298854c4c4e1f">AllocaDbgUsers</a>, <a href="#a8827ceeac0aefbbd0f0b75b0a25917bb">AllocaDPUsers</a>, <a href="#a80f3f320b61b0e000301e831da872a16">AllocaLookup</a>, <a href="#a764c3a6c9b85fb9e84283d4f21ff4bd2">Allocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata/#ad93429799d281f5a6534821bc14fa36c">anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::BB</a>, <a href="#ad3b28cf56cd977cfcc409819a699db01">BBNumPreds</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a714e5448566006046f747d9ec4df8241">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::calculate</a>, <a href="/web-llvm/docs/api/classes/anonymous-promotememorytoregister-cpp-/largeblockinfo/#a66fc0bee6bbc4081ce7c2f5dc30a604a">anonymous{PromoteMemoryToRegister.cpp}::LargeBlockInfo::clear</a>, <a href="#a67ec6009a3fa3761c566d7a3f23cd2dd">DbgAssignsToDelete</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#acac0a0a393ce41aadc29e623549b6bfa">llvm::at::deleteAssignmentMarkers</a>, <a href="#a5654e9ce725c1e004e3c581755edbd8c">DT</a>, <a href="#ad51cdfe53983ad12fef31954127d7930">DVRAssignsToDelete</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a63cfb2a0dae69153fd961eb335949caa">llvm::BasicBlock::front</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5023b360abc7a5d1612061fba30003a6">llvm::isAllocaPromotable</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata/#a18184dbfe73aeba751307ac82f0e5209">anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::Locations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="#a97a87b539cedba599f6314d804374737">NewPhiNodes</a>, <a href="#ad6407cb982fe1adb61f80dc780208d79">NoSignedZeros</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata/#ab9573d1a944e1048e7fd1c0c488eced2">anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::Pred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a82f896385cac84a2e477159ad31ace74">removeIntrinsicUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a9180c82ceffac7e5586cc2d6f368f996">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::setDefiningBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a8efdd1ea3537e57552087a2767969557">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::setLiveInBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="#ad0fce47906b1b2760ab7e533c04b864c">SQ</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata/#add5219f842875c33a4168bf4bb6b37f5">anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::Values</a> and <a href="#a19d9b4f8f4591430966fdde73d6c3dfe">Visited</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cleanUpDbgAssigns() {#aaa72b4540c74be94ca22e5e5ceacc0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::cleanUpDbgAssigns ()</td>
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

<p>Delete dbg.assigns that have been demoted to dbg.values.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### ComputeLiveInBlocks() {#a061daec9de0d6f8cc82bd1ece8cc0236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PromoteMem2Reg::ComputeLiveInBlocks (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/allocainfo">AllocaInfo</a> &amp; Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; DefBlocks, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; LiveInBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine which blocks the value is live in.</p>


<p>These are blocks which lead to uses. Knowing this allows us to avoid inserting PHI nodes into blocks which don't lead to uses (thus, the inserted phi nodes would be dead).</p>


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### getNumPreds() {#aae60551be3b8cd1f59dd7de7549a39bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::getNumPreds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### QueuePhiNode() {#aaf99e1c950952113ea8c785344636986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PromoteMem2Reg::QueuePhiNode (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, unsigned AllocaNo, unsigned &amp; Version)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Queue a phi-node to be added to a basic-block for a specific Alloca.</p>


<p>Returns true if there wasn't already a phi-node for that variable</p>


<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### RemoveFromAllocasList() {#af5716f3a33bef514c8d2e235395274a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::RemoveFromAllocasList (unsigned &amp; AllocaIdx)</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### RenamePass() {#a14961f923cd9f63240af6877ae2a83ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PromoteMem2Reg::RenamePass (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Pred, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata/#a18e5b1dbb4e7b1463315c636b916abd0">RenamePassData::ValVector</a> &amp; IncomingVals, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata/#a81ba17b4e41561256ed0b2a82aaac8ce">RenamePassData::LocationVector</a> &amp; IncomingLocs, std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata">RenamePassData</a> &gt; &amp; Worklist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively traverse the CFG of the function, renaming loads and stores to the allocas which we are promoting.</p>


<p>IncomingVals indicates what value each Alloca contains on exit from the predecessor block Pred.</p>


<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AC {#a2df7a2d6c0b51ace59a4ac48bcec8b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A cache of @llvm.assume intrinsics used by SimplifyInstruction.</p>

<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a721c66ae31a226c5f4244f7827ddbba2">PromoteMem2Reg</a> and <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### AllocaATInfo {#aef98790a823ccff8c29fbe3364b40172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AssignmentTrackingInfo, 8&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::AllocaATInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For each alloca, keep an instance of a helper class that gives us an easy way to update assignment tracking debug info if the alloca is promoted.</p>

<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### AllocaDbgUsers {#a80bb056010ea690822b298854c4c4e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AllocaInfo::DbgUserVec, 8&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::AllocaDbgUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For each alloca, we keep track of the dbg.declare intrinsic that describes it, if any, so that we can convert it to a dbg.value intrinsic if the alloca gets promoted.</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### AllocaDPUsers {#a8827ceeac0aefbbd0f0b75b0a25917bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AllocaInfo::DPUserVec, 8&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::AllocaDPUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### AllocaLookup {#a80f3f320b61b0e000301e831da872a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AllocaInst *, unsigned&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::AllocaLookup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reverse mapping of Allocas.</p>

<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### Allocas {#a764c3a6c9b85fb9e84283d4f21ff4bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;AllocaInst *&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::Allocas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The alloca instructions being promoted.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a721c66ae31a226c5f4244f7827ddbba2">PromoteMem2Reg</a> and <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### BBNumPreds {#ad3b28cf56cd977cfcc409819a699db01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::BBNumPreds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lazily compute the number of predecessors a block has, indexed by block number.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### DbgAssignsToDelete {#a67ec6009a3fa3761c566d7a3f23cd2dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;DbgAssignIntrinsic *, 8&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::DbgAssignsToDelete</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set of dbg.assigns to delete because they've been demoted to dbg.values.</p>


<p>Call cleanUpDbgAssigns to delete them.</p>


<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### DIB {#af32428cc1cd9368e86984af8c7da8d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIBuilder anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::DIB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a721c66ae31a226c5f4244f7827ddbba2">PromoteMem2Reg</a>.</p>

</div>
</div>

### DT {#a5654e9ce725c1e004e3c581755edbd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a721c66ae31a226c5f4244f7827ddbba2">PromoteMem2Reg</a> and <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### DVRAssignsToDelete {#ad51cdfe53983ad12fef31954127d7930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;DbgVariableRecord *, 8&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::DVRAssignsToDelete</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### NewPhiNodes {#a97a87b539cedba599f6314d804374737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;unsigned, unsigned&gt;, PHINode *&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::NewPhiNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The PhiNodes we're adding.</p>


<p>That map is used to simplify some Phi nodes as we iterate over it, so it should have deterministic iterators. We could use a <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>, but since basic blocks have numbers, using these are more efficient.</p>


<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### NoSignedZeros {#ad6407cb982fe1adb61f80dc780208d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::NoSignedZeros = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the function has the no-signed-zeros-fp-math attribute set.</p>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### PhiToAllocaMap {#a4f0b91643b65c8761c9eeeadc64492dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PHINode *, unsigned&gt; anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::PhiToAllocaMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For each PHI node, keep track of which entry in Allocas it corresponds to.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### SQ {#ad0fce47906b1b2760ab7e533c04b864c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SimplifyQuery anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::SQ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a721c66ae31a226c5f4244f7827ddbba2">PromoteMem2Reg</a> and <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

</div>
</div>

### Visited {#a19d9b4f8f4591430966fdde73d6c3dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of basic blocks the renamer has already visited.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a31d32412508ee492e69d8695f88e6dcf">run</a>.</p>

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
