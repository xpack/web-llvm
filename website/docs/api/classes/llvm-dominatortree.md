---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dominatortree
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DominatorTree` Class

<p>Concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> that is used to compute a normal dominator tree. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DominatorTree { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase&lt;NodeT, IsPostDom&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Core dominator tree base class. <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb795f905a206e347ffc8c87fb9b6935">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, false &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45241423aa6938dee80cf04ba6eb978a">DominatorTree</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf76c1ec4070ca158a8b30d0b7989558">DominatorTree</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefeadea2057e320609553f6dbe57089f">DominatorTree</a> (DominatorTree &amp;DT, DomTreeBuilder::BBUpdates U)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5abacbe0c3439b1f549f2d14292d0b1">invalidate</a> (Function &amp;F, const PreservedAnalyses &amp;PA, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation explicitly. <a href="#ae5abacbe0c3439b1f549f2d14292d0b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c69311e8d44898dac36a155c3d8691d">dominates</a> (const BasicBlock *BB, const Use &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the (end of the) basic block BB dominates the use U. <a href="#a5c69311e8d44898dac36a155c3d8691d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a752d16df3e1e92baea8a720f33f8e2fb">dominates</a> (const Value *Def, const Use &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if value Def dominates use U, in the sense that Def is available at U, and could be substituted as the used value without violating the SSA dominance requirement. <a href="#a752d16df3e1e92baea8a720f33f8e2fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f7e1b2632b5f08523080e6f1f2271f">dominates</a> (const Value *Def, const Instruction *User) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if value Def dominates all possible uses inside instruction <a href="/web-llvm/docs/api/classes/llvm/user">User</a>. <a href="#a55f7e1b2632b5f08523080e6f1f2271f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcbcee65df47d0fb478f233cf836722">dominates</a> (const Value *Def, BasicBlock::iterator User) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff2a6ccc1db7f9718b2ea1a1aea01d8f">dominates</a> (const Instruction *Def, const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Def would dominate a use in any instruction in BB. <a href="#aff2a6ccc1db7f9718b2ea1a1aea01d8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa37be9270ea603d5273c3f58e8a4c3f">dominates</a> (const BasicBlockEdge &amp;BBE, const Use &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if an edge dominates a use. <a href="#afa37be9270ea603d5273c3f58e8a4c3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f6d6fa3db0135b61c54c14f40cd6be">dominates</a> (const BasicBlockEdge &amp;BBE, const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff74a4ce99c42504c5dcad1003d52fff">dominates</a> (const BasicBlockEdge &amp;BBE1, const BasicBlockEdge &amp;BBE2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if edge <span class="doxyComputerOutput">BBE1</span> dominates edge <span class="doxyComputerOutput">BBE2</span>. <a href="#aff74a4ce99c42504c5dcad1003d52fff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a70f2c359aadd76a72aaaede16aca4a">isReachableFromEntry</a> (const Use &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide an overload for a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>. <a href="#a1a70f2c359aadd76a72aaaede16aca4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ec50ab2c78eff965caf3da71cd08be4">findNearestCommonDominator</a> (Instruction *I1, Instruction *I2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the nearest instruction I that dominates both I1 and I2, in the sense that a result produced before I will be available at both I1 and I2. <a href="#a2ec50ab2c78eff965caf3da71cd08be4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67d0c7d19a0660da533ec8076c1d8268">viewGraph</a> (const Twine &amp;Name, const Twine &amp;Title)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d17087b538162053fd17725c6b6d295">viewGraph</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbbae03d2d929f2710f31e1ece63e46b">dominates</a> (const DomTreeNodeBase&lt; BasicBlock &gt; *A, const DomTreeNodeBase&lt; BasicBlock &gt; *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dominates - Returns true iff A dominates B. <a href="#abbbae03d2d929f2710f31e1ece63e46b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ef9cd5a97e33dfd2e429cb3892e596e">dominates</a> (const BasicBlock *A, const BasicBlock *B) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec8ce584def33a7ca7449db33936db1">isReachableFromEntry</a> (const BasicBlock *A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReachableFromEntry - Return true if A is dominated by the entry block of the function containing it. <a href="#a1ec8ce584def33a7ca7449db33936db1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed0e32e5c8189fdc6c701dfbdf7f76b">isReachableFromEntry</a> (const DomTreeNodeBase&lt; BasicBlock &gt; *A) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36bb9b5ba771a695be122a96a30b08f3">findNearestCommonDominator</a> (BasicBlock *A, BasicBlock *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find nearest common dominator basic block for basic block A and B. <a href="#a36bb9b5ba771a695be122a96a30b08f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6fbad0e1e729b07da64172041676bb8">findNearestCommonDominator</a> (const BasicBlock *A, const BasicBlock *B) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c97a14fbf3e15f6bdf12c921087ea02">findNearestCommonDominator</a> (iterator_range&lt; IteratorTy &gt; Nodes) const</td>
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

<p>Concrete subclass of <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase">DominatorTreeBase</a> that is used to compute a normal dominator tree.</p>


<p>Definition: A block is said to be forward statically reachable if there is a path from the entry of the function to the block. A statically reachable block may become statically unreachable during optimization.</p>


<p>A forward unreachable block may appear in the dominator tree, or it may not. If it does, dominance queries will return results as if all reachable blocks dominate it. When asking for a <a href="/web-llvm/docs/api/classes/node">Node</a> corresponding to a potentially unreachable block, calling code must handle the case where the block was unreachable and the result of <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">getNode()</a> is nullptr.</p>


<p>Generally, a block known to be unreachable when the dominator tree is constructed will not be in the tree. One which becomes unreachable after the dominator tree is initially constructed may still exist in the tree, even if the tree is properly updated. Calling code should not rely on the preceding statements; this is stated only to assist human understanding.</p>


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Base {#acb795f905a206e347ffc8c87fb9b6935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DominatorTree::Base =  DominatorTreeBase&lt;BasicBlock, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DominatorTree() {#a45241423aa6938dee80cf04ba6eb978a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DominatorTree::DominatorTree ()</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Referenced by <a href="#aefeadea2057e320609553f6dbe57089f">DominatorTree</a>.</p>

</div>
</div>

### DominatorTree() {#adf76c1ec4070ca158a8b30d0b7989558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DominatorTree::DominatorTree (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa0641ae965656ff9988d67a35140e4d9">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::recalculate</a>.</p>

</div>
</div>

### DominatorTree() {#aefeadea2057e320609553f6dbe57089f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DominatorTree::DominatorTree (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/namespaces/llvm/domtreebuilder/#a2a9e2a2431f6f6ecbb7996d72036bbbb">DomTreeBuilder::BBUpdates</a> U)</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>References <a href="#a45241423aa6938dee80cf04ba6eb978a">DominatorTree</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#afc022c576bec78143017832c543fe8f7">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::Parent</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa0641ae965656ff9988d67a35140e4d9">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::recalculate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dominates() {#a5c69311e8d44898dac36a155c3d8691d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DominatorTree::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the (end of the) basic block BB dominates the use U.</p>

<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5c69311e8d44898dac36a155c3d8691d">dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ade6d93f9485649bade540a37ec163058">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::properlyDominates</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a0937bbe895c7ed05d32c861b0f9e0f97">llvm::LoopSafetyInfo::allLoopPathsLeadToBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#aa67d22298695c49e80b79cb8a271928b">llvm::LoopAccessInfo::blockNeedsPredication</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a341358b4e9c3ffb463182ea3280b2016">BrPHIToSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0e686f0d790f0fd925a036c4cb50199b">CalculateUnswitchCostMultiplier</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#adbe30a5e0e6f5dc00dac4c72dbffb905">canProveExitOnFirstIteration</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ad1f0acfffdda650ed4ceb4d4622c1248">checkBasicSSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a32203e7352f128904822ee859e9ae839">checkHoistValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a866163a9dbd27133c221fc2569333ddb">anonymous{CodeMoverUtils.cpp}::ControlConditions::collectControlConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d8cb47f2535cdf5f9608baabfa78f4e">llvm::computeKnownBitsFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a93cb45813945a1bb817bee6664d452be">computeKnownFPClassFromContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#aa2cbc07e426705bbdb98c0f6ae7e3f72">containsUnconditionalCallSafepoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion/#aead9a4f05ccb13941f28611766176f30">anonymous{HotColdSplitting.cpp}::OutliningRegion::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp/#aaf5c3bcafb3f5f0f1a0fd9ddfe9b6e1a">doesStoreDominatesAllLatches</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="#a5c69311e8d44898dac36a155c3d8691d">dominates</a>, <a href="#ad7f6d6fa3db0135b61c54c14f40cd6be">dominates</a>, <a href="#afa37be9270ea603d5273c3f58e8a4c3f">dominates</a>, <a href="#aff74a4ce99c42504c5dcad1003d52fff">dominates</a>, <a href="#aff2a6ccc1db7f9718b2ea1a1aea01d8f">dominates</a>, <a href="#a55f7e1b2632b5f08523080e6f1f2271f">dominates</a>, <a href="#a752d16df3e1e92baea8a720f33f8e2fb">dominates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a8b9e4ec572c189d8f8afc4f71da55a9c">findBasePointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a8db2bdc3994fcf7d2631f887443ad477">findBBsToSinkInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a52374e76082ee94158724e5695a88a02">findBestNonTrivialUnswitchCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typemetadatautils-cpp/#a64702c7c3e6913b9076666d4e071b35d">findCallsAtConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a5a43eda4795549e941b4bacafdb956bb">foldConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a73b18943dffc9db671d3217c90b15a4f">foldGuardedFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab15c69cfc260f1de61bb644d88b1ed85">foldSelectToPhiImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp/#af0470a389063c0b4665f29617596051a">getFreezeInsertPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a995c9f54308d436b9046a8741b149671">getInsertPointForUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#ad06f2af2991a303ba80e1e9fea006eaf">getInvariantGroupClobberingInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#a56378412b516c96bbab7cd31b530e0ff">getMinAnalyzeableBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aa898a031df90bb6ac31dc9cb253b310e">getReductionInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a58bcd428c0ca38b723b8ef938868ec4a">llvm::coro::getSpillInsertionPt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a64bba3cf05c8cb1baa848483e7150830">hoistValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a864a2ad11bbf83cf2b910e43d461cd02">insertParsePoints</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a508cede7bc51eb83285e5fe30d14b701">IsAcceptableTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a82d87658bf2f69df81493401a7c6dc52">IsBackEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb077dd7e8e0c4efa7d2aaba0d21dab7">llvm::isControlFlowEquivalent</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a203487323e0aa341b6c24f9ef20b5909">llvm::RecurrenceDescriptor::isFixedOrderRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#abc3ce3c416891376602062102e3f6086">isFullDominator</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#aef4460eccacc720018aa15086026c11d">llvm::HardwareLoopInfo::isHardwareLoopCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a08c9c2fedd8f175884c88275c7987e03">isKnownNonNullFromDominatingCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5804b68ebc77c8751a9cb4e066735450">llvm::isOverflowIntrinsicNoWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfg-cpp/#a3044854435d0fc239faf5505d55a80dc">isReachableImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a56c7f8ee6d9b85e582f1ebd77ecea124">llvm::isReachedBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adffe8dd96d1c957f04909ca9c2cd79ba">llvm::isSafeToMoveBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f7c11444c9e7d7c1036ae1f049f4cee">llvm::isValidAssumeForContext</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#ade252ec650f1f043ccf664b66c038d38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isValidCtxInstructionForOutsideAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#acd81badac05008b8ec9f327167344baa">IVUseShouldUsePostIncValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#af664c713571d51d8130da27b28cc2088">liesBetween</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a023f82db84f5e5ed13398308496689e7">llvm::mustExecuteUBIfPoisonOnPathTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#a3ddbec9e8a91a1d6a95110e5a197cde2">nearest_common_dominatee</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidatecompare/#aea9f11701fcbd34a98f7da033c725845">anonymous{LoopFuse.cpp}::FusionCandidateCompare::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a14d6eb48f298d47bdf871282b0c03f58">partitionLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#aaa1d9cfaf2d4ef4eca30ce71eb8c3a89">peelToTurnInvariantLoadsDerefencebale</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a604892413799925b9f8c886abee9e5ca">PickMostRelevantLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#a5477ec209ccebe7296e10d954c3fb86a">PrintDebugDomInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2120880bb6a40c7cbcf7e8c44b17a4b3">llvm::replaceDominatedUsesWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8dab43be03b9188d73d2f790461f767c">llvm::replaceDominatedUsesWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcde543cdc7a264cce4572bcb6796dc8">llvm::replaceDominatedUsesWithIf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a193d89bd37affe20169074ca1013f91a">llvm::replaceDominatedUsesWithIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a160dacda9f89b4c190ff303c6f4ed15e">reportMayClobberedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/placesafepointspass/#adcb87ee7d8b9f08bc82da9cae1c74429">llvm::PlaceSafepointsPass::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a7118a8527081192cbd8b839926fb95d4">simplifyCommonValuePhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>, <a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion/#a631ea87e33f8e50c1b90ae334ceea4c8">anonymous{HotColdSplitting.cpp}::OutliningRegion::takeSingleEntrySubRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/phitransaddr/#a020dcdde43c7bdff11476f1f5b64ef25">llvm::PHITransAddr::translateValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#a5109075f25d18bf4127922f2ab403dca">UpdateSSA</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#af412caabe4d2526271b50f052f9d3aef">valueDominatesPHI</a>.</p>

</div>
</div>

### dominates() {#a752d16df3e1e92baea8a720f33f8e2fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DominatorTree::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if value Def dominates use U, in the sense that Def is available at U, and could be substituted as the used value without violating the SSA dominance requirement.</p>


<p>In particular, it is worth noting that:</p>


<ul class="doxyList ">
<li>Non-instruction Defs dominate everything.</li>
<li>Def does not dominate a use in Def itself (outside of degenerate cases like unreachable code or trivial phi cycles).</li>
<li>Invoke Defs only dominate uses in their default destination.</li>
</ul>

<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5c69311e8d44898dac36a155c3d8691d">dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a1a70f2c359aadd76a72aaaede16aca4a">isReachableFromEntry</a>.</p>

</div>
</div>

### dominates() {#a55f7e1b2632b5f08523080e6f1f2271f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DominatorTree::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if value Def dominates all possible uses inside instruction <a href="/web-llvm/docs/api/classes/llvm/user">User</a>.</p>


<p>Same comments as for the Use-based API apply.</p>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5c69311e8d44898dac36a155c3d8691d">dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a1a70f2c359aadd76a72aaaede16aca4a">isReachableFromEntry</a>.</p>

</div>
</div>

### dominates() {#a0fcbcee65df47d0fb478f233cf836722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTree::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> User)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#a73ba38b119a12eb092295458fde44f52">dominates</a>.</p>

</div>
</div>

### dominates() {#aff2a6ccc1db7f9718b2ea1a1aea01d8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DominatorTree::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Def, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if Def would dominate a use in any instruction in BB.</p>


<p>If Def is an instruction in BB, then Def does not dominate BB.</p>


<p>Does not accept <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to avoid ambiguity with dominance checks between two basic blocks.</p>


<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="#a5c69311e8d44898dac36a155c3d8691d">dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="#a1a70f2c359aadd76a72aaaede16aca4a">isReachableFromEntry</a>.</p>

</div>
</div>

### dominates() {#afa37be9270ea603d5273c3f58e8a4c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DominatorTree::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblockedge">BasicBlockEdge</a> &amp; BBE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if an edge dominates a use.</p>


<p>If BBE is not a unique edge between start and end of the edge, it can never dominate the use.</p>


<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5c69311e8d44898dac36a155c3d8691d">dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblockedge/#a1eb1618f664ccb996a42b6d3ad8b9bbe">llvm::BasicBlockEdge::getEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblockedge/#a3aece19d76fe5bc5720cc369ef330b17">llvm::BasicBlockEdge::getStart</a>.</p>

</div>
</div>

### dominates() {#ad7f6d6fa3db0135b61c54c14f40cd6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DominatorTree::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblockedge">BasicBlockEdge</a> &amp; BBE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="#a5c69311e8d44898dac36a155c3d8691d">dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblockedge/#a1eb1618f664ccb996a42b6d3ad8b9bbe">llvm::BasicBlockEdge::getEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblockedge/#a3aece19d76fe5bc5720cc369ef330b17">llvm::BasicBlockEdge::getStart</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>

</div>
</div>

### dominates() {#aff74a4ce99c42504c5dcad1003d52fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DominatorTree::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblockedge">BasicBlockEdge</a> &amp; BBE1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblockedge">BasicBlockEdge</a> &amp; BBE2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if edge <span class="doxyComputerOutput">BBE1</span> dominates edge <span class="doxyComputerOutput">BBE2</span>.</p>

<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="#a5c69311e8d44898dac36a155c3d8691d">dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblockedge/#a1eb1618f664ccb996a42b6d3ad8b9bbe">llvm::BasicBlockEdge::getEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblockedge/#a3aece19d76fe5bc5720cc369ef330b17">llvm::BasicBlockEdge::getStart</a>.</p>

</div>
</div>

### dominates() {#abbbae03d2d929f2710f31e1ece63e46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; BasicBlock, IsPostDom &gt;::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt; * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt; * B)</td>
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

<p>dominates - Returns true iff A dominates B.</p>


<p>Note that this is not a constant time operation!</p>


<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### dominates() {#a2ef9cd5a97e33dfd2e429cb3892e596e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; BasicBlock, IsPostDom &gt;::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#a2ec50ab2c78eff965caf3da71cd08be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * DominatorTree::findNearestCommonDominator (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the nearest instruction I that dominates both I1 and I2, in the sense that a result produced before I will be available at both I1 and I2.</p>

<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="#a2ec50ab2c78eff965caf3da71cd08be4">findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a> and <a href="#a1a70f2c359aadd76a72aaaede16aca4a">isReachableFromEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a61b5cb822ee8e25eee3418a520337962">findCommonDominator</a>, <a href="#a2ec50ab2c78eff965caf3da71cd08be4">findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a995c9f54308d436b9046a8741b149671">getInsertPointForUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a15231e29111a0d8c49ffbe239f7047b6">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::insertBaseTaggedPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb077dd7e8e0c4efa7d2aaba0d21dab7">llvm::isControlFlowEquivalent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aa715758b669411461023dd64ef038e2a">nearest_common_dominator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90896a5c2c14e27297f4fdb0196e24b3">llvm::nonStrictlyPostDominate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#aa91fc385b3c151e89ac23b656e9bf8b6">usersDominator</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#a36bb9b5ba771a695be122a96a30b08f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::DominatorTreeBase&lt; BasicBlock, IsPostDom &gt;::findNearestCommonDominator (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * A, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B)</td>
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

<p>Find nearest common dominator basic block for basic block A and B.</p>


<p>A and B must have tree nodes.</p>


<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#af6fbad0e1e729b07da64172041676bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * llvm::DominatorTreeBase&lt; BasicBlock, IsPostDom &gt;::findNearestCommonDominator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B)</td>
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



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### findNearestCommonDominator() {#a4c97a14fbf3e15f6bdf12c921087ea02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::DominatorTreeBase&lt; BasicBlock, IsPostDom &gt;::findNearestCommonDominator (<a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; IteratorTy &gt; Nodes)</td>
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



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### invalidate() {#ae5abacbe0c3439b1f549f2d14292d0b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DominatorTree::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, FunctionAnalysisManager::Invalidator &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle invalidation explicitly.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### isReachableFromEntry() {#a1a70f2c359aadd76a72aaaede16aca4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DominatorTree::isReachableFromEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide an overload for a <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>.</p>

<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a1a70f2c359aadd76a72aaaede16aca4a">isReachableFromEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a10e1b14fd1da88aad682e5d70ab224bb">buildExtractionBlockSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a930e3a524f031bdb14fe281e4eff4219">checkClobberSanity</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a607c1e689b230ff38733bfc0bfd3b6da">collectUnswitchCandidatesWithInjections</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a13971a178ec8248ecf4b0a903c4db1c6">deleteDeadClonedBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="#aff2a6ccc1db7f9718b2ea1a1aea01d8f">dominates</a>, <a href="#a55f7e1b2632b5f08523080e6f1f2271f">dominates</a>, <a href="#a752d16df3e1e92baea8a720f33f8e2fb">dominates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a48a060decf79d58559a8e9e28df764f0">findBestInsertionSet</a>, <a href="#a2ec50ab2c78eff965caf3da71cd08be4">findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#aff79915252b3641f62311a35a060f054">foldUnusualPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo/#a68ed7ba6b7bd3212a48c4fb730e1bc4e">llvm::FunctionPropertiesInfo::getFunctionPropertiesInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a995c9f54308d436b9046a8741b149671">getInsertPointForUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a864a2ad11bbf83cf2b910e43d461cd02">insertParsePoints</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a0ffc25db9de504390b4b05af70e4d31d">isBlockInLCSSAForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a634fa78fa798ed1e2910ecb71b0718c7">llvm::isPotentiallyReachable</a>, <a href="#a1a70f2c359aadd76a72aaaede16aca4a">isReachableFromEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfg-cpp/#a3044854435d0fc239faf5505d55a80dc">isReachableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a7a59feca56f2ecfe5c74d6c04b0c45c7">ProcessBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a275ed8c2ebcd61ba635dbf7c119e7ed2">llvm::coro::BaseCloner::replaceEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a5b6fe6d57aa5475337994b0daec8cc54">llvm::JumpThreadingPass::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/instsimplifypass-cpp/#a49359723de1a046072e8cc931068d43f">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#ad69716246dabb743839cafceb902ef46">llvm::RewriteStatepointsForGC::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/phitransaddr/#a020dcdde43c7bdff11476f1f5b64ef25">llvm::PHITransAddr::translateValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### isReachableFromEntry() {#a1ec8ce584def33a7ca7449db33936db1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; BasicBlock, IsPostDom &gt;::isReachableFromEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * A)</td>
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

<p>isReachableFromEntry - Return true if A is dominated by the entry block of the function containing it.</p>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### isReachableFromEntry() {#a3ed0e32e5c8189fdc6c701dfbdf7f76b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DominatorTreeBase&lt; BasicBlock, IsPostDom &gt;::isReachableFromEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase">DomTreeNodeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt; * A)</td>
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



<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a>.</p>

</div>
</div>

### viewGraph() {#a67d0c7d19a0660da533ec8076c1d8268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DominatorTree::viewGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Title)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domprinter-cpp">DomPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab8635363d4287c93f64c55ad5567fcf0">llvm::ViewGraph</a>.</p>

</div>
</div>

### viewGraph() {#a7d17087b538162053fd17725c6b6d295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DominatorTree::viewGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/domprinter-cpp">DomPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="#a7d17087b538162053fd17725c6b6d295">viewGraph</a>.</p>


<p>Referenced by <a href="#a7d17087b538162053fd17725c6b6d295">viewGraph</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtree-h">GenericDomTree.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/domprinter-cpp">DomPrinter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp">Dominators.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
