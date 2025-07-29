---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/phitransaddr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PHITransAddr` Class

<p><a href="/web-llvm/docs/api/classes/llvm/phitransaddr">PHITransAddr</a> - An address value which tracks and handles phi translation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PHITransAddr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">llvm/Analysis/PHITransAddr.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4e879f0d6ff7882c48b158c5549010">PHITransAddr</a> (Value *Addr, const DataLayout &amp;DL, AssumptionCache *AC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7568cf897d20bd4a22c12b43bd200dc">getAddr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac419457dd48749860dfa5b85a43a0637">needsPHITranslationFromBlock</a> (BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>needsPHITranslationFromBlock - Return true if moving from the specified <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> to its predecessors requires PHI translation. <a href="#ac419457dd48749860dfa5b85a43a0637">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5efb6e7305495567d0e1c27683565f1f">isPotentiallyPHITranslatable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isPotentiallyPHITranslatable - If this needs PHI translation, return true if we have some hope of doing it. <a href="#a5efb6e7305495567d0e1c27683565f1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a020dcdde43c7bdff11476f1f5b64ef25">translateValue</a> (BasicBlock *CurBB, BasicBlock *PredBB, const DominatorTree *DT, bool MustDominate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateValue - PHI translate the current address up the CFG from CurBB to Pred, updating our state to reflect any needed changes. <a href="#a020dcdde43c7bdff11476f1f5b64ef25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b823fe521dfaefebd59ddf5f7f6bd7">translateWithInsertion</a> (BasicBlock *CurBB, BasicBlock *PredBB, const DominatorTree &amp;DT, SmallVectorImpl&lt; Instruction * &gt; &amp;NewInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>translateWithInsertion - PHI translate this value into the specified predecessor block, inserting a computation of the value if it is unavailable. <a href="#aa4b823fe521dfaefebd59ddf5f7f6bd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d08402d35c5bb6cc0faf2b0e4bacb6c">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706fc677031e5d0fc38869aed8478491">verify</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>verify - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> internal consistency of this data structure. <a href="#a706fc677031e5d0fc38869aed8478491">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c62db26e8636d1188213aa6944bba1">translateSubExpr</a> (Value *V, BasicBlock *CurBB, BasicBlock *PredBB, const DominatorTree *DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf0ecff578f759104883f470f5303af">insertTranslatedSubExpr</a> (Value *InVal, BasicBlock *CurBB, BasicBlock *PredBB, const DominatorTree &amp;DT, SmallVectorImpl&lt; Instruction * &gt; &amp;NewInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insertTranslatedSubExpr - Insert a computation of the PHI translated version of 'V' for the edge PredBB-&gt;CurBB into the end of the PredBB block. <a href="#aedf0ecff578f759104883f470f5303af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa700268b0497c5af6bd329d0d4fe7f94">addAsInput</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addAsInput - If the specified value is an instruction, add it as an input. <a href="#aa700268b0497c5af6bd329d0d4fe7f94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21b96efd8e2d7417caa6f4d8c850e7d0">Addr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Addr - The actual address we're analyzing. <a href="#a21b96efd8e2d7417caa6f4d8c850e7d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6ea1ee03ccde8b83a37e31881d305f">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> we are playing with. <a href="#abc6ea1ee03ccde8b83a37e31881d305f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f76dfe81497fb0a5d323f9e8e3f698f">TLI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TLI - The target library info if known, otherwise null. <a href="#a0f76dfe81497fb0a5d323f9e8e3f698f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e28db3f548d2d0fba6de7a578924f6">AC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A cache of @llvm.assume calls used by SimplifyInstruction. <a href="#a13e28db3f548d2d0fba6de7a578924f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a827e751b36e9ee94453d092fbae1ac4a">InstInputs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InstInputs - The inputs for our symbolic address. <a href="#a827e751b36e9ee94453d092fbae1ac4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/phitransaddr">PHITransAddr</a> - An address value which tracks and handles phi translation.</p>


<p>As we walk "up" the CFG through predecessors, we need to ensure that the address we're tracking is kept up to date. For example, if we're analyzing an address of "&amp;A[i]" and walk through the definition of 'i' which is a PHI node, we <em>must</em> phi translate i to get "&amp;A[j]" or else we will analyze an incorrect pointer in the predecessor block.</p>


<p>This is designed to be a relatively small object that lives on the stack and is copyable.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PHITransAddr() {#a4c4e879f0d6ff7882c48b158c5549010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PHITransAddr::PHITransAddr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a3d08402d35c5bb6cc0faf2b0e4bacb6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void PHITransAddr::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp">PHITransAddr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### getAddr() {#ae7568cf897d20bd4a22c12b43bd200dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::PHITransAddr::getAddr ()</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>.</p>

</div>
</div>

### isPotentiallyPHITranslatable() {#a5efb6e7305495567d0e1c27683565f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PHITransAddr::isPotentiallyPHITranslatable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isPotentiallyPHITranslatable - If this needs PHI translation, return true if we have some hope of doing it.</p>


<p>This should be used as a filter to avoid calling PHITranslateValue in hopeless situations.</p>


<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp">PHITransAddr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp/#a2c64eb39d5bdd73f8ac9d47338931ce8">canPHITrans</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>.</p>

</div>
</div>

### needsPHITranslationFromBlock() {#ac419457dd48749860dfa5b85a43a0637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PHITransAddr::needsPHITranslationFromBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>needsPHITranslationFromBlock - Return true if moving from the specified <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> to its predecessors requires PHI translation.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>.</p>

</div>
</div>

### translateValue() {#a020dcdde43c7bdff11476f1f5b64ef25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PHITransAddr::translateValue (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CurBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PredBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, bool MustDominate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>translateValue - PHI translate the current address up the CFG from CurBB to Pred, updating our state to reflect any needed changes.</p>


<p>PHITranslateValue - PHI translate the current address up the CFG from CurBB to Pred, updating our state to reflect any needed changes.</p>


<p>If 'MustDominate' is true, the translated value must dominate PredBB.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp">PHITransAddr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a1a70f2c359aadd76a72aaaede16aca4a">llvm::DominatorTree::isReachableFromEntry</a> and <a href="#a706fc677031e5d0fc38869aed8478491">verify</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>.</p>

</div>
</div>

### translateWithInsertion() {#aa4b823fe521dfaefebd59ddf5f7f6bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PHITransAddr::translateWithInsertion (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CurBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PredBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; NewInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>translateWithInsertion - PHI translate this value into the specified predecessor block, inserting a computation of the value if it is unavailable.</p>


<p>PHITranslateWithInsertion - PHI translate this value into the specified predecessor block, inserting a computation of the value if it is unavailable.</p>


<p>All newly created instructions are added to the NewInsts list. This returns null on failure.</p>


<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>, definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp">PHITransAddr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### verify() {#a706fc677031e5d0fc38869aed8478491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PHITransAddr::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>verify - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> internal consistency of this data structure.</p>


<p>If the structure is valid, it returns true. If invalid, it prints errors and returns false.</p>


<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp">PHITransAddr.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp/#af743eac3b984c084268a3d988a8ea10c">verifySubExpr</a>.</p>


<p>Referenced by <a href="#a020dcdde43c7bdff11476f1f5b64ef25">translateValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addAsInput() {#aa700268b0497c5af6bd329d0d4fe7f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::PHITransAddr::addAsInput (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>addAsInput - If the specified value is an instruction, add it as an input.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>

</div>
</div>

### insertTranslatedSubExpr() {#aedf0ecff578f759104883f470f5303af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PHITransAddr::insertTranslatedSubExpr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * InVal, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CurBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PredBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; NewInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>insertTranslatedSubExpr - Insert a computation of the PHI translated version of 'V' for the edge PredBB-&gt;CurBB into the end of the PredBB block.</p>


<p>All newly created instructions are added to the NewInsts list. This returns null on failure.</p>


<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp">PHITransAddr.cpp</a>.</p>

</div>
</div>

### translateSubExpr() {#a16c62db26e8636d1188213aa6944bba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PHITransAddr::translateSubExpr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CurBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PredBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp">PHITransAddr.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#a13e28db3f548d2d0fba6de7a578924f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::PHITransAddr::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A cache of @llvm.assume calls used by SimplifyInstruction.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>

</div>
</div>

### Addr {#a21b96efd8e2d7417caa6f4d8c850e7d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::PHITransAddr::Addr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Addr - The actual address we're analyzing.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>

</div>
</div>

### DL {#abc6ea1ee03ccde8b83a37e31881d305f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::PHITransAddr::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> we are playing with.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>

</div>
</div>

### InstInputs {#a827e751b36e9ee94453d092fbae1ac4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction*, 4&gt; llvm::PHITransAddr::InstInputs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>InstInputs - The inputs for our symbolic address.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>

</div>
</div>

### TLI {#a0f76dfe81497fb0a5d323f9e8e3f698f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* llvm::PHITransAddr::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TLI - The target library info if known, otherwise null.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/phitransaddr-h">PHITransAddr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp">PHITransAddr.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
