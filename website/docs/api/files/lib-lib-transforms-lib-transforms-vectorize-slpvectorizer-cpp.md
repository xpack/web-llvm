---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SLPVectorizer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/slpvectorizer-h">llvm/Transforms/Vectorize/SLPVectorizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityqueue-h">llvm/ADT/PriorityQueue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scopeexit-h">llvm/ADT/ScopeExit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setoperations-h">llvm/ADT/SetOperations.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">llvm/ADT/SmallBitVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-h">llvm/ADT/iterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">llvm/ADT/iterator_range.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/codemetrics-h">llvm/Analysis/CodeMetrics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/constantfolding-h">llvm/Analysis/ConstantFolding.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/demandedbits-h">llvm/Analysis/DemandedBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/globalsmodref-h">llvm/Analysis/GlobalsModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">llvm/Analysis/IVDescriptors.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopaccessanalysis-h">llvm/Analysis/LoopAccessAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorylocation-h">llvm/Analysis/MemoryLocation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dotgraphtraits-h">llvm/Support/DOTGraphTraits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">llvm/Support/DebugCounter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">llvm/Support/GraphWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/instructioncost-h">llvm/Support/InstructionCost.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/injecttlimappings-h">llvm/Transforms/Utils/InjectTLIMappings.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/looputils-h">llvm/Transforms/Utils/LoopUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">llvm/Transforms/Utils/ScalarEvolutionExpander.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;set&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-slpvectorizer-cpp-">anonymous{SLPVectorizer.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/slpvectorizer">slpvectorizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A private "module" namespace for types and utilities used by this pass. <a href="/web-llvm/docs/api/namespaces/llvm/slpvectorizer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">placeholders</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/instructionsstate">InstructionsState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main data required for vectorization of instructions. <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/instructionsstate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp">BoUpSLP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bottom Up SLP Vectorizer. <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo">EdgeInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This structure holds any data we need about the edges being traversed during buildTree_rec(). <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics">LookAheadHeuristics</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper class used for scoring candidates for two consecutive lanes. <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands">VLOperands</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper data structure to hold the operands of a vector of instructions. <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/vloperands/operanddata">OperandData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For each operand we need (i) the value, and (ii) the opcode that it would be attached to if the expression was in a left-linearized form. <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/vloperands/operanddata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/vloperands/operandsorderdata">OperandsOrderData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data structure that helps to reorder operands. <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/vloperands/operandsorderdata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/treeentry">TreeEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/externaluser">ExternalUser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This POD struct describes one external user in the vectorized tree. <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/externaluser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/scheduledata">ScheduleData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains all scheduling relevant data for an instruction. <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/scheduledata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/blockscheduling">BlockScheduling</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains all scheduling data for a basic block. <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/blockscheduling/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/orderstypedensemapinfo">OrdersTypeDenseMapInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a> implementation for holding DenseMaps and DenseSets of sorted SmallVectors of unsigned. <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/orderstypedensemapinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db">GraphTraits&lt;BoUpSLP *&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits/childiteratortype-671e6b51bae1ee9c9bea09f55398ff49">ChildIteratorType&lt;BoUpSLP * &gt;::ChildIteratorType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the VectorizableTree to the index iterator to be able to return <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a7ceeff5a65c10abe289db52446ac088a">TreeEntry</a> pointers. <a href="/web-llvm/docs/api/structs/llvm/graphtraits/childiteratortype-671e6b51bae1ee9c9bea09f55398ff49/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/graphtraits/nodes-iterator-0333db08b4884940a0b852ccb2ddad27">nodes_iterator&lt;BoUpSLP * &gt;::nodes_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the node iterator we just need to turn the <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a7ceeff5a65c10abe289db52446ac088a">TreeEntry</a> iterator into a TreeEntry* iterator so that it dereferences to <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a55cdb660a488b62f949a57dc65f5296e">NodeRef</a>. <a href="/web-llvm/docs/api/classes/llvm/graphtraits/nodes-iterator-0333db08b4884940a0b852ccb2ddad27/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-860e5f7a11c435b145d274344a0415db">DOTGraphTraits&lt;BoUpSLP *&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/phihandler">PHIHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows to correctly handle operands of the phi nodes based on the <span class="doxyComputerOutput">Main</span> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> order of incoming basic blocks/values. <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/phihandler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis">BaseShuffleAnalysis</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base class for shuffle instruction emission and shuffle cost estimation. <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator">ShuffleCostEstimator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merges shuffle masks and emits final shuffle instruction, if required. <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/shufflecostbuilder">ShuffleCostBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-slpvectorizer-cpp-/valueselect">ValueSelect</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns incoming <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, if the requested type is <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * too, or a default value, otherwise. <a href="/web-llvm/docs/api/structs/anonymous-slpvectorizer-cpp-/valueselect/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-slpvectorizer-cpp-/shuffledinsertdata">ShuffledInsertData&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data type for handling buildvector sequences with the reused scalars from other tree entries. <a href="/web-llvm/docs/api/structs/anonymous-slpvectorizer-cpp-/shuffledinsertdata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder">ShuffleInstructionBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merges shuffle masks and emits final shuffle instruction, if required. <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/shuffleirbuilder">ShuffleIRBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction">HorizontalReduction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Model horizontal reductions. <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36ebcd8ea18a5e24ffe0c11fb9e965f">STATISTIC</a> (NumVectorInstructions, "Number of vector instructions generated")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55bb4ea2a7861858f599f46799ec73e">DEBUG_COUNTER</a> (VectorizedGraphs, "slp-vectorized", "Controls which SLP graphs should be vectorized.")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3ea54a95743867473d32853d3c65603">isValidElementType</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> for the element types that the SLP vectorizer supports. <a href="#aa3ea54a95743867473d32853d3c65603">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df55d50aee24118cfdc34ecb32db484">getValueType</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of the given value/instruction <span class="doxyComputerOutput">V</span>. <a href="#a9df55d50aee24118cfdc34ecb32db484">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a> (Type *ScalarTy, unsigned VF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f2ea425bfb988422fc240db77cf946">getFullVectorNumberOfElements</a> (const TargetTransformInfo &amp;TTI, Type *Ty, unsigned Sz)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of elements of the given type <span class="doxyComputerOutput">Ty</span>, not less than <span class="doxyComputerOutput">Sz</span>, which forms type, which splits by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a></span> into whole vector types during legalization. <a href="#a64f2ea425bfb988422fc240db77cf946">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd93b259f88f77258d2428448d9f8032">getFloorFullVectorNumberOfElements</a> (const TargetTransformInfo &amp;TTI, Type *Ty, unsigned Sz)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of elements of the given type <span class="doxyComputerOutput">Ty</span>, not greater than <span class="doxyComputerOutput">Sz</span>, which forms type, which splits by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a></span> into whole vector types during legalization. <a href="#abd93b259f88f77258d2428448d9f8032">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8af0e2291ce043c892dc0c8d85cc81e1">transformScalarShuffleIndiciesToVector</a> (unsigned VecTyNumElements, SmallVectorImpl&lt; int &gt; &amp;Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5e446b08fdb38a854b35dbab34bc0c">getShufflevectorNumGroups</a> (ArrayRef&lt; Value * &gt; VL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9f28186f9e231cea3f08c0b623129f4">calculateShufflevectorMask</a> (ArrayRef&lt; Value * &gt; VL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6848b7e929178610d01e1b2b5052af86">isConstant</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a9edb69d0ed6fda201d59948acfd89">isVectorLikeInstWithConstOps</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if <span class="doxyComputerOutput">V</span> is one of vector-like instructions, i.e. <a href="#a06a9edb69d0ed6fda201d59948acfd89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74addefa3085903bdce006cd86cb2a27">getPartNumElems</a> (unsigned Size, unsigned NumParts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns power-of-2 number of elements in a single register (part), given the total number of elements <span class="doxyComputerOutput">Size</span> and number of registers (parts) <span class="doxyComputerOutput">NumParts</span>. <a href="#a74addefa3085903bdce006cd86cb2a27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b9e7c9e471d8a5babf5b80f50029b8f">getNumElems</a> (unsigned Size, unsigned PartNumElems, unsigned Part)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns correct remaining number of elements, considering total amount <span class="doxyComputerOutput">Size</span>, (power-of-2 number) of elements in a single register <span class="doxyComputerOutput">PartNumElems</span> and current register (part) <span class="doxyComputerOutput">Part</span>. <a href="#a3b9e7c9e471d8a5babf5b80f50029b8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f3bcb74818214fe1e8df656c52ab206">shortBundleName</a> (ArrayRef&lt; Value * &gt; VL, int Idx=-1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a short descriptor of the instruction bundle suitable for debug output. <a href="#a9f3bcb74818214fe1e8df656c52ab206">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd5114d6b451e9ca85a36fc3f19f76c4">allSameBlock</a> (ArrayRef&lt; Value * &gt; VL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7568c08b526dbf7f7b5402f3eb605b55">allConstant</a> (ArrayRef&lt; Value * &gt; VL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef5b86735d738868e5fb00a18643b1c">isSplat</a> (ArrayRef&lt; Value * &gt; VL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0da56db6da27340e5a7151a4676106a">isCommutative</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adb57ca02be42b4c1e078def74670fb93">getInsertExtractIndex</a> (const Value *Inst, unsigned Offset) -&gt; std::optional&lt; unsigned &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77fa69a2017071ea8148d68badf475d1">getElementIndex</a> (const Value *Inst, unsigned Offset=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd40bb67aec98438b791520159fb146">buildUseMask</a> (int VF, ArrayRef&lt; int &gt; Mask, UseMask MaskArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prepares a use bitset for the given mask either for the first argument or for the second. <a href="#a2fd40bb67aec98438b791520159fb146">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsPoisonOnly = false&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac396bb87eb4db1dd3ce315e4d91ee2de">isUndefVector</a> (const Value *V, const SmallBitVector &amp;UseMask={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given value is actually an undefined constant vector. <a href="#ac396bb87eb4db1dd3ce315e4d91ee2de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ec">TargetTransformInfo::ShuffleKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d72247c1a3137bc2c2c7aaf0000b03">isFixedVectorShuffle</a> (ArrayRef&lt; Value * &gt; VL, SmallVectorImpl&lt; int &gt; &amp;Mask, AssumptionCache *AC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the vector of instructions can be represented as a shuffle, like: x0 = extractelement &lt;4 x i8&gt; x, i32 0 x3 = extractelement &lt;4 x i8&gt; x, i32 3 y1 = extractelement &lt;4 x i8&gt; y, i32 1 y2 = extractelement &lt;4 x i8&gt; y, i32 2 x0x0 = mul i8 x0, x0 x3x3 = mul i8 x3, x3 y1y1 = mul i8 y1, y1 y2y2 = mul i8 y2, y2 ins1 = insertelement &lt;4 x i8&gt; poison, i8 x0x0, i32 0 ins2 = insertelement &lt;4 x i8&gt; ins1, i8 x3x3, i32 1 ins3 = insertelement &lt;4 x i8&gt; ins2, i8 y1y1, i32 2 ins4 = insertelement &lt;4 x i8&gt; ins3, i8 y2y2, i32 3 ret &lt;4 x i8&gt; ins4 can be transformed into: %1 = shufflevector &lt;4 x i8&gt; x, &lt;4 x i8&gt; y, &lt;4 x i32&gt; &lt;i32 0, i32 3, i32 5, i32 6&gt; %2 = mul &lt;4 x i8&gt; %1, %1 ret &lt;4 x i8&gt; %2 Mask will return the Shuffle Mask equivalent to the extracted elements. <a href="#ad5d72247c1a3137bc2c2c7aaf0000b03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992052c8e8463f5d055c79ca8abb9521">getExtractIndex</a> (Instruction *E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f3292dcaad99569501ace7909f2ccf0">isValidForAlternation</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static InstructionsState</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a> (ArrayRef&lt; Value * &gt; VL, const TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a321240b67a372a24d41687f6a2e96877">areCompatibleCmpOps</a> (Value *BaseOp0, Value *BaseOp1, Value *Op0, Value *Op1, const TargetLibraryInfo &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the provided operands of 2 cmp instructions are compatible, i.e. <a href="#a321240b67a372a24d41687f6a2e96877">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a807bb3d2ecc2999993a91d499bd26543">isCmpSameOrSwapped</a> (const CmpInst *BaseCI, const CmpInst *CI, const TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfbce373feafd33ca9e104d8b164ece">allSameType</a> (ArrayRef&lt; Value * &gt; VL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596e8b6e6b71f454b18f982f947e5e03">doesInTreeUserNeedToExtract</a> (Value *Scalar, Instruction *UserInst, TargetLibraryInfo *TLI, const TargetTransformInfo *TTI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae9f536130472bd3fbdd23c3d4486b3b">getLocation</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ca9742688618517cc4690fb947fb609">isSimple</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae122b7b9960cfd970b1d5c0d83f22039">addMask</a> (SmallVectorImpl&lt; int &gt; &amp;Mask, ArrayRef&lt; int &gt; SubMask, bool ExtendingManyInputs=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shuffles <span class="doxyComputerOutput">Mask</span> in accordance with the given <span class="doxyComputerOutput">SubMask</span>. <a href="#ae122b7b9960cfd970b1d5c0d83f22039">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a> (MutableArrayRef&lt; unsigned &gt; Order)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Order may have elements assigned special value (size) which is out of bounds. <a href="#ae203ebf95f0711b6d63e3672baeaf669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4617b6f7b2916249d12f30bc81a17855">getAltInstrMask</a> (ArrayRef&lt; Value * &gt; VL, unsigned Opcode0, unsigned Opcode1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a3e80130d3f25468190ba343064b37e">reorderReuses</a> (SmallVectorImpl&lt; int &gt; &amp;Reuses, ArrayRef&lt; int &gt; Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reorders the given <span class="doxyComputerOutput">Reuses</span> mask according to the given <span class="doxyComputerOutput">Mask</span>. <a href="#a4a3e80130d3f25468190ba343064b37e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633db91afb11db086004de9e3eb37217">reorderOrder</a> (SmallVectorImpl&lt; unsigned &gt; &amp;Order, ArrayRef&lt; int &gt; Mask, bool BottomOrder=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reorders the given <span class="doxyComputerOutput">Order</span> according to the given <span class="doxyComputerOutput">Mask</span>. <a href="#a633db91afb11db086004de9e3eb37217">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8c65a150fe96c228db5b19d6b09e3a">arePointersCompatible</a> (Value *Ptr1, Value *Ptr2, const TargetLibraryInfo &amp;TLI, bool CompareOpcodes=true)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae06eb06e1d6ba6b5e8d319eef5d16280">computeCommonAlignment</a> (ArrayRef&lt; Value * &gt; VL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates minimal alignment as a common alignment. <a href="#ae06eb06e1d6ba6b5e8d319eef5d16280">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa640d51b943ce0396e7131bf2352f8a">isReverseOrder</a> (ArrayRef&lt; unsigned &gt; Order)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Order</span> represents reverse order. <a href="#afa640d51b943ce0396e7131bf2352f8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a> (ArrayRef&lt; Value * &gt; PointerOps, Type *ElemTy, const DataLayout &amp;DL, ScalarEvolution &amp;SE, SmallVectorImpl&lt; unsigned &gt; &amp;SortedIndices, Instruction *Inst=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the provided list of pointers <span class="doxyComputerOutput">Pointers</span> represents the strided pointers for type ElemTy. <a href="#a0a8a72a5038e4a261d35418751506868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac10dff634cacc4be44046af5ee45f92a">getGEPCosts</a> (const TargetTransformInfo &amp;TTI, ArrayRef&lt; Value * &gt; Ptrs, Value *BasePtr, unsigned Opcode, TTI::TargetCostKind CostKind, Type *ScalarTy, VectorType *VecTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the scalar and the vector costs from vectorizing set of GEPs. <a href="#ac10dff634cacc4be44046af5ee45f92a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c4c7b26972597220296eab6450669b0">getShuffleCost</a> (const TargetTransformInfo &amp;TTI, TTI::ShuffleKind Kind, VectorType *Tp, ArrayRef&lt; int &gt; Mask={}, TTI::TargetCostKind CostKind=TTI::TCK_RecipThroughput, int Index=0, VectorType *SubTp=nullptr, ArrayRef&lt; const Value * &gt; Args={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the cost of the shuffle instructions with the given <span class="doxyComputerOutput">Kind</span>, vector type <span class="doxyComputerOutput">Tp</span> and optional <span class="doxyComputerOutput">Mask</span>. <a href="#a3c4c7b26972597220296eab6450669b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3560dc2fa2aa91cd3ea182c6d6cd8030">createInsertVector</a> (IRBuilderBase &amp;Builder, Value *Vec, Value *V, unsigned Index, function_ref&lt; Value *(Value *, Value *, ArrayRef&lt; int &gt;)&gt; Generator={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Correctly creates insert_subvector, checking that the index is multiple of the subvectors length. <a href="#a3560dc2fa2aa91cd3ea182c6d6cd8030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a4c284255a153d29ddcbd05bcf5345">createExtractVector</a> (IRBuilderBase &amp;Builder, Value *Vec, unsigned SubVecVF, unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Correctly creates extract_subvector, checking that the index is multiple of the subvectors length. <a href="#ae3a4c284255a153d29ddcbd05bcf5345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d26c707fd7389b46ad98970d56faf24">clusterSortPtrAccesses</a> (ArrayRef&lt; Value * &gt; VL, ArrayRef&lt; BasicBlock * &gt; BBs, Type *ElemTy, const DataLayout &amp;DL, ScalarEvolution &amp;SE, SmallVectorImpl&lt; unsigned &gt; &amp;SortedIndices)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6927d96b3815417479246b5afc732e">areTwoInsertFromSameBuildVector</a> (InsertElementInst *VU, InsertElementInst *V, function_ref&lt; Value *(InsertElementInst *)&gt; GetBaseOperand)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if two insertelement instructions are from the same buildvector. <a href="#abe6927d96b3815417479246b5afc732e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0feeaece30961860a542ba8ee2a1f9f3">isRepeatedNonIdentityClusteredMask</a> (ArrayRef&lt; int &gt; Mask, unsigned Sz)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given mask is a "clustered" mask with the same clusters of size <span class="doxyComputerOutput">Sz</span>, which are not identity submasks. <a href="#a0feeaece30961860a542ba8ee2a1f9f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bbe053c13b73cf6ed1276f66b615fc7">combineOrders</a> (MutableArrayRef&lt; unsigned &gt; Order, ArrayRef&lt; unsigned &gt; SecondaryOrder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fb7740f0fb6e5a825320f3c63df3263">dumpOrder</a> (const BoUpSLP::OrdersType &amp;Order)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a> (const BoUpSLP &amp;R, ArrayRef&lt; Value * &gt; VL, const DataLayout &amp;DL, ScalarEvolution &amp;SE, const TargetTransformInfo &amp;TTI, SmallVectorImpl&lt; SmallVector&lt; std::pair&lt; LoadInst *, int &gt; &gt; &gt; &amp;GatheredLoads, bool AddNew=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to find subvector of loads and builds new vector of only loads if can be profitable. <a href="#a9e4f7b81913ac2176cac1eaa2b66a0b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2acd0e4598d1a9c34a8f2d9c9f98aaca">needToScheduleSingleInstruction</a> (ArrayRef&lt; Value * &gt; VL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; size_t, size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a> (Value *V, const TargetLibraryInfo *TLI, function_ref&lt; hash_code(size_t, LoadInst *)&gt; LoadsSubkeyGenerator, bool AllowAlternate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates key/subkey pair for the given value to provide effective sorting of the values and better detection of the vectorizable values sequences. <a href="#a81425fa662eac9cc9cd5d21f1c66695e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb636ad432c97f9178ff3f966e93d819">isAlternateInstruction</a> (const Instruction *I, const Instruction *MainOp, const Instruction *AltOp, const TargetLibraryInfo &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the specified instruction <span class="doxyComputerOutput">I</span> is an alternate operation for the given <span class="doxyComputerOutput">MainOp</span> and <span class="doxyComputerOutput">AltOp</span> instructions. <a href="#afb636ad432c97f9178ff3f966e93d819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a8b818a539c2cbbe1a954a875c5fcec">getVectorCallCosts</a> (CallInst *CI, FixedVectorType *VecTy, TargetTransformInfo *TTI, TargetLibraryInfo *TLI, ArrayRef&lt; Type * &gt; ArgTys)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9875dff9496a8c83bc0bcf749858c45b">buildIntrinsicArgTypes</a> (const CallInst *CI, const Intrinsic::ID ID, const unsigned VF, unsigned MinBW, const TargetTransformInfo *TTI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Builds the arguments types vector for the given call instruction with the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span> for the specified vector factor. <a href="#a9875dff9496a8c83bc0bcf749858c45b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0109582eb646d501101a7e6a059814fb">isLoadCombineCandidateImpl</a> (Value *Root, unsigned NumElts, TargetTransformInfo *TTI, bool MustMatchOrInst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a405ff61e8571b58fecaa716540af108f">isFirstInsertElement</a> (const InsertElementInst *IE1, const InsertElementInst *IE2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the <span class="doxyComputerOutput">IE1</span> instructions is followed by <span class="doxyComputerOutput">IE2</span> instruction in the buildvector sequence. <a href="#a405ff61e8571b58fecaa716540af108f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a67399cd92cbad7bcf7d0fbe417f779ec">performExtractsShuffleAction</a> (MutableArrayRef&lt; std::pair&lt; T *, SmallVector&lt; int &gt; &gt; &gt; ShuffleMask, Value *Base, function_ref&lt; unsigned(T *)&gt; GetVF, function_ref&lt; std::pair&lt; T *, bool &gt;(T *, ArrayRef&lt; int &gt;, bool)&gt; ResizeAction, function_ref&lt; T *(ArrayRef&lt; int &gt;, ArrayRef&lt; T * &gt;)&gt; Action)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the analysis of the provided shuffle masks and performs the requested actions on the vectors with the given shuffle masks. <a href="#a67399cd92cbad7bcf7d0fbe417f779ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9245aac1330cef52005ed7a9f789c37">propagateMetadata</a> (Instruction *Inst, ArrayRef&lt; Value * &gt; VL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad281a65c549980abb2d08fc3973df2a8">getRdxKind</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets recurrence kind from the specified value. <a href="#ad281a65c549980abb2d08fc3973df2a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce98f2299c58e68c25ff0f9a0108f3c">checkTreeSizes</a> (ArrayRef&lt; std::pair&lt; unsigned, unsigned &gt; &gt; Sizes, bool First)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the quadratic mean deviation is less than 90% of the mean size. <a href="#a7ce98f2299c58e68c25ff0f9a0108f3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d5504ae0acaa8a22f450dceccae9b5">getAggregateSize</a> (Instruction *InsertInst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c995d3af67d9f0024160f8480989563">findBuildAggregate_rec</a> (Instruction *LastInsertInst, TargetTransformInfo *TTI, SmallVectorImpl&lt; Value * &gt; &amp;BuildVectorOpds, SmallVectorImpl&lt; Value * &gt; &amp;InsertElts, unsigned OperandOffset, const BoUpSLP &amp;R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a296bc5fd6767824b2baf15675296743f">findBuildAggregate</a> (Instruction *LastInsertInst, TargetTransformInfo *TTI, SmallVectorImpl&lt; Value * &gt; &amp;BuildVectorOpds, SmallVectorImpl&lt; Value * &gt; &amp;InsertElts, const BoUpSLP &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recognize construction of vectors like ra = insertelement &lt;4 x float&gt; poison, float s0, i32 0 rb = insertelement &lt;4 x float&gt; ra, float s1, i32 1 rc = insertelement &lt;4 x float&gt; rb, float s2, i32 2 rd = insertelement &lt;4 x float&gt; rc, float s3, i32 3 starting from the last insertelement or insertvalue instruction. <a href="#a296bc5fd6767824b2baf15675296743f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa898a031df90bb6ac31dc9cb253b310e">getReductionInstr</a> (const DominatorTree *DT, PHINode *P, BasicBlock *ParentBB, LoopInfo *LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try and get a reduction instruction from a phi node. <a href="#aa898a031df90bb6ac31dc9cb253b310e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a526067810066884b7bb20ad94dcde">matchRdxBop</a> (Instruction *I, Value *&amp;V0, Value *&amp;V1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad25cdf8e7c874eae6f692b4319c6afe4">tryGetSecondaryReductionRoot</a> (PHINode *Phi, Instruction *Root)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We could have an initial reduction that is not an add. <a href="#ad25cdf8e7c874eae6f692b4319c6afe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf33b25adbec09e3d48e920bbcfe34a">getNonPhiOperand</a> (Instruction *I, PHINode *Phi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Returns</span> the first operand of <span class="doxyComputerOutput">I</span> that does not match <span class="doxyComputerOutput">Phi</span>. <a href="#aedf33b25adbec09e3d48e920bbcfe34a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bd7a084a808c1f12f4cdc5e1a67aa70">isReductionCandidate</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns true if <span class="doxyComputerOutput">I</span> is a candidate instruction for reduction vectorization. <a href="#a7bd7a084a808c1f12f4cdc5e1a67aa70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac48731694e324e56e35cb2b4f20345d0">tryToVectorizeSequence</a> (SmallVectorImpl&lt; T * &gt; &amp;Incoming, function_ref&lt; bool(T *, T *)&gt; Comparator, function_ref&lt; bool(T *, T *)&gt; AreCompatible, function_ref&lt; bool(ArrayRef&lt; T * &gt;, bool)&gt; TryToVectorizeHelper, bool MaxVFOnly, BoUpSLP &amp;R)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsCompatibility&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a> (Value *V, Value *V2, TargetLibraryInfo &amp;TLI, const DominatorTree &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two cmp instructions. <a href="#af5d61d0124d62ee38726acc83dcdc037">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a036e0a1db6c8bc87545585362e94b033">RunSLPVectorization</a>("vectorize-slp", cl::init(true), cl::Hidden, cl::desc("Run the SLP vectorization passes"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b6f16f98498a168902dd2d5cd8f9462">SLPReVec</a>("slp-revec", cl::init(false), cl::Hidden, cl::desc("Enable vectorization for wider vector utilization"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704fbec676f53c0e32a778dcd57d21d9">SLPCostThreshold</a>("slp-threshold", cl::init(0), cl::Hidden, cl::desc("Only vectorize if you gain more than this " "number "))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a810249c0345682081378ebbda3b097d3">SLPSkipEarlyProfitabilityCheck</a>("slp-skip-early-profitability-check", cl::init(false), cl::Hidden, cl::desc("When true, SLP vectorizer bypasses profitability checks based on " "heuristics and makes vectorization decision via cost modeling."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67d4a829531287f2d81c7a306b52a4d7">ShouldVectorizeHor</a>("slp-vectorize-hor", cl::init(true), cl::Hidden, cl::desc("Attempt to vectorize horizontal reductions"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81dd3124ab70c150ac09a8bb9b921de8">ShouldStartVectorizeHorAtStore</a>("slp-vectorize-hor-store", cl::init(false), cl::Hidden, cl::desc("Attempt to vectorize horizontal reductions feeding into a store"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ca809da394247bba762653f861875a1">MaxVectorRegSizeOption</a>("slp-max-reg-size", cl::init(128), cl::Hidden, cl::desc("Attempt to vectorize for this register size in bits"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470e4a44fc1d069edcb7e3e0b6e7f014">MaxVFOption</a>("slp-max-vf", cl::init(0), cl::Hidden, cl::desc("Maximum SLP vectorization factor (0=unlimited)"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfadb82d555661f3a7010a5ff6778e8a">ScheduleRegionSizeBudget</a>("slp-schedule-budget", cl::init(100000), cl::Hidden, cl::desc("Limit the size of the SLP scheduling region per block"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Limits the size of scheduling regions in a block. <a href="#acfadb82d555661f3a7010a5ff6778e8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4b62196a6175779b466b2e8f0e5cc12">MinVectorRegSizeOption</a>("slp-min-reg-size", cl::init(128), cl::Hidden, cl::desc("Attempt to vectorize for this register size in bits"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbff8697d64e4ee139aa777b68999872">RecursionMaxDepth</a>("slp-recursion-max-depth", cl::init(12), cl::Hidden, cl::desc("Limit the recursion depth when building a vectorizable tree"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630e10d123952904d5da8a02713d935a">MinTreeSize</a>("slp-min-tree-size", cl::init(3), cl::Hidden, cl::desc("Only vectorize small trees if they are fully vectorizable"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468123f1f142182cbdad8c20e98b64fd">LookAheadMaxDepth</a>("slp-max-look-ahead-depth", cl::init(2), cl::Hidden, cl::desc("The maximum look-ahead depth for operand reordering scores"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99e5e5bf957082c728b786a978a3b18a">RootLookAheadMaxDepth</a>("slp-max-root-look-ahead-depth", cl::init(2), cl::Hidden, cl::desc("The maximum look-ahead depth for searching best rooting option"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9350d9f87e91559fd54f4e66190255">MinProfitableStridedLoads</a>("slp-min-strided-loads", cl::init(2), cl::Hidden, cl::desc("The minimum number of loads, which should be considered strided, " "if the stride is > 1 or is runtime value"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ffea6d979c6f85d480c0f4187207058">MaxProfitableLoadStride</a>("slp-max-stride", cl::init(8), cl::Hidden, cl::desc("The maximum stride, considered to be profitable."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565c181d9f5686f1c52dee18510cb8a1">ViewSLPTree</a>("view-slp-tree", cl::Hidden, cl::desc("Display the SLP trees with Graphviz"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617fa15d11df5807cbc0e7191ff649d3">VectorizeNonPowerOf2</a>("slp-vectorize-non-power-of-2", cl::init(false), cl::Hidden, cl::desc("Try to vectorize with non-power-of-2 number of elements."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d624115133c3a9ac3109be4be89a32f">AliasedCheckLimit</a> = 10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75df5de932994d1472ad3cda6a88cf21">UsesLimit</a> = 64</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ce8fdf40e75ddf217650e2b1b15b5e6">MaxMemDepDistance</a> = 160</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d78104bfada8d17dad04e588b7d9a17">MinScheduleRegionSize</a> = 16</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the ScheduleRegionSizeBudget is exhausted, we allow small scheduling regions to be handled. <a href="#a3d78104bfada8d17dad04e588b7d9a17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a9c293de5315c98b1ff09bf30c26ff">MaxPHINumOperands</a> = 128</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum allowed number of operands in the PHI nodes. <a href="#a12a9c293de5315c98b1ff09bf30c26ff">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a274654b7f5932cae6a71a113322481be">SV_NAME</a>&nbsp;&nbsp;&nbsp;"slp-vectorizer"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"SLP"</td>
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

### addMask() {#ae122b7b9960cfd970b1d5c0d83f22039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addMask (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; SubMask, bool ExtendingManyInputs=false)</td>
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

<p>Shuffles <span class="doxyComputerOutput">Mask</span> in accordance with the given <span class="doxyComputerOutput">SubMask</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExtendingManyInputs</td>
<td class="doxyParamItemDescription"><p>Supports reshuffling of the mask with not only one but two input vectors.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>.</p>

</div>
</div>

### allConstant() {#a7568c08b526dbf7f7b5402f3eb605b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool allConstant (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if all of the values in <span class="doxyComputerOutput">VL</span> are constants (but not globals/constant expressions).</p></dd>
</dl>


<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a6dee2d9e1e2a288de903228075ac71de">isConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ad633712289394ee2c1d80b79432d11df">llvm::slpvectorizer::BoUpSLP::isTreeNotExtendable</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa054ca3a90996e96887be015cf288270">llvm::slpvectorizer::BoUpSLP::isTreeTinyAndNotFullyVectorizable</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### allSameBlock() {#abd5114d6b451e9ca85a36fc3f19f76c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool allSameBlock (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all of the instructions in <span class="doxyComputerOutput">VL</span> are in the same block or false otherwise.</p></dd>
</dl>


<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="#a06a9edb69d0ed6fda201d59948acfd89">isVectorLikeInstWithConstOps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9b5301a03dc90d7ac00440e2de4d9149">llvm::iterator_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ad633712289394ee2c1d80b79432d11df">llvm::slpvectorizer::BoUpSLP::isTreeNotExtendable</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa054ca3a90996e96887be015cf288270">llvm::slpvectorizer::BoUpSLP::isTreeTinyAndNotFullyVectorizable</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>.</p>

</div>
</div>

### allSameType() {#aabfbce373feafd33ca9e104d8b164ece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool allSameType (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if all of the values in <span class="doxyComputerOutput">VL</span> have the same type or false otherwise.</p></dd>
</dl>


<p>Definition at line 1093 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a9a5d97b0aecbff971c950b2daae62509">llvm::slpvectorizer::BoUpSLP::buildTree</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ad022a5da5618f159f353f6faa4c902cb">llvm::slpvectorizer::BoUpSLP::buildTree</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>.</p>

</div>
</div>

### areCompatibleCmpOps() {#a321240b67a372a24d41687f6a2e96877}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areCompatibleCmpOps (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BaseOp0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BaseOp1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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

<p>Checks if the provided operands of 2 cmp instructions are compatible, i.e.</p>


<p>compatible instructions or constants, or just some other regular values.</p>


<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a6848b7e929178610d01e1b2b5052af86">isConstant</a>.</p>


<p>Referenced by <a href="#a807bb3d2ecc2999993a91d499bd26543">isCmpSameOrSwapped</a>.</p>

</div>
</div>

### arePointersCompatible() {#abf8c65a150fe96c228db5b19d6b09e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool arePointersCompatible (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, bool CompareOpcodes=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 4790 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a6dee2d9e1e2a288de903228075ac71de">isConstant</a> and <a href="#adbff8697d64e4ee139aa777b68999872">RecursionMaxDepth</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>.</p>

</div>
</div>

### areTwoInsertFromSameBuildVector() {#abe6927d96b3815417479246b5afc732e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areTwoInsertFromSameBuildVector (<a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a> * VU, <a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a> * V, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *(<a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a> *)&gt; GetBaseOperand)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if two insertelement instructions are from the same buildvector.</p>

<p>Definition at line 5500 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/insertelementinst/#a49230ece74a48a27fb2bb1a4928b6e29">llvm::InsertElementInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a> and <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a585f149dd8c344a40c53b1694d3161ed">llvm::SmallBitVector::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### buildIntrinsicArgTypes() {#a9875dff9496a8c83bc0bcf749858c45b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Type * &gt; buildIntrinsicArgTypes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned VF, unsigned MinBW, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI)</td>
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

<p>Builds the arguments types vector for the given call instruction with the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span> for the specified vector factor.</p>

<p>Definition at line 11077 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad6db62129ba3650d98ce56fa03ab5f1">llvm::isVectorIntrinsicWithScalarOpAtArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">llvm::Intrinsic::not_intrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### buildUseMask() {#a2fd40bb67aec98438b791520159fb146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector buildUseMask (int VF, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, UseMask MaskArg)</td>
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

<p>Prepares a use bitset for the given mask either for the first argument or for the second.</p>

<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-slpvectorizer-cpp-/#a600545eb53de812fc4daae8ecb72199da8545ba2c4d270d3cca72fb93da2a21d8">anonymous{SLPVectorizer.cpp}::FirstArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-slpvectorizer-cpp-/#a600545eb53de812fc4daae8ecb72199da018f3de8f2e77f6f34af68e83516cb9f">anonymous{SLPVectorizer.cpp}::SecondArg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-slpvectorizer-cpp-/#a600545eb53de812fc4daae8ecb72199da3e1e09be16e530770bc81cd5f2b2edb9">anonymous{SLPVectorizer.cpp}::UndefsAsMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a047b7995a79492824633a62540717492">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::peekThroughShuffles</a> and <a href="#a67399cd92cbad7bcf7d0fbe417f779ec">performExtractsShuffleAction</a>.</p>

</div>
</div>

### calculateRtStride() {#a0a8a72a5038e4a261d35418751506868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; calculateRtStride (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; PointerOps, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; SortedIndices, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst=nullptr)</td>
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

<p>Checks if the provided list of pointers <span class="doxyComputerOutput">Pointers</span> represents the strided pointers for type ElemTy.</p>


<p>If they are not, std::nullopt is returned. Otherwise, if <span class="doxyComputerOutput">Inst</span> is not specified, just initialized optional value is returned to show that the pointers represent strided pointers. If <span class="doxyComputerOutput">Inst</span> specified, the runtime stride is materialized before the given <span class="doxyComputerOutput">Inst</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if the pointers are not pointers with the runtime stride, nullptr or actual stride value, otherwise.</p></dd>
</dl>


<p>Definition at line 4834 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#ac711b5659270bd9e66b8f38ec481260c">llvm::SCEVExpander::expandCodeFor</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a2eb94d079d8416118f4aaed865ab05d7">llvm::ScalarEvolution::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8bcb86d8d126d95b0dc05f09e8f3df96">llvm::ScalarEvolution::getMinusSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aeca82ae7bafbb557b7026f7d035643b8">llvm::ScalarEvolution::getUDivExactExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a87b23e247f35b163544f1ce8e920801c">llvm::SCEV::isNonConstantNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a4541962f9c18aacceb7243520eb15e1f">llvm::SCEV::isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>.</p>

</div>
</div>

### calculateShufflevectorMask() {#aa9f28186f9e231cea3f08c0b623129f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; int &gt; calculateShufflevectorMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a shufflevector mask which is used to vectorize shufflevectors e.g., %5 = shufflevector &lt;8 x i16&gt; %3, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 0, i32 1, i32 2, i32 3&gt; %6 = shufflevector &lt;8 x i16&gt; %3, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 4, i32 5, i32 6, i32 7&gt; %7 = shufflevector &lt;8 x i16&gt; %4, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 0, i32 1, i32 2, i32 3&gt; %8 = shufflevector &lt;8 x i16&gt; %4, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 4, i32 5, i32 6, i32 7&gt; the result is &lt;0, 1, 2, 3, 12, 13, 14, 15, 16, 17, 18, 19, 28, 29, 30, 31&gt;</p></dd>
</dl>


<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="#a7f5e446b08fdb38a854b35dbab34bc0c">getShufflevectorNumGroups</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>.</p>

</div>
</div>

### checkTreeSizes() {#a7ce98f2299c58e68c25ff0f9a0108f3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkTreeSizes (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; unsigned, unsigned &gt; &gt; Sizes, bool First)</td>
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

<p>Checks if the quadratic mean deviation is less than 90% of the mean size.</p>

<p>Definition at line 18692 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>.</p>

</div>
</div>

### clusterSortPtrAccesses() {#a2d26c707fd7389b46ad98970d56faf24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool clusterSortPtrAccesses (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; BBs, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; SortedIndices)</td>
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



<p>Definition at line 5369 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#adbff8697d64e4ee139aa777b68999872">RecursionMaxDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a183245826b2f3e16c86e81e567db9b51">llvm::slpvectorizer::BoUpSLP::findPartiallyOrderedLoads</a>.</p>

</div>
</div>

### combineOrders() {#a4bbe053c13b73cf6ed1276f66b615fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void combineOrders (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; unsigned &gt; Order, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; SecondaryOrder)</td>
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



<p>Definition at line 5916 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a585f149dd8c344a40c53b1694d3161ed">llvm::SmallBitVector::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a2eb73a15ea2a5105bd2cec95863d7113">llvm::slpvectorizer::BoUpSLP::reorderBottomToTop</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>.</p>

</div>
</div>

### compareCmp() {#af5d61d0124d62ee38726acc83dcdc037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsCompatibility&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool compareCmp (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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

<p>Compare two cmp instructions.</p>


<p>If IsCompatibility is true, function returns true if 2 cmps have same/swapped predicates and mos compatible corresponding operands. If IsCompatibility is false, function implements strict weak ordering relation between two cmp instructions, returning true if the first instruction is "less" than the second, i.e. its predicate is less than the predicate of the second or the operands IDs are less than the operands IDs of the second cmp instruction.</p>


<p>Definition at line 21327 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a718717ee958956ec34ed177ef0b7f2ba">llvm::DomTreeNodeBase&lt; NodeT &gt;::getDFSNumIn</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ad8295b9b507d1d847cd46856f8255eab">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a9f382207d841377156d4c7868b66b9a5">llvm::Type::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac7b0ed5c6d30bad74769c6e87ab0edb8">llvm::Type::getTypeID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aa3ea54a95743867473d32853d3c65603">isValidElementType</a>.</p>

</div>
</div>

### computeCommonAlignment() {#ae06eb06e1d6ba6b5e8d319eef5d16280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align computeCommonAlignment (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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

<p>Calculates minimal alignment as a common alignment.</p>

<p>Definition at line 4809 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a44361e635fd7461e3a8eeb7fc9ad4f04">llvm::getAlign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>.</p>

</div>
</div>

### createExtractVector() {#ae3a4c284255a153d29ddcbd05bcf5345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * createExtractVector (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Vec, unsigned SubVecVF, unsigned Index)</td>
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

<p>Correctly creates extract_subvector, checking that the index is multiple of the subvectors length.</p>


<p>Otherwise, generates shuffle using <span class="doxyComputerOutput">Generator</span> or using default shuffle.</p>


<p>Definition at line 5010 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a102aafbf0ca4e05fa1620a24f797fcfb">llvm::IRBuilderBase::CreateExtractVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa226d30eebf99ef84a0c2b1afcfc98b2">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### createInsertVector() {#a3560dc2fa2aa91cd3ea182c6d6cd8030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * createInsertVector (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Vec, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt;)&gt; Generator={})</td>
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

<p>Correctly creates insert_subvector, checking that the index is multiple of the subvectors length.</p>


<p>Otherwise, generates shuffle using <span class="doxyComputerOutput">Generator</span> or using default shuffle.</p>


<p>Definition at line 4979 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### DEBUG\_COUNTER() {#ab55bb4ea2a7861858f599f46799ec73e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_COUNTER (VectorizedGraphs, "slp-vectorized", "Controls which SLP graphs should be vectorized.")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### doesInTreeUserNeedToExtract() {#a596e8b6e6b71f454b18f982f947e5e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool doesInTreeUserNeedToExtract (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Scalar, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UserInst, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if in-tree use also needs extract. This refers to possible scalar operand in vectorized instruction.</p></dd>
</dl>


<p>Definition at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a11c66d01880f53332fc7ad53f565b039">llvm::getVectorIntrinsicIDForCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a9a2e07f0b5ef19c59116913d4875a4e3">llvm::slpvectorizer::BoUpSLP::buildExternalUses</a>.</p>

</div>
</div>

### dumpOrder() {#a9fb7740f0fb6e5a825320f3c63df3263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void dumpOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a056d3cd46ef12f648e431fe9776451a1">BoUpSLP::OrdersType</a> &amp; Order)</td>
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



<p>Definition at line 6734 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### findBuildAggregate() {#a296bc5fd6767824b2baf15675296743f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool findBuildAggregate (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * LastInsertInst, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; BuildVectorOpds, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; InsertElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp">BoUpSLP</a> &amp; R)</td>
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

<p>Recognize construction of vectors like ra = insertelement &lt;4 x float&gt; poison, float s0, i32 0 rb = insertelement &lt;4 x float&gt; ra, float s1, i32 1 rc = insertelement &lt;4 x float&gt; rb, float s2, i32 2 rd = insertelement &lt;4 x float&gt; rc, float s3, i32 3 starting from the last insertelement or insertvalue instruction.</p>


<p>Also recognize homogeneous aggregates like {&lt;2 x float&gt;, &lt;2 x float&gt;}, {{float, float}, {float, float}}, [2 x {float, float}] and so on. See llvm/test/Transforms/SLPVectorizer/X86/pr42022.ll for examples.</p>


<p>Assume LastInsertInst is of <a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a> or <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">InsertValueInst</a> type.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it matches.</p></dd>
</dl>


<p>Definition at line 20903 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60a348350395aef11d68f58111bcf499">llvm::erase</a>, <a href="#a3c995d3af67d9f0024160f8480989563">findBuildAggregate_rec</a>, <a href="#ad7d5504ae0acaa8a22f450dceccae9b5">getAggregateSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### findBuildAggregate\_rec() {#a3c995d3af67d9f0024160f8480989563}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void findBuildAggregate_rec (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * LastInsertInst, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; BuildVectorOpds, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; InsertElts, unsigned OperandOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp">BoUpSLP</a> &amp; R)</td>
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



<p>Definition at line 20864 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a3c995d3af67d9f0024160f8480989563">findBuildAggregate_rec</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a296bc5fd6767824b2baf15675296743f">findBuildAggregate</a> and <a href="#a3c995d3af67d9f0024160f8480989563">findBuildAggregate_rec</a>.</p>

</div>
</div>

### fixupOrderingIndices() {#ae203ebf95f0711b6d63e3672baeaf669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fixupOrderingIndices (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; unsigned &gt; Order)</td>
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

<p>Order may have elements assigned special value (size) which is out of bounds.</p>


<p>Such indices only appear on places which correspond to undef values (see canReuseExtract for details) and used in order to avoid undef values have effect on operands ordering. The first loop below simply finds all unused indices and then the next loop nest assigns these indices for undef values positions. As an example below Order has two undef positions and they have assigned values 3 and 7 respectively: before: 6 9 5 4 9 2 1 0 after: 6 3 5 4 7 2 1 0</p>


<p>Definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#ae0307ad5c950df7f6fb56dc8326184ce">llvm::SmallBitVector::count</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a12297e7775aa1fc62fbea882aef623fc">llvm::SmallBitVector::find_first</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a823f7f9343d9bb1e02104ae3b2d3edb9">llvm::SmallBitVector::find_next</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#af66ea412504abedf84eebd3a5c744bd8">llvm::SmallBitVector::none</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#af1232d0679de538d35381496f43e303a">llvm::SmallBitVector::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a2eb73a15ea2a5105bd2cec95863d7113">llvm::slpvectorizer::BoUpSLP::reorderBottomToTop</a>, <a href="#a633db91afb11db086004de9e3eb37217">reorderOrder</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>.</p>

</div>
</div>

### gatherPossiblyVectorizableLoads() {#a9e4f7b81913ac2176cac1eaa2b66a0b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void gatherPossiblyVectorizableLoads (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp">BoUpSLP</a> &amp; R, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *, int &gt; &gt; &gt; &amp; GatheredLoads, bool AddNew=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Tries to find subvector of loads and builds new vector of only loads if can be profitable.</p>

<p>Definition at line 6789 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cc11b26432f9343b3c532f06171ad04">llvm::bit_ceil</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#afebe38e4f4ade382a8e857b27cd990a2">llvm::SetVector&lt; T, Vector, Set, N &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#ae04ad615dfdd885e85cbddda146787c6">llvm::SmallSet&lt; T, N, C &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="#a9df55d50aee24118cfdc34ecb32db484">getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="#aa3ea54a95743867473d32853d3c65603">isValidElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#adbff8697d64e4ee139aa777b68999872">RecursionMaxDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>.</p>

</div>
</div>

### generateKeySubkey() {#a81425fa662eac9cc9cd5d21f1c66695e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; size_t, size_t &gt; generateKeySubkey (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a>(size_t, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *)&gt; LoadsSubkeyGenerator, bool AllowAlternate)</td>
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

<p>Generates key/subkey pair for the given value to provide effective sorting of the values and better detection of the vectorizable values sequences.</p>


<p>The keys/subkeys can be used for better sorting of the values themselves (keys) and in values subgroups (subkeys).</p>


<p>Definition at line 7417 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a8cfcd92a373cdd7deefb939dd76b83e3">llvm::SmallBitVector::all</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/vfdatabase/#ab3e99bee894f145998d620d3d2a2f900">llvm::VFDatabase::getMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c66d01880f53332fc7ad53f565b039">llvm::getVectorIntrinsicIDForCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af9c2825ab53adf1bf8c9fa19ec89d986">llvm::Instruction::isIntDivRem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb65ce026673a69aac75e5a7a26007b3">llvm::isTriviallyVectorizable</a>, <a href="#ac396bb87eb4db1dd3ce315e4d91ee2de">isUndefVector</a>, <a href="#a8f3292dcaad99569501ace7909f2ccf0">isValidForAlternation</a> and <a href="#a06a9edb69d0ed6fda201d59948acfd89">isVectorLikeInstWithConstOps</a>.</p>


<p>Referenced by <a href="#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>.</p>

</div>
</div>

### getAggregateSize() {#ad7d5504ae0acaa8a22f450dceccae9b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; getAggregateSize (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertInst)</td>
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



<p>Definition at line 20836 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5f6edc5246188225b3f49bd5c974c759">llvm::Type::isSingleValueType</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>.</p>


<p>Referenced by <a href="#a296bc5fd6767824b2baf15675296743f">findBuildAggregate</a>.</p>

</div>
</div>

### getAltInstrMask() {#a4617b6f7b2916249d12f30bc81a17855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector getAltInstrMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, unsigned Opcode0, unsigned Opcode1)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a bitset for selecting opcodes. false for Opcode0 and true for Opcode1.</p></dd>
</dl>


<p>Definition at line 1212 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/instructionsstate/#a7db7259747f6de85c6d0f47c26a5e3c6">anonymous{SLPVectorizer.cpp}::InstructionsState::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>.</p>

</div>
</div>

### getElementIndex() {#a77fa69a2017071ea8148d68badf475d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; getElementIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Inst, unsigned Offset=0)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>inserting or extracting index of InsertElement, ExtractElement or InsertValue instruction, using Offset as base offset for index.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if the index is not an immediate.</p></dd>
</dl>


<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#adb57ca02be42b4c1e078def74670fb93">getInsertExtractIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getExtractIndex() {#a992052c8e8463f5d055c79ca8abb9521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; getExtractIndex (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * E)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if Extract{<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>,Element} instruction extracts element Idx.</p></dd>
</dl>


<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>.</p>

</div>
</div>

### getFloorFullVectorNumberOfElements() {#abd93b259f88f77258d2428448d9f8032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getFloorFullVectorNumberOfElements (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Sz)</td>
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

<p>Returns the number of elements of the given type <span class="doxyComputerOutput">Ty</span>, not greater than <span class="doxyComputerOutput">Sz</span>, which forms type, which splits by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a></span> into whole vector types during legalization.</p>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4cc11b26432f9343b3c532f06171ad04">llvm::bit_ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae22967d11b695d268992470debfae4b2">llvm::bit_floor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a> and <a href="#aa3ea54a95743867473d32853d3c65603">isValidElementType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### getFullVectorNumberOfElements() {#a64f2ea425bfb988422fc240db77cf946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getFullVectorNumberOfElements (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Sz)</td>
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

<p>Returns the number of elements of the given type <span class="doxyComputerOutput">Ty</span>, not less than <span class="doxyComputerOutput">Sz</span>, which forms type, which splits by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a></span> into whole vector types during legalization.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4cc11b26432f9343b3c532f06171ad04">llvm::bit_ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a> and <a href="#aa3ea54a95743867473d32853d3c65603">isValidElementType</a>.</p>

</div>
</div>

### getGEPCosts() {#ac10dff634cacc4be44046af5ee45f92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; InstructionCost, InstructionCost &gt; getGEPCosts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Ptrs, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BasePtr, unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarTy, <a href="/web-llvm/docs/api/classes/vectortype">VectorType</a> * VecTy)</td>
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

<p>Calculate the scalar and the vector costs from vectorizing set of GEPs.</p>

<p>Definition at line 9521 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>.</p>

</div>
</div>

### getInsertExtractIndex() {#adb57ca02be42b4c1e078def74670fb93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; getInsertExtractIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Inst, unsigned Offset)</td>
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



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a77fa69a2017071ea8148d68badf475d1">getElementIndex</a>.</p>

</div>
</div>

### getLocation() {#aae9f536130472bd3fbdd23c3d4486b3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocation getLocation (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> location that is being access by the instruction.</p></dd>
</dl>


<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getNonPhiOperand() {#aedf33b25adbec09e3d48e920bbcfe34a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * getNonPhiOperand (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi)</td>
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

<p><span class="doxyComputerOutput">Returns</span> the first operand of <span class="doxyComputerOutput">I</span> that does not match <span class="doxyComputerOutput">Phi</span>.</p>


<p>If operand is not an instruction it returns nullptr.</p>


<p>Definition at line 21027 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ad3a526067810066884b7bb20ad94dcde">matchRdxBop</a>.</p>

</div>
</div>

### getNumElements() {#a2f1d58ac35de4475017aca6c5bda6d44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getNumElements (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the number of elements for Ty.</p></dd>
</dl>


<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a55bde2ba6aacac745a29a7e50c6be007">llvm::MachineIRBuilder::buildSplatBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7032e1ab44275cf7331a7898a3713aad">llvm::slpvectorizer::BoUpSLP::computeMinimumValueSizes</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#aae7bcd5b9d58b7641cac20c16ef38306">containsUndefinedElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ace7e2f01b65afba76343f22d042a12df">CreateGCRelocates</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ae2198d73f3c2de2cee53f3d15db39abe">expandAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a505ddaadef479f2d0c0810c203000eaa">expandCrossIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ab26ebd710695202964347075355c501d">expandExpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a8be283da675a1b678e17fd283f14945c">expandLogIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a604f6e897606d25237935a3374fe7a3e">extractVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/initializerbuilder/#abb4311f92fffab12cf33d0aa638f944e">anonymous{AArch64StackTagging.cpp}::InitializerBuilder::flatten</a>, <a href="#a4617b6f7b2916249d12f30bc81a17855">getAltInstrMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aad5def33faf75944be159808071d9698">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a9ab346ad59b02578a3fc143c77397761">llvm::PPCTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2e6c50683f73779b6b83effaf07ca30">llvm::getNumberOfParts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#aa5453e30640ec93e948873506385608f">llvm::X86TTIImpl::getScalarizationOverhead</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a694f0a06fb32a28862ef184803eaadd8">llvm::SystemZTTIImpl::getVectorTruncCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a330cf3a6980af7480c8de1c2dd643769">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::getVF</a>, <a href="#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a75cf62ffe10261611bab4d74598ab0e4">insertVector</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9e49f6fa199d88e91bf282cf91e34740">llvm::X86TTIImpl::isLegalMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4d641f1bb211aeafa37ac31552b04cb5">llvm::X86TTIImpl::isLegalMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a4679b8d3496374b0f0fead1b778f99a2">llvm::ShuffleVectorInst::isValidOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab4c31035e44c7bda618eb2eb81dcf314">isVectorPromotionViableForSlice</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#ad69716246dabb743839cafceb902ef46">llvm::RewriteStatepointsForGC::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>.</p>

</div>
</div>

### getNumElems() {#a3b9e7c9e471d8a5babf5b80f50029b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getNumElems (unsigned Size, unsigned PartNumElems, unsigned Part)</td>
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

<p>Returns correct remaining number of elements, considering total amount <span class="doxyComputerOutput">Size</span>, (power-of-2 number) of elements in a single register <span class="doxyComputerOutput">PartNumElems</span> and current register (part) <span class="doxyComputerOutput">Part</span>.</p>

<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>.</p>

</div>
</div>

### getPartNumElems() {#a74addefa3085903bdce006cd86cb2a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPartNumElems (unsigned Size, unsigned NumParts)</td>
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

<p>Returns power-of-2 number of elements in a single register (part), given the total number of elements <span class="doxyComputerOutput">Size</span> and number of registers (parts) <span class="doxyComputerOutput">NumParts</span>.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4cc11b26432f9343b3c532f06171ad04">llvm::bit_ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#ad9982431e49e2d23ded133fcb20f8f98">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::add</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a551b374dc91637e6406a55d9ebea95ca">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::add</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>.</p>

</div>
</div>

### getRdxKind() {#ad281a65c549980abb2d08fc3973df2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurKind getRdxKind (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Gets recurrence kind from the specified value.</p>

<p>Definition at line 20833 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a842f13add9ede73561cdbad22101b255">anonymous{SLPVectorizer.cpp}::HorizontalReduction::getRdxKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>.</p>

</div>
</div>

### getReductionInstr() {#aa898a031df90bb6ac31dc9cb253b310e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * getReductionInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * P, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ParentBB, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI)</td>
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

<p>Try and get a reduction instruction from a phi node.</p>


<p>Given a phi node <span class="doxyComputerOutput">P</span> in a block <span class="doxyComputerOutput">ParentBB</span>, consider possible reductions if they come from either <span class="doxyComputerOutput">ParentBB</span> or a containing loop latch.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>A candidate reduction value if possible, or</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">nullptr </span></span></div>

</div>


<p>if not possible.</p>
</dd>
</dl>


<p>Definition at line 20939 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getSameOpcode() {#acb2c6a8dafac1cdf8927e67b28baab1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionsState getSameOpcode (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>analysis of the Instructions in <span class="doxyComputerOutput">VL</span> described in <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/instructionsstate">InstructionsState</a>, the Opcode that we suppose the whole list could be vectorized even if its structure is diverse.</p></dd>
</dl>


<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#afebe38e4f4ade382a8e857b27cd990a2">llvm::SetVector&lt; T, Vector, Set, N &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a7a21e7face454c8ea6c4b9e12b506e40">llvm::CallBase::getBundleOperandsStartIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/vfdatabase/#ab3e99bee894f145998d620d3d2a2f900">llvm::VFDatabase::getMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c66d01880f53332fc7ad53f565b039">llvm::getVectorIntrinsicIDForCall</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aecc0c27ae96638bc9d8fa4caffa92c31">llvm::CallBase::hasOperandBundles</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/instructionsstate/#a0bf29d49efe73cc6ef80fc4f139047e7">anonymous{SLPVectorizer.cpp}::InstructionsState::InstructionsState</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/instructionsstate/#aa41895bee309e6f2ca245800c5809527">anonymous{SLPVectorizer.cpp}::InstructionsState::invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="#a807bb3d2ecc2999993a91d499bd26543">isCmpSameOrSwapped</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb65ce026673a69aac75e5a7a26007b3">llvm::isTriviallyVectorizable</a>, <a href="#a8f3292dcaad99569501ace7909f2ccf0">isValidForAlternation</a>, <a href="#a06a9edb69d0ed6fda201d59948acfd89">isVectorLikeInstWithConstOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b5301a03dc90d7ac00440e2de4d9149">llvm::iterator_range</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a321240b67a372a24d41687f6a2e96877">areCompatibleCmpOps</a>, <a href="#abf8c65a150fe96c228db5b19d6b09e3a">arePointersCompatible</a>, <a href="#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a266c328585c72cd84dc48ef488acef49">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getShallowScore</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#ab3635230226f6d60dad04b8e83d848fd">llvm::slpvectorizer::BoUpSLP::VLOperands::reorder</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### getShuffleCost() {#a3c4c7b26972597220296eab6450669b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost getShuffleCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ec">TTI::ShuffleKind</a> Kind, <a href="/web-llvm/docs/api/classes/vectortype">VectorType</a> * Tp, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask={}, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bb">TTI::TargetCostKind</a> CostKind=TTI::TCK_RecipThroughput, int Index=0, <a href="/web-llvm/docs/api/classes/vectortype">VectorType</a> * SubTp=nullptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args={})</td>
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

<p>Returns the cost of the shuffle instructions with the given <span class="doxyComputerOutput">Kind</span>, vector type <span class="doxyComputerOutput">Tp</span> and optional <span class="doxyComputerOutput">Mask</span>.</p>


<p>Adds SLP-specifc cost estimation for insert subvector pattern.</p>


<p>Definition at line 4955 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>.</p>

</div>
</div>

### getShufflevectorNumGroups() {#a7f5e446b08fdb38a854b35dbab34bc0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getShufflevectorNumGroups (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>the number of groups of shufflevector A group has the following features</p>


<ol class="doxyList" type="1">
<li>All of value in a group are shufflevector.</li>
<li>The mask of all shufflevector is isExtractSubvectorMask.</li>
<li>The mask of all shufflevector uses all of the elements of the source. e.g., it is 1 group (%0) %1 = shufflevector &lt;16 x i8&gt; %0, &lt;16 x i8&gt; poison, &lt;8 x i32&gt; &lt;i32 0, i32 1, i32 2, i32 3, i32 4, i32 5, i32 6, i32 7&gt; %2 = shufflevector &lt;16 x i8&gt; %0, &lt;16 x i8&gt; poison, &lt;8 x i32&gt; &lt;i32 8, i32 9, i32 10, i32 11, i32 12, i32 13, i32 14, i32 15&gt; it is 2 groups (%3 and %4) %5 = shufflevector &lt;8 x i16&gt; %3, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 0, i32 1, i32 2, i32 3&gt; %6 = shufflevector &lt;8 x i16&gt; %3, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 4, i32 5, i32 6, i32 7&gt; %7 = shufflevector &lt;8 x i16&gt; %4, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 0, i32 1, i32 2, i32 3&gt; %8 = shufflevector &lt;8 x i16&gt; %4, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 4, i32 5, i32 6, i32 7&gt; it is 0 group %12 = shufflevector &lt;8 x i16&gt; %10, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 0, i32 1, i32 2, i32 3&gt; %13 = shufflevector &lt;8 x i16&gt; %11, &lt;8 x i16&gt; poison, &lt;4 x i32&gt; &lt;i32 0, i32 1, i32 2, i32 3&gt;</li>
</ol>
</dd>
</dl>


<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a8cfcd92a373cdd7deefb939dd76b83e3">llvm::SmallBitVector::all</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>.</p>


<p>Referenced by <a href="#aa9f28186f9e231cea3f08c0b623129f4">calculateShufflevectorMask</a>.</p>

</div>
</div>

### getValueType() {#a9df55d50aee24118cfdc34ecb32db484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * getValueType (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Returns the type of the given value/instruction <span class="doxyComputerOutput">V</span>.</p>


<p>If it is store, returns the type of its value operand, for Cmp - the types of the compare operands and for insertelement - the type os the inserted operand. Otherwise, just the type of the value is returned.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#addec051710bc0afc4147859062eb31a4">CollectOpsToWiden</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acd51098a84aa870fd12ee3f5c31961af">combineArithReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaef2336d9f0305e57b22c5be16c73caa">combineMulToPMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7af5f6d50f3be3168a1d91d056c78c8c">combineToHorizontalAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600isellowering-cpp/#ad9e1097d647444e0c961dcd323944ff9">CompactSwizzlableVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0841165650bd49aa4995c4dfa3fdf650">detectPMADDUBSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#adc81cc844c6c6c32c8be216807aa54f5">FoldBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aacaef610100337e738457d3788cb0be8">foldCONCAT_VECTORS</a>, <a href="#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a77912b33da00edf1cb4143f66890519b">llvm::RISCVTTIImpl::getIntImmCostInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad53162a9cc816e1dcb3141b9b175cc36">getTestBitOperand</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantglobals/#ga67eb1005ab6e286927090875eefb4e5d">LLVMGlobalGetValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f5195509d89464589e673074691103a">matchPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a309d56d62904382ce197ab216f4ec43f">narrowVectorSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/resultstack/#a314645887ef1a5da942974d16ff180a4">anonymous{HexagonISelDAGToDAGHVX.cpp}::ResultStack::ResultStack</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a987ea3641182dca7a7d5ceddd248f045">llvm::SelectionDAGISel::SelectInlineAsmMemoryOperands</a>.</p>

</div>
</div>

### getVectorCallCosts() {#a8a8b818a539c2cbbe1a954a875c5fcec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; InstructionCost, InstructionCost &gt; getVectorCallCosts (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> * VecTy, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; ArgTys)</td>
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



<p>Definition at line 9039 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/vfshape/#aacd1691cd95a1e3e538fcee4c2cc8d05">llvm::VFShape::get</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#a1893caf878859959ba6a3d5442ef1439">llvm::FixedVectorType::getNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c66d01880f53332fc7ad53f565b039">llvm::getVectorIntrinsicIDForCall</a>, <a href="/web-llvm/docs/api/groups/vfdatabase/#ga27014498d4eea7c1e7455cc33538ca2b">llvm::VFDatabase::getVectorizedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a1fb374eb65dcf7cd3d1671efb2616f76">llvm::CallBase::isNoBuiltin</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a>.</p>

</div>
</div>

### getWidenedType() {#a065bd87e0b855701cd8ca61aa05d4c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * getWidenedType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarTy, unsigned VF)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the vector type of ScalarTy based on vectorization factor.</p></dd>
</dl>


<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#ad9982431e49e2d23ded133fcb20f8f98">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::add</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a551b374dc91637e6406a55d9ebea95ca">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::add</a>, <a href="#a9875dff9496a8c83bc0bcf749858c45b">buildIntrinsicArgTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aac9cfeffe904936120849defcaa5afbc">llvm::slpvectorizer::BoUpSLP::canMapToVector</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7032e1ab44275cf7331a7898a3713aad">llvm::slpvectorizer::BoUpSLP::computeMinimumValueSizes</a>, <a href="#ae3a4c284255a153d29ddcbd05bcf5345">createExtractVector</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="#abd93b259f88f77258d2428448d9f8032">getFloorFullVectorNumberOfElements</a>, <a href="#a64f2ea425bfb988422fc240db77cf946">getFullVectorNumberOfElements</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#adac504434993ab1673128914746eef47">llvm::slpvectorizer::BoUpSLP::getReductionType</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a266c328585c72cd84dc48ef488acef49">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getShallowScore</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aee3b49d7f15550d64c7db0e29a124c6d">llvm::slpvectorizer::BoUpSLP::getSpillCost</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d6443d726d7d8cdb827119e6f8f7819">llvm::hasFullVectorsOrPowerOf2</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa054ca3a90996e96887be015cf288270">llvm::slpvectorizer::BoUpSLP::isTreeTinyAndNotFullyVectorizable</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#a4055f1bab55c76c243c3bf42c1a7e45a">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::needToDelay</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### isAlternateInstruction() {#afb636ad432c97f9178ff3f966e93d819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAlternateInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MainOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * AltOp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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

<p>Checks if the specified instruction <span class="doxyComputerOutput">I</span> is an alternate operation for the given <span class="doxyComputerOutput">MainOp</span> and <span class="doxyComputerOutput">AltOp</span> instructions.</p>

<p>Definition at line 9101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a807bb3d2ecc2999993a91d499bd26543">isCmpSameOrSwapped</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### isCmpSameOrSwapped() {#a807bb3d2ecc2999993a91d499bd26543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCmpSameOrSwapped (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * BaseCI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if a compare instruction <span class="doxyComputerOutput">CI</span> has similar "look" and same predicate as <span class="doxyComputerOutput">BaseCI</span>, "as is" or with its operands and predicate swapped, false otherwise.</p></dd>
</dl>


<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="#a321240b67a372a24d41687f6a2e96877">areCompatibleCmpOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a> and <a href="#afb636ad432c97f9178ff3f966e93d819">isAlternateInstruction</a>.</p>

</div>
</div>

### isCommutative() {#ab0da56db6da27340e5a7151a4676106a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCommutative (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if <span class="doxyComputerOutput">I</span> is commutative, handles <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a>.</p></dd>
</dl>


<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a75df5de932994d1472ad3cda6a88cf21">UsesLimit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a54d9af6b4c656c782e017020406e8291">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getScoreAtLevelRec</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac399325c88de95b03c19e68e1229a8f7">llvm::FastISel::selectBinaryOp</a>.</p>

</div>
</div>

### isConstant() {#a6848b7e929178610d01e1b2b5052af86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstant (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the value is a constant (but not globals/constant expressions).</p></dd>
</dl>


<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a321240b67a372a24d41687f6a2e96877">areCompatibleCmpOps</a> and <a href="#a06a9edb69d0ed6fda201d59948acfd89">isVectorLikeInstWithConstOps</a>.</p>

</div>
</div>

### isFirstInsertElement() {#a405ff61e8571b58fecaa716540af108f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFirstInsertElement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a> * IE1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a> * IE2)</td>
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

<p>Checks if the <span class="doxyComputerOutput">IE1</span> instructions is followed by <span class="doxyComputerOutput">IE2</span> instruction in the buildvector sequence.</p>

<p>Definition at line 12306 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### isFixedVectorShuffle() {#ad5d72247c1a3137bc2c2c7aaf0000b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; TargetTransformInfo::ShuffleKind &gt; isFixedVectorShuffle (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC)</td>
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

<p>Checks if the vector of instructions can be represented as a shuffle, like: x0 = extractelement &lt;4 x i8&gt; x, i32 0 x3 = extractelement &lt;4 x i8&gt; x, i32 3 y1 = extractelement &lt;4 x i8&gt; y, i32 1 y2 = extractelement &lt;4 x i8&gt; y, i32 2 x0x0 = mul i8 x0, x0 x3x3 = mul i8 x3, x3 y1y1 = mul i8 y1, y1 y2y2 = mul i8 y2, y2 ins1 = insertelement &lt;4 x i8&gt; poison, i8 x0x0, i32 0 ins2 = insertelement &lt;4 x i8&gt; ins1, i8 x3x3, i32 1 ins3 = insertelement &lt;4 x i8&gt; ins2, i8 y1y1, i32 2 ins4 = insertelement &lt;4 x i8&gt; ins3, i8 y2y2, i32 3 ret &lt;4 x i8&gt; ins4 can be transformed into: %1 = shufflevector &lt;4 x i8&gt; x, &lt;4 x i8&gt; y, &lt;4 x i32&gt; &lt;i32 0, i32 3, i32 5, i32 6&gt; %2 = mul &lt;4 x i8&gt; %1, %1 ret &lt;4 x i8&gt; %2 Mask will return the Shuffle Mask equivalent to the extracted elements.</p>


<p>TODO: Can we split off and reuse the shuffle mask detection from ShuffleVectorInst/getShuffleCost?</p>


<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a873403a2506ac332f62ad4c2d7dc1835">llvm::all</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae058c4750de2c85f12a1f96841ac9ae3">llvm::isGuaranteedNotToBePoison</a>, <a href="#ac396bb87eb4db1dd3ce315e4d91ee2de">isUndefVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53eca7beec9815d0197f2d31fac9968e9205b">llvm::TargetTransformInfo::SK_PermuteSingleSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecab4616961a3bfdaec42aedc4fc426ccfe">llvm::TargetTransformInfo::SK_PermuteTwoSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53eca64d439485545faa793c20de7fbfd274c">llvm::TargetTransformInfo::SK_Select</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fa4e81c184ac3ad48a389cd4454c4a05bb">Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### isLoadCombineCandidateImpl() {#a0109582eb646d501101a7e6a059814fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLoadCombineCandidateImpl (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Root, unsigned NumElts, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, bool MustMatchOrInst)</td>
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



<p>Definition at line 12012 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac9e78b3aa02ec087c4621358f506718">llvm::PatternMatch::m_APInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6ba4022cd30993a84d111871dd0f6ba6">llvm::PatternMatch::m_ZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a49a7bbde7c622cc904ed4f8c1857cae6">llvm::slpvectorizer::BoUpSLP::isLoadCombineCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a541f9da09ec4756f94ba8de97508ad80">llvm::slpvectorizer::BoUpSLP::isLoadCombineReductionCandidate</a>.</p>

</div>
</div>

### isReductionCandidate() {#a7bd7a084a808c1f12f4cdc5e1a67aa70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isReductionCandidate (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>\Returns true if <span class="doxyComputerOutput">I</span> is a candidate instruction for reduction vectorization.</p>

<p>Definition at line 21036 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a5e8a1ef711294cc52d6e2c41279f4c0f">IsSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="#ad3a526067810066884b7bb20ad94dcde">matchRdxBop</a>.</p>

</div>
</div>

### isRepeatedNonIdentityClusteredMask() {#a0feeaece30961860a542ba8ee2a1f9f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRepeatedNonIdentityClusteredMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, unsigned Sz)</td>
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

<p>Checks if the given mask is a "clustered" mask with the same clusters of size <span class="doxyComputerOutput">Sz</span>, which are not identity submasks.</p>

<p>Definition at line 5876 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a81aa4ff7f63f7988abea1abbe9eb0342">llvm::ShuffleVectorInst::isIdentityMask</a>.</p>

</div>
</div>

### isReverseOrder() {#afa640d51b943ce0396e7131bf2352f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isReverseOrder (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Order)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Order</span> represents reverse order.</p>

<p>Definition at line 4817 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>.</p>

</div>
</div>

### isSimple() {#a3ca9742688618517cc4690fb947fb609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSimple (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the instruction is not a volatile or atomic load/store.</p></dd>
</dl>


<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a7c431da15318b73b5a0112e2d2d91f87">anonymous{DAGCombiner.cpp}::DAGCombiner::DAGCombiner</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-40c0487dcb3f4d8e14e777af1c8b8493/#a60d42be2ddfebc806754968fd9f76a5f">llvm::DOTGraphTraits&lt; const MachineFunction * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-538e36c252d953ff6ef6fdd090230f28/#a316ced7d2eb0e6d3714361713dfb1700">llvm::DOTGraphTraits&lt; DomTreeNode * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-55c8cb82503f51812ad190e425a6fd3d/#a965cbc8ca7a71e0b6b41e4b82c5beab1">llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-41c48be9c9012afa1dbd1bc6b52e29f7/#ae51532421a54cfa2c854595c71cb99b2">llvm::DOTGraphTraits&lt; DOTMachineFuncInfo * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-98588480f432ad6b5e85a9f166846cbf/#ae56d02d80b27a2c753565bf7da9ae566">llvm::DOTGraphTraits&lt; MachineBlockFrequencyInfo * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-a54b3e8998714e8c0ac78d7291bb6d5c/#a75697b62c0ea1d2ce77e6f470776395e">llvm::DOTGraphTraits&lt; RegionNode * &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a6ad23b58059ffd91df6a2dddf30c5d71">llvm::X86TargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa267be29b6ab02eda3ff34dd9c608b0c">tryToFoldExtOfMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo/#a0fffc1a69ef51a1f23e7e5026b7e5733">llvm::MachineBlockFrequencyInfo::view</a> and <a href="/web-llvm/docs/api/classes/llvm/mbfiwrapper/#ac751900508725abf9710c3081b08e5ca">llvm::MBFIWrapper::view</a>.</p>

</div>
</div>

### isSplat() {#a6ef5b86735d738868e5fb00a18643b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSplat (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if all of the values in <span class="doxyComputerOutput">VL</span> are identical or some of them are <a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a>.</p></dd>
</dl>


<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### isUndefVector() {#ac396bb87eb4db1dd3ce315e4d91ee2de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsPoisonOnly = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallBitVector isUndefVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallbitvector">SmallBitVector</a> &amp; UseMask={})</td>
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

<p>Checks if the given value is actually an undefined constant vector.</p>


<p>Also, if the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/anonymous-slpvectorizer-cpp-/#a600545eb53de812fc4daae8ecb72199d">UseMask</a></span> is not empty, tries to check if the non-masked elements actually mask the insertelement buildvector, if any.</p>


<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>, <a href="#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a266c328585c72cd84dc48ef488acef49">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getShallowScore</a>, <a href="#ad5d72247c1a3137bc2c2c7aaf0000b03">isFixedVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a047b7995a79492824633a62540717492">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::peekThroughShuffles</a> and <a href="#a67399cd92cbad7bcf7d0fbe417f779ec">performExtractsShuffleAction</a>.</p>

</div>
</div>

### isValidElementType() {#aa3ea54a95743867473d32853d3c65603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidElementType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> for the element types that the SLP vectorizer supports.</p>


<p>The most important thing to filter here are types which are invalid in LLVM vectors. We also filter target specific types which have absolutely no meaningful vectorization path such as x86_fp80 and ppc_f128. This just avoids spending time checking the cost model and realizing that they will be inevitably scalarized.</p>


<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa6a2194fc011669faabe43322d7c6c5f">llvm::VectorType::isValidElementType</a> and <a href="#a8b6f16f98498a168902dd2d5cd8f9462">SLPReVec</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aac9cfeffe904936120849defcaa5afbc">llvm::slpvectorizer::BoUpSLP::canMapToVector</a>, <a href="#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="#abd93b259f88f77258d2428448d9f8032">getFloorFullVectorNumberOfElements</a>, <a href="#a64f2ea425bfb988422fc240db77cf946">getFullVectorNumberOfElements</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a266c328585c72cd84dc48ef488acef49">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getShallowScore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d6443d726d7d8cdb827119e6f8f7819">llvm::hasFullVectorsOrPowerOf2</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>.</p>

</div>
</div>

### isValidForAlternation() {#a8f3292dcaad99569501ace7909f2ccf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidForAlternation (unsigned Opcode)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">Opcode</span> is allowed as part of the main/alternate instruction for SLP vectorization.</p></dd>
</dl>


<p>Example of unsupported opcode is SDIV that can potentially cause UB if the "shuffled out" lane would result in division by zero.</p>


<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#af9c2825ab53adf1bf8c9fa19ec89d986">llvm::Instruction::isIntDivRem</a>.</p>


<p>Referenced by <a href="#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a> and <a href="#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>.</p>

</div>
</div>

### isVectorLikeInstWithConstOps() {#a06a9edb69d0ed6fda201d59948acfd89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isVectorLikeInstWithConstOps (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Checks if <span class="doxyComputerOutput">V</span> is one of vector-like instructions, i.e.</p>


<p>undef, insertelement/extractelement with constant indices for fixed vector type or extractvalue instruction.</p>


<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a6848b7e929178610d01e1b2b5052af86">isConstant</a>.</p>


<p>Referenced by <a href="#abd5114d6b451e9ca85a36fc3f19f76c4">allSameBlock</a>, <a href="#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a>, <a href="#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### matchRdxBop() {#ad3a526067810066884b7bb20ad94dcde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchRdxBop (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; V1)</td>
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



<p>Definition at line 20983 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0698afabe907d2d3b87889d2e0349d47">llvm::PatternMatch::m_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#aedf33b25adbec09e3d48e920bbcfe34a">getNonPhiOperand</a> and <a href="#a7bd7a084a808c1f12f4cdc5e1a67aa70">isReductionCandidate</a>.</p>

</div>
</div>

### needToScheduleSingleInstruction() {#a2acd0e4598d1a9c34a8f2d9c9f98aaca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool needToScheduleSingleInstruction (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified list of values has only one instruction that requires scheduling, false otherwise.</p></dd>
</dl>


<p>Definition at line 7398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05a7412bf10f2226fb69f2876b76e9cd">llvm::doesNotNeedToBeScheduled</a>.</p>

</div>
</div>

### performExtractsShuffleAction() {#a67399cd92cbad7bcf7d0fbe417f779ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * performExtractsShuffleAction (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; std::pair&lt; T *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int &gt; &gt; &gt; ShuffleMask, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Base, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; unsigned(T *)&gt; GetVF, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; std::pair&lt; T *, bool &gt;(T *, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt;, bool)&gt; ResizeAction, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; T *(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt;, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T * &gt;)&gt; Action)</td>
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

<p>Does the analysis of the provided shuffle masks and performs the requested actions on the vectors with the given shuffle masks.</p>


<p>It tries to do it in several steps.</p>


<ol class="doxyList" type="1">
<li>If the Base vector is not undef vector, resizing the very first mask to have common VF and perform action for 2 input vectors (including non-undef Base). Other shuffle masks are combined with the resulting after the 1 stage and processed as a shuffle of 2 elements.</li>
<li>If the Base is undef vector and have only 1 shuffle mask, perform the action only for 1 vector with the given mask, if it is not the identity mask.</li>
<li>If &gt; 2 masks are used, perform the remaining shuffle actions for 2 vectors, combing the masks properly between the steps.</li>
</ol>

<p>Definition at line 12361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a8cfcd92a373cdd7deefb939dd76b83e3">llvm::SmallBitVector::all</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="#a2fd40bb67aec98438b791520159fb146">buildUseMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/anonymous-slpvectorizer-cpp-/valueselect/#a516904428a3b2e8421fe7c844a156ed3">anonymous{SLPVectorizer.cpp}::ValueSelect::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac396bb87eb4db1dd3ce315e4d91ee2de">isUndefVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a585f149dd8c344a40c53b1694d3161ed">llvm::SmallBitVector::test</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-slpvectorizer-cpp-/#a600545eb53de812fc4daae8ecb72199da3e1e09be16e530770bc81cd5f2b2edb9">anonymous{SLPVectorizer.cpp}::UndefsAsMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### propagateMetadata() {#ad9245aac1330cef52005ed7a9f789c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * propagateMetadata (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">I</span> after propagating metadata from <span class="doxyComputerOutput">VL</span> only for instructions in <span class="doxyComputerOutput">VL</span>.</p></dd>
</dl>


<p>Definition at line 15274 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48a6deb3e714d54e75caadcf84b0ca76">llvm::propagateMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### reorderOrder() {#a633db91afb11db086004de9e3eb37217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reorderOrder (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask, bool BottomOrder=false)</td>
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

<p>Reorders the given <span class="doxyComputerOutput">Order</span> according to the given <span class="doxyComputerOutput">Mask</span>.</p>


<p><span class="doxyComputerOutput">Order</span> - is the original order of the scalars. Procedure transforms the provided order in accordance with the given <span class="doxyComputerOutput">Mask</span>. If the resulting <span class="doxyComputerOutput">Order</span> is just an identity order, <span class="doxyComputerOutput">Order</span> is cleared.</p>


<p>Definition at line 4582 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f0917bf2ae18fac81fea6bf7e887115">llvm::inversePermutation</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a81aa4ff7f63f7988abea1abbe9eb0342">llvm::ShuffleVectorInst::isIdentityMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="#a4a3e80130d3f25468190ba343064b37e">reorderReuses</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a2eb73a15ea2a5105bd2cec95863d7113">llvm::slpvectorizer::BoUpSLP::reorderBottomToTop</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>.</p>

</div>
</div>

### reorderReuses() {#a4a3e80130d3f25468190ba343064b37e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reorderReuses (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Reuses, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
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

<p>Reorders the given <span class="doxyComputerOutput">Reuses</span> mask according to the given <span class="doxyComputerOutput">Mask</span>.</p>


<p><span class="doxyComputerOutput">Reuses</span> contains original mask for the scalars reused in the node. Procedure transform this mask in accordance with the given <span class="doxyComputerOutput">Mask</span>.</p>


<p>Definition at line 4568 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a2eb73a15ea2a5105bd2cec95863d7113">llvm::slpvectorizer::BoUpSLP::reorderBottomToTop</a> and <a href="#a633db91afb11db086004de9e3eb37217">reorderOrder</a>.</p>

</div>
</div>

### shortBundleName() {#a9f3bcb74818214fe1e8df656c52ab206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string shortBundleName (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, int Idx=-1)</td>
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

<p>Print a short descriptor of the instruction bundle suitable for debug output.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>.</p>

</div>
</div>

### STATISTIC() {#ae36ebcd8ea18a5e24ffe0c11fb9e965f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumVectorInstructions, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> generated")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### transformScalarShuffleIndiciesToVector() {#a8af0e2291ce043c892dc0c8d85cc81e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void transformScalarShuffleIndiciesToVector (unsigned VecTyNumElements, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99416758c13252bef45320a6ba6aa09c">llvm::MutableArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>.</p>

</div>
</div>

### tryGetSecondaryReductionRoot() {#ad25cdf8e7c874eae6f692b4319c6afe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * tryGetSecondaryReductionRoot (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Root)</td>
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

<p>We could have an initial reduction that is not an add.</p>


<p>r *= v1 + v2 + v3 + v4 In such a case start looking for a tree rooted in the first '+'. \Returns the new root if found, which may be nullptr if not an instruction.</p>


<p>Definition at line 21009 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a9a63158f073cdcf3696b623f1b8e0601">anonymous{SLPVectorizer.cpp}::HorizontalReduction::getFirstOperandIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### tryToVectorizeSequence() {#ac48731694e324e56e35cb2b4f20345d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryToVectorizeSequence (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; T * &gt; &amp; Incoming, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(T *, T *)&gt; Comparator, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(T *, T *)&gt; AreCompatible, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T * &gt;, bool)&gt; TryToVectorizeHelper, bool MaxVFOnly, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp">BoUpSLP</a> &amp; R)</td>
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



<p>Definition at line 21208 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AliasedCheckLimit {#a9d624115133c3a9ac3109be4be89a32f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned AliasedCheckLimit = 10</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### LookAheadMaxDepth {#a468123f1f142182cbdad8c20e98b64fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; LookAheadMaxDepth("slp-max-look-ahead-depth", cl::init(2), cl::Hidden, cl::desc("The maximum look-ahead depth for operand reordering scores"))</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### MaxMemDepDistance {#a4ce8fdf40e75ddf217650e2b1b15b5e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned MaxMemDepDistance = 160</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### MaxPHINumOperands {#a12a9c293de5315c98b1ff09bf30c26ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned MaxPHINumOperands = 128</td>
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

<p>Maximum allowed number of operands in the PHI nodes.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### MaxProfitableLoadStride {#a1ffea6d979c6f85d480c0f4187207058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxProfitableLoadStride("slp-max-stride", cl::init(8), cl::Hidden, cl::desc("The maximum stride, considered to be profitable."))</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>.</p>

</div>
</div>

### MaxVectorRegSizeOption {#a1ca809da394247bba762653f861875a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; MaxVectorRegSizeOption("slp-max-reg-size", cl::init(128), cl::Hidden, cl::desc("Attempt to vectorize for this register size in bits"))</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a8f40b270f64be7a9b63bc9cfb3b2977a">llvm::slpvectorizer::BoUpSLP::BoUpSLP</a>.</p>

</div>
</div>

### MaxVFOption {#a470e4a44fc1d069edcb7e3e0b6e7f014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxVFOption("slp-max-vf", cl::init(0), cl::Hidden, cl::desc("Maximum SLP vectorization factor (0=unlimited)"))</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a782cc6906561f01e563f30e50833235d">llvm::slpvectorizer::BoUpSLP::getMaximumVF</a>.</p>

</div>
</div>

### MinProfitableStridedLoads {#a3d9350d9f87e91559fd54f4e66190255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MinProfitableStridedLoads("slp-min-strided-loads", cl::init(2), cl::Hidden, cl::desc("The minimum number of loads, which should be considered strided, " "if the stride is &gt; 1 or is runtime value"))</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>.</p>

</div>
</div>

### MinScheduleRegionSize {#a3d78104bfada8d17dad04e588b7d9a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int MinScheduleRegionSize = 16</td>
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

<p>If the ScheduleRegionSizeBudget is exhausted, we allow small scheduling regions to be handled.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### MinTreeSize {#a630e10d123952904d5da8a02713d935a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MinTreeSize("slp-min-tree-size", cl::init(3), cl::Hidden, cl::desc("Only vectorize small trees if they are fully vectorizable"))</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa054ca3a90996e96887be015cf288270">llvm::slpvectorizer::BoUpSLP::isTreeTinyAndNotFullyVectorizable</a>.</p>

</div>
</div>

### MinVectorRegSizeOption {#ad4b62196a6175779b466b2e8f0e5cc12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; MinVectorRegSizeOption("slp-min-reg-size", cl::init(128), cl::Hidden, cl::desc("Attempt to vectorize for this register size in bits"))</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a8f40b270f64be7a9b63bc9cfb3b2977a">llvm::slpvectorizer::BoUpSLP::BoUpSLP</a>.</p>

</div>
</div>

### RecursionMaxDepth {#adbff8697d64e4ee139aa777b68999872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; RecursionMaxDepth("slp-recursion-max-depth", cl::init(12), cl::Hidden, cl::desc("Limit the recursion depth when building a vectorizable tree"))</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="#abf8c65a150fe96c228db5b19d6b09e3a">arePointersCompatible</a>, <a href="#a2d26c707fd7389b46ad98970d56faf24">clusterSortPtrAccesses</a>, <a href="#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a54f30c8bea3912d1d0f347626c395be6">llvm::slpvectorizer::BoUpSLP::getVectorElementSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>.</p>

</div>
</div>

### RootLookAheadMaxDepth {#a99e5e5bf957082c728b786a978a3b18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; RootLookAheadMaxDepth("slp-max-root-look-ahead-depth", cl::init(2), cl::Hidden, cl::desc("The maximum look-ahead depth for searching best rooting option"))</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af3dd2dd5c72b919c173c6bc31d7c3ac3">llvm::slpvectorizer::BoUpSLP::findBestRootPair</a>.</p>

</div>
</div>

### RunSLPVectorization {#a036e0a1db6c8bc87545585362e94b033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; RunSLPVectorization("vectorize-slp", cl::init(true), cl::Hidden, cl::desc("Run the SLP vectorization passes"))</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/slpvectorizerpass/#ad2e77c37d75ccdfcb7a3bc4fa8d58c85">llvm::SLPVectorizerPass::runImpl</a>.</p>

</div>
</div>

### ScheduleRegionSizeBudget {#acfadb82d555661f3a7010a5ff6778e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; ScheduleRegionSizeBudget("slp-schedule-budget", cl::init(100000), cl::Hidden, cl::desc("Limit the size of the SLP scheduling region per block"))</td>
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

<p>Limits the size of scheduling regions in a block.</p>


<p>It avoid long compile times for <em>very</em> large blocks where vector instructions are spread over a wide range. This limit is way higher than needed by real-world functions.</p>


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ShouldStartVectorizeHorAtStore {#a81dd3124ab70c150ac09a8bb9b921de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ShouldStartVectorizeHorAtStore("slp-vectorize-hor-store", cl::init(false), cl::Hidden, cl::desc( "Attempt to vectorize horizontal reductions feeding into a store"))</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ShouldVectorizeHor {#a67d4a829531287f2d81c7a306b52a4d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ShouldVectorizeHor("slp-vectorize-hor", cl::init(true), cl::Hidden, cl::desc("Attempt to vectorize horizontal reductions"))</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### SLPCostThreshold {#a704fbec676f53c0e32a778dcd57d21d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; SLPCostThreshold("slp-threshold", cl::init(0), cl::Hidden, cl::desc("Only vectorize if you gain more than this " "number "))</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa054ca3a90996e96887be015cf288270">llvm::slpvectorizer::BoUpSLP::isTreeTinyAndNotFullyVectorizable</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### SLPReVec {#a8b6f16f98498a168902dd2d5cd8f9462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SLPReVec("slp-revec", cl::init(false), cl::Hidden, cl::desc("Enable vectorization for wider vector utilization"))</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="#aa3ea54a95743867473d32853d3c65603">isValidElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### SLPSkipEarlyProfitabilityCheck {#a810249c0345682081378ebbda3b097d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SLPSkipEarlyProfitabilityCheck("slp-skip-early-profitability-check", cl::init(false), cl::Hidden, cl::desc("When true, SLP vectorizer bypasses profitability checks based on " "heuristics and makes vectorization decision via cost modeling."))</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### UsesLimit {#a75df5de932994d1472ad3cda6a88cf21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int UsesLimit = 64</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a9a2e07f0b5ef19c59116913d4875a4e3">llvm::slpvectorizer::BoUpSLP::buildExternalUses</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a266c328585c72cd84dc48ef488acef49">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getShallowScore</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="#ab0da56db6da27340e5a7151a4676106a">isCommutative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3097c66d0a4a009897e2ea77298a37f1">llvm::isUsedOutsideBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### VectorizeNonPowerOf2 {#a617fa15d11df5807cbc0e7191ff649d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; VectorizeNonPowerOf2("slp-vectorize-non-power-of-2", cl::init(false), cl::Hidden, cl::desc("Try to vectorize with non-power-of-2 number of elements."))</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a> and <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>.</p>

</div>
</div>

### ViewSLPTree {#a565c181d9f5686f1c52dee18510cb8a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewSLPTree("view-slp-tree", cl::Hidden, cl::desc("Display the SLP trees with Graphviz"))</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"SLP"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### SV\_NAME {#a274654b7f5932cae6a71a113322481be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SV_NAME&nbsp;&nbsp;&nbsp;"slp-vectorizer"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
