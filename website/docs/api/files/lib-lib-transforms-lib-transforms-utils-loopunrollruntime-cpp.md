---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LoopUnrollRuntime.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">llvm/Analysis/DomTreeUpdater.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionsimplify-h">llvm/Analysis/InstructionSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopiterator-h">llvm/Analysis/LoopIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profdatautils-h">llvm/IR/ProfDataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/cloning-h">llvm/Transforms/Utils/Cloning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looputils-h">llvm/Transforms/Utils/LoopUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">llvm/Transforms/Utils/ScalarEvolutionExpander.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/unrollloop-h">llvm/Transforms/Utils/UnrollLoop.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83a4a18d11086a64b8851319c00671a1">STATISTIC</a> (NumRuntimeUnrolled, "Number of loops unrolled with run-time trip counts")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af700561cb065af85122cd321d6c4b989">ConnectProlog</a> (Loop *L, Value *BECount, unsigned Count, BasicBlock *PrologExit, BasicBlock *OriginalLoopLatchExit, BasicBlock *PreHeader, BasicBlock *NewPreHeader, ValueToValueMapTy &amp;VMap, DominatorTree *DT, LoopInfo *LI, bool PreserveLCSSA, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Connect the unrolling prolog code to the original loop. <a href="#af700561cb065af85122cd321d6c4b989">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a> (Loop *L, Value *ModVal, BasicBlock *NewExit, BasicBlock *Exit, BasicBlock *PreHeader, BasicBlock *EpilogPreHeader, BasicBlock *NewPreHeader, ValueToValueMapTy &amp;VMap, DominatorTree *DT, LoopInfo *LI, bool PreserveLCSSA, ScalarEvolution &amp;SE, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Connect the unrolling epilog code to the original loop. <a href="#a4ebed10d3e842e81a2df6974c2fd3760">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a> (Loop *L, Value *NewIter, const bool UseEpilogRemainder, const bool UnrollRemainder, BasicBlock *InsertTop, BasicBlock *InsertBot, BasicBlock *Preheader, std::vector&lt; BasicBlock * &gt; &amp;NewBlocks, LoopBlocksDFS &amp;LoopBlocks, ValueToValueMapTy &amp;VMap, DominatorTree *DT, LoopInfo *LI, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clone of the blocks in a loop and connect them together. <a href="#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b4edd31a148a751a95e80997f81c31">canProfitablyRuntimeUnrollMultiExitLoop</a> (Loop *L, SmallVectorImpl&lt; BasicBlock * &gt; &amp;OtherExits, BasicBlock *LatchExit, bool UseEpilogRemainder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we can profitably unroll the multi-exit loop L. <a href="#a98b4edd31a148a751a95e80997f81c31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bab17532f2b606ad25679ed9e138c73">CreateTripRemainder</a> (IRBuilder&lt;&gt; &amp;B, Value *BECount, Value *TripCount, unsigned Count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate ModVal = (BECount + 1) % Count on the abstract integer domain accounting for the possibility of unsigned overflow in the 2s complement domain. <a href="#a7bab17532f2b606ad25679ed9e138c73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c245e2a4a3f5a845a1cbe2922af167">UnrollRuntimeMultiExit</a>("unroll-runtime-multi-exit", cl::init(false), cl::Hidden, cl::desc("Allow runtime unrolling for loops with multiple exits, when " "epilog is generated"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a873b044e9706fd66860c6178f74a51f9">UnrollRuntimeOtherExitPredictable</a>("unroll-runtime-other-exit-predictable", cl::init(false), cl::Hidden, cl::desc("Assume the non latch exit block to be predictable"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71d5cd8a9f3f2982e334cb8ce9245e96">UnrolledLoopHeaderWeights</a>[] = {1, 127}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae905d898b267ca244e6d89fb1fba7c0e">EpilogHeaderWeights</a>[] = {1, 127}</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"loop-unroll"</td>
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

### canProfitablyRuntimeUnrollMultiExitLoop() {#a98b4edd31a148a751a95e80997f81c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canProfitablyRuntimeUnrollMultiExitLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; OtherExits, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LatchExit, bool UseEpilogRemainder)</td>
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

<p>Returns true if we can profitably unroll the multi-exit loop L.</p>


<p>Currently, we return true only if UnrollRuntimeMultiExit is set to true.</p>


<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#ae9c245e2a4a3f5a845a1cbe2922af167">UnrollRuntimeMultiExit</a> and <a href="#a873b044e9706fd66860c6178f74a51f9">UnrollRuntimeOtherExitPredictable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### CloneLoopBlocks() {#a399d7b7e2e6aec8e1ad80d3d73b7b1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * CloneLoopBlocks (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewIter, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool UseEpilogRemainder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool UnrollRemainder, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertTop, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertBot, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Preheader, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; NewBlocks, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs">LoopBlocksDFS</a> &amp; LoopBlocks, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, unsigned Count)</td>
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

<p>Create a clone of the blocks in a loop and connect them together.</p>


<p>A new loop will be created including all cloned blocks, and the iterator of the new loop switched to count NewIter down to 0. The cloned blocks should be inserted between InsertTop and InsertBot. InsertTop should be new preheader, InsertBot new loop exit. Returns the new cloned loop that is created.</p>


<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac3328dd05f047ea11f19504685b0e136">llvm::addClonedBlockToLoopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a4211a49504539a8a37aebb00e1390370">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::addNewBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#a003fe6215d300fc9720b1b056cdf4c23">llvm::LoopBlocksDFS::beginRPO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a75043d12a76b84200e9ed593719dc5eb">llvm::MDBuilder::createBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/loopblocksdfs/#aeebda6b0288bea7cd706111624ca73f6">llvm::LoopBlocksDFS::endRPO</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#ae6be28efa794d11d2b1395fa77d7ebef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ae9562b96f6f3fa41bd36538c080035ee">llvm::PHINode::getBasicBlockIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#aab2bf365c9f4b976adc7479576dfd5bb">llvm::DomTreeNodeBase&lt; NodeT &gt;::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a453de62c2dadf7b4b8df04e89f6ab4e0">llvm::DomTreeNodeBase&lt; NodeT &gt;::getIDom</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#afbcd78588d5235f99698b5c30f591382">llvm::Loop::getLoopID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fce2ce0e32b20e41b0aa9f8ca70c2">llvm::hasBranchWeightMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e3f06a77c19d1098df61d28499fcf3b">llvm::LLVMLoopUnrollFollowupAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac127703689b2c3771640f7fa800d61dc">llvm::LLVMLoopUnrollFollowupRemainder</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a368216c9c116e3f30d8dd352ce1370fc">llvm::makeFollowupLoopID</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5ba57877c55dfdbe6e3bbfdacd9ef8c1">llvm::PHINode::setIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a88cdefb709309eddc6e5daca0be6a7b4">llvm::PHINode::setIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#ae27590daf21d575c9bb75c966fe256f2">llvm::Loop::setLoopAlreadyUnrolled</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#adf4be757fa30ca7fe3e8b119438100f0">llvm::Loop::setLoopID</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae959364e4640ac025bbc046d3d7c7e61">llvm::Instruction::setSuccessor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### ConnectEpilog() {#a4ebed10d3e842e81a2df6974c2fd3760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConnectEpilog (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ModVal, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewExit, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Exit, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PreHeader, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * EpilogPreHeader, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewPreHeader, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, bool PreserveLCSSA, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, unsigned Count)</td>
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

<p>Connect the unrolling epilog code to the original loop.</p>


<p>The unrolling epilog code contains code to execute the 'extra' iterations if the run-time trip count modulo the unroll count is non-zero.</p>


<p>This function performs the following:</p>


<ul class="doxyList ">
<li>Update PHI nodes at the unrolling loop exit and epilog loop exit</li>
<li>Create PHI nodes at the unrolling loop exit to combine values that exit the unrolling loop code and jump around it.</li>
<li>Update PHI operands in the epilog loop by the new PHI nodes</li>
<li>Branch around the epilog loop if extra iters (ModVal) is zero.</li>
</ul>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a2881c226e1c102190d54c3b664330aba">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::changeImmediateDominator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a75043d12a76b84200e9ed593719dc5eb">llvm::MDBuilder::createBranchWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a2ec50ab2c78eff965caf3da71cd08be4">llvm::DominatorTree::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a804545e5b568edec8b970da32cd37359">llvm::ScalarEvolution::forgetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ae9562b96f6f3fa41bd36538c080035ee">llvm::PHINode::getBasicBlockIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fce2ce0e32b20e41b0aa9f8ca70c2">llvm::hasBranchWeightMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5ba57877c55dfdbe6e3bbfdacd9ef8c1">llvm::PHINode::setIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a506bcfb6f92a2184453e1fa9655f62a1">llvm::PHINode::setIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9d391b6acc6d90c9b8a8442324b1aa6f">llvm::SplitBlockPredecessors</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### ConnectProlog() {#af700561cb065af85122cd321d6c4b989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConnectProlog (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BECount, unsigned Count, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PrologExit, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OriginalLoopLatchExit, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PreHeader, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewPreHeader, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, bool PreserveLCSSA, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Connect the unrolling prolog code to the original loop.</p>


<p>The unrolling prolog code contains code to execute the 'extra' iterations if the run-time trip count modulo the unroll count is non-zero.</p>


<p>This function performs the following:</p>


<ul class="doxyList ">
<li>Create PHI nodes at prolog end block to combine values that exit the prolog code and jump around the prolog.</li>
<li>Add a PHI operand to a PHI node at the loop exit block for values that exit the prolog and go around the loop.</li>
<li>Branch around the original loop if the trip count is less than the unroll factor.</li>
</ul>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a2881c226e1c102190d54c3b664330aba">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::changeImmediateDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a75043d12a76b84200e9ed593719dc5eb">llvm::MDBuilder::createBranchWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a2ec50ab2c78eff965caf3da71cd08be4">llvm::DominatorTree::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aa6dc58a1259941c7a17142e6103d059e">llvm::ScalarEvolution::forgetLcssaPhiWithNewPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fce2ce0e32b20e41b0aa9f8ca70c2">llvm::hasBranchWeightMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9d391b6acc6d90c9b8a8442324b1aa6f">llvm::SplitBlockPredecessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a> and <a href="#a71d5cd8a9f3f2982e334cb8ce9245e96">UnrolledLoopHeaderWeights</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### CreateTripRemainder() {#a7bab17532f2b606ad25679ed9e138c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * CreateTripRemainder (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BECount, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TripCount, unsigned Count)</td>
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

<p>Calculate ModVal = (BECount + 1) % Count on the abstract integer domain accounting for the possibility of unsigned overflow in the 2s complement domain.</p>


<p>Preconditions: 1) TripCount = BECount + 1 (allowing overflow) 2) Log2(Count) &lt;= <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">BitWidth(BECount)</a></p>


<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### STATISTIC() {#a83a4a18d11086a64b8851319c00671a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumRuntimeUnrolled, "Number of <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a49ae40a9c91d665793aaed656c26ca30">loops</a> unrolled with run-time trip counts")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### EpilogHeaderWeights {#ae905d898b267ca244e6d89fb1fba7c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t EpilogHeaderWeights[] = {1, 127}</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### UnrolledLoopHeaderWeights {#a71d5cd8a9f3f2982e334cb8ce9245e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t UnrolledLoopHeaderWeights[] = {1, 127}</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>


<p>Referenced by <a href="#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>.</p>

</div>
</div>

### UnrollRuntimeMultiExit {#ae9c245e2a4a3f5a845a1cbe2922af167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnrollRuntimeMultiExit("unroll-runtime-multi-exit", cl::init(false), cl::Hidden, cl::desc("Allow runtime unrolling for loops with multiple exits, when " "epilog is generated"))</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>


<p>Referenced by <a href="#a98b4edd31a148a751a95e80997f81c31">canProfitablyRuntimeUnrollMultiExitLoop</a>.</p>

</div>
</div>

### UnrollRuntimeOtherExitPredictable {#a873b044e9706fd66860c6178f74a51f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UnrollRuntimeOtherExitPredictable("unroll-runtime-other-exit-predictable", cl::init(false), cl::Hidden, cl::desc("Assume the non latch exit block to be predictable"))</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>


<p>Referenced by <a href="#a98b4edd31a148a751a95e80997f81c31">canProfitablyRuntimeUnrollMultiExitLoop</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"loop-unroll"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp">LoopUnrollRuntime.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
