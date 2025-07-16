---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/local-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Local.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemapinfo-h">llvm/ADT/DenseMapInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">llvm/ADT/Hashing.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumebundlequeries-h">llvm/Analysis/AssumeBundleQueries.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/constantfolding-h">llvm/Analysis/ConstantFolding.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/domtreeupdater-h">llvm/Analysis/DomTreeUpdater.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionsimplify-h">llvm/Analysis/InstructionSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryssaupdater-h">llvm/Analysis/MemorySSAUpdater.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cfg-h">llvm/IR/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">llvm/IR/ConstantRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dibuilder-h">llvm/IR/DIBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/ehpersonalities-h">llvm/IR/EHPersonalities.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/getelementptrtypeiterator-h">llvm/IR/GetElementPtrTypeIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalobject-h">llvm/IR/GlobalObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "llvm/IR/IntrinsicsWebAssembly.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/memorymodelrelaxationannotations-h">llvm/IR/MemoryModelRelaxationAnnotations.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profdatautils-h">llvm/IR/ProfDataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">llvm/Transforms/Utils/ValueMapper.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;map&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-local-cpp-">anonymous{Local.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-local-cpp-/bitpart">BitPart</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A potential constituent of a bitreverse or bswap expression. <a href="/web-llvm/docs/api/structs/anonymous-local-cpp-/bitpart/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8dfef195cfd8a028f2dedf33c85a61">PredBlockVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02334b9cb9a6fd5fe6f4407dea7e1781">IncomingValueMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3243057e017aad4e091381fa3d9d10">DbgValReplacement</a> = std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A replacement for a dbg.value expression. <a href="#a4f3243057e017aad4e091381fa3d9d10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10125d51d3ff20feb0e8e217f552eac2">STATISTIC</a> (NumRemoved, "Number of unreachable basic blocks removed")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3ea19a7d0181e0ce206ab75c05f563a">STATISTIC</a> (NumPHICSEs, "Number of PHI's that got CSE'd")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86d26e60cc16331137a491fdcd7744a3">areAllUsesEqual</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>areAllUsesEqual - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the uses of a value are all the same. <a href="#a86d26e60cc16331137a491fdcd7744a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d068ffb71feb72ff6d1dee350ec7677">simplifyAndDCEInstruction</a> (Instruction *I, SmallSetVector&lt; Instruction *, 16 &gt; &amp;WorkList, const DataLayout &amp;DL, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c71badb215d0f31fc84eb7985934e77">CanMergeValues</a> (Value *First, Value *Second)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can choose one of these values to use in place of the other. <a href="#a7c71badb215d0f31fc84eb7985934e77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ec1591dd8e7639e5b5e1869b49e9b5">CanPropagatePredecessorsForPHIs</a> (BasicBlock *BB, BasicBlock *Succ, const SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;BBPreds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can fold BB, an almost-empty BB ending in an unconditional branch to Succ, into Succ. <a href="#aa8ec1591dd8e7639e5b5e1869b49e9b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbbdeb8f2d6f4843eacd55fb7d985387">selectIncomingValueForBlock</a> (Value *OldVal, BasicBlock *BB, IncomingValueMap &amp;IncomingValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines the value to use as the phi node input for a block. <a href="#acbbdeb8f2d6f4843eacd55fb7d985387">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd9116f3c9e74b7c836560911000c8e">gatherIncomingValuesToPhi</a> (PHINode *PN, IncomingValueMap &amp;IncomingValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a map from block to value for the operands of a given phi. <a href="#a3bd9116f3c9e74b7c836560911000c8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a> (PHINode *PN, const IncomingValueMap &amp;IncomingValues)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the incoming undef values to a phi with the values from a block-to-value map. <a href="#a705c6c2b8e570441356edb8db2dd8ddb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fccc775a9d83203b8d67f98dc0a3c4">CanRedirectPredsOfEmptyBBToSucc</a> (BasicBlock *BB, BasicBlock *Succ, const SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;BBPreds, BasicBlock *&amp;CommonPred)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b6f64940804c14b1e0cc4ad04fb18a">introduceTooManyPhiEntries</a> (BasicBlock *BB, BasicBlock *Succ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether removing <span class="doxyComputerOutput">BB</span> will make the phis in its <span class="doxyComputerOutput">Succ</span> have too many incoming entries. <a href="#ac4b6f64940804c14b1e0cc4ad04fb18a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a> (BasicBlock *BB, const PredBlockVector &amp;BBPreds, PHINode *PN, BasicBlock *CommonPred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace a value flowing from a block to a phi with potentially multiple instances of that value flowing from the block's predecessors to the phi. <a href="#ae7d61f8763322c1d7c8181f00798d9c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5133cfd6ce1419c7162cd0d7ba39ea9">EliminateDuplicatePHINodesNaiveImpl</a> (BasicBlock *BB, SmallPtrSetImpl&lt; PHINode * &gt; &amp;ToRemove)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a> (BasicBlock *BB, SmallPtrSetImpl&lt; PHINode * &gt; &amp;ToRemove)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a8305f7bf6d7dc8b192e257785c1fe4">PhiHasDebugValue</a> (DILocalVariable *DIVar, DIExpression *DIExpr, PHINode *APN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>===------------------------------------------------------------------—===// Dbg <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic">Intrinsic</a> utilities <a href="#a2a8305f7bf6d7dc8b192e257785c1fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bdd0669ab7b82ba709bfedcb751dcc3">valueCoversEntireFragment</a> (Type *ValTy, DbgVariableIntrinsic *DII)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the alloc size of <span class="doxyComputerOutput">ValTy</span> is large enough to cover the variable (or fragment of the variable) described by <span class="doxyComputerOutput">DII</span>. <a href="#a0bdd0669ab7b82ba709bfedcb751dcc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d7d91d31a8121c140a4da8645c6474">valueCoversEntireFragment</a> (Type *ValTy, DbgVariableRecord *DVR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0da78bd6844fdff5ec2fc0654d00de7">insertDbgValueOrDbgVariableRecord</a> (DIBuilder &amp;Builder, Value *DV, DILocalVariable *DIVar, DIExpression *DIExpr, const DebugLoc &amp;NewLoc, BasicBlock::iterator Instr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642caf268486d4a9e8a4b879a86448c2">insertDbgValueOrDbgVariableRecordAfter</a> (DIBuilder &amp;Builder, Value *DV, DILocalVariable *DIVar, DIExpression *DIExpr, const DebugLoc &amp;NewLoc, Instruction *Instr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae41c589bd3c54f2a968e8336f3aa98">dropInitialDeref</a> (const DIExpression *DIExpr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e06c0b653fcb0e20fbec6bee3d3d40d">isArray</a> (AllocaInst *AI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this alloca is either a VLA or an array. <a href="#a7e06c0b653fcb0e20fbec6bee3d3d40d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a226deca7d8508b6b646c8596d4c174a7">isStructure</a> (AllocaInst *AI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this alloca is a structure. <a href="#a226deca7d8508b6b646c8596d4c174a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a> (BasicBlock *BB, SmallVectorImpl&lt; PHINode * &gt; &amp;InsertedPHIs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf65ce696212774397a4c1a3afc44275">updateOneDbgValueForAlloca</a> (const DebugLoc &amp;Loc, DILocalVariable *DIVar, DIExpression *DIExpr, Value *NewAddress, DbgValueInst *DVI, DbgVariableRecord *DVR, DIBuilder &amp;Builder, int Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe18f2bacebf9cbf307a33cf86b81e4e">salvageDbgAssignAddress</a> (T *Assign)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7144f12bd93229efcf87a052ab80d5e6">getSalvageOpsForGEP</a> (GetElementPtrInst *GEP, const DataLayout &amp;DL, uint64_t CurrentLocOps, SmallVectorImpl&lt; uint64_t &gt; &amp;Opcodes, SmallVectorImpl&lt; Value * &gt; &amp;AdditionalValues)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a7c90efaafea9d737d727d5f13e520">getDwarfOpForBinOp</a> (Instruction::BinaryOps Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4826d44e6c44f689b31757f02ad3b76f">handleSSAValueOperands</a> (uint64_t CurrentLocOps, SmallVectorImpl&lt; uint64_t &gt; &amp;Opcodes, SmallVectorImpl&lt; Value * &gt; &amp;AdditionalValues, Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55a8ce252bfbfa1af642af05f2c31e10">getSalvageOpsForBinOp</a> (BinaryOperator *BI, uint64_t CurrentLocOps, SmallVectorImpl&lt; uint64_t &gt; &amp;Opcodes, SmallVectorImpl&lt; Value * &gt; &amp;AdditionalValues)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a981d4a79d3783f0327fab0e9fcb7d938">getDwarfOpForIcmpPred</a> (CmpInst::Predicate Pred)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b323f2153ac64cdbab7e81c15575c0d">getSalvageOpsForIcmpOp</a> (ICmpInst *Icmp, uint64_t CurrentLocOps, SmallVectorImpl&lt; uint64_t &gt; &amp;Opcodes, SmallVectorImpl&lt; Value * &gt; &amp;AdditionalValues)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a> (Instruction &amp;From, Value &amp;To, Instruction &amp;DomPoint, DominatorTree &amp;DT, function_ref&lt; DbgValReplacement(DbgVariableIntrinsic &amp;DII)&gt; RewriteExpr, function_ref&lt; DbgValReplacement(DbgVariableRecord &amp;DVR)&gt; RewriteDVRExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Point debug users of <span class="doxyComputerOutput">From</span> to <span class="doxyComputerOutput">To</span> using exprs given by <span class="doxyComputerOutput">RewriteExpr</span>, possibly moving/undefing users to prevent use-before-def. <a href="#ab8b1a901ef225bb4a12ca046d13f4b45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1484fd35d5f2401ee532e8aea2aba44c">isBitCastSemanticsPreserving</a> (const DataLayout &amp;DL, Type *FromTy, Type *ToTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a bitcast between a value of type <span class="doxyComputerOutput">FromTy</span> to type <span class="doxyComputerOutput">ToTy</span> would losslessly preserve the bits and semantics of the value. <a href="#a1484fd35d5f2401ee532e8aea2aba44c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a> (Function &amp;F, SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;Reachable, DomTreeUpdater *DTU=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c142cb2c6d5ca1e5f142d4062839944">combineMetadata</a> (Instruction *K, const Instruction *J, bool DoesKMove, bool AAOnly=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If AAOnly is set, only intersect alias analysis metadata and preserve other known metadata. <a href="#a3c142cb2c6d5ca1e5f142d4062839944">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RootType, typename ShouldReplaceFn&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a92e7361f7532de414322df105163781f">replaceDominatedUsesWith</a> (Value *From, Value *To, const RootType &amp;Root, const ShouldReplaceFn &amp;ShouldReplace)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; BitPart &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16fecc86f9853cc81abd01a5a6f1604">collectBitParts</a> (Value *V, bool MatchBSwaps, bool MatchBitReversals, std::map&lt; Value *, std::optional&lt; BitPart &gt; &gt; &amp;BPS, int Depth, bool &amp;FoundRoot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the specified subexpression and see if it is capable of providing pieces of a bswap or bitreverse. <a href="#aa16fecc86f9853cc81abd01a5a6f1604">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f3d7adf7647a76ba410be64215a9d74">bitTransformIsCorrectForBSwap</a> (unsigned From, unsigned To, unsigned BitWidth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2d13d2dd35f8bac23c71adf9e740aa6">bitTransformIsCorrectForBitReverse</a> (unsigned From, unsigned To, unsigned BitWidth)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d5e787d14a0d34fc9f68deaced56bc5">PHICSEDebugHash</a>("phicse-debug-hash", cl::init(false), cl::Hidden, cl::desc("Perform extra assertion checking to verify that PHINodes's hash " "function is well-behaved w.r.t. its isEqual predicate"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa5586371e4169c68295e702dc682af1">PHICSENumPHISmallSize</a>("phicse-num-phi-smallsize", cl::init(32), cl::Hidden, cl::desc("When the basic block contains not more than this number of PHI nodes, " "perform a (faster!) exhaustive search instead of set-driven one."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae908402f3042b6131823fec54c72f18c">MaxPhiEntriesIncreaseAfterRemovingEmptyBlock</a>("max-phi-entries-increase-after-removing-empty-block", cl::init(1000), cl::Hidden, cl::desc("Stop removing an empty block if removing it will introduce more " "than this number of phi entries in its successor"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae67ef27038e310f603f3b1bc4fb6eda2">BitPartRecursionMaxDepth</a> = 48</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"local"</td>
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

## Typedefs

### DbgValReplacement {#a4f3243057e017aad4e091381fa3d9d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DbgValReplacement =  std::optional&lt;DIExpression *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A replacement for a dbg.value expression.</p>

<p>Definition at line 2655 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>

</div>
</div>

### IncomingValueMap {#a02334b9cb9a6fd5fe6f4407dea7e1781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using IncomingValueMap =  SmallDenseMap&lt;BasicBlock *, Value *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 928 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>

</div>
</div>

### PredBlockVector {#abf8dfef195cfd8a028f2dedf33c85a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using PredBlockVector =  SmallVector&lt;BasicBlock *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### areAllUsesEqual() {#a86d26e60cc16331137a491fdcd7744a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areAllUsesEqual (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>areAllUsesEqual - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the uses of a value are all the same.</p>


<p>This is similar to Instruction::hasOneUse() except this will also return true when there are no uses or multiple uses that all refer to the same value.</p>


<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad3cf19784335900227e275fd488e4727">llvm::RecursivelyDeleteDeadPHINode</a>.</p>

</div>
</div>

### bitTransformIsCorrectForBitReverse() {#af2d13d2dd35f8bac23c71adf9e740aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool bitTransformIsCorrectForBitReverse (unsigned From, unsigned To, unsigned BitWidth)</td>
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



<p>Definition at line 4080 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>.</p>

</div>
</div>

### bitTransformIsCorrectForBSwap() {#a9f3d7adf7647a76ba410be64215a9d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool bitTransformIsCorrectForBSwap (unsigned From, unsigned To, unsigned BitWidth)</td>
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



<p>Definition at line 4069 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>.</p>

</div>
</div>

### CanMergeValues() {#a7c71badb215d0f31fc84eb7985934e77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CanMergeValues (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * First, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Second)</td>
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

<p>Return true if we can choose one of these values to use in place of the other.</p>


<p>Note that we will always choose the non-undef value to keep.</p>


<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#aa8ec1591dd8e7639e5b5e1869b49e9b5">CanPropagatePredecessorsForPHIs</a>.</p>

</div>
</div>

### CanPropagatePredecessorsForPHIs() {#aa8ec1591dd8e7639e5b5e1869b49e9b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CanPropagatePredecessorsForPHIs (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Succ, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BBPreds)</td>
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

<p>Return true if we can fold BB, an almost-empty BB ending in an unconditional branch to Succ, into Succ.</p>


<p>Assumption: Succ is the single successor for BB.</p>


<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#a7c71badb215d0f31fc84eb7985934e77">CanMergeValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa408bc83db2292cc1a57a3e6b206c2">llvm::succ_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>.</p>

</div>
</div>

### CanRedirectPredsOfEmptyBBToSucc() {#a72fccc775a9d83203b8d67f98dc0a3c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CanRedirectPredsOfEmptyBBToSucc (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Succ, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BBPreds, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *&amp; CommonPred)</td>
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



<p>Definition at line 1024 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ae020673b5ca2bae358005b8980413c4c">llvm::BasicBlock::hasNPredecessorsOrMore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>.</p>

</div>
</div>

### collectBitParts() {#aa16fecc86f9853cc81abd01a5a6f1604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt; BitPart &gt; &amp; collectBitParts (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool MatchBSwaps, bool MatchBitReversals, std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, std::optional&lt; BitPart &gt; &gt; &amp; BPS, int Depth, bool &amp; FoundRoot)</td>
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

<p>Analyze the specified subexpression and see if it is capable of providing pieces of a bswap or bitreverse.</p>


<p>The subexpression provides a potential piece of a bswap or bitreverse if it can be proved that each non-zero bit in the output of the expression came from a corresponding bit in some other value. This function is recursive, and the end result is a mapping of bitnumber to bitnumber. It is the caller's responsibility to validate that the bitnumber to bitnumber mapping is correct for a bswap or bitreverse.</p>


<p>For example, if the current subexpression if "(shl i32 %X, 24)" then we know that the expression deposits the low byte of X into the high byte of the result and that all other bits are zero. This expression is accepted and a <a href="/web-llvm/docs/api/structs/anonymous-local-cpp-/bitpart">BitPart</a> is returned with Provider set to X and Provenance[24-31] set to [0-7].</p>


<p>For vector types, all analysis is performed at the per-element level. No cross-element analysis is supported (shuffle/insertion/reduction), and all constant masks must be splatted across all elements.</p>


<p>To avoid revisiting values, the <a href="/web-llvm/docs/api/structs/anonymous-local-cpp-/bitpart">BitPart</a> results are memoized into the provided map. To avoid unnecessary copying of BitParts, BitParts are constructed in-place in the <span class="doxyComputerOutput">BPS</span> map. Because of this <span class="doxyComputerOutput">BPS</span> needs to store BitParts objects, not pointers. As we need the concept of a nullptr BitParts (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> has been analyzed and the analysis failed), we an Optional type instead to provide the same functionality.</p>


<p>Because we pass around references into <span class="doxyComputerOutput">BPS</span>, we must use a container that does not invalidate internal references (std::map instead of <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>).</p>


<p>Definition at line 3849 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/anonymous-local-cpp-/bitpart/#a6cad94d1198ae156fb92d86da87d0992">anonymous{Local.cpp}::BitPart::BitPart</a>, <a href="#ae67ef27038e310f603f3b1bc4fb6eda2">BitPartRecursionMaxDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aa16fecc86f9853cc81abd01a5a6f1604">collectBitParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0eb993474e9ffa2056f664cdc2e14ad4">llvm::PatternMatch::m_BitReverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae4e4b162282728d327227c5773592d65">llvm::PatternMatch::m_BSwap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9b00c4440366f614c142157502105fda">llvm::PatternMatch::m_FShl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ad2886e078317288a5a7c0709ee5a58d4">llvm::PatternMatch::m_FShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a457859e1ce3f174bb32567725e78a091">llvm::PatternMatch::m_LogicalShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1b8442c10c9ed6e0e07160b54541450e">llvm::PatternMatch::m_Trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6ba4022cd30993a84d111871dd0f6ba6">llvm::PatternMatch::m_ZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a27ad8ac0b3b15a21f86c5f89e0c9cdd0">llvm::APInt::popcount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af4b1ccc0b78f9da9f3f3944e06007f1d">llvm::APInt::uge</a>, <a href="/web-llvm/docs/api/structs/anonymous-local-cpp-/bitpart/#ab896f3f4307e3285fa11e20c638ffe70acb4045e015f2ff8334244fe843e91508">anonymous{Local.cpp}::BitPart::Unset</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="#aa16fecc86f9853cc81abd01a5a6f1604">collectBitParts</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>.</p>

</div>
</div>

### combineMetadata() {#a3c142cb2c6d5ca1e5f142d4062839944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void combineMetadata (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * J, bool DoesKMove, bool AAOnly=false)</td>
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

<p>If AAOnly is set, only intersect alias analysis metadata and preserve other known metadata.</p>


<p>Unknown metadata is always dropped.</p>


<p>Definition at line 3302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mmrametadata/#a6ef87eb55b64d064718fec836a989773">llvm::MMRAMetadata::combine</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a114eb8de3666c449d56ef4bf4609f0f6">llvm::MDNode::getMergedCallsiteMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ab7e8482721c713476d67087bfa6410b8">llvm::MDNode::getMergedMemProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7f27e470647cae7ae9225bae804bf006">llvm::MDNode::getMergedProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6c09737e146b2d816c911a047ac67ba4">llvm::Instruction::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a088247f165cc7e2ca9a3917adc0e75df">llvm::MDNode::getMostGenericAliasScope</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#af9b9a04442e0f04f60751aca1783ff3b">llvm::MDNode::getMostGenericAlignmentOrDereferenceable</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a9d9f2d817781a31c771406d1f0acc9fb">llvm::MDNode::getMostGenericFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a45a64ff2883d51edeb926ee63a4f64ac">llvm::MDNode::getMostGenericNoaliasAddrspace</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aac6e3a0dec40a6721857cbbd4330039f">llvm::MDNode::getMostGenericRange</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a3c210e8905029a012df3384a7eeb63ad">llvm::MDNode::getMostGenericTBAA</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#acdbfda46c9837123ef7143244fc1f904">llvm::MDNode::intersect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51d22a1ed809d7cb1c1eb46c820c8226">llvm::intersectAccessGroups</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad25f5892645ebf5417a8dab1730e52be">llvm::combineAAMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9b43098c569ea8289ed1ab70ee9a00af">llvm::combineMetadataForCSE</a>.</p>

</div>
</div>

### dropInitialDeref() {#a5ae41c589bd3c54f2a968e8336f3aa98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIExpression * dropInitialDeref (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * DIExpr)</td>
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



<p>Definition at line 1763 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a9b7e344136f26c673bbd64e6cb88178a">llvm::DIExpression::getElements</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a36d31b1eb92d4a290df06be8709c39be">llvm::InsertDebugValueAtStoreLoc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2ffbb17abf202aabdbb70f00a84905c9">llvm::InsertDebugValueAtStoreLoc</a>.</p>

</div>
</div>

### EliminateDuplicatePHINodesNaiveImpl() {#aa5133cfd6ce1419c7162cd0d7ba39ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EliminateDuplicatePHINodesNaiveImpl (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; &amp; ToRemove)</td>
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



<p>Definition at line 1392 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a602468cf8d0763769b6b39ece1117ad7">llvm::Instruction::isIdenticalToWhenDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5ddf07853114e72808bc2713805814f3">llvm::EliminateDuplicatePHINodes</a>.</p>

</div>
</div>

### EliminateDuplicatePHINodesSetBasedImpl() {#ab880924a451b73edfe368d53c3d8631c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EliminateDuplicatePHINodesSetBasedImpl (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; &amp; ToRemove)</td>
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



<p>Definition at line 1428 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a47670479395f375c7501109d25cb475f">llvm::PHINode::block_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aaf337eae2193217943c7c0d7a65e61bb">llvm::PHINode::block_end</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1fbf4d66a9eeaa9ade03e8febee097ee">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa52ac704c30d37ea926b7e186f4fac83">getHashValueImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80edfc5e42059e045aa7bf7fe42bee3">llvm::hash_combine_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a12f59da641309f7afb7b1d32cb59a7bf">isEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa60423084fe7d27af0ffbba889cbdf1a">isEqualImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp/#a1aed031578039adc6374053233f53d6f">isSentinel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a8d5e787d14a0d34fc9f68deaced56bc5">PHICSEDebugHash</a>, <a href="#aaa5586371e4169c68295e702dc682af1">PHICSENumPHISmallSize</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a5b0a15cec07aa8f0f9e60cd343676bca">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::reserve</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a3bf42baf773b375802538951c88d8e12">ToRemove</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#ad93396a26f6fd589ed400bb280319836">llvm::User::value_op_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5d1730a173d0a69624b80e1e22e6d225">llvm::User::value_op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5ddf07853114e72808bc2713805814f3">llvm::EliminateDuplicatePHINodes</a>.</p>

</div>
</div>

### gatherIncomingValuesToPhi() {#a3bd9116f3c9e74b7c836560911000c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void gatherIncomingValuesToPhi (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="#a02334b9cb9a6fd5fe6f4407dea7e1781">IncomingValueMap</a> &amp; IncomingValues)</td>
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

<p>Create a map from block to value for the operands of a given phi.</p>


<p>Create a map from block to value for each non-undef value flowing into <span class="doxyComputerOutput">PN</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PN</td>
<td class="doxyParamItemDescription"><p>The phi we are collecting the map for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IncomingValues</td>
<td class="doxyParamItemDescription"><p>[out] The map from block to value for this phi.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>.</p>

</div>
</div>

### getDwarfOpForBinOp() {#a25a7c90efaafea9d737d727d5f13e520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getDwarfOpForBinOp (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2476 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Referenced by <a href="#a55a8ce252bfbfa1af642af05f2c31e10">getSalvageOpsForBinOp</a>.</p>

</div>
</div>

### getDwarfOpForIcmpPred() {#a981d4a79d3783f0327fab0e9fcb7d938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getDwarfOpForIcmpPred (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2552 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>.</p>


<p>Referenced by <a href="#a7b323f2153ac64cdbab7e81c15575c0d">getSalvageOpsForIcmpOp</a>.</p>

</div>
</div>

### getSalvageOpsForBinOp() {#a55a8ce252bfbfa1af642af05f2c31e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getSalvageOpsForBinOp (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BI, uint64_t CurrentLocOps, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Opcodes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; AdditionalValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2518 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a272fe723d8c234f2137d34621a5cef78">llvm::DIExpression::appendOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a25a7c90efaafea9d737d727d5f13e520">getDwarfOpForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a4826d44e6c44f689b31757f02ad3b76f">handleSSAValueOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>.</p>

</div>
</div>

### getSalvageOpsForGEP() {#a7144f12bd93229efcf87a052ab80d5e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getSalvageOpsForGEP (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, uint64_t CurrentLocOps, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Opcodes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; AdditionalValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a272fe723d8c234f2137d34621a5cef78">llvm::DIExpression::appendOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a8da97c44f514ad1ae9ccf4518b0f88aa">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>.</p>

</div>
</div>

### getSalvageOpsForIcmpOp() {#a7b323f2153ac64cdbab7e81c15575c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getSalvageOpsForIcmpOp (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Icmp, uint64_t CurrentLocOps, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Opcodes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; AdditionalValues)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2577 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a981d4a79d3783f0327fab0e9fcb7d938">getDwarfOpForIcmpPred</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="#a4826d44e6c44f689b31757f02ad3b76f">handleSSAValueOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a>.</p>

</div>
</div>

### handleSSAValueOperands() {#a4826d44e6c44f689b31757f02ad3b76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleSSAValueOperands (uint64_t CurrentLocOps, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Opcodes, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; AdditionalValues, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 2506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a55a8ce252bfbfa1af642af05f2c31e10">getSalvageOpsForBinOp</a> and <a href="#a7b323f2153ac64cdbab7e81c15575c0d">getSalvageOpsForIcmpOp</a>.</p>

</div>
</div>

### insertDbgValueOrDbgVariableRecord() {#ac0da78bd6844fdff5ec2fc0654d00de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertDbgValueOrDbgVariableRecord (<a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DV, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DIVar, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * DIExpr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; NewLoc, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Instr)</td>
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



<p>Definition at line 1693 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a4ff1bb484be62f8dac94fc087f72f524">llvm::DebugLoc::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a915a8d23e084b7a40475a3ce2245495b">llvm::DIBuilder::insertDbgValueIntrinsic</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanagerimpl-h/#a926189935285d6e5df83fc0f45bf9b36">UseNewDbgInfoFormat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a79e6c0c958b2de133d4b9d0e2c62f1e4">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8946e172b10c0ef5eaebb28ebb7662ad">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e94595f29a0adde822a318f82dac61">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82984d4a91e7dc2072dfd8fad2854618">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="#a642caf268486d4a9e8a4b879a86448c2">insertDbgValueOrDbgVariableRecordAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36d31b1eb92d4a290df06be8709c39be">llvm::InsertDebugValueAtStoreLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ffbb17abf202aabdbb70f00a84905c9">llvm::InsertDebugValueAtStoreLoc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7994fd7ca0d8f8fcf2a9d18d151d0988">llvm::LowerDbgDeclare</a>.</p>

</div>
</div>

### insertDbgValueOrDbgVariableRecordAfter() {#a642caf268486d4a9e8a4b879a86448c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertDbgValueOrDbgVariableRecordAfter (<a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * DV, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DIVar, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * DIExpr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; NewLoc, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr)</td>
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



<p>Definition at line 1710 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Reference <a href="#ac0da78bd6844fdff5ec2fc0654d00de7">insertDbgValueOrDbgVariableRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab77dd880f8a4804500c2fd5c4df979ee">llvm::ConvertDebugDeclareToDebugValue</a>.</p>

</div>
</div>

### insertDbgVariableRecordsForPHIs() {#ad19c7559d6302321172436f45c771171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertDbgVariableRecordsForPHIs (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; &amp; InsertedPHIs)</td>
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



<p>Definition at line 2067 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a79a16a0ec88a38e513d42b64923cb8e2">llvm::DbgVariableRecord::clone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a0881334358ff6ff7ff8cea5562c7988e">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae876eb96b89c1afcc3e9cd285cc3f08c">llvm::filterDbgVars</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a365301682c41f8a7094218176d712cda">llvm::BasicBlock::insertDbgRecordBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#afd3574da4a2a86d1540dbdfcef171dd8">llvm::DbgVariableRecord::location_ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae0ac412244054beacd97e316ded0fed3">llvm::DbgVariableRecord::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a4dfea19770364b880a77c3f0c1c0f67c">llvm::insertDebugValuesForPHIs</a>.</p>

</div>
</div>

### introduceTooManyPhiEntries() {#ac4b6f64940804c14b1e0cc4ad04fb18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool introduceTooManyPhiEntries (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Succ)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether removing <span class="doxyComputerOutput">BB</span> will make the phis in its <span class="doxyComputerOutput">Succ</span> have too many incoming entries.</p>


<p>This function does not check whether <span class="doxyComputerOutput">BB</span> is foldable or not.</p>


<p>Definition at line 1057 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a526630ff85b48f29ac5b4c519c6c2243">llvm::BasicBlock::hasNPredecessors</a>, <a href="#ae908402f3042b6131823fec54c72f18c">MaxPhiEntriesIncreaseAfterRemovingEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a13da92d2694197fbcb5b95fd94e7570d">llvm::BasicBlock::phis</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3f211484edf604716a6c80030b0a0375">llvm::pred_size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>.</p>

</div>
</div>

### isArray() {#a7e06c0b653fcb0e20fbec6bee3d3d40d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isArray (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI)</td>
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

<p>Determine whether this alloca is either a VLA or an array.</p>

<p>Definition at line 1936 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#aea74164514e7164813ab30bcc4b7c557">llvm::AllocaInst::isArrayAllocation</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a2a394517076e7dd2bdcd7dde33dfcb7d">llvm::Type::isArrayTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7994fd7ca0d8f8fcf2a9d18d151d0988">llvm::LowerDbgDeclare</a>.</p>

</div>
</div>

### isBitCastSemanticsPreserving() {#a1484fd35d5f2401ee532e8aea2aba44c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isBitCastSemanticsPreserving (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToTy)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a bitcast between a value of type <span class="doxyComputerOutput">FromTy</span> to type <span class="doxyComputerOutput">ToTy</span> would losslessly preserve the bits and semantics of the value.</p>


<p>This predicate is symmetric, i.e swapping <span class="doxyComputerOutput">FromTy</span> and <span class="doxyComputerOutput">ToTy</span> should give the same result.</p>


<p>Note that Type::canLosslesslyBitCastTo is not suitable here because it allows semantically unequivalent bitcasts, such as &lt;2 x i64&gt; -&gt; &lt;4 x i32&gt;, and also does not allow lossless pointer &lt;-&gt; integer conversions.</p>


<p>Definition at line 2758 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#abf313eff420b7c6c8e322a2e9c53cd90">llvm::Type::isIntOrPtrTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>.</p>

</div>
</div>

### isStructure() {#a226deca7d8508b6b646c8596d4c174a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isStructure (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * AI)</td>
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

<p>Determine whether this alloca is a structure.</p>

<p>Definition at line 1942 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a81eef9d7336f7ee43be79630d8e8ec86">llvm::Type::isStructTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7994fd7ca0d8f8fcf2a9d18d151d0988">llvm::LowerDbgDeclare</a>.</p>

</div>
</div>

### markAliveBlocks() {#a0af4594038f5cb46e7a4c86713520c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool markAliveBlocks (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Reachable, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU=nullptr)</td>
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



<p>Definition at line 3027 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57f0e4faf4e39fa79daf9de35b1c7244">llvm::canSimplifyInvokeNoUnwind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b3fdb09b0789963c439d41fe91e44a1">llvm::changeToCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a71c91cbbfc1c0ecf9a69e10ccf739bd7">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Delete</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a066f917f4a73ce07260b0e4262be92ba">DenseMapInfo&lt; LocallyHashedType &gt;::Empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a1423601a8e4ec304e0756df4e761ebbb">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getEmptyKey</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/structs/anonymous-gvnsink-cpp-/densemapinfo/#a9571e26b946751eaf015a9b8dc508be9">anonymous{GVNSink.cpp}::DenseMapInfo&lt; ModelledPHI &gt;::getTombstoneKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80edfc5e42059e045aa7bf7fe42bee3">llvm::hash_combine_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a9aeeca2833810f01b20545a46fe22503">llvm::DominatorTreeBase&lt; BasicBlock, false &gt;::Insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a12f59da641309f7afb7b1d32cb59a7bf">isEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#afc43bc5ec4b20c7c5d663bef90da6066">llvm::PatternMatch::m_CombineOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#adea6dc2e42baa345b97be48b0370313d">llvm::PatternMatch::m_Undef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae77be336e228cf9aa00709a8606dfb98">llvm::PatternMatch::m_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b03ed78a8e299bde6d26a8793cd4e06">llvm::NullPointerIsDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#afe7af0c3ec2ef1f525173acd2ea4ba60">llvm::BasicBlock::removePredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06add2496ae8d635f9f169602771c88d376">llvm::Successor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#ad93396a26f6fd589ed400bb280319836">llvm::User::value_op_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5d1730a173d0a69624b80e1e22e6d225">llvm::User::value_op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aec88b7682025edff7984c3b6c8da8ac9">llvm::removeUnreachableBlocks</a>.</p>

</div>
</div>

### PhiHasDebugValue() {#a2a8305f7bf6d7dc8b192e257785c1fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PhiHasDebugValue (<a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DIVar, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * DIExpr, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * APN)</td>
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

<p>===------------------------------------------------------------------—===// Dbg <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic">Intrinsic</a> utilities</p>


<p>See if there is a dbg.value intrinsic for DIVar for the PHI node.</p>


<p>Definition at line 1611 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d7448a42ae4db532d3ba40e250ec825">llvm::findDbgValues</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a79e6c0c958b2de133d4b9d0e2c62f1e4">llvm::ConvertDebugDeclareToDebugValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a59e94595f29a0adde822a318f82dac61">llvm::ConvertDebugDeclareToDebugValue</a>.</p>

</div>
</div>

### redirectValuesFromPredecessorsToPhi() {#ae7d61f8763322c1d7c8181f00798d9c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void redirectValuesFromPredecessorsToPhi (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abf8dfef195cfd8a028f2dedf33c85a61">PredBlockVector</a> &amp; BBPreds, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * CommonPred)</td>
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

<p>Replace a value flowing from a block to a phi with potentially multiple instances of that value flowing from the block's predecessors to the phi.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The block with the value flowing into the phi.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BBPreds</td>
<td class="doxyParamItemDescription"><p>The predecessors of BB.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PN</td>
<td class="doxyParamItemDescription"><p>The phi that we are updating.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CommonPred</td>
<td class="doxyParamItemDescription"><p>The common predecessor of BB and PN's <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a></p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1089 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a3bd9116f3c9e74b7c836560911000c8e">gatherIncomingValuesToPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a>, <a href="#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a> and <a href="#acbbdeb8f2d6f4843eacd55fb7d985387">selectIncomingValueForBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>.</p>

</div>
</div>

### replaceDominatedUsesWith() {#a92e7361f7532de414322df105163781f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RootType, typename ShouldReplaceFn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned replaceDominatedUsesWith (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * From, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * To, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RootType &amp; Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ShouldReplaceFn &amp; ShouldReplace)</td>
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



<p>Definition at line 3533 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a62213d5211c9d944e5ede1f0059a6ae2">llvm::Value::printAsOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>

</div>
</div>

### replaceUndefValuesInPhi() {#a705c6c2b8e570441356edb8db2dd8ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceUndefValuesInPhi (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a02334b9cb9a6fd5fe6f4407dea7e1781">IncomingValueMap</a> &amp; IncomingValues)</td>
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

<p>Replace the incoming undef values to a phi with the values from a block-to-value map.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PN</td>
<td class="doxyParamItemDescription"><p>The phi we are replacing the undefs in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IncomingValues</td>
<td class="doxyParamItemDescription"><p>A map from block to value.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a88cdefb709309eddc6e5daca0be6a7b4">llvm::PHINode::setIncomingValue</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>.</p>

</div>
</div>

### rewriteDebugUsers() {#ab8b1a901ef225bb4a12ca046d13f4b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool rewriteDebugUsers (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; From, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; To, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; DomPoint, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="#a4f3243057e017aad4e091381fa3d9d10">DbgValReplacement</a>(<a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a> &amp;DII)&gt; RewriteExpr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="#a4f3243057e017aad4e091381fa3d9d10">DbgValReplacement</a>(<a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp;DVR)&gt; RewriteDVRExpr)</td>
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

<p>Point debug users of <span class="doxyComputerOutput">From</span> to <span class="doxyComputerOutput">To</span> using exprs given by <span class="doxyComputerOutput">RewriteExpr</span>, possibly moving/undefing users to prevent use-before-def.</p>


<p>Returns true if changes are made.</p>


<p>Definition at line 2660 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26bad0f6e5435a5a4dc50850c5b8f628">llvm::findDbgUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aa1b7611e70113463caabc2bc84bd08bf">llvm::DbgRecord::getMarker</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a91bd28adea418a08cec78b72413d9d45">llvm::Instruction::getNextNonDebugInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a36e5e8e39d6d654db719920186533fac">llvm::DbgMarker::MarkedInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a54507f01d7d06127068ee0663233511d">llvm::Instruction::moveAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a04a8b2dc4d72db72e1f87bdec4074973">llvm::DbgRecord::removeFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a3d995a069d73ebebbd6a4aace342ef76">llvm::DbgVariableIntrinsic::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae0ac412244054beacd97e316ded0fed3">llvm::DbgVariableRecord::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26be1141b23850a2b4eb78021d99e862">llvm::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a71808acf992f787300ec18d5700f09cc">llvm::DbgVariableIntrinsic::setExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a8e803431f2ec29d9982f5cd7815712ee">llvm::DbgVariableRecord::setExpression</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a4e5b9edb51eec9dbca592075eb64dfcb">Users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>.</p>

</div>
</div>

### salvageDbgAssignAddress() {#afe18f2bacebf9cbf307a33cf86b81e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void salvageDbgAssignAddress (T * Assign)</td>
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



<p>Definition at line 2270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a5f48305fa7d23161515c94bca7c2beb6">llvm::DIExpression::appendOpsToArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a7cc5f1632a4c520497898439c17dc026">llvm::DIExpression::getFragmentInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99356c6b92999b95181b5d79c03868ee">llvm::salvageDebugInfoImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a245a901981dbba45d423697bb3351b1b">llvm::salvageDebugInfoForDbgValues</a>.</p>

</div>
</div>

### selectIncomingValueForBlock() {#acbbdeb8f2d6f4843eacd55fb7d985387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * selectIncomingValueForBlock (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OldVal, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="#a02334b9cb9a6fd5fe6f4407dea7e1781">IncomingValueMap</a> &amp; IncomingValues)</td>
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

<p>Determines the value to use as the phi node input for a block.</p>


<p>Select between <span class="doxyComputerOutput">OldVal</span> any value that we know flows from <span class="doxyComputerOutput">BB</span> to a particular phi on the basis of which one (if either) is not undef. Update IncomingValues based on the selected value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OldVal</td>
<td class="doxyParamItemDescription"><p>The value we are considering selecting.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BB</td>
<td class="doxyParamItemDescription"><p>The block that the value flows in from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IncomingValues</td>
<td class="doxyParamItemDescription"><p>A map from block-to-value for other phi inputs that we have examined.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the selected value.</p></dd>
</dl>


<p>Definition at line 942 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>.</p>

</div>
</div>

### simplifyAndDCEInstruction() {#a7d068ffb71feb72ff6d1dee350ec7677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool simplifyAndDCEInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt; &amp; WorkList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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



<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a627b2f86ac433d829482d5a5a0f50668">llvm::isInstructionTriviallyDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26be1141b23850a2b4eb78021d99e862">llvm::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a42108fe3c2695cb429e6fe312908fa0d">llvm::SimplifyInstructionsInBlock</a>.</p>

</div>
</div>

### STATISTIC() {#a10125d51d3ff20feb0e8e217f552eac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumRemoved, "Number of unreachable basic <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> removed")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ac3ea19a7d0181e0ce206ab75c05f563a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPHICSEs, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>'s that got <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp/#ac56c14d91bc69a17e4e5936093b3bc05">CSE</a>'d")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>

</div>
</div>

### updateOneDbgValueForAlloca() {#acf65ce696212774397a4c1a3afc44275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateOneDbgValueForAlloca (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * DIVar, <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * DIExpr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewAddress, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst">DbgValueInst</a> * DVI, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * DVR, <a href="/web-llvm/docs/api/classes/llvm/dibuilder">DIBuilder</a> &amp; Builder, int Offset)</td>
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



<p>Definition at line 2213 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#aaa07b8d87479ec84346886b96ef5912a">llvm::DIExpression::getElement</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a1b59c8fe81267b338774bf6c542f90ee">llvm::DIExpression::getNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab804b15bb92ff685d7c1464b2816d608">llvm::DIExpression::prepend</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a3d995a069d73ebebbd6a4aace342ef76">llvm::DbgVariableIntrinsic::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae0ac412244054beacd97e316ded0fed3">llvm::DbgVariableRecord::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a71808acf992f787300ec18d5700f09cc">llvm::DbgVariableIntrinsic::setExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a8e803431f2ec29d9982f5cd7815712ee">llvm::DbgVariableRecord::setExpression</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab5dbbd2f6fe6ff78b5f809228236eb0d">llvm::replaceDbgValueForAlloca</a>.</p>

</div>
</div>

### valueCoversEntireFragment() {#a0bdd0669ab7b82ba709bfedcb751dcc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool valueCoversEntireFragment (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a> * DII)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the alloc size of <span class="doxyComputerOutput">ValTy</span> is large enough to cover the variable (or fragment of the variable) described by <span class="doxyComputerOutput">DII</span>.</p>


<p>This is primarily intended as a helper for the different ConvertDebugDeclareToDebugValue functions. The dbg.declare that is converted describes an alloca'd variable, so we need to use the alloc size of the value when doing the comparison. E.g. an i1 value will be identified as covering an n-bit fragment, if the store size of i1 is at least n bits.</p>


<p>Definition at line 1641 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#aa436f5a29352b2ea04248061b0ed8a4d">llvm::DIExpression::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af65afd02332c4f21c2fab7d217d6600f">llvm::Instruction::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#ad1707c1c1ab1f3278424f265893c87fb">llvm::DbgVariableIntrinsic::getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a8976759fe7e2d0329628f86b42957704">llvm::DbgVariableIntrinsic::getNumVariableLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a854857be09a21f27fb21ba872fe6f639">llvm::DbgVariableIntrinsic::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a5702a1d09ac6ee86196a38b3f682a570">llvm::DbgVariableIntrinsic::getVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a8c005ab74340f04df81ce12b8511a27a">llvm::DbgVariableIntrinsic::isAddressOfVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#afb486f9022a26e1cc53ff189710dbde5">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab77dd880f8a4804500c2fd5c4df979ee">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79e6c0c958b2de133d4b9d0e2c62f1e4">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8946e172b10c0ef5eaebb28ebb7662ad">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a07a576318c1a362676e2d4ff00b921bb">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e94595f29a0adde822a318f82dac61">llvm::ConvertDebugDeclareToDebugValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a82984d4a91e7dc2072dfd8fad2854618">llvm::ConvertDebugDeclareToDebugValue</a>.</p>

</div>
</div>

### valueCoversEntireFragment() {#a05d7d91d31a8121c140a4da8645c6474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool valueCoversEntireFragment (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * DVR)</td>
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



<p>Definition at line 1668 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#aa436f5a29352b2ea04248061b0ed8a4d">llvm::DIExpression::getActiveBits</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#abcbe492bce3ccc16e0bbb50292576c5c">llvm::Module::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a8ec5a479378113fc24b647afa2f06ee5">llvm::DbgVariableRecord::getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a7f3d614408430191567752182cc78bf5">llvm::DbgRecord::getModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#acd6da9d5bae0cbf845fe0016fcb4c9bb">llvm::DbgVariableRecord::getNumVariableLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#aa774c62045e74bb457b32713c0670696">llvm::DbgVariableRecord::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a99dac64e3a954ffbcbf1fc6726a743a2">llvm::DbgVariableRecord::getVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a637a15d148a2daafc86b1be17e01bca9">llvm::DbgVariableRecord::isAddressOfVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#afb486f9022a26e1cc53ff189710dbde5">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BitPartRecursionMaxDepth {#ae67ef27038e310f603f3b1bc4fb6eda2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned BitPartRecursionMaxDepth = 48</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Referenced by <a href="#aa16fecc86f9853cc81abd01a5a6f1604">collectBitParts</a>.</p>

</div>
</div>

### MaxPhiEntriesIncreaseAfterRemovingEmptyBlock {#ae908402f3042b6131823fec54c72f18c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxPhiEntriesIncreaseAfterRemovingEmptyBlock("max-phi-entries-increase-after-removing-empty-block", cl::init(1000), cl::Hidden, cl::desc("Stop removing an empty block if removing it will introduce more " "than this number of phi entries in its successor"))</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Referenced by <a href="#ac4b6f64940804c14b1e0cc4ad04fb18a">introduceTooManyPhiEntries</a>.</p>

</div>
</div>

### PHICSEDebugHash {#a8d5e787d14a0d34fc9f68deaced56bc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PHICSEDebugHash("phicse-debug-hash", cl::init(false), cl::Hidden, cl::desc("Perform extra assertion checking to verify that PHINodes's hash " "function is well-behaved w.r.t. its isEqual predicate"))</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5ddf07853114e72808bc2713805814f3">llvm::EliminateDuplicatePHINodes</a> and <a href="#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>.</p>

</div>
</div>

### PHICSENumPHISmallSize {#aaa5586371e4169c68295e702dc682af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; PHICSENumPHISmallSize("phicse-num-phi-smallsize", cl::init(32), cl::Hidden, cl::desc( "When the basic block contains not more than this number of PHI nodes, " "perform a (faster!) exhaustive search instead of set-driven one."))</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5ddf07853114e72808bc2713805814f3">llvm::EliminateDuplicatePHINodes</a> and <a href="#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>.</p>

</div>
</div>

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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"local"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp">Local.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
