---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mustbeexecutedcontextexplorer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MustBeExecutedContextExplorer` Struct Reference

<p>A "must be executed context" for a given program point PP is the set of instructions, potentially before and after PP, that are executed always when PP is reached. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MustBeExecutedContextExplorer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">llvm/Analysis/MustExecute.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b61f538f0532c2c064f601a989a8cf">iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator-based interface. <a href="#af9b61f538f0532c2c064f601a989a8cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9101e36bf9abb8452e588119217215">const_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e794eebb1f990ce46e5e3482a97f6ee">MustBeExecutedContextExplorer</a> (bool ExploreInterBlock, bool ExploreCFGForward, bool ExploreCFGBackward, GetterTy&lt; const LoopInfo &gt; LIGetter=[](const Function &amp;) { return nullptr;}, GetterTy&lt; const DominatorTree &gt; DTGetter=[](const Function &amp;) { return nullptr;}, GetterTy&lt; const PostDominatorTree &gt; PDTGetter=[](const Function &amp;) { return nullptr;})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In the description of the parameters we use PP to denote a program point for which the must be executed context is explored, or put differently, for which the <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a> is created. <a href="#a4e794eebb1f990ce46e5e3482a97f6ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af9b61f538f0532c2c064f601a989a8cf">iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a626aecb5a83600489c4128d5493cea8d">begin</a> (const Instruction *PP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator to explore the context around <span class="doxyComputerOutput">PP</span>. <a href="#a626aecb5a83600489c4128d5493cea8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aec9101e36bf9abb8452e588119217215">const_iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cddec5e0924c288d231a6592325de3c">begin</a> (const Instruction *PP) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator to explore the cached context around <span class="doxyComputerOutput">PP</span>. <a href="#a0cddec5e0924c288d231a6592325de3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af9b61f538f0532c2c064f601a989a8cf">iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48adde8f5f98e34f61e40c727a0c8cdb">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an universal end iterator. <a href="#a48adde8f5f98e34f61e40c727a0c8cdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af9b61f538f0532c2c064f601a989a8cf">iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d063e4b839d810bb1e2773d855c114">end</a> (const Instruction *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aec9101e36bf9abb8452e588119217215">const_iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f803ce2776d1407c46413d50b5aa0a6">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aec9101e36bf9abb8452e588119217215">const_iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2ef528dbf6ce269f36730ff53b58abe">end</a> (const Instruction *) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">llvm::iterator_range</a>&lt; <a href="#af9b61f538f0532c2c064f601a989a8cf">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cbad11b160003ae7f4ebb06bc25d981">range</a> (const Instruction *PP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a8cbad11b160003ae7f4ebb06bc25d981">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">llvm::iterator_range</a>&lt; <a href="#aec9101e36bf9abb8452e588119217215">const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1f3506cc7035c5be0db2a02fdd89268">range</a> (const Instruction *PP) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator range to explore the cached context around <span class="doxyComputerOutput">PP</span>. <a href="#ae1f3506cc7035c5be0db2a02fdd89268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae9298fe73358958f4aea76bf1a42b0e">checkForAllContext</a> (const Instruction *PP, function_ref&lt; bool(const Instruction *)&gt; Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#aae9298fe73358958f4aea76bf1a42b0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592fdf7adf13aace9ebdd0dc06efc6db">findInContextOf</a> (const Instruction *I, const Instruction *PP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to look for <span class="doxyComputerOutput">I</span> in the context of <span class="doxyComputerOutput">PP</span>. <a href="#a592fdf7adf13aace9ebdd0dc06efc6db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3386f23306622d58407b92ae55f3962">findInContextOf</a> (const Instruction *I, iterator &amp;EIt, iterator &amp;EEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to look for <span class="doxyComputerOutput">I</span> in the context defined by <span class="doxyComputerOutput">EIt</span> and <span class="doxyComputerOutput">EEnd</span>. <a href="#ab3386f23306622d58407b92ae55f3962">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bcb8bb92d8385a81a07659c6e1ec6fc">getMustBeExecutedNextInstruction</a> (MustBeExecutedIterator &amp;It, const Instruction *PP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the next instruction that is guaranteed to be executed after <span class="doxyComputerOutput">PP</span>. <a href="#a1bcb8bb92d8385a81a07659c6e1ec6fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa990506f9bd98f9c5d4f82fdfe633116">getMustBeExecutedPrevInstruction</a> (MustBeExecutedIterator &amp;It, const Instruction *PP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the previous instr. <a href="#aa990506f9bd98f9c5d4f82fdfe633116">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0cac3cc09d07bc44ffd388ff8be5e49">findForwardJoinPoint</a> (const BasicBlock *InitBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the next join point from <span class="doxyComputerOutput">InitBB</span> in forward direction. <a href="#ab0cac3cc09d07bc44ffd388ff8be5e49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dca3347facf58865b34df5e5df676f0">findBackwardJoinPoint</a> (const BasicBlock *InitBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the next join point from <span class="doxyComputerOutput">InitBB</span> in backward direction. <a href="#a0dca3347facf58865b34df5e5df676f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c69dc51db80876ffbc1132c69aab1a">ExploreInterBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parameter that limit the performed exploration. <a href="#a08c69dc51db80876ffbc1132c69aab1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a533792a35fe00dee2c6e2fb30763c8da">ExploreCFGForward</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a526e5839365653306608b0e2b95854f5">ExploreCFGBackward</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">GetterTy&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b0ec5a0d24d053d8c17ec249feb456">LIGetter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a91b0ec5a0d24d053d8c17ec249feb456">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">GetterTy&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04d445ef93dd2265e5e708492c911b6">DTGetter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">GetterTy&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57174ed7dc4a10e8e3e514fca5b898be">PDTGetter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, std::optional&lt; bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55715060df4c36bdc73fc9ceb59c4320">BlockTransferMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a55715060df4c36bdc73fc9ceb59c4320">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, std::optional&lt; bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e75ba59830d9f060f7a51d1360bb7a">IrreducibleControlMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map to cache containsIrreducibleCFG results. <a href="#a33e75ba59830d9f060f7a51d1360bb7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae036e8c66aefbf553e33744ef4468722">InstructionIteratorMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from instructions to associated must be executed iterators. <a href="#ae036e8c66aefbf553e33744ef4468722">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d1abf7c19a3a698e8dda59d921ac5b1">EndIterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A unique end iterator. <a href="#a7d1abf7c19a3a698e8dda59d921ac5b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A "must be executed context" for a given program point PP is the set of instructions, potentially before and after PP, that are executed always when PP is reached.</p>


<p>The <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer">MustBeExecutedContextExplorer</a> an interface to explore "must be executed contexts" in a module through the use of <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a>.</p>


<p>The explorer exposes "must be executed iterators" that traverse the must be executed context. There is little information sharing between iterators as the expected use case involves few iterators for "far apart" instructions. If that changes, we should consider caching more intermediate results.</p>


<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#aec9101e36bf9abb8452e588119217215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MustBeExecutedContextExplorer::const_iterator =  const MustBeExecutedIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### iterator {#af9b61f538f0532c2c064f601a989a8cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MustBeExecutedContextExplorer::iterator =  MustBeExecutedIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator-based interface.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a>. {</p></dd>
</dl>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MustBeExecutedContextExplorer() {#a4e794eebb1f990ce46e5e3482a97f6ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MustBeExecutedContextExplorer::MustBeExecutedContextExplorer (bool ExploreInterBlock, bool ExploreCFGForward, bool ExploreCFGBackward, GetterTy&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &gt; LIGetter=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;) { return nullptr;}, GetterTy&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &gt; DTGetter=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;) { return nullptr;}, GetterTy&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &gt; PDTGetter=[](<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;) { return nullptr;})</td>
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

<p>In the description of the parameters we use PP to denote a program point for which the must be executed context is explored, or put differently, for which the <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a> is created.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExploreInterBlock</td>
<td class="doxyParamItemDescription"><p>Flag to indicate if instructions in blocks other than the parent of PP should be explored.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExploreCFGForward</td>
<td class="doxyParamItemDescription"><p>Flag to indicate if instructions located after PP in the CFG, e.g., post-dominating PP, should be explored.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExploreCFGBackward</td>
<td class="doxyParamItemDescription"><p>Flag to indicate if instructions located before PP in the CFG, e.g., dominating PP, should be explored.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>References <a href="#a526e5839365653306608b0e2b95854f5">ExploreCFGBackward</a>, <a href="#a533792a35fe00dee2c6e2fb30763c8da">ExploreCFGForward</a> and <a href="#a08c69dc51db80876ffbc1132c69aab1a">ExploreInterBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a626aecb5a83600489c4128d5493cea8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator &amp; llvm::MustBeExecutedContextExplorer::begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PP)</td>
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

<p>Return an iterator to explore the context around <span class="doxyComputerOutput">PP</span>.</p>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>Referenced by <a href="#aae9298fe73358958f4aea76bf1a42b0e">checkForAllContext</a>, <a href="#a592fdf7adf13aace9ebdd0dc06efc6db">findInContextOf</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#acf71d4170b64e15a937f8c8ed61cbd68">anonymous{AttributorAttributes.cpp}::followUsesInContext</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#aff3d225ae8841fccee34cd8a722f14b2">llvm::Attributor::getAttrsFromAssumes</a>, <a href="#a8cbad11b160003ae7f4ebb06bc25d981">range</a> and <a href="#ae1f3506cc7035c5be0db2a02fdd89268">range</a>.</p>

</div>
</div>

### begin() {#a0cddec5e0924c288d231a6592325de3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator &amp; llvm::MustBeExecutedContextExplorer::begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PP)</td>
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

<p>Return an iterator to explore the cached context around <span class="doxyComputerOutput">PP</span>.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### checkForAllContext() {#aae9298fe73358958f4aea76bf1a42b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MustBeExecutedContextExplorer::checkForAllContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PP, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *)&gt; Pred)</td>
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

<p>}</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> <span class="doxyComputerOutput">Pred</span> on all instructions in the context.</p>


<p>This method will evaluate <span class="doxyComputerOutput">Pred</span> and return true if <span class="doxyComputerOutput">Pred</span> holds in every instruction.</p>


<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>References <a href="#a626aecb5a83600489c4128d5493cea8d">begin</a> and <a href="#a48adde8f5f98e34f61e40c727a0c8cdb">end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a4acb22dc4402babad62f8b4815129809">anonymous{AttributorAttributes.cpp}::followUsesInMBEC</a>.</p>

</div>
</div>

### end() {#a48adde8f5f98e34f61e40c727a0c8cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator &amp; llvm::MustBeExecutedContextExplorer::end ()</td>
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

<p>Return an universal end iterator.</p>


<p>{</p>


<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>Referenced by <a href="#aae9298fe73358958f4aea76bf1a42b0e">checkForAllContext</a>, <a href="#a592fdf7adf13aace9ebdd0dc06efc6db">findInContextOf</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#acf71d4170b64e15a937f8c8ed61cbd68">anonymous{AttributorAttributes.cpp}::followUsesInContext</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#aff3d225ae8841fccee34cd8a722f14b2">llvm::Attributor::getAttrsFromAssumes</a>, <a href="#a8cbad11b160003ae7f4ebb06bc25d981">range</a> and <a href="#ae1f3506cc7035c5be0db2a02fdd89268">range</a>.</p>

</div>
</div>

### end() {#ae1d063e4b839d810bb1e2773d855c114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator &amp; llvm::MustBeExecutedContextExplorer::end (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *)</td>
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



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### end() {#a5f803ce2776d1407c46413d50b5aa0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator &amp; llvm::MustBeExecutedContextExplorer::end ()</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### end() {#ab2ef528dbf6ce269f36730ff53b58abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator &amp; llvm::MustBeExecutedContextExplorer::end (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *)</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### findBackwardJoinPoint() {#a0dca3347facf58865b34df5e5df676f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * MustBeExecutedContextExplorer::findBackwardJoinPoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InitBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the next join point from <span class="doxyComputerOutput">InitBB</span> in backward direction.</p>

<p>Declaration at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a74aa9daea070e2ad3394a3ec58b7316a">llvm::BasicBlock::getUniquePredecessor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#aa990506f9bd98f9c5d4f82fdfe633116">getMustBeExecutedPrevInstruction</a>.</p>

</div>
</div>

### findForwardJoinPoint() {#ab0cac3cc09d07bc44ffd388ff8be5e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * MustBeExecutedContextExplorer::findForwardJoinPoint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InitBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the next join point from <span class="doxyComputerOutput">InitBB</span> in forward direction.</p>

<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#a7d1b25613e8e6f7f9a46d71943a8df32">getOrCreateCachedOptional</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a57f1945911ca1e95d0f51d7c3516b529">llvm::BasicBlock::getUniqueSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abff5a423c1f45e23958dde8ee695c9a9">llvm::isGuaranteedToTransferExecutionToSuccessor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#a7a63141397040dbcc271c76f5ea3e6e3">maybeEndlessLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add8cf45ebe45732b4baff48cb3a8d435">llvm::mayContainIrreducibleControl</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#a1bcb8bb92d8385a81a07659c6e1ec6fc">getMustBeExecutedNextInstruction</a>.</p>

</div>
</div>

### findInContextOf() {#a592fdf7adf13aace9ebdd0dc06efc6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MustBeExecutedContextExplorer::findInContextOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PP)</td>
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

<p>Helper to look for <span class="doxyComputerOutput">I</span> in the context of <span class="doxyComputerOutput">PP</span>.</p>


<p>The context is expanded until <span class="doxyComputerOutput">I</span> was found or no more expansion is possible.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True, iff <span class="doxyComputerOutput">I</span> was found.</p></dd>
</dl>


<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>References <a href="#a626aecb5a83600489c4128d5493cea8d">begin</a>, <a href="#a48adde8f5f98e34f61e40c727a0c8cdb">end</a>, <a href="#a592fdf7adf13aace9ebdd0dc06efc6db">findInContextOf</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a592fdf7adf13aace9ebdd0dc06efc6db">findInContextOf</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#acf71d4170b64e15a937f8c8ed61cbd68">anonymous{AttributorAttributes.cpp}::followUsesInContext</a> and <a href="/web-llvm/docs/api/structs/llvm/attributor/#aff3d225ae8841fccee34cd8a722f14b2">llvm::Attributor::getAttrsFromAssumes</a>.</p>

</div>
</div>

### findInContextOf() {#ab3386f23306622d58407b92ae55f3962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MustBeExecutedContextExplorer::findInContextOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="#af9b61f538f0532c2c064f601a989a8cf">iterator</a> &amp; EIt, <a href="#af9b61f538f0532c2c064f601a989a8cf">iterator</a> &amp; EEnd)</td>
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

<p>Helper to look for <span class="doxyComputerOutput">I</span> in the context defined by <span class="doxyComputerOutput">EIt</span> and <span class="doxyComputerOutput">EEnd</span>.</p>


<p>The context is expanded until <span class="doxyComputerOutput">I</span> was found or no more expansion is possible.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True, iff <span class="doxyComputerOutput">I</span> was found.</p></dd>
</dl>


<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator/#aa84ccbb4a623e74932c411a2f0e735b0">llvm::MustBeExecutedIterator::count</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getMustBeExecutedNextInstruction() {#a1bcb8bb92d8385a81a07659c6e1ec6fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * MustBeExecutedContextExplorer::getMustBeExecutedNextInstruction (<a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a> &amp; It, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the next instruction that is guaranteed to be executed after <span class="doxyComputerOutput">PP</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">It</td>
<td class="doxyParamItemDescription"><p>The iterator that is used to traverse the must be executed context.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PP</td>
<td class="doxyParamItemDescription"><p>The program point for which the next instruction that is guaranteed to execute is determined.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a08c69dc51db80876ffbc1132c69aab1a">ExploreInterBlock</a>, <a href="#ab0cac3cc09d07bc44ffd388ff8be5e49">findForwardJoinPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4848d1a141ddc7cf0068460fba53ba37">llvm::BasicBlock::front</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6e5d2e18c81baaeec7dadc81a0dea993">llvm::Instruction::getSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abff5a423c1f45e23958dde8ee695c9a9">llvm::isGuaranteedToTransferExecutionToSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a7653277511df1034148a37520a585bb5">llvm::Instruction::isTerminator</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### getMustBeExecutedPrevInstruction() {#aa990506f9bd98f9c5d4f82fdfe633116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * MustBeExecutedContextExplorer::getMustBeExecutedPrevInstruction (<a href="/web-llvm/docs/api/structs/llvm/mustbeexecutediterator">MustBeExecutedIterator</a> &amp; It, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the previous instr.</p>


<p>that is guaranteed to be executed before <span class="doxyComputerOutput">PP</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">It</td>
<td class="doxyParamItemDescription"><p>The iterator that is used to traverse the must be executed context.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PP</td>
<td class="doxyParamItemDescription"><p>The program point for which the previous instr. that is guaranteed to execute is determined.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a08c69dc51db80876ffbc1132c69aab1a">ExploreInterBlock</a>, <a href="#a0dca3347facf58865b34df5e5df676f0">findBackwardJoinPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a1dfdcf6998ec28bfd2f8d2cdebc984a9">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getPrevNode</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### range() {#a8cbad11b160003ae7f4ebb06bc25d981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::iterator_range&lt; iterator &gt; llvm::MustBeExecutedContextExplorer::range (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PP)</td>
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

<p>}</p>


<p>Return an iterator range to explore the context around <span class="doxyComputerOutput">PP</span>.</p>


<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>References <a href="#a626aecb5a83600489c4128d5493cea8d">begin</a>, <a href="#a48adde8f5f98e34f61e40c727a0c8cdb">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mustbeexecutedcontextprinterpass/#a1b1a19034ac7bbb0481e54e850fc431a">llvm::MustBeExecutedContextPrinterPass::run</a>.</p>

</div>
</div>

### range() {#ae1f3506cc7035c5be0db2a02fdd89268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::iterator_range&lt; const_iterator &gt; llvm::MustBeExecutedContextExplorer::range (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * PP)</td>
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

<p>Return an iterator range to explore the cached context around <span class="doxyComputerOutput">PP</span>.</p>

<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>References <a href="#a626aecb5a83600489c4128d5493cea8d">begin</a>, <a href="#a48adde8f5f98e34f61e40c727a0c8cdb">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ExploreCFGBackward {#a526e5839365653306608b0e2b95854f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::MustBeExecutedContextExplorer::ExploreCFGBackward</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>Referenced by <a href="#a4e794eebb1f990ce46e5e3482a97f6ee">MustBeExecutedContextExplorer</a>.</p>

</div>
</div>

### ExploreCFGForward {#a533792a35fe00dee2c6e2fb30763c8da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::MustBeExecutedContextExplorer::ExploreCFGForward</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>Referenced by <a href="#a4e794eebb1f990ce46e5e3482a97f6ee">MustBeExecutedContextExplorer</a>.</p>

</div>
</div>

### ExploreInterBlock {#a08c69dc51db80876ffbc1132c69aab1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::MustBeExecutedContextExplorer::ExploreInterBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parameter that limit the performed exploration.</p>


<p>See the constructor for their meaning. {</p>


<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>


<p>Referenced by <a href="#a1bcb8bb92d8385a81a07659c6e1ec6fc">getMustBeExecutedNextInstruction</a>, <a href="#aa990506f9bd98f9c5d4f82fdfe633116">getMustBeExecutedPrevInstruction</a> and <a href="#a4e794eebb1f990ce46e5e3482a97f6ee">MustBeExecutedContextExplorer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockTransferMap {#a55715060df4c36bdc73fc9ceb59c4320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, std::optional&lt;bool&gt; &gt; llvm::MustBeExecutedContextExplorer::BlockTransferMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>


<p>Map to cache isGuaranteedToTransferExecutionToSuccessor results.</p>


<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### DTGetter {#af04d445ef93dd2265e5e708492c911b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetterTy&lt;const DominatorTree&gt; llvm::MustBeExecutedContextExplorer::DTGetter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### EndIterator {#a7d1abf7c19a3a698e8dda59d921ac5b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MustBeExecutedIterator llvm::MustBeExecutedContextExplorer::EndIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A unique end iterator.</p>

<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### InstructionIteratorMap {#ae036e8c66aefbf553e33744ef4468722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Instruction *, std::unique_ptr&lt;MustBeExecutedIterator&gt; &gt; llvm::MustBeExecutedContextExplorer::InstructionIteratorMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from instructions to associated must be executed iterators.</p>

<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### IrreducibleControlMap {#a33e75ba59830d9f060f7a51d1360bb7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, std::optional&lt;bool&gt; &gt; llvm::MustBeExecutedContextExplorer::IrreducibleControlMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map to cache containsIrreducibleCFG results.</p>

<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### LIGetter {#a91b0ec5a0d24d053d8c17ec249feb456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetterTy&lt;const LoopInfo&gt; llvm::MustBeExecutedContextExplorer::LIGetter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>


<p>Getters for common CFG analyses: <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a>, and <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a>. {</p>


<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

### PDTGetter {#a57174ed7dc4a10e8e3e514fca5b898be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetterTy&lt;const PostDominatorTree&gt; llvm::MustBeExecutedContextExplorer::PDTGetter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">MustExecute.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
