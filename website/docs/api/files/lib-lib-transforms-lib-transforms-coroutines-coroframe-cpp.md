---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CoroFrame.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corointernal-h">CoroInternal.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scopeexit-h">llvm/ADT/ScopeExit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacklifetime-h">llvm/Analysis/StackLifetime.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">llvm/IR/DIBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h">llvm/Support/OptimizedStructLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/abi-h">llvm/Transforms/Coroutines/ABI.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">llvm/Transforms/Coroutines/CoroInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/materializationutils-h">llvm/Transforms/Coroutines/MaterializationUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/spillutils-h">llvm/Transforms/Coroutines/SpillUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/suspendcrossinginfo-h">llvm/Transforms/Coroutines/SuspendCrossingInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/promotememtoreg-h">llvm/Transforms/Utils/PromoteMemToReg.h</a>"
#include &lt;algorithm&gt;
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-coroframe-cpp-">anonymous{CoroFrame.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-coroframe-cpp-/framedatainfo">FrameDataInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder">FrameTypeBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-coroframe-cpp-/frametypebuilder/field">Field</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0999556f0dc8e0fb4ccec5b3e121a1">dumpSpills</a> (StringRef Title, const coro::SpillInfo &amp;Spills)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49cc8ffa2bb7e7ced148a4acb2d9ea87">dumpAllocas</a> (const SmallVectorImpl&lt; coro::AllocaInfo &gt; &amp;Allocas)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d73f71509ec34798d5810859701347">cacheDIVar</a> (FrameDataInfo &amp;FrameData, DenseMap&lt; Value *, DILocalVariable * &gt; &amp;DIVarCache)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdaf5010e3f77d9d6e8ae04f5e0248e8">solveTypeName</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create name for <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#acdaf5010e3f77d9d6e8ae04f5e0248e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a> (DIBuilder &amp;Builder, Type *Ty, const DataLayout &amp;Layout, DIScope *Scope, unsigned LineNum, DenseMap&lt; Type *, DIType * &gt; &amp;DITypeCache)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> (Function &amp;F, coro::Shape &amp;Shape, FrameDataInfo &amp;FrameData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build artificial debug info for C++ coroutine frames to allow users to inspect the contents of the frame directly. <a href="#a86c6fee36a1f17461710c01e694ee8df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a> (Function &amp;F, coro::Shape &amp;Shape, FrameDataInfo &amp;FrameData, bool OptimizeFrame)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0885df5b78cc732639a9d52a87d040e">insertSpills</a> (const FrameDataInfo &amp;FrameData, coro::Shape &amp;Shape)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642ec4238f02650fc1e70d5b4ac8d844">movePHIValuesToInsertedBlock</a> (BasicBlock *SuccBB, BasicBlock *InsertedBB, BasicBlock *PredBB, PHINode *UntilPHI=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9fcdedd3580f924cf782f155b549a22">rewritePHIsForCleanupPad</a> (BasicBlock *CleanupPadBB, CleanupPadInst *CleanupPad)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03cdd58b24dc91b4e3819e218a399cbf">cleanupSinglePredPHIs</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a> (BasicBlock &amp;BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0647ca6021ca57224016effde79d4d7e">rewritePHIs</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a973240859e7ff5af51dad8426b400053">splitBlockIfNotFirst</a> (Instruction *I, const Twine &amp;Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c76b23c53f62a58c09936547b2842d">splitAround</a> (Instruction *I, const Twine &amp;Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711449044c2aef3a8aba56149e421b60">willLeaveFunctionImmediatelyAfter</a> (BasicBlock *BB, unsigned depth=3)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After we split the coroutine, will the given basic block be along an obvious exit path for the resumption function? <a href="#a711449044c2aef3a8aba56149e421b60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b0e7da15eccab3545643118aa2f99f">localAllocaNeedsStackSave</a> (CoroAllocaAllocInst *AI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36b39e8a1384a23b9899d2c9e2e08e72">lowerLocalAllocas</a> (ArrayRef&lt; CoroAllocaAllocInst * &gt; LocalAllocas, SmallVectorImpl&lt; Instruction * &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn each of the given local allocas into a normal (dynamic) alloca instruction. <a href="#a36b39e8a1384a23b9899d2c9e2e08e72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7795d2b31b375031144ce50d0f6fa34">emitGetSwiftErrorValue</a> (IRBuilder&lt;&gt; &amp;Builder, Type *ValueTy, coro::Shape &amp;Shape)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current swifterror value. <a href="#ad7795d2b31b375031144ce50d0f6fa34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d306b9a19fc37d00329692ef499b1b1">emitSetSwiftErrorValue</a> (IRBuilder&lt;&gt; &amp;Builder, Value *V, coro::Shape &amp;Shape)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the given value as the current swifterror value. <a href="#a3d306b9a19fc37d00329692ef499b1b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43a2acbd71eac7be9bdd1094a21bd6ab">emitSetAndGetSwiftErrorValueAround</a> (Instruction *Call, AllocaInst *Alloca, coro::Shape &amp;Shape)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the swifterror value from the given alloca before a call, then put in back in the alloca afterwards. <a href="#a43a2acbd71eac7be9bdd1094a21bd6ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55af5cce8eb7833907578e6fc3f0ab5e">eliminateSwiftErrorAlloca</a> (Function &amp;F, AllocaInst *Alloca, coro::Shape &amp;Shape)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate a formerly-swifterror alloca by inserting the get/set intrinsics and attempting to MemToReg the alloca away. <a href="#a55af5cce8eb7833907578e6fc3f0ab5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a> (Function &amp;F, Argument &amp;Arg, coro::Shape &amp;Shape, SmallVectorImpl&lt; AllocaInst * &gt; &amp;AllocasToPromote)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"Eliminate" a swifterror argument by reducing it to the alloca case and then loading and storing in the prologue and epilog. <a href="#a8356860a8bef082ff15df896ecec7732">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311a80924f5342813ae67daa5e5ff444">eliminateSwiftError</a> (Function &amp;F, coro::Shape &amp;Shape)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate all problematic uses of swifterror arguments and allocas from the function. <a href="#a311a80924f5342813ae67daa5e5ff444">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a> (Function &amp;F, coro::Shape &amp;Shape, SuspendCrossingInfo &amp;Checker, const DominatorTree &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each local variable that all of its user are only used inside one of suspended region, we sink their lifetime.start markers to the place where after the suspend block. <a href="#abb3297c94836debc08248e7ae3f47582">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> &amp; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a> (SmallDenseMap&lt; Argument *, AllocaInst *, 4 &gt; &amp;ArgToAllocaMap, bool UseEntryValue, Function *F, Value *Storage, DIExpression *Expr, bool SkipOutermostLoad)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecfc696c759c52249220099347df84da">UseNewDbgInfoFormat</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"coro-frame"</td>
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

### buildFrameDebugInfo() {#a86c6fee36a1f17461710c01e694ee8df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void buildFrameDebugInfo (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, FrameDataInfo &amp; FrameData)</td>
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

<p>Build artificial debug info for C++ coroutine frames to allow users to inspect the contents of the frame directly.</p>


<p>Create Debug information for coroutine frame with debug name "__coro_frame". The debug information for the fields of coroutine frame is constructed from the following way:</p>


<ol class="doxyList" type="1">
<li>For all the value in the Frame, we search the use of dbg.declare to find the corresponding debug variables for the value. If we can find the debug variable, we can get full and accurate debug information.</li>
<li>If we can't get debug information in step 1 and 2, we could only try to build the <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> by <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. We did this in solveDIType. We only handle integer, float, double, integer type and struct type for now.</li>
</ol>

<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a4e554c60419835fc3c74b91b28ca31c8">llvm::coro::Shape::ABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a44d73f71509ec34798d5810859701347">cacheDIVar</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a836d9cba6deced0bb1fa7333ce5afd3a">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ae6081972b0560d0f16bd503654924b1b">llvm::DIBuilder::createAutoVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#aa7a54c168f44523926f5bcf1f69e3cb4">llvm::DIBuilder::createBasicType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ad1d53e81b2b3ddcc4518e816fc89711d">llvm::DIBuilder::createExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adbf77460ca5103d4d0b2708b013a1b88">llvm::DIBuilder::createMemberType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a8f163bf8a14c1c7823f6d8fce7fb5ac7">llvm::DIBuilder::createPointerType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#afe762b489a1c62e1d3baf58b330e6652">llvm::DIBuilder::createStructType</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">llvm::DbgVariableRecord::Declare</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchfieldindex/#aef925686aca6c6970964fea2c25bf242a0416e9f2fbff942bd66bfa6d7e759d47">llvm::coro::Shape::SwitchFieldIndex::Destroy</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a0a1a8e48ba1e5d845e979d5da8de597d">llvm::coro::Shape::FrameAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a5eac2988672b484645dcbcd706430967">llvm::coro::Shape::FramePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a742806b2e667a87817ae171e1ec59826">llvm::coro::Shape::FrameSize</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a24c5fed9b14aed8a3b4f3828472fbab5">llvm::coro::Shape::FrameTy</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abbc2b566b9aa870d5b7131017b7ba66daa44087d1fe20ab5e128a0f592b6a85c1">llvm::DICompileUnit::FullDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#aad2e50b107c264353f4de80e03f9f754">llvm::MDTuple::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aee3c78d73273cb8449cd10cc15edcb83">llvm::StructType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/discope/#a693505a142c46203bb19ff1f09b5ea22">llvm::DIScope::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a33880aaca0ad05e5f1557f079305bde5">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::getFixedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#ac406c2b5a7e2d11174becab5cb27765d">llvm::coro::Shape::getInsertPtAfterFramePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a777848a3e8c10c10721c852d4efb9e3b">llvm::DIType::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a858efd7b61654c0de28c56f9adafa13d">llvm::StructType::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ac22bd3a0571eb4e961def1c480247296">llvm::DIBuilder::getOrCreateArray</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#aab0e2582dd592f549f16c9a26b9d5f42">llvm::coro::Shape::getPromiseAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchloweringstorage/#a9d132e5f83821984ce6d37cb38a99c24">llvm::coro::Shape::SwitchLoweringStorage::IndexAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchloweringstorage/#a1640d3af02b4a49eaa3422920056bb6d">llvm::coro::Shape::SwitchLoweringStorage::IndexField</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchloweringstorage/#a1d3459ac1d0c3c498b3a522fbdcb0e7b">llvm::coro::Shape::SwitchLoweringStorage::IndexOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a9019e662ee1c0c04e06e9871650268c8">llvm::DIBuilder::insertDeclare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aaedb78de657237c48255243a68e1dbc1">llvm::dwarf::isCPlusPlus</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#afee05194feacd4f95209e840e7242332">llvm::DIBuilder::replaceArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a160e9e1a4fd597f83034c8b2ba316984">llvm::MDNode::replaceOperandWith</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchfieldindex/#aef925686aca6c6970964fea2c25bf242a012dd1dc85c718e8159980fa4273d9e6">llvm::coro::Shape::SwitchFieldIndex::Resume</a>, <a href="#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#abe8f7906a8618f90e2a75109a778054a">llvm::coro::Shape::SwitchLowering</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h/#a926189935285d6e5df83fc0f45bf9b36">UseNewDbgInfoFormat</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#ab47fb8dadd631b1c67a285b16607e4c5">llvm::coro::BaseABI::buildCoroutineFrame</a>.</p>

</div>
</div>

### buildFrameType() {#a712c7e27f92253c99bcc20689a4e93b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * buildFrameType (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, FrameDataInfo &amp; FrameData, bool OptimizeFrame)</td>
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



<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a4e554c60419835fc3c74b91b28ca31c8">llvm::coro::Shape::ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a0cca043bc17f6f673acb6324db527dae">llvm::coro::Shape::AsyncLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/asyncloweringstorage/#a3bf2569bd6f6975476d99b67f036a0e7">llvm::coro::Shape::AsyncLoweringStorage::ContextHeaderSize</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/asyncloweringstorage/#a6b353e50aa2fb0fadf3c46ad81a28e00">llvm::coro::Shape::AsyncLoweringStorage::ContextSize</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a5fd0aa934908c837c6d78097a2fd667b">llvm::coro::Shape::CoroSuspends</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a0a1a8e48ba1e5d845e979d5da8de597d">llvm::coro::Shape::FrameAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/asyncloweringstorage/#a257b93881a8ca56ed33f4326672b738d">llvm::coro::Shape::AsyncLoweringStorage::FrameOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a742806b2e667a87817ae171e1ec59826">llvm::coro::Shape::FrameSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a092114fb63cfb76b89bd59081681814b">anonymous{CoroFrame.cpp}::FrameTypeBuilder::FrameTypeBuilder</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/asyncloweringstorage/#a12d93f5ae63381caf2a4ef0fdba3a668">llvm::coro::Shape::AsyncLoweringStorage::getContextAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#aab0e2582dd592f549f16c9a26b9d5f42">llvm::coro::Shape::getPromiseAlloca</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a2acb69a078f9bb3184aa59c6d4966861">llvm::coro::Shape::getRetconCoroId</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchloweringstorage/#a9d132e5f83821984ce6d37cb38a99c24">llvm::coro::Shape::SwitchLoweringStorage::IndexAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchloweringstorage/#a1640d3af02b4a49eaa3422920056bb6d">llvm::coro::Shape::SwitchLoweringStorage::IndexField</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchloweringstorage/#a1d3459ac1d0c3c498b3a522fbdcb0e7b">llvm::coro::Shape::SwitchLoweringStorage::IndexOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/retconloweringstorage/#a4df922b446b5bfca3248510df728539b">llvm::coro::Shape::RetconLoweringStorage::IsFrameInlineInStorage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a238ef12f09938dac4efe5ca56dc125d9">llvm::Log2_64_Ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#ace1508259ecd37ceaafb9162d3768fff">llvm::coro::Shape::RetconLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a> and <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#abe8f7906a8618f90e2a75109a778054a">llvm::coro::Shape::SwitchLowering</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#ab47fb8dadd631b1c67a285b16607e4c5">llvm::coro::BaseABI::buildCoroutineFrame</a>.</p>

</div>
</div>

### cacheDIVar() {#a44d73f71509ec34798d5810859701347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void cacheDIVar (FrameDataInfo &amp; FrameData, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * &gt; &amp; DIVarCache)</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a836d9cba6deced0bb1fa7333ce5afd3a">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19d345e6fa45d60ff4092769417b89b2">llvm::findDbgDeclares</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9c256eafdc8fb849f7320bc37120a5c">llvm::findDVRDeclares</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>.</p>


<p>Referenced by <a href="#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>.</p>

</div>
</div>

### cleanupSinglePredPHIs() {#a03cdd58b24dc91b4e3819e218a399cbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void cleanupSinglePredPHIs (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a8bd87bda26e6aac77644f79dbd06c340">llvm::coro::normalizeCoroutine</a>.</p>

</div>
</div>

### dumpAllocas() {#a49cc8ffa2bb7e7ced148a4acb2d9ea87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpAllocas (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coro/allocainfo">coro::AllocaInfo</a> &gt; &amp; Allocas)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#ab47fb8dadd631b1c67a285b16607e4c5">llvm::coro::BaseABI::buildCoroutineFrame</a>.</p>

</div>
</div>

### dumpSpills() {#a6f0999556f0dc8e0fb4ccec5b3e121a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dumpSpills (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Title, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a35a3966816510601e97cb071765f1ed0">coro::SpillInfo</a> &amp; Spills)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#ab47fb8dadd631b1c67a285b16607e4c5">llvm::coro::BaseABI::buildCoroutineFrame</a>.</p>

</div>
</div>

### eliminateSwiftError() {#a311a80924f5342813ae67daa5e5ff444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void eliminateSwiftError (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape)</td>
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

<p>Eliminate all problematic uses of swifterror arguments and allocas from the function.</p>


<p>We'll fix them up later when splitting the function.</p>


<p>Definition at line 1740 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a55af5cce8eb7833907578e6fc3f0ab5e">eliminateSwiftErrorAlloca</a>, <a href="#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a4cac84457299517e69ff9764fed2db">llvm::PromoteMemToReg</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a8bd87bda26e6aac77644f79dbd06c340">llvm::coro::normalizeCoroutine</a>.</p>

</div>
</div>

### eliminateSwiftErrorAlloca() {#a55af5cce8eb7833907578e6fc3f0ab5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void eliminateSwiftErrorAlloca (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Alloca, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape)</td>
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

<p>Eliminate a formerly-swifterror alloca by inserting the get/set intrinsics and attempting to MemToReg the alloca away.</p>

<p>Definition at line 1676 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a43a2acbd71eac7be9bdd1094a21bd6ab">emitSetAndGetSwiftErrorValueAround</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/use/#a53a48d67682705c5f7f06ffc850fd622">llvm::Use::getUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5023b360abc7a5d1612061fba30003a6">llvm::isAllocaPromotable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/use/#a40360b4fa7b8e6920a68e5a8a0814f1f">llvm::Use::set</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#a311a80924f5342813ae67daa5e5ff444">eliminateSwiftError</a> and <a href="#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a>.</p>

</div>
</div>

### eliminateSwiftErrorArgument() {#a8356860a8bef082ff15df896ecec7732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void eliminateSwiftErrorArgument (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp; Arg, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; &amp; AllocasToPromote)</td>
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

<p>"Eliminate" a swifterror argument by reducing it to the alloca case and then loading and storing in the prologue and epilog.</p>


<p>The argument keeps the swifterror flag.</p>


<p>Definition at line 1702 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#adc470e92d3cd5fb8d54d7b9179841463">llvm::coro::Shape::CoroEnds</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a5fd0aa934908c837c6d78097a2fd667b">llvm::coro::Shape::CoroSuspends</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="#a55af5cce8eb7833907578e6fc3f0ab5e">eliminateSwiftErrorAlloca</a>, <a href="#a43a2acbd71eac7be9bdd1094a21bd6ab">emitSetAndGetSwiftErrorValueAround</a>, <a href="#a3d306b9a19fc37d00329692ef499b1b1">emitSetSwiftErrorValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>


<p>Referenced by <a href="#a311a80924f5342813ae67daa5e5ff444">eliminateSwiftError</a>.</p>

</div>
</div>

### emitGetSwiftErrorValue() {#ad7795d2b31b375031144ce50d0f6fa34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * emitGetSwiftErrorValue (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValueTy, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape)</td>
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

<p>Get the current swifterror value.</p>

<p>Definition at line 1613 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a> and <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#ae290085a52a8df4810b4e7f48dbe1ac5">llvm::coro::Shape::SwiftErrorOps</a>.</p>


<p>Referenced by <a href="#a43a2acbd71eac7be9bdd1094a21bd6ab">emitSetAndGetSwiftErrorValueAround</a>.</p>

</div>
</div>

### emitSetAndGetSwiftErrorValueAround() {#a43a2acbd71eac7be9bdd1094a21bd6ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * emitSetAndGetSwiftErrorValueAround (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Call, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * Alloca, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape)</td>
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

<p>Set the swifterror value from the given alloca before a call, then put in back in the alloca afterwards.</p>


<p>Returns an address that will stand in for the swifterror slot until splitting.</p>


<p>Definition at line 1646 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="#ad7795d2b31b375031144ce50d0f6fa34">emitGetSwiftErrorValue</a>, <a href="#a3d306b9a19fc37d00329692ef499b1b1">emitSetSwiftErrorValue</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>


<p>Referenced by <a href="#a55af5cce8eb7833907578e6fc3f0ab5e">eliminateSwiftErrorAlloca</a> and <a href="#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a>.</p>

</div>
</div>

### emitSetSwiftErrorValue() {#a3d306b9a19fc37d00329692ef499b1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * emitSetSwiftErrorValue (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape)</td>
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

<p>Set the given value as the current swifterror value.</p>


<p>Returns a slot that can be used as a swifterror slot.</p>


<p>Definition at line 1628 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpointernull/#a96f5c85e4022e369266541b2db3fda69">llvm::ConstantPointerNull::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a> and <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#ae290085a52a8df4810b4e7f48dbe1ac5">llvm::coro::Shape::SwiftErrorOps</a>.</p>


<p>Referenced by <a href="#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a> and <a href="#a43a2acbd71eac7be9bdd1094a21bd6ab">emitSetAndGetSwiftErrorValueAround</a>.</p>

</div>
</div>

### insertSpills() {#af0885df5b78cc732639a9d52a87d040e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertSpills (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FrameDataInfo &amp; FrameData, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape)</td>
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



<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a4e554c60419835fc3c74b91b28ca31c8">llvm::coro::Shape::ABI</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#ae3a9a76ce45cff6c0385091993bccdcc">llvm::coro::Shape::AllocaSpillBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a24aa4117da86c41684ad25742832dfa6">llvm::coro::Async</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#abfb56acef5d60fefb2edc417f0bfbda0">llvm::coro::Shape::CoroBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeb6ccc122c2f6868fc3a1e68e1ae157c">llvm::IRBuilderBase::CreateAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3313ae2d314fb689cebdaf062d86eec5">llvm::IRBuilderBase::CreateAlignedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa4f2cec52a8e17a4c72319334fbef771">llvm::IRBuilderBase::CreateAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa85037712ab4c5044582974769aa4b62">llvm::IRBuilderBase::CreateConstInBoundsGEP2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a64b6c97b8faad5ec83f37d906fca7bc4">llvm::IRBuilderBase::CreateInBoundsGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a89f675aadae7232445c74ee4167ff591">llvm::IRBuilderBase::CreateNot</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5b416a8603ccb844165c8df22454ac05">llvm::IRBuilderBase::CreatePtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae2c3391c27b9fa4f64f9ed1bdbbdea4ca2709046ed364cc54b91f908e85e512ed">llvm::DbgVariableRecord::Declare</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/tinyptrvector/#a9dc659b723e6725130ad354ed821d400">llvm::TinyPtrVector&lt; EltTy &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae876eb96b89c1afcc3e9cd285cc3f08c">llvm::filterDbgVars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19d345e6fa45d60ff4092769417b89b2">llvm::findDbgDeclares</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26bad0f6e5435a5a4dc50850c5b8f628">llvm::findDbgUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9c256eafdc8fb849f7320bc37120a5c">llvm::findDVRDeclares</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b2a153b655ed78a07468297eb4c6256">llvm::for_each</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a64f8c7400de58c117c5af250f000675f">FramePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a5eac2988672b484645dcbcd706430967">llvm::coro::Shape::FramePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a24c5fed9b14aed8a3b4f3828472fbab5">llvm::coro::Shape::FrameTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aee3c78d73273cb8449cd10cc15edcb83">llvm::StructType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4e5c1b91bf5e2860398e3fa35c96b5af">llvm::IRBuilderBase::GetInsertPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#ac406c2b5a7e2d11174becab5cb27765d">llvm::coro::Shape::getInsertPtAfterFramePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a58bcd428c0ca38b723b8ef938868ec4a">llvm::coro::getSpillInsertionPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a9019e662ee1c0c04e06e9871650268c8">llvm::DIBuilder::insertDeclare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#aea74164514e7164813ab30bcc4b7c557">llvm::AllocaInst::isArrayAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/switchloweringstorage/#a6af0b7b0e5d0e8f4b8b4f4199a885204">llvm::coro::Shape::SwitchLoweringStorage::PromiseAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7e8dad1701aa6445be4a29f654b0473c">llvm::Value::replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380aad9d7f07127e321d1358b695c8720166">llvm::coro::Retcon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380a6ec6c15fe79ec2274d2c3e79ae4bcc41">llvm::coro::RetconOnce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a36a5e731a6e92a83c26e5fee63d12380abbc155fb2b111bf61c4f5ff892915e6b">llvm::coro::Switch</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#abe8f7906a8618f90e2a75109a778054a">llvm::coro::Shape::SwitchLowering</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h/#a926189935285d6e5df83fc0f45bf9b36">UseNewDbgInfoFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#ab47fb8dadd631b1c67a285b16607e4c5">llvm::coro::BaseABI::buildCoroutineFrame</a>.</p>

</div>
</div>

### localAllocaNeedsStackSave() {#a47b0e7da15eccab3545643118aa2f99f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool localAllocaNeedsStackSave (<a href="/web-llvm/docs/api/classes/llvm/coroallocaallocinst">CoroAllocaAllocInst</a> * AI)</td>
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



<p>Definition at line 1557 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a> and <a href="#a711449044c2aef3a8aba56149e421b60">willLeaveFunctionImmediatelyAfter</a>.</p>


<p>Referenced by <a href="#a36b39e8a1384a23b9899d2c9e2e08e72">lowerLocalAllocas</a>.</p>

</div>
</div>

### lowerLocalAllocas() {#a36b39e8a1384a23b9899d2c9e2e08e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void lowerLocalAllocas (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/coroallocaallocinst">CoroAllocaAllocInst</a> * &gt; LocalAllocas, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; DeadInsts)</td>
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

<p>Turn each of the given local allocas into a normal (dynamic) alloca instruction.</p>

<p>Definition at line 1575 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#acd200f2f1bf30751d0489584a0565243">llvm::IRBuilderBase::CreateStackRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1f41fdcdad0b0b862da8b557701b4bff">llvm::IRBuilderBase::CreateStackSave</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a47b0e7da15eccab3545643118aa2f99f">localAllocaNeedsStackSave</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#af3bb24b322533dbe8a63c84b18568fe1">llvm::AllocaInst::setAlignment</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#ab47fb8dadd631b1c67a285b16607e4c5">llvm::coro::BaseABI::buildCoroutineFrame</a>.</p>

</div>
</div>

### movePHIValuesToInsertedBlock() {#a642ec4238f02650fc1e70d5b4ac8d844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void movePHIValuesToInsertedBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * SuccBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertedBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PredBB, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * UntilPHI=nullptr)</td>
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



<p>Definition at line 1317 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a63cfb2a0dae69153fd961eb335949caa">llvm::BasicBlock::front</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>.</p>


<p>Referenced by <a href="#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a> and <a href="#ab9fcdedd3580f924cf782f155b549a22">rewritePHIsForCleanupPad</a>.</p>

</div>
</div>

### rewritePHIs() {#a5a93b5fcf433128b2fd9d563792eb4cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rewritePHIs (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
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



<p>Definition at line 1427 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a266367eb01c634406b32f816d2d9c6bf">llvm::BasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="#a642ec4238f02650fc1e70d5b4ac8d844">movePHIValuesToInsertedBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="#ab9fcdedd3580f924cf782f155b549a22">rewritePHIsForCleanupPad</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a8bd87bda26e6aac77644f79dbd06c340">llvm::coro::normalizeCoroutine</a> and <a href="#a0647ca6021ca57224016effde79d4d7e">rewritePHIs</a>.</p>

</div>
</div>

### rewritePHIs() {#a0647ca6021ca57224016effde79d4d7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rewritePHIs (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 1503 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>.</p>

</div>
</div>

### rewritePHIsForCleanupPad() {#ab9fcdedd3580f924cf782f155b549a22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rewritePHIsForCleanupPad (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CleanupPadBB, <a href="/web-llvm/docs/api/classes/llvm/cleanuppadinst">CleanupPadInst</a> * CleanupPad)</td>
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



<p>Definition at line 1335 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8b123015de85b2f41b0deda2aeaad9d3">llvm::IRBuilderBase::CreateSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a39acc29443d48968a798fb22a76fa4c0">llvm::IRBuilderBase::CreateUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aa286a0f7f5d38488d593bb7ef0ba183e">llvm::BasicBlock::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7be2e1490f01c049d748436f03760c5">llvm::IRBuilderBase::getInt8Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af09e4096de244d2fb345891328714a63">llvm::Instruction::insertAfter</a>, <a href="#a642ec4238f02650fc1e70d5b4ac8d844">movePHIValuesToInsertedBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f211484edf604716a6c80030b0a0375">llvm::pred_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0fd53f63d349dc8a7c5fc0cdd7a94c8d">llvm::Instruction::removeFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae2c2758db51113863d0114f08c4b482a">llvm::setUnwindEdgeTo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac1ced98ffeb2b6991821751661b136d6">llvm::updatePhiNodes</a>.</p>


<p>Referenced by <a href="#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>.</p>

</div>
</div>

### salvageDebugInfoImpl() {#a22d247369eb256f74de55d2260c3b82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; Value &amp;, DIExpression &amp; &gt; &gt; salvageDebugInfoImpl (<a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> *, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, 4 &gt; &amp; ArgToAllocaMap, bool UseEntryValue, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Storage, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr, bool SkipOutermostLoad)</td>
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



<p>Definition at line 1855 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a5f48305fa7d23161515c94bca7c2beb6">llvm::DIExpression::appendOpsToArg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a6472489551b8960cc115a93d95eef9f6a18f3c7099f5b8bfe10361a97ee34a5c9">llvm::DIExpression::DerefBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a6472489551b8960cc115a93d95eef9f6a732b32a9387e1f0a0b49cd59b96905ae">llvm::DIExpression::EntryValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a9aef6cbb464a57070a26cf422b979df9">llvm::DIExpression::getNumLocationOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a012168d44e49d5120cf8919cd096fd3b">llvm::DIExpression::isEntryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ac9a4fe1aa8e698aa8cd6a24751a80d91">llvm::DIExpression::isSingleLocationExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab804b15bb92ff685d7c1464b2816d608">llvm::DIExpression::prepend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>

</div>
</div>

### sinkLifetimeStartMarkers() {#abb3297c94836debc08248e7ae3f47582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void sinkLifetimeStartMarkers (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp; Shape, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo">SuspendCrossingInfo</a> &amp; Checker, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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

<p>For each local variable that all of its user are only used inside one of suspended region, we sink their lifetime.start markers to the place where after the suspend block.</p>


<p>Doing so minimizes the lifetime of each variable, hence minimizing the amount of data we end up putting on the frame.</p>


<p>Definition at line 1775 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a5fd0aa934908c837c6d78097a2fd667b">llvm::coro::Shape::CoroSuspends</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a79c007dcf9fff57e1569e778d7885b5e">llvm::BasicBlock::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo/#a184a65eb9ac1cd8093ea44d3490b3e70">llvm::SuspendCrossingInfo::isDefinitionAcrossSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#ab1faa49b43014e07caaf2bf2d3db07e4">isLifetimeStart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a64f8e14ffe5fb52d552fcb9058286ad3">llvm::coro::isSuspendBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi/#ab47fb8dadd631b1c67a285b16607e4c5">llvm::coro::BaseABI::buildCoroutineFrame</a>.</p>

</div>
</div>

### solveDIType() {#a70c89294063fc90c89bb113d2af8c7c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIType * solveDIType (<a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/classes/llvm/discope">DIScope</a> * Scope, unsigned LineNum, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, <a href="/web-llvm/docs/api/classes/llvm/ditype">DIType</a> * &gt; &amp; DITypeCache)</td>
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



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ab6cf034bd9dd454892e193bc3340998b">llvm::DIBuilder::createArrayType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#aa7a54c168f44523926f5bcf1f69e3cb4">llvm::DIBuilder::createBasicType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adbf77460ca5103d4d0b2708b013a1b88">llvm::DIBuilder::createMemberType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a8f163bf8a14c1c7823f6d8fce7fb5ac7">llvm::DIBuilder::createPointerType</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#afe762b489a1c62e1d3baf58b330e6652">llvm::DIBuilder::createStructType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a800e74bec9b78d6739665027c3616a55">llvm::DataLayout::getABITypeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#aafecafc5b47638df4c3080736b1c3934">llvm::DIType::getAlignInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#aa8344d578094fea8b187e046d07d7455">llvm::StructLayout::getElementOffsetInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a777848a3e8c10c10721c852d4efb9e3b">llvm::DIType::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#ac22bd3a0571eb4e961def1c480247296">llvm::DIBuilder::getOrCreateArray</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#aaec462f93a64e27fa16d1416b1dbbb8b">llvm::DIBuilder::getOrCreateSubrange</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#af9185c7e96873c6d2c13e1f1b6322cf6">llvm::DataLayout::getPrefTypeAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/ditype/#a8b53bdd5b8f1d8cd12a392c256cb54f3">llvm::DIType::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a61135fb8666f0b7a37b4e1bbcf1db131">llvm::DataLayout::getStructLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#afee05194feacd4f95209e840e7242332">llvm::DIBuilder::replaceArrays</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>, <a href="#acdaf5010e3f77d9d6e8ae04f5e0248e8">solveTypeName</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a> and <a href="#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### solveTypeName() {#acdaf5010e3f77d9d6e8ae04f5e0248e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef solveTypeName (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Create name for <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>


<p>It uses <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> to store new created string to avoid memory leak.</p>


<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a> and <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>.</p>


<p>Referenced by <a href="#a70c89294063fc90c89bb113d2af8c7c5">solveDIType</a>.</p>

</div>
</div>

### splitAround() {#a54c76b23c53f62a58c09936547b2842d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void splitAround (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
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



<p>Definition at line 1530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a973240859e7ff5af51dad8426b400053">splitBlockIfNotFirst</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a8bd87bda26e6aac77644f79dbd06c340">llvm::coro::normalizeCoroutine</a>.</p>

</div>
</div>

### splitBlockIfNotFirst() {#a973240859e7ff5af51dad8426b400053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * splitBlockIfNotFirst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
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



<p>Definition at line 1517 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a54c76b23c53f62a58c09936547b2842d">splitAround</a>.</p>

</div>
</div>

### willLeaveFunctionImmediatelyAfter() {#a711449044c2aef3a8aba56149e421b60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool willLeaveFunctionImmediatelyAfter (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, unsigned depth=3)</td>
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

<p>After we split the coroutine, will the given basic block be along an obvious exit path for the resumption function?</p>

<p>Definition at line 1537 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a64f8e14ffe5fb52d552fcb9058286ad3">llvm::coro::isSuspendBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a> and <a href="#a711449044c2aef3a8aba56149e421b60">willLeaveFunctionImmediatelyAfter</a>.</p>


<p>Referenced by <a href="#a47b0e7da15eccab3545643118aa2f99f">localAllocaNeedsStackSave</a> and <a href="#a711449044c2aef3a8aba56149e421b60">willLeaveFunctionImmediatelyAfter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### UseNewDbgInfoFormat {#aecfc696c759c52249220099347df84da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; UseNewDbgInfoFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"coro-frame"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp">CoroFrame.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
