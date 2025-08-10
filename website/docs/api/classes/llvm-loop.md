---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Loop` Class

<p>Represents a single loop in the control flow graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Loop { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopbase">LoopBase&lt;BlockT, LoopT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instances of this class are used to represent loops that are detected in the flow graph. <a href="/web-llvm/docs/api/classes/llvm/loopbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67d39ab5b81ea5504f2edd07bda0239a">LoopInfoBase&lt; BasicBlock, Loop &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aab5f5596fc1f3da04b1099b1810b51">LoopBase&lt; BasicBlock, Loop &gt;</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac8d9d994df02930bc14bbc5dcf9119a">Loop</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33af80ff072c61cb9fda4bbefd9ed3cc">Loop</a> (BasicBlock *BB)</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd97727fefabadf2f9bd4eb6c532af96">~Loop</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cb6a58fb0ded82b4c7755fc4c27c86d">isLoopInvariant</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified value is loop invariant. <a href="#a6cb6a58fb0ded82b4c7755fc4c27c86d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e82aea5fab8cf3a878003444f25ee7">hasLoopInvariantOperands</a> (const Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all the operands of the specified instruction are loop invariant. <a href="#a54e82aea5fab8cf3a878003444f25ee7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58027d845fb948a63a8ff44851699d5">makeLoopInvariant</a> (Value *V, bool &amp;Changed, Instruction *InsertPt=nullptr, MemorySSAUpdater *MSSAU=nullptr, ScalarEvolution *SE=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the given value is an instruction inside of the loop and it can be hoisted, do so to make it trivially loop-invariant. <a href="#ae58027d845fb948a63a8ff44851699d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f134722dec96eeaf23085a29b5da9f7">makeLoopInvariant</a> (Instruction *I, bool &amp;Changed, Instruction *InsertPt=nullptr, MemorySSAUpdater *MSSAU=nullptr, ScalarEvolution *SE=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the given instruction is inside of the loop and it can be hoisted, do so to make it trivially loop-invariant. <a href="#a9f134722dec96eeaf23085a29b5da9f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae731e6e33c2f2a9a6ebd1d51886ce534">getCanonicalInductionVariable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if the loop has a canonical induction variable: an integer recurrence that starts at 0 and increments by one each time through the loop. <a href="#ae731e6e33c2f2a9a6ebd1d51886ce534">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d7349c6beeae9b9ac526c9f74f4efdb">getLatchCmpInst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the latch condition instruction. <a href="#a7d7349c6beeae9b9ac526c9f74f4efdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb36e1cc49a96f09e233c4cfe1e65fdf">getIncomingAndBackEdge</a> (BasicBlock *&amp;Incoming, BasicBlock *&amp;Backedge) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the unique incoming and back edge. <a href="#aeb36e1cc49a96f09e233c4cfe1e65fdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds">LoopBounds</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096b15bbaad7c5f24d29b0592339b9e8">getBounds</a> (ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the struct <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds">LoopBounds</a> collected if all struct members are found, else std::nullopt. <a href="#a096b15bbaad7c5f24d29b0592339b9e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05e97728516fbeeaa9426496257c800">getInductionVariable</a> (ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the loop induction variable if found, else return nullptr. <a href="#ab05e97728516fbeeaa9426496257c800">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b4fb592be76abb594711e92bb35e5c">getInductionDescriptor</a> (ScalarEvolution &amp;SE, InductionDescriptor &amp;IndDesc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the loop induction descriptor for the loop induction variable. <a href="#a87b4fb592be76abb594711e92bb35e5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe702618f56478e67eb0f705efb648b6">isAuxiliaryInductionVariable</a> (PHINode &amp;AuxIndVar, ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> <span class="doxyComputerOutput">AuxIndVar</span> is. <a href="#afe702618f56478e67eb0f705efb648b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a580a6361a2bad87e6071ecc795bdae96">getLoopGuardBranch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the loop guard branch, if it exists. <a href="#a580a6361a2bad87e6071ecc795bdae96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25404d322e551103ea5a4af8686099b9">isGuarded</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true iff the loop is. <a href="#a25404d322e551103ea5a4af8686099b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bf09763773a48bc03a0461fb572a0c">isRotatedForm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the loop is in rotated form. <a href="#a94bf09763773a48bc03a0461fb572a0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f94a30e706065eb238b74f57c497ee">isCanonical</a> (ScalarEvolution &amp;SE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the loop induction variable starts at zero and increments by one each time through the loop. <a href="#a01f94a30e706065eb238b74f57c497ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021a92f02d7e959877a4154277fc5c91">isLCSSAForm</a> (const DominatorTree &amp;DT, bool IgnoreTokens=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> is in LCSSA form. <a href="#a021a92f02d7e959877a4154277fc5c91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d406a8bba858837a1a34c03510b124">isRecursivelyLCSSAForm</a> (const DominatorTree &amp;DT, const LoopInfo &amp;LI, bool IgnoreTokens=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> and all inner subloops are in LCSSA form. <a href="#ad4d406a8bba858837a1a34c03510b124">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac233a2693163ed58305215ca2f6921e3">isLoopSimplifyForm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> is in the form that the LoopSimplify form transforms loops to, which is sometimes called normal form. <a href="#ac233a2693163ed58305215ca2f6921e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b0ea1f1455192f5e0b0d033784c2d22">isSafeToClone</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the loop body is safe to clone in practice. <a href="#a1b0ea1f1455192f5e0b0d033784c2d22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bce47fa5e8edaf4eef3ddc67a78193c">isAnnotatedParallel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the loop is annotated parallel. <a href="#a5bce47fa5e8edaf4eef3ddc67a78193c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbcd78588d5235f99698b5c30f591382">getLoopID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the llvm.loop loop id metadata node for this loop if it is present. <a href="#afbcd78588d5235f99698b5c30f591382">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4be757fa30ca7fe3e8b119438100f0">setLoopID</a> (MDNode *LoopID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the llvm.loop loop id metadata for this loop. <a href="#adf4be757fa30ca7fe3e8b119438100f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae27590daf21d575c9bb75c966fe256f2">setLoopAlreadyUnrolled</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add llvm.loop.unroll.disable to this loop's loop id metadata. <a href="#ae27590daf21d575c9bb75c966fe256f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0930d54ec09b50bbfa09ec317e0df42">setLoopMustProgress</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add llvm.loop.mustprogress to this loop's loop id metadata. <a href="#aa0930d54ec09b50bbfa09ec317e0df42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a487a3724136e3332c86f2f26189ce">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50473b1fa66150ed4edc08ede2b4e51f">dumpVerbose</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615131659002c10601eef598d42d025e">getStartLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the debug location of the start of this loop. <a href="#a615131659002c10601eef598d42d025e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop/locrange">LocRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66fe46192625e4eaeee9c41eaca644eb">getLocRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the source code span of the loop. <a href="#a66fe46192625e4eaeee9c41eaca644eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4746e455f9041187249483e7f5e5f5">getLocStr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a string containing the debug location of the loop (file name + line number if present, otherwise module name). <a href="#a2b4746e455f9041187249483e7f5e5f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917a64b00c1745fd0c78c2b2320cd4ad">getName</a> () const</td>
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

<p>Represents a single loop in the control flow graph.</p>


<p>Note that not all SCCs in the CFG are necessarily loops.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<div class="doxySectionDef">

## Friends

### LoopBase&lt; BasicBlock, Loop &gt; {#a6aab5f5596fc1f3da04b1099b1810b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/loopbase">LoopBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### LoopInfoBase&lt; BasicBlock, Loop &gt; {#a67d39ab5b81ea5504f2edd07bda0239a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/loopinfobase">LoopInfoBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Loop() {#aac8d9d994df02930bc14bbc5dcf9119a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Loop::Loop ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

### Loop() {#a33af80ff072c61cb9fda4bbefd9ed3cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Loop::Loop (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~Loop() {#acd97727fefabadf2f9bd4eb6c532af96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Loop::~Loop ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a61a487a3724136e3332c86f2f26189ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Loop::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BasicBlock, Loop &gt;::print</a>.</p>

</div>
</div>

### dumpVerbose() {#a50473b1fa66150ed4edc08ede2b4e51f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Loop::dumpVerbose ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BasicBlock, Loop &gt;::print</a>.</p>

</div>
</div>

### getBounds() {#a096b15bbaad7c5f24d29b0592339b9e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Loop::LoopBounds &gt; Loop::getBounds (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the struct <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds">LoopBounds</a> collected if all struct members are found, else std::nullopt.</p>

<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#a075be8282fe6debdda46c86d24a07684">llvm::Loop::LoopBounds::getBounds</a> and <a href="#ab05e97728516fbeeaa9426496257c800">getInductionVariable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a797a9f600b2119356e4ea74cdc6ba25a">llvm::LoopNest::getInterveningInstructions</a>.</p>

</div>
</div>

### getCanonicalInductionVariable() {#ae731e6e33c2f2a9a6ebd1d51886ce534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * Loop::getCanonicalInductionVariable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if the loop has a canonical induction variable: an integer recurrence that starts at 0 and increments by one each time through the loop.</p>


<p>If so, return the phi node that corresponds to it.</p>


<p>The IndVarSimplify pass transforms loops to have a canonical induction variable.</p>


<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getHeader</a>, <a href="#aeb36e1cc49a96f09e233c4cfe1e65fdf">getIncomingAndBackEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3eb7a9b091032d4d053727b7a578a97e">llvm::isUniformLoop</a>.</p>

</div>
</div>

### getIncomingAndBackEdge() {#aeb36e1cc49a96f09e233c4cfe1e65fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::getIncomingAndBackEdge (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; Incoming, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; Backedge)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the unique incoming and back edge.</p>


<p>Return false if they are non-unique or the loop is dead; otherwise, return true.</p>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3e549d97549636a7f08779d5cd98540">llvm::pred_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2103c335fa6ab933312c3871c82b0106">llvm::pred_end</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#ae731e6e33c2f2a9a6ebd1d51886ce534">getCanonicalInductionVariable</a>.</p>

</div>
</div>

### getInductionDescriptor() {#a87b4fb592be76abb594711e92bb35e5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::getInductionDescriptor (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor">InductionDescriptor</a> &amp; IndDesc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the loop induction descriptor for the loop induction variable.</p>


<p>Return true if the loop induction variable is found.</p>


<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="#ab05e97728516fbeeaa9426496257c800">getInductionVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>.</p>


<p>Referenced by <a href="#a01f94a30e706065eb238b74f57c497ee">isCanonical</a>.</p>

</div>
</div>

### getInductionVariable() {#ab05e97728516fbeeaa9426496257c800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * Loop::getInductionVariable (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the loop induction variable if found, else return nullptr.</p>


<p>An instruction is considered as the loop induction variable if</p>


<ul class="doxyList ">
<li>it is an induction variable of the loop; and</li>
<li>it is used to determine the condition of the branch in the loop latch</li>
</ul>

<p>Note: the induction variable doesn't need to be canonical, i.e. starts at zero and increments by one each time through the loop (but it can be).</p>


<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getHeader</a>, <a href="#a7d7349c6beeae9b9ac526c9f74f4efdb">getLatchCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a> and <a href="#ac233a2693163ed58305215ca2f6921e3">isLoopSimplifyForm</a>.</p>


<p>Referenced by <a href="#a096b15bbaad7c5f24d29b0592339b9e8">getBounds</a> and <a href="#a87b4fb592be76abb594711e92bb35e5c">getInductionDescriptor</a>.</p>

</div>
</div>

### getLatchCmpInst() {#a7d7349c6beeae9b9ac526c9f74f4efdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ICmpInst * Loop::getLatchCmpInst ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the latch condition instruction.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>.</p>


<p>Referenced by <a href="#ab05e97728516fbeeaa9426496257c800">getInductionVariable</a>.</p>

</div>
</div>

### getLocRange() {#a66fe46192625e4eaeee9c41eaca644eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop::LocRange Loop::getLocRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the source code span of the loop.</p>

<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getHeader</a>, <a href="#afbcd78588d5235f99698b5c30f591382">getLoopID</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopPreheader</a>.</p>


<p>Referenced by <a href="#a615131659002c10601eef598d42d025e">getStartLoc</a>.</p>

</div>
</div>

### getLocStr() {#a2b4746e455f9041187249483e7f5e5f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Loop::getLocStr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a string containing the debug location of the loop (file name + line number if present, otherwise module name).</p>


<p>Meant to be used for debug printing within LLVM_DEBUG.</p>


<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a9a4fa55f19f0d5bb47d1fe6802e18d1a">llvm::Module::getModuleIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a> and <a href="#a615131659002c10601eef598d42d025e">getStartLoc</a>.</p>

</div>
</div>

### getLoopGuardBranch() {#a580a6361a2bad87e6071ecc795bdae96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchInst * Loop::getLoopGuardBranch ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the loop guard branch, if it exists.</p>


<p>This currently only works on simplified loop, as it requires a preheader and a latch to identify the guard. It will work on loops of the form:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">GuardBB:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br cond1, Preheader, ExitSucc &lt;== GuardBranch</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Preheader:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br <a href="/web-llvm/docs/api/namespaces/anonymous-lvcompare-cpp-/#a1ad6686ca7dcf67bc791fff07fdf7818abf50d5e661106d0abe925af3c2e6f7e7">Header</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/anonymous-lvcompare-cpp-/#a1ad6686ca7dcf67bc791fff07fdf7818abf50d5e661106d0abe925af3c2e6f7e7">Header</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"> ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br Latch</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Latch:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br cond2, <a href="/web-llvm/docs/api/namespaces/anonymous-lvcompare-cpp-/#a1ad6686ca7dcf67bc791fff07fdf7818abf50d5e661106d0abe925af3c2e6f7e7">Header</a>, ExitBlock</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">ExitBlock:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br ExitSucc</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">ExitSucc:</span></span></div>

</div>


<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#afd50c2de451ac9fc0865dc747dd2d485">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getUniqueExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a74aa9daea070e2ad3394a3ec58b7316a">llvm::BasicBlock::getUniquePredecessor</a>, <a href="#ac233a2693163ed58305215ca2f6921e3">isLoopSimplifyForm</a>, <a href="#a94bf09763773a48bc03a0461fb572a0c">isRotatedForm</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#ad56f6a9b5cd05940017c4544df48bc30">llvm::BranchInst::isUnconditional</a> and <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a0c3d91a5a6e71c114dea21819cc71382">llvm::LoopNest::skipEmptyBlockUntil</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#a410517ee51b91e86b7908a3895138054">getInnerLoopGuardCmp</a> and <a href="#a25404d322e551103ea5a4af8686099b9">isGuarded</a>.</p>

</div>
</div>

### getLoopID() {#afbcd78588d5235f99698b5c30f591382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * Loop::getLoopID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the llvm.loop loop id metadata node for this loop if it is present.</p>


<p>If this loop contains the same llvm.loop metadata on each branch to the header then the node is returned. If any latch instruction does not contain llvm.loop or if multiple latches contain different nodes then 0 is returned.</p>


<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a542a6493b191eb84b5457d35ecd685c5">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatches</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a55c9054d63d1c6a39e9c09ba13a482fa">llvm::addStringMetadataToLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f91ce019424451ab50bf348826fa270">llvm::findOptionMDForLoop</a>, <a href="#a66fe46192625e4eaeee9c41eaca644eb">getLocRange</a>, <a href="#a5bce47fa5e8edaf4eef3ddc67a78193c">isAnnotatedParallel</a>, <a href="#ae27590daf21d575c9bb75c966fe256f2">setLoopAlreadyUnrolled</a>, <a href="#aa0930d54ec09b50bbfa09ec317e0df42">setLoopMustProgress</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>.</p>

</div>
</div>

### getName() {#a917a64b00c1745fd0c78c2b2320cd4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Loop::getName ()</td>
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



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getHeader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#ad2c7f512c7735232319f74e85a4263e2">llvm::LoopNest::getMaxPerfectDepth</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6a1c647f91f86b7bfea85c0cee90de91">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### getStartLoc() {#a615131659002c10601eef598d42d025e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc Loop::getStartLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the debug location of the start of this loop.</p>


<p>This looks for a BB terminating instruction with a known debug location by looking at the preheader and header blocks. If it cannot find a terminating instruction with location information, it returns an unknown location.</p>


<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="#a66fe46192625e4eaeee9c41eaca644eb">getLocRange</a> and <a href="/web-llvm/docs/api/classes/llvm/loop/locrange/#a6dead4c305138073ea71f75ae64f0dce">llvm::Loop::LocRange::getStart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a8ce6d27f2029316071fd8130578a2229">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::currentLimitations</a>, <a href="#a2b4746e455f9041187249483e7f5e5f5">getLocStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopinterchange-cpp-/loopinterchange/#a5342eefdd06826f163b13f40992ce8e4">anonymous{LoopInterchange.cpp}::LoopInterchange::processLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0c19b37908311872f655348755e8d003">llvm::reportVectorization</a>.</p>

</div>
</div>

### hasLoopInvariantOperands() {#a54e82aea5fab8cf3a878003444f25ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::hasLoopInvariantOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all the operands of the specified instruction are loop invariant.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>.</p>

</div>
</div>

### isAnnotatedParallel() {#a5bce47fa5e8edaf4eef3ddc67a78193c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::isAnnotatedParallel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the loop is annotated parallel.</p>


<p>A parallel loop can be assumed to not contain any dependencies between iterations by the compiler. That is, any loop-carried dependency checking can be skipped completely when parallelizing the loop on the target machine. Thus, if the parallel loop information originates from the programmer, e.g. via the OpenMP parallel for pragma, it is the programmer's responsibility to ensure there are no loop-carried dependencies. The final execution order of the instructions across iterations is not guaranteed, thus, the end result might or might not implement actual concurrent execution of instructions across multiple iterations.</p>


<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BasicBlock, Loop &gt;::blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f91ce019424451ab50bf348826fa270">llvm::findOptionMDForLoop</a>, <a href="#afbcd78588d5235f99698b5c30f591382">getLoopID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ca75e2df56b775d5bb91f20a37229ee">llvm::isValidAsAccessGroup</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a571612461ea4af620bc4c441d61579a3">llvm::MDNode::operands</a>.</p>

</div>
</div>

### isAuxiliaryInductionVariable() {#afe702618f56478e67eb0f705efb648b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::isAuxiliaryInductionVariable (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; AuxIndVar, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> <span class="doxyComputerOutput">AuxIndVar</span> is.</p>


<ul class="doxyList ">
<li>in the loop header</li>
<li>not used outside of the loop</li>
<li>incremented by a loop invariant step for each loop iteration</li>
<li>step instruction opcode should be add or sub Note: auxiliary induction variable is not required to be used in the conditional branch in the loop latch. (but it can be)</li>
</ul>

<p>Declaration at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#adc4aaaf8ba6ab1a510c593a6c6370499">llvm::InductionDescriptor::getInductionOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a83b5b65084a0c1de3a76f36f198b1b0c">llvm::InductionDescriptor::getStep</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a19768af81df7e5fe571bc08dcd48b3">llvm::ScalarEvolution::isLoopInvariant</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

### isCanonical() {#a01f94a30e706065eb238b74f57c497ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::isCanonical (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the loop induction variable starts at zero and increments by one each time through the loop.</p>

<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#af27bf00d939332f3d6ef27ea34440487">llvm::InductionDescriptor::getConstIntStepValue</a>, <a href="#a87b4fb592be76abb594711e92bb35e5c">getInductionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#adc4aaaf8ba6ab1a510c593a6c6370499">llvm::InductionDescriptor::getInductionOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#aea63dae61a488e20e237f5f517ed1491">llvm::InductionDescriptor::getStartValue</a> and <a href="/web-llvm/docs/api/classes/llvm/constantint/#a244bfbe5aae876e56cf5e62f0f27867a">llvm::ConstantInt::isOne</a>.</p>

</div>
</div>

### isGuarded() {#a25404d322e551103ea5a4af8686099b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Loop::isGuarded ()</td>
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

<p>Return true iff the loop is.</p>


<ul class="doxyList ">
<li>in simplify rotated form, and</li>
<li>guarded by a loop guard branch.</li>
</ul>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<p>Reference <a href="#a580a6361a2bad87e6071ecc795bdae96">getLoopGuardBranch</a>.</p>

</div>
</div>

### isLCSSAForm() {#a021a92f02d7e959877a4154277fc5c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::isLCSSAForm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, bool IgnoreTokens=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> is in LCSSA form.</p>


<p>If <span class="doxyComputerOutput">IgnoreTokens</span> is set to true, token values defined inside loop are allowed to violate LCSSA form.</p>


<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BasicBlock, Loop &gt;::blocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a0ffc25db9de504390b4b05af70e4d31d">isBlockInLCSSAForm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### isLoopInvariant() {#a6cb6a58fb0ded82b4c7755fc4c27c86d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::isLoopInvariant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified value is loop invariant.</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a158e2caed73e4b5d2ad70c1b2a0e0cc8">llvm::canSinkOrHoistInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf87a16be872504ce4d0ab9714dc6217">llvm::findHistogram</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a7af4f3d780a4c92809414d5e43d98337">llvm::RecurrenceDescriptor::isAnyOfPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#ab63d5eb7a9919d4e5f2c8d614e9bda97">isSafeToExecuteUnconditionally</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3eb7a9b091032d4d053727b7a578a97e">llvm::isUniformLoop</a> and <a href="#a9f134722dec96eeaf23085a29b5da9f7">makeLoopInvariant</a>.</p>

</div>
</div>

### isLoopSimplifyForm() {#ac233a2693163ed58305215ca2f6921e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::isLoopSimplifyForm ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> is in the form that the LoopSimplify form transforms loops to, which is sometimes called normal form.</p>

<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopPreheader</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae7ebc88c9b32b51b749bd5bbcfaa5fb8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::hasDedicatedExits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#aa476d5315e502f74f064165e49a3ff9b">checkLoopsStructure</a>, <a href="#ab05e97728516fbeeaa9426496257c800">getInductionVariable</a>, <a href="#a580a6361a2bad87e6071ecc795bdae96">getLoopGuardBranch</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>.</p>

</div>
</div>

### isRecursivelyLCSSAForm() {#ad4d406a8bba858837a1a34c03510b124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::isRecursivelyLCSSAForm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, bool IgnoreTokens=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> and all inner subloops are in LCSSA form.</p>


<p>If <span class="doxyComputerOutput">IgnoreTokens</span> is set to true, token values defined inside loop are allowed to violate LCSSA form.</p>


<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BasicBlock, Loop &gt;::blocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a0ffc25db9de504390b4b05af70e4d31d">isBlockInLCSSAForm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>.</p>

</div>
</div>

### isRotatedForm() {#a94bf09763773a48bc03a0461fb572a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Loop::isRotatedForm ()</td>
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

<p>Return true if the loop is in rotated form.</p>


<p>This does not check if the loop was rotated by loop rotation, instead it only checks if the loop is in rotated form (has a valid latch that exists the loop).</p>


<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a7cea07afaa9cb9cb11334832b90eaf0a">llvm::LoopBase&lt; BasicBlock, Loop &gt;::isInvalid</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#af691775d5a45e28afbdb3e97cab22eee">llvm::LoopBase&lt; BasicBlock, Loop &gt;::isLoopExiting</a>.</p>


<p>Referenced by <a href="#a580a6361a2bad87e6071ecc795bdae96">getLoopGuardBranch</a>.</p>

</div>
</div>

### isSafeToClone() {#a1b0ea1f1455192f5e0b0d033784c2d22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::isSafeToClone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the loop body is safe to clone in practice.</p>

<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a78bec3084b9a47ee11cc2e56f9004717">llvm::LoopBase&lt; BasicBlock, Loop &gt;::blocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### makeLoopInvariant() {#ae58027d845fb948a63a8ff44851699d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::makeLoopInvariant (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool &amp; Changed, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPt=nullptr, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU=nullptr, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the given value is an instruction inside of the loop and it can be hoisted, do so to make it trivially loop-invariant.</p>


<p>Return true if <span class="doxyComputerOutput">V</span> is already loop-invariant, and false if <span class="doxyComputerOutput">V</span> can't be made loop-invariant. If <span class="doxyComputerOutput">V</span> is made loop-invariant, <span class="doxyComputerOutput">Changed</span> is set to true. This function can be used as a slightly more aggressive replacement for isLoopInvariant.</p>


<p>If InsertPt is specified, it is the point to hoist instructions to. If null, the terminator of the loop preheader is used.</p>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ae58027d845fb948a63a8ff44851699d5">makeLoopInvariant</a>.</p>


<p>Referenced by <a href="#a9f134722dec96eeaf23085a29b5da9f7">makeLoopInvariant</a> and <a href="#ae58027d845fb948a63a8ff44851699d5">makeLoopInvariant</a>.</p>

</div>
</div>

### makeLoopInvariant() {#a9f134722dec96eeaf23085a29b5da9f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Loop::makeLoopInvariant (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, bool &amp; Changed, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPt=nullptr, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU=nullptr, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the given instruction is inside of the loop and it can be hoisted, do so to make it trivially loop-invariant.</p>


<p>Return true if <span class="doxyComputerOutput">I</span> is already loop-invariant, and false if <span class="doxyComputerOutput">I</span> can't be made loop-invariant. If <span class="doxyComputerOutput">I</span> is made loop-invariant, <span class="doxyComputerOutput">Changed</span> is set to true. This function can be used as a slightly more aggressive replacement for isLoopInvariant.</p>


<p>If InsertPt is specified, it is the point to hoist instructions to. If null, the terminator of the loop preheader is used.</p>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a9773fde54683945b9e34a0f2e5c1a5a5a7806c120eb87aea9fbb52fed327e09de">llvm::MemorySSA::BeforeTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a830ba09d5969cd66878b05c17fdf66b6">llvm::ScalarEvolution::forgetBlockAndLoopDispositions</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#ab15de610fca1c900038bf3c333919e45">llvm::MemorySSA::getMemoryAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a01a350909e784d6fa43181a72de61529">llvm::MemorySSAUpdater::getMemorySSA</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a6cb6a58fb0ded82b4c7755fc4c27c86d">isLoopInvariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8601ff0320b6e29a13a2194200853425">llvm::isSafeToSpeculativelyExecute</a>, <a href="#ae58027d845fb948a63a8ff44851699d5">makeLoopInvariant</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ae26e0fb4a78dc439a03ac42c4ba6e674">llvm::MemorySSAUpdater::moveToPlace</a>.</p>

</div>
</div>

### setLoopAlreadyUnrolled() {#ae27590daf21d575c9bb75c966fe256f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Loop::setLoopAlreadyUnrolled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add llvm.loop.unroll.disable to this loop's loop id metadata.</p>


<p>Remove existing unroll metadata and add unroll disable metadata to indicate the loop has already been unrolled. This prevents a loop from being unrolled more than is directed by a pragma if the loop unrolling pass is run more than once (which it generally is).</p>


<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getHeader</a>, <a href="#afbcd78588d5235f99698b5c30f591382">getLoopID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8a1ae2e1de53a840bee516d1f5bb173">llvm::makePostTransformationMetadata</a> and <a href="#adf4be757fa30ca7fe3e8b119438100f0">setLoopID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>.</p>

</div>
</div>

### setLoopID() {#adf4be757fa30ca7fe3e8b119438100f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Loop::setLoopID (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * LoopID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the llvm.loop loop id metadata for this loop.</p>


<p>The LoopID metadata node will be added to each terminator instruction in the loop that branches to the loop header.</p>


<p>The LoopID metadata node should have one or more operands and the first operand should be the node itself.</p>


<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a542a6493b191eb84b5457d35ecd685c5">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatches</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a55c9054d63d1c6a39e9c09ba13a482fa">llvm::addStringMetadataToLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>, <a href="#ae27590daf21d575c9bb75c966fe256f2">setLoopAlreadyUnrolled</a>, <a href="#aa0930d54ec09b50bbfa09ec317e0df42">setLoopMustProgress</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>.</p>

</div>
</div>

### setLoopMustProgress() {#aa0930d54ec09b50bbfa09ec317e0df42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Loop::setLoopMustProgress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add llvm.loop.mustprogress to this loop's loop id metadata.</p>

<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3f91ce019424451ab50bf348826fa270">llvm::findOptionMDForLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getHeader</a>, <a href="#afbcd78588d5235f99698b5c30f591382">getLoopID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8a1ae2e1de53a840bee516d1f5bb173">llvm::makePostTransformationMetadata</a> and <a href="#adf4be757fa30ca7fe3e8b119438100f0">setLoopID</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">LoopInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp">LoopInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
