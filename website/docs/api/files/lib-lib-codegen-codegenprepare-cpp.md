---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/codegenprepare-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CodeGenPrepare.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/codegenprepare-h">llvm/CodeGen/CodeGenPrepare.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">llvm/ADT/PointerIntPair.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">llvm/Analysis/BranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/instructionsimplify-h">llvm/Analysis/InstructionSimplify.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/analysis-h">llvm/CodeGen/Analysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">llvm/CodeGen/BasicBlockSectionsProfileReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">llvm/CodeGen/ISDOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/machinevaluetype-h">llvm/CodeGenTypes/MachineValueType.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/getelementptrtypeiterator-h">llvm/IR/GetElementPtrTypeIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "llvm/IR/IntrinsicsAArch64.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/patternmatch-h">llvm/IR/PatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profdatautils-h">llvm/IR/ProfDataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/statepoint-h">llvm/IR/Statepoint.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">llvm/IR/ValueMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">llvm/Support/BlockFrequency.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">llvm/Support/BranchProbability.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/bypassslowdivision-h">llvm/Transforms/Utils/BypassSlowDivision.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/simplifylibcalls-h">llvm/Transforms/Utils/SimplifyLibCalls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sizeopts-h">llvm/Transforms/Utils/SizeOpts.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;limits&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-">anonymous{CodeGenPrepare.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare">CodeGenPrepare</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenpreparelegacypass">CodeGenPrepareLegacyPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode">ExtAddrMode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an extended version of TargetLowering::AddrMode which holds actual Value*'s for register values. <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class provides transaction based operation on the IR. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/typepromotionaction">TypePromotionAction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents the common interface of the individual transaction. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/typepromotionaction/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/insertionhandler">InsertionHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility to remember the position of an instruction. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/insertionhandler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/instructionmovebefore">InstructionMoveBefore</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move an instruction before another. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/instructionmovebefore/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/operandsetter">OperandSetter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the operand of an instruction with a new value. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/operandsetter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/operandshider">OperandsHider</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hide the operands of an instruction. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/operandshider/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/truncbuilder">TruncBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a truncate instruction. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/truncbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/sextbuilder">SExtBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a sign extension instruction. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/sextbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/zextbuilder">ZExtBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a zero extension instruction. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/zextbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/typemutator">TypeMutator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mutate an instruction to another type. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/typemutator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/usesreplacer">UsesReplacer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace the uses of an instruction by another instruction. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/usesreplacer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/typepromotiontransaction/usesreplacer/instructionandidx">InstructionAndIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper structure to keep track of the replaced uses. <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/typepromotiontransaction/usesreplacer/instructionandidx/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/instructionremover">InstructionRemover</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an instruction from the IR. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction/instructionremover/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/addressingmodematcher">AddressingModeMatcher</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper class for matching addressing modes. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/addressingmodematcher/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/phinodesetiterator">PhiNodeSetIterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An iterator for <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/phinodeset">PhiNodeSet</a>. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/phinodesetiterator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/phinodeset">PhiNodeSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps a set of PHINodes. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/phinodeset/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker">SimplificationTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of simplification of Phi nodes. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/addressingmodecombiner">AddressingModeCombiner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper class for combining addressing modes. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/addressingmodecombiner/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotionhelper">TypePromotionHelper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hepler class to perform type promotion. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotionhelper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/vectorpromotehelper">VectorPromoteHelper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class to promote a scalar operation to a vector one. <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/vectorpromotehelper/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6059e0984be477af12647e0574a01af0">STATISTIC</a> (NumBlocksElim, "Number of blocks eliminated")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa30f41b73332156614f88439d24da8ac">STATISTIC</a> (NumPHIsElim, "Number of trivial PHIs eliminated")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4aba4ac8014186037d27ffc57196ac3">STATISTIC</a> (NumGEPsElim, "Number of GEPs converted to casts")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac922eae769aaa3ee158e915f036129e4">STATISTIC</a> (NumCmpUses, "Number of uses of Cmp expressions replaced with uses of " "sunken Cmps")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09f1c42adaebc495651949c7d4e64c3c">STATISTIC</a> (NumCastUses, "Number of uses of Cast expressions replaced with uses " "of sunken Casts")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6853dee9da71b8737b7c731c505988d8">STATISTIC</a> (NumMemoryInsts, "Number of memory instructions whose address " "computations were sunk")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff39dc0be076dc904665065cf5c6ede2">STATISTIC</a> (NumMemoryInstsPhiCreated, "Number of phis created when address " "computations were sunk to memory instructions")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c487b469e600b10b65c400de3741735">STATISTIC</a> (NumMemoryInstsSelectCreated, "Number of select created when address " "computations were sunk to memory instructions")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382d2cdafa179d7c4561bfe746d2a4ad">STATISTIC</a> (NumExtsMoved, "Number of [s|z]ext instructions combined with loads")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c84a6266af376a7dc168db6dd0e1ce4">STATISTIC</a> (NumExtUses, "Number of uses of [s|z]ext instructions optimized")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc95b24e3dc47ccf0a7afcc846d82c34">STATISTIC</a> (NumAndsAdded, "Number of and mask instructions added to form ext loads")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf676a4c39b6a1c7019dbbec6fc89500">STATISTIC</a> (NumAndUses, "Number of uses of and mask instructions optimized")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05852bdf4c63ca1e5306e1422db248f3">STATISTIC</a> (NumRetsDup, "Number of return instructions duplicated")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8d62a4d9ff57ddca8ab070f4e396c0c">STATISTIC</a> (NumDbgValueMoved, "Number of debug value instructions moved")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5e95a01071c306a5fa9e6e3e07183c">STATISTIC</a> (NumSelectsExpanded, "Number of selects turned into branches")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4644887cd2ba8fba1a1c6f97d234e7e2">STATISTIC</a> (NumStoreExtractExposed, "Number of store(extractelement) exposed")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca449a7620b1306ed7586ba6bdc4faa">INITIALIZE_PASS_BEGIN</a> (CodeGenPrepareLegacyPass, DEBUG_TYPE, "Optimize for code generation", false, false) INITIALIZE_PASS_END(CodeGenPrepareLegacyPass</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e092ecf7889abf7277f13824e0c601">replaceAllUsesWith</a> (Value *Old, Value *New, SmallSet&lt; BasicBlock *, 32 &gt; &amp;FreshBBs, bool IsHuge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all old uses with new ones, and push the updated BBs into FreshBBs. <a href="#a19e092ecf7889abf7277f13824e0c601">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f5b32a03cc4a6072855d8c8cf7c748f">computeBaseDerivedRelocateMap</a> (const SmallVectorImpl&lt; GCRelocateInst * &gt; &amp;AllRelocateCalls, MapVector&lt; GCRelocateInst *, SmallVector&lt; GCRelocateInst *, 0 &gt; &gt; &amp;RelocateInstMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e431b29d5cd842ab00f85ec2cdab8b2">getGEPSmallConstantIntOffsetV</a> (GetElementPtrInst *GEP, SmallVectorImpl&lt; Value * &gt; &amp;OffsetV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9364799319bac519aa565ec882986e6d">simplifyRelocatesOffABase</a> (GCRelocateInst *RelocatedBase, const SmallVectorImpl&lt; GCRelocateInst * &gt; &amp;Targets)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a> (CastInst *CI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sink the specified cast instruction into its user blocks. <a href="#a3cc8a3a2506bf528398d0aef0850f31a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b82cff474790446f1288f1a086c1cd6">OptimizeNoopCopyExpression</a> (CastInst *CI, const TargetLowering &amp;TLI, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified cast instruction is a noop copy (e.g. <a href="#a3b82cff474790446f1288f1a086c1cd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f54e95337782bd4fb335dd547c05ecc">matchIncrement</a> (const Instruction *IVInc, Instruction *&amp;LHS, Constant *&amp;Step)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50cfddd4c98e75ef287c16996698dc1c">getIVIncrement</a> (const PHINode *PN, const LoopInfo *LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If given <span class="doxyComputerOutput">PN</span> is an inductive variable with value IVInc coming from the backedge, and on each iteration it gets increased by Step, return pair &lt;IVInc, Step&gt;. <a href="#a50cfddd4c98e75ef287c16996698dc1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f1e7b38e65d10c01900bd4d458a03b">isIVIncrement</a> (const Value *V, const LoopInfo *LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af23979229be4fb2286896bf920e3e235">matchUAddWithOverflowConstantEdgeCases</a> (CmpInst *Cmp, BinaryOperator *&amp;Add)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match special-case patterns that check for unsigned add overflow. <a href="#af23979229be4fb2286896bf920e3e235">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a3e4aad4cb2fdde7ce294a531cd52a">sinkCmpExpression</a> (CmpInst *Cmp, const TargetLowering &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sink the given <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> into user blocks to reduce the number of virtual registers that must be created and coalesced. <a href="#a24a3e4aad4cb2fdde7ce294a531cd52a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c59bcf49cb7343886e8f425d6d877b">foldICmpWithDominatingICmp</a> (CmpInst *Cmp, const TargetLowering &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For pattern like: <a href="#a98c59bcf49cb7343886e8f425d6d877b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fb33a8a29e076405285e5282eba81fd">swapICmpOperandsToExposeCSEOpportunities</a> (CmpInst *Cmp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Many architectures use the same instruction for both subtract and cmp. <a href="#a3fb33a8a29e076405285e5282eba81fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f580ab00002a65787ab52ef2aa9a439">foldFCmpToFPClassTest</a> (CmpInst *Cmp, const TargetLowering &amp;TLI, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf468add8b9e6811a1643026e25eadb4">isRemOfLoopIncrementWithLoopInvariant</a> (Instruction *Rem, const LoopInfo *LI, Value *&amp;RemAmtOut, Value *&amp;AddInstOut, Value *&amp;AddOffsetOut, PHINode *&amp;LoopIncrPNOut)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a> (Instruction *Rem, const DataLayout *DL, const LoopInfo *LI, SmallSet&lt; BasicBlock *, 32 &gt; &amp;FreshBBs, bool IsHuge)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6536b980547806c6fb158add5334c3ab">adjustIsPower2Test</a> (CmpInst *Cmp, const TargetLowering &amp;TLI, const TargetTransformInfo &amp;TTI, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some targets have better codegen for <span class="doxyComputerOutput">ctpop(X) u&lt; 2</span> than <span class="doxyComputerOutput">ctpop(X) == 1</span>. <a href="#a6536b980547806c6fb158add5334c3ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a> (Instruction *AndI, const TargetLowering &amp;TLI, SetOfInstrs &amp;InsertedInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Duplicate and sink the given 'and' instruction into user blocks where it is used in a compare to allow isel to generate better code for targets where this operation can be combined. <a href="#a0049977ff1075a98e9f512bbf4d181a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e2fd6fce422c4ab3cea555782abbb6">isExtractBitsCandidateUse</a> (Instruction *User)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the candidates could be combined with a shift instruction, which includes: <a href="#a19e2fd6fce422c4ab3cea555782abbb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a> (BinaryOperator *ShiftI, Instruction *User, ConstantInt *CI, DenseMap&lt; BasicBlock *, BinaryOperator * &gt; &amp;InsertedShifts, const TargetLowering &amp;TLI, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sink both shift and truncate instruction to the use of truncate's BB. <a href="#a0327169186859791aafa580e4fb547e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a> (BinaryOperator *ShiftI, ConstantInt *CI, const TargetLowering &amp;TLI, const DataLayout &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sink the shift <em>right</em> instruction into user blocks if the uses could potentially be combined with this shift instruction and generate BitExtract instruction. <a href="#a2c05548feac70b16d31caf0cfb225714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a> (IntrinsicInst *CountZeros, LoopInfo &amp;LI, const TargetLowering *TLI, const DataLayout *DL, ModifyDT &amp;ModifiedDT, SmallSet&lt; BasicBlock *, 32 &gt; &amp;FreshBBs, bool IsHugeFunc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If counting leading or trailing zeros is an expensive operation and a zero input is defined, add a check for zero to avoid calling the intrinsic. <a href="#adfad68845808cb6acd116e50b15bc281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87548c69480b23599d643d518412895c">isIntrinsicOrLFToBeTailCalled</a> (const TargetLibraryInfo *TLInfo, const CallInst *CI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d0372d5a469c089a4f2a299dd679558">MightBeFoldableInst</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a little filter, which returns true if an addressing computation involving I might be folded into a load/store accessing it. <a href="#a9d0372d5a469c089a4f2a299dd679558">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca87c42e8556b7f2e73454d63efa87f2">isPromotedInstructionLegal</a> (const TargetLowering &amp;TLI, const DataLayout &amp;DL, Value *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not <span class="doxyComputerOutput">Val</span> is a legal instruction for <span class="doxyComputerOutput">TLI</span>. <a href="#aca87c42e8556b7f2e73454d63efa87f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86026627b644e50527898aad0747b3e5">IsOperandAMemoryOperand</a> (CallInst *CI, InlineAsm *IA, Value *OpVal, const TargetLowering &amp;TLI, const TargetRegisterInfo &amp;TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if all uses of OpVal by the specified inline asm call are due to memory operands. <a href="#a86026627b644e50527898aad0747b3e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a498962c0029b14cf3cc8fb08c5e20ab2">FindAllMemoryUses</a> (Instruction *I, SmallVectorImpl&lt; std::pair&lt; Use *, Type * &gt; &gt; &amp;MemoryUses, SmallPtrSetImpl&lt; Instruction * &gt; &amp;ConsideredInsts, const TargetLowering &amp;TLI, const TargetRegisterInfo &amp;TRI, bool OptSize, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI, unsigned &amp;SeenInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively walk all the uses of I until we find a memory use. <a href="#a498962c0029b14cf3cc8fb08c5e20ab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0065098f13d0b2ef0e39f9d2e1ecdd">FindAllMemoryUses</a> (Instruction *I, SmallVectorImpl&lt; std::pair&lt; Use *, Type * &gt; &gt; &amp;MemoryUses, const TargetLowering &amp;TLI, const TargetRegisterInfo &amp;TRI, bool OptSize, ProfileSummaryInfo *PSI, BlockFrequencyInfo *BFI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad897d4beb50aa8f0d4d2eaa08ac0987d">IsNonLocalValue</a> (Value *V, BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified values are defined in a different basic block than BB. <a href="#ad897d4beb50aa8f0d4d2eaa08ac0987d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae965d93aa46ad834c21718eba4b5b78e">hasSameExtUse</a> (Value *Val, const TargetLowering &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if all the uses of <span class="doxyComputerOutput">Val</span> are equivalent (or free) zero or sign extensions. <a href="#ae965d93aa46ad834c21718eba4b5b78e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ece31d94cdd66e58cef49d73f2263f">sinkSelectOperand</a> (const TargetTransformInfo *TTI, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if V (an operand of a select instruction) is an expensive instruction that is only used once. <a href="#a10ece31d94cdd66e58cef49d73f2263f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bde686b6506cc9e63919272711713f4">isFormingBranchFromSelectProfitable</a> (const TargetTransformInfo *TTI, const TargetLowering *TLI, SelectInst *SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> should be turned into an explicit branch. <a href="#a4bde686b6506cc9e63919272711713f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596c5a8a807f6ce192718084a11648de">getTrueOrFalseValue</a> (SelectInst *SI, bool isTrue, const SmallPtrSet&lt; const Instruction *, 2 &gt; &amp;Selects)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">isTrue</span> is true, return the true value of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span>, otherwise return false value of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span>. <a href="#a596c5a8a807f6ce192718084a11648de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c7e1486d1d466b3be981adcb21a6359">splitMergedValStore</a> (StoreInst &amp;SI, const DataLayout &amp;DL, const TargetLowering &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the instruction sequence of store below, F and I values are bundled together as an i64 value before being stored into memory. <a href="#a3c7e1486d1d466b3be981adcb21a6359">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e586008202db1f802e906a489d7574">GEPSequentialConstIndexed</a> (GetElementPtrInst *GEP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8528dea79f0940669c4fcb751940ca94">tryUnmergingGEPsAcrossIndirectBr</a> (GetElementPtrInst *GEPI, const TargetTransformInfo *TTI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2bfc3e2f7b1661868517e662ac7496c">optimizeBranch</a> (BranchInst *Branch, const TargetLowering &amp;TLI, SmallSet&lt; BasicBlock *, 32 &gt; &amp;FreshBBs, bool IsHugeFunc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a43b0bc7c25aaaa14cf3d79d7f13c78">DbgInserterHelper</a> (DbgValueInst *DVI, BasicBlock::iterator VI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8803aa267830622708ede7b732c7ae2">DbgInserterHelper</a> (DbgVariableRecord *DVR, BasicBlock::iterator VI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c5d0cb41bbb1777e779a8da35e7bd4">scaleWeights</a> (uint64_t &amp;NewTrue, uint64_t &amp;NewFalse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scale down both weights to fit into uint32_t. <a href="#a25c5d0cb41bbb1777e779a8da35e7bd4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62cd718328addb93b7bfbfd788fa9c33">DisableBranchOpts</a>("disable-cgp-branch-opts", cl::Hidden, cl::init(false), cl::desc("Disable branch optimizations in CodeGenPrepare"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23f3d86779d204fbf6db71ce8f41d7b">DisableGCOpts</a>("disable-cgp-gc-opts", cl::Hidden, cl::init(false), cl::desc("Disable GC optimizations in CodeGenPrepare"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af42b66ae716b910d032498490940ae08">DisableSelectToBranch</a>("disable-cgp-select2branch", cl::Hidden, cl::init(false), cl::desc("Disable select to branch conversion."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5410093a9a86bd6e68eb3ffb32cbce13">AddrSinkUsingGEPs</a>("addr-sink-using-gep", cl::Hidden, cl::init(true), cl::desc("Address sinking in CGP using GEPs."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add2019bfb348f5241b4110eb77775410">EnableAndCmpSinking</a>("enable-andcmp-sinking", cl::Hidden, cl::init(true), cl::desc("Enable sinking and/cmp into branches."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6cf6a2bf01ee44a0f0843d8c3512cd">DisableStoreExtract</a>("disable-cgp-store-extract", cl::Hidden, cl::init(false), cl::desc("Disable store(extract) optimizations in CodeGenPrepare"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a686688e72eafe6375f8ae1ed184123">StressStoreExtract</a>("stress-cgp-store-extract", cl::Hidden, cl::init(false), cl::desc("Stress test store(extract) optimizations in CodeGenPrepare"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a337eb74e6c82771bb21ce598a8d3090c">DisableExtLdPromotion</a>("disable-cgp-ext-ld-promotion", cl::Hidden, cl::init(false), cl::desc("Disable ext(promotable(ld)) -> promoted(ext(ld)) optimization in " "CodeGenPrepare"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeabb375be2dc51a3d518b9d2a1140fe6">StressExtLdPromotion</a>("stress-cgp-ext-ld-promotion", cl::Hidden, cl::init(false), cl::desc("Stress test ext(promotable(ld)) -> promoted(ext(ld)) " "optimization in CodeGenPrepare"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346da4fb7a62e95531402c0b2a85c4fd">DisablePreheaderProtect</a>("disable-preheader-prot", cl::Hidden, cl::init(false), cl::desc("Disable protection against removing loop preheaders"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cdb6fbcff4780503fef226b46b6f10b">ProfileGuidedSectionPrefix</a>("profile-guided-section-prefix", cl::Hidden, cl::init(true), cl::desc("Use profile info to add section prefix for hot/cold functions"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a276112f96ea0d245fec9eaa1306712c0">ProfileUnknownInSpecialSection</a>("profile-unknown-in-special-section", cl::Hidden, cl::desc("In profiling mode like sampleFDO, if a function doesn't have " "profile, we cannot tell the function is cold for sure because " "it may be a function newly added without ever being sampled. " "With the flag enabled, compiler can put such profile unknown " "functions into a special section, so runtime system can choose " "to handle it in a different way than .text section, to save " "RAM for example. "))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaabb67aa574169b8cf2db8baf993b9ea">BBSectionsGuidedSectionPrefix</a>("bbsections-guided-section-prefix", cl::Hidden, cl::init(true), cl::desc("Use the basic-block-sections profile to determine the text " "section prefix for hot functions. Functions with " "basic-block-sections profile will be placed in `.text.hot` " "regardless of their FDO profile info. Other functions won't be " "impacted, i.e., their prefixes will be decided by FDO/sampleFDO " "profiles."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb1402a601e394cbb3a7b1a1c4e4634f">FreqRatioToSkipMerge</a>("cgp-freq-ratio-to-skip-merge", cl::Hidden, cl::init(2), cl::desc("Skip merging empty blocks if (frequency of empty block) / " "(frequency of destination block) is greater than this ratio"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac7126af5085fb735db4c727a0ab4e9">ForceSplitStore</a>("force-split-store", cl::Hidden, cl::init(false), cl::desc("Force store splitting no matter what the target query says."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6412f4a5842ffe108c2aa493fa0fe1b1">EnableTypePromotionMerge</a>("cgp-type-promotion-merge", cl::Hidden, cl::desc("Enable merging of redundant sexts when one is dominating" " the other."), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa653d45524ba8feb6e97dd4f961b7c3e">DisableComplexAddrModes</a>("disable-complex-addr-modes", cl::Hidden, cl::init(false), cl::desc("Disables combining addressing modes with different parts " "in optimizeMemoryInst."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afedfbc99c6b04e20643eb77da796d522">AddrSinkNewPhis</a>("addr-sink-new-phis", cl::Hidden, cl::init(false), cl::desc("Allow creation of Phis in Address sinking."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a732a4fb41e78c56627fb9748f00935ab">AddrSinkNewSelects</a>("addr-sink-new-select", cl::Hidden, cl::init(true), cl::desc("Allow creation of selects in Address sinking."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b23d217bd678cd7aef7d152d945537">AddrSinkCombineBaseReg</a>("addr-sink-combine-base-reg", cl::Hidden, cl::init(true), cl::desc("Allow combining of BaseReg field in Address sinking."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f303fd2cc8c48e50ab97c59f3558cc">AddrSinkCombineBaseGV</a>("addr-sink-combine-base-gv", cl::Hidden, cl::init(true), cl::desc("Allow combining of BaseGV field in Address sinking."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a00df51e1fa276c0c8860fe5ac1f95c">AddrSinkCombineBaseOffs</a>("addr-sink-combine-base-offs", cl::Hidden, cl::init(true), cl::desc("Allow combining of BaseOffs field in Address sinking."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a984c73ae4b3ecbd1c9a237c11e38ac62">AddrSinkCombineScaledReg</a>("addr-sink-combine-scaled-reg", cl::Hidden, cl::init(true), cl::desc("Allow combining of ScaledReg field in Address sinking."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa139a070bbd3c66bb6fd2dbdee1dd893">EnableGEPOffsetSplit</a>("cgp-split-large-offset-gep", cl::Hidden, cl::init(true), cl::desc("Enable splitting large offset of GEP."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa667cc0d6f6fc39b8d40b9b9828b81bb">EnableICMP_EQToICMP_ST</a>("cgp-icmp-eq2icmp-st", cl::Hidden, cl::init(false), cl::desc("Enable ICMP_EQ to ICMP_S(L|G)T conversion."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67824c7146db82e49933e0a1ac1d3b9">VerifyBFIUpdates</a>("cgp-verify-bfi-updates", cl::Hidden, cl::init(false), cl::desc("Enable BFI update verification for " "CodeGenPrepare."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7858eecb954b54795df357b6935414">OptimizePhiTypes</a>("cgp-optimize-phi-types", cl::Hidden, cl::init(true), cl::desc("Enable converting phi types in CodeGenPrepare"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eff5790402995c83be65f9260826b41">HugeFuncThresholdInCGPP</a>("cgpp-huge-func", cl::init(10000), cl::Hidden, cl::desc("Least BB number of huge function."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a31871450a2ceec97ef89dbdae54921">MaxAddressUsersToScan</a>("cgp-max-address-users-to-scan", cl::init(100), cl::Hidden, cl::desc("Max number of address users to look at"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d9ea3fbe9aad1268fdabb3863c336c">DisableDeletePHIs</a>("disable-cgp-delete-phis", cl::Hidden, cl::init(false), cl::desc("Disable elimination of dead PHI nodes."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Optimize <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a109eb00135035c7badb12cece015c58d">generation</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Optimize <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82626751cd03ec5db2cc4939a10ad956">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"codegenprepare"</td>
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

### adjustIsPower2Test() {#a6536b980547806c6fb158add5334c3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool adjustIsPower2Test (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Some targets have better codegen for <span class="doxyComputerOutput">ctpop(X) u&lt; 2</span> than <span class="doxyComputerOutput">ctpop(X) == 1</span>.</p>


<p>This function converts <span class="doxyComputerOutput">ctpop(X) ==/!= 1</span> into <span class="doxyComputerOutput">ctpop(X) u&lt;/u&gt; 2/1</span> if the result cannot be zero.</p>


<p>Definition at line 2155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### computeBaseDerivedRelocateMap() {#a8f5b32a03cc4a6072855d8c8cf7c748f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeBaseDerivedRelocateMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst">GCRelocateInst</a> * &gt; &amp; AllRelocateCalls, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst">GCRelocateInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst">GCRelocateInst</a> *, 0 &gt; &gt; &amp; RelocateInstMap)</td>
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



<p>Definition at line 1201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a0881334358ff6ff7ff8cea5562c7988e">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert</a>.</p>

</div>
</div>

### DbgInserterHelper() {#a5a43b0bc7c25aaaa14cf3d79d7f13c78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgInserterHelper (<a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst">DbgValueInst</a> * DVI, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> VI)</td>
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



<p>Definition at line 8904 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af09e4096de244d2fb345891328714a63">llvm::Instruction::insertAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0fd53f63d349dc8a7c5fc0cdd7a94c8d">llvm::Instruction::removeFromParent</a>.</p>

</div>
</div>

### DbgInserterHelper() {#ac8803aa267830622708ede7b732c7ae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgInserterHelper (<a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * DVR, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> VI)</td>
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



<p>Definition at line 8912 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a930f97c50e2e4eddb8a6cd55a4dfd5bd">llvm::BasicBlock::insertDbgRecordAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a365301682c41f8a7094218176d712cda">llvm::BasicBlock::insertDbgRecordBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a04a8b2dc4d72db72e1f87bdec4074973">llvm::DbgRecord::removeFromParent</a>.</p>

</div>
</div>

### despeculateCountZeros() {#adfad68845808cb6acd116e50b15bc281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool despeculateCountZeros (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * CountZeros, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> * DL, ModifyDT &amp; ModifiedDT, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 32 &gt; &amp; FreshBBs, bool IsHugeFunc)</td>
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

<p>If counting leading or trailing zeros is an expensive operation and a zero input is defined, add a check for zero to avoid calling the intrinsic.</p>


<p>We want to transform: z = call i64 @llvm.cttz.i64(i64 A, i1 false)</p>


<p>into: entry: cmpz = icmp eq i64 A, 0 br i1 cmpz, label cond.end, label cond.false cond.false: z = call i64 @llvm.cttz.i64(i64 A, i1 true) br label cond.end cond.end: ctz = phi i64 [ 64, entry ], [ z, cond.false ]</p>


<p>If the transform is performed, return true and set ModifiedDT to true.</p>


<p>Definition at line 2494 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a563ec77bbc82ad22aab9621dd14c01cd">llvm::IRBuilderBase::CreateFreeze</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8c75539a39f167f352b37ccdd788a7e4">llvm::IRBuilderBase::CreateICmpEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae7c8f643db1fdc579f1aa5320c7a0398">llvm::IRBuilderBase::getInt</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a3f3b252f63d32a9a6e05208ce26562bf">llvm::User::getOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a42ce8aa34864a9d974958b9d3d36ad17">llvm::IRBuilderBase::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#abe9a0c5ce415f4e7498d75deb8de0896">llvm::TargetLoweringBase::isCheapToSpeculateCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a42e6689af9067a1afe64eac0267deb01">llvm::TargetLoweringBase::isCheapToSpeculateCttz</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab8a7ef433279aabf7f30fa5504a4d4ef">llvm::isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9893e3e4b14f8fa15d7c3c25a6a0b6f6">llvm::isKnownNonZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af5758ce8e1ea07d0c154e97556db4379acdb2e8290f0e8cd4bedd2a20c95047a9">anonymous{CodeGenPrepare.cpp}::ModifyBBDT</a>, <a href="#a19e092ecf7889abf7277f13824e0c601">replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#abc10b887caad109288ffceb230493a85">llvm::CallBase::setArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>.</p>

</div>
</div>

### FindAllMemoryUses() {#a498962c0029b14cf3cc8fb08c5e20ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FindAllMemoryUses (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &gt; &amp; MemoryUses, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; ConsideredInsts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, bool OptSize, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, unsigned &amp; SeenInsts)</td>
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

<p>Recursively walk all the uses of I until we find a memory use.</p>


<p>If we find an obviously non-foldable instruction, return true. Add accessed addresses and types to MemoryUses.</p>


<p>Definition at line 5506 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a498962c0029b14cf3cc8fb08c5e20ab2">FindAllMemoryUses</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#ad11e8ccbd7550fb3b77f1d2cbc921b50">llvm::AtomicCmpXchgInst::getPointerOperandIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a2f8f88574a509cf4545cd6420b405aaf">llvm::AtomicRMWInst::getPointerOperandIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#add13b402166ae4d70f5b93c3c4cfba99">llvm::StoreInst::getPointerOperandIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a86026627b644e50527898aad0747b3e5">IsOperandAMemoryOperand</a>, <a href="#a1a31871450a2ceec97ef89dbdae54921">MaxAddressUsersToScan</a>, <a href="#a9d0372d5a469c089a4f2a299dd679558">MightBeFoldableInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a0f0065098f13d0b2ef0e39f9d2e1ecdd">FindAllMemoryUses</a> and <a href="#a498962c0029b14cf3cc8fb08c5e20ab2">FindAllMemoryUses</a>.</p>

</div>
</div>

### FindAllMemoryUses() {#a0f0065098f13d0b2ef0e39f9d2e1ecdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FindAllMemoryUses (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &gt; &amp; MemoryUses, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, bool OptSize, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI)</td>
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



<p>Definition at line 5579 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="#a498962c0029b14cf3cc8fb08c5e20ab2">FindAllMemoryUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### foldFCmpToFPClassTest() {#a1f580ab00002a65787ab52ef2aa9a439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool foldFCmpToFPClassTest (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Definition at line 1950 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7fb2c76ce3457d7b38dcdfbe1d5fd051">llvm::IRBuilderBase::createIsFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da00a4419741933f5cb7ec001aaa6e6bb5">llvm::fcInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9ef7edd1261f6570677d850b5cf2cfc">llvm::fcmpToClassTest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b3a8b47a5344da71953bc4eb38c5179">llvm::getFCmpCondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7ddfa7ca92088dcd1b6c8936bca6917a">llvm::TargetLoweringBase::isCondCodeLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af4dac2cd51ca7d7082cabfba3f81dd27">llvm::TargetLoweringBase::isFAbsFree</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1106b8a15061e8494873e10bb8a364e5">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>.</p>

</div>
</div>

### foldICmpWithDominatingICmp() {#a98c59bcf49cb7343886e8f425d6d877b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool foldICmpWithDominatingICmp (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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

<p>For pattern like:</p>


<p>DomCond = icmp sgt/slt CmpOp0, CmpOp1 (might not be in DomBB) ... DomBB: ... br DomCond, TrueBB, CmpBB CmpBB: (with DomBB being the single predecessor) ... Cmp = icmp eq CmpOp0, CmpOp1 ...</p>


<p>It would use two comparison on targets that lowering of icmp sgt/slt is different from lowering of icmp eq (PowerPC). This function try to convert 'Cmp = icmp eq CmpOp0, CmpOp1' to ' Cmp = icmp slt/sgt CmpOp0, CmpOp1'. After that, DomCond and Cmp can use the same comparison so reduce one comparison.</p>


<p>Return true if any changes are made.</p>


<p>Definition at line 1851 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aa667cc0d6f6fc39b8d40b9b9828b81bb">EnableICMP_EQToICMP_ST</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a18c621c39394892e502cf03313e04bf7">llvm::TargetLoweringBase::isEqualityCmpFoldedWithSignedCmp</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a811d001fa503a556ac2a48d64366500f">llvm::PatternMatch::m_Br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a6550fe5bd437c1c3c6e237d726e36b90">llvm::BranchInst::swapSuccessors</a>.</p>

</div>
</div>

### foldURemOfLoopIncrement() {#af950841a4443ffb7aff66ae75fee8442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool foldURemOfLoopIncrement (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Rem, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> * DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 32 &gt; &amp; FreshBBs, bool IsHuge)</td>
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



<p>Definition at line 2068 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a706649daecd068a72d8e06df2fd83549">llvm::IRBuilderBase::CreateNUWAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="#aaf468add8b9e6811a1643026e25eadb4">isRemOfLoopIncrementWithLoopInvariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5f6c38f6f64c2118341c829f97e26396">llvm::PatternMatch::m_ImmConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab65bddcf2ef369ad6d5678882800a7da">llvm::PatternMatch::m_NSWAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a19e092ecf7889abf7277f13824e0c601">replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e0af1b16cab9e0efc63a6ce9de2b9cc">llvm::simplifyAddInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecb805c568634be3390c7da36836d63e">llvm::simplifyURemInst</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>

</div>
</div>

### GEPSequentialConstIndexed() {#ac3e586008202db1f802e906a489d7574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GEPSequentialConstIndexed (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP)</td>
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



<p>Definition at line 8364 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac828b9b52935f87659a4adf237f820a3">llvm::gep_type_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a8528dea79f0940669c4fcb751940ca94">tryUnmergingGEPsAcrossIndirectBr</a>.</p>

</div>
</div>

### getGEPSmallConstantIntOffsetV() {#a0e431b29d5cd842ab00f85ec2cdab8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getGEPSmallConstantIntOffsetV (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEP, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; OffsetV)</td>
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



<p>Definition at line 1236 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a9364799319bac519aa565ec882986e6d">simplifyRelocatesOffABase</a>.</p>

</div>
</div>

### getIVIncrement() {#a50cfddd4c98e75ef287c16996698dc1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; Instruction *, Constant * &gt; &gt; getIVIncrement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI)</td>
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

<p>If given <span class="doxyComputerOutput">PN</span> is an inductive variable with value IVInc coming from the backedge, and on each iteration it gets increased by Step, return pair &lt;IVInc, Step&gt;.</p>


<p>Otherwise, return std::nullopt.</p>


<p>Definition at line 1527 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="#a9f54e95337782bd4fb335dd547c05ecc">matchIncrement</a>.</p>


<p>Referenced by <a href="#ab0f1e7b38e65d10c01900bd4d458a03b">isIVIncrement</a> and <a href="#aaf468add8b9e6811a1643026e25eadb4">isRemOfLoopIncrementWithLoopInvariant</a>.</p>

</div>
</div>

### getTrueOrFalseValue() {#a596c5a8a807f6ce192718084a11648de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * getTrueOrFalseValue (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> * SI, bool isTrue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt; &amp; Selects)</td>
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

<p>If <span class="doxyComputerOutput">isTrue</span> is true, return the true value of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span>, otherwise return false value of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span>.</p>


<p>If the true/false value of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/si">SI</a></span> is defined by any select instructions in <span class="doxyComputerOutput">Selects</span>, look through the defining select instruction until the true/false value is not defined in <span class="doxyComputerOutput">Selects</span>.</p>


<p>Definition at line 7330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### hasSameExtUse() {#ae965d93aa46ad834c21718eba4b5b78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasSameExtUse (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if all the uses of <span class="doxyComputerOutput">Val</span> are equivalent (or free) zero or sign extensions.</p>

<p>Definition at line 6327 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a13e877ef779ba7a0688081079f4f9b03">llvm::Type::getIntegerBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a342be90695496b88a8854a775dfd030f">llvm::TargetLoweringBase::isZExtFree</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#aaca449a7620b1306ed7586ba6bdc4faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (CodeGenPrepareLegacyPass, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Optimize <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> code generation", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### isExtractBitsCandidateUse() {#a19e2fd6fce422c4ab3cea555782abbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isExtractBitsCandidateUse (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the candidates could be combined with a shift instruction, which includes:</p>


<ol class="doxyList" type="1">
<li>Truncate instruction</li>
<li>And instruction and the imm is a mask of the low bits: imm &amp; (imm+1) == 0</li>
</ol>

<p>Definition at line 2283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>.</p>

</div>
</div>

### isFormingBranchFromSelectProfitable() {#a4bde686b6506cc9e63919272711713f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFormingBranchFromSelectProfitable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> * SI)</td>
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

<p>Returns true if a <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> should be turned into an explicit branch.</p>

<p>Definition at line 7285 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac19cbbc4935a23e1d44f65e1eaba6b1d">llvm::extractBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a0333345669e75a54c7de3d5fe0f6e746">llvm::BranchProbability::getBranchProbability</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa9f4cbd152c2c5d84007f3ad710ee895">llvm::TargetLoweringBase::isPredictableSelectExpensive</a> and <a href="#a10ece31d94cdd66e58cef49d73f2263f">sinkSelectOperand</a>.</p>

</div>
</div>

### isIntrinsicOrLFToBeTailCalled() {#a87548c69480b23599d643d518412895c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIntrinsicOrLFToBeTailCalled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
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



<p>Definition at line 2810 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>

</div>
</div>

### isIVIncrement() {#ab0f1e7b38e65d10c01900bd4d458a03b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIVIncrement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI)</td>
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



<p>Definition at line 1542 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a50cfddd4c98e75ef287c16996698dc1c">getIVIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="#a9f54e95337782bd4fb335dd547c05ecc">matchIncrement</a>.</p>

</div>
</div>

### IsNonLocalValue() {#ad897d4beb50aa8f0d4d2eaa08ac0987d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsNonLocalValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Return true if the specified values are defined in a different basic block than BB.</p>

<p>Definition at line 5725 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### IsOperandAMemoryOperand() {#a86026627b644e50527898aad0747b3e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsOperandAMemoryOperand (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> * IA, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OpVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if all uses of OpVal by the specified inline asm call are due to memory operands.</p>


<p>If so, return true, otherwise return false.</p>


<p>Definition at line 5481 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a420d729d2e7d056ec884c094ccdc4467">llvm::TargetLowering::C_Memory</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a279a7f92d056886ac713c0f06cc73045">llvm::TargetLowering::ComputeConstraintToUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a1c5e8b6aef41aead06d61ff0530ed9c2">llvm::TargetLowering::ParseConstraints</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a498962c0029b14cf3cc8fb08c5e20ab2">FindAllMemoryUses</a>.</p>

</div>
</div>

### isPromotedInstructionLegal() {#aca87c42e8556b7f2e73454d63efa87f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPromotedInstructionLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not <span class="doxyComputerOutput">Val</span> is a legal instruction for <span class="doxyComputerOutput">TLI</span>.</p>



:::info
<p><span class="doxyComputerOutput">Val</span> is assumed to be the product of some type promotion. Therefore if <span class="doxyComputerOutput">Val</span> has an undefined state in <span class="doxyComputerOutput">TLI</span>, this is assumed to be legal, as the non-promoted value would have had the same state.</p>
:::


<p>Definition at line 4652 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a025e6664b2f55d2c217543c34eb1f64e">llvm::TargetLoweringBase::InstructionOpcodeToISD</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa93fbbc66d52a51d178af8ac4398ec05">llvm::TargetLoweringBase::isOperationLegalOrCustom</a>.</p>

</div>
</div>

### isRemOfLoopIncrementWithLoopInvariant() {#aaf468add8b9e6811a1643026e25eadb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRemOfLoopIncrementWithLoopInvariant (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Rem, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; RemAmtOut, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; AddInstOut, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; AddOffsetOut, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *&amp; LoopIncrPNOut)</td>
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



<p>Definition at line 1983 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a50cfddd4c98e75ef287c16996698dc1c">getIVIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a33e25e1952cc74de88c6af4d687f404a">llvm::PatternMatch::m_c_NUWAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c7ef38b3e115873246f1d5e491d80c3">llvm::PatternMatch::m_NUWAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3b3d2d8c64a7881acb82bc7467569aa9">llvm::PatternMatch::m_One</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a11e5bad6c60d5c3cc5e7881bddd0204d">llvm::PatternMatch::m_URem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>.</p>

</div>
</div>

### matchIncrement() {#a9f54e95337782bd4fb335dd547c05ecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchIncrement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IVInc, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; LHS, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&amp; Step)</td>
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



<p>Definition at line 1508 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aefdfcd6977f799b0f35e93d75114121c">llvm::ConstantExpr::getNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a16be5fe0cce90e51f8c0e0c4d6c589f6">llvm::PatternMatch::m_Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a445051c482340bacd1e3264406421afb">llvm::PatternMatch::m_ExtractValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2adca0e23c974dbb32019dccb22547bc">llvm::PatternMatch::m_Instruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#a50cfddd4c98e75ef287c16996698dc1c">getIVIncrement</a> and <a href="#ab0f1e7b38e65d10c01900bd4d458a03b">isIVIncrement</a>.</p>

</div>
</div>

### matchUAddWithOverflowConstantEdgeCases() {#af23979229be4fb2286896bf920e3e235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchUAddWithOverflowConstantEdgeCases (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> *&amp; Add)</td>
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

<p>Match special-case patterns that check for unsigned add overflow.</p>

<p>Definition at line 1638 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ef056813d120034e387417e9cde341">llvm::PatternMatch::m_AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a54d7212b9b2c57cced42037ae2fa7c61">llvm::PatternMatch::m_ZeroInt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### MightBeFoldableInst() {#a9d0372d5a469c089a4f2a299dd679558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MightBeFoldableInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>This is a little filter, which returns true if an addressing computation involving I might be folded into a load/store accessing it.</p>


<p>This doesn't need to be perfect, but needs to accept at least the set of instructions that MatchOperationAddr can.</p>


<p>Definition at line 4621 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a498962c0029b14cf3cc8fb08c5e20ab2">FindAllMemoryUses</a>.</p>

</div>
</div>

### optimizeBranch() {#ad2bfc3e2f7b1661868517e662ac7496c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool optimizeBranch (<a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * Branch, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 32 &gt; &amp; FreshBBs, bool IsHugeFunc)</td>
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



<p>Definition at line 8532 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a843d43d070f0b1c6a133403edce488ef">llvm::IRBuilderBase::CreateCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ad4613def4002aa69721553e567ca4187">llvm::Instruction::dropPoisonGeneratingFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad1b0513de876d1c85cf6268ca21b2c86">llvm::APInt::isPowerOf2</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aae3b959a0a2981340fd03c29f528f2f0">llvm::APInt::logBase2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a310fbeb4d6c1b137dfd8713d354f3d76">llvm::PatternMatch::m_Shr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af67d1f3a518964d80a109bb3d9d5cf1e">llvm::Instruction::moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af7763c45db027300e49b43037e5a1a60">llvm::TargetLoweringBase::preferZeroCompareBranch</a>, <a href="#a19e092ecf7889abf7277f13824e0c601">replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### OptimizeExtractBits() {#a2c05548feac70b16d31caf0cfb225714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OptimizeExtractBits (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * ShiftI, <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Sink the shift <em>right</em> instruction into user blocks if the uses could potentially be combined with this shift instruction and generate BitExtract instruction.</p>


<p>It will only be applied if the architecture supports BitExtract instruction. Here is an example: BB1: x.extract.shift = lshr i64 arg1, 32 BB2: x.extract.trunc = trunc i64 x.extract.shift to i16 ==&gt;</p>


<p>BB2: x.extract.shift.1 = lshr i64 arg1, 32 x.extract.trunc = trunc i64 x.extract.shift.1 to i16</p>


<p>CodeGen will recognize the pattern in BB2 and generate BitExtract instruction. Return true if any changes are made.</p>


<p>Definition at line 2392 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a19e2fd6fce422c4ab3cea555782abbb6">isExtractBitsCandidateUse</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26be1141b23850a2b4eb78021d99e862">llvm::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#aa22118b2b3f206bfda2ffab4cda94d64">llvm::Value::user_end</a>.</p>

</div>
</div>

### OptimizeNoopCopyExpression() {#a3b82cff474790446f1288f1a086c1cd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OptimizeNoopCopyExpression (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> * CI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>If the specified cast instruction is a noop copy (e.g.</p>


<p>it's casting from one pointer type to another, i32-&gt;i8 on <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a>), sink it into user blocks to reduce the number of virtual registers that must be created and coalesced.</p>


<p>Return true if any changes are made.</p>


<p>Definition at line 1465 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a3bf257bfbd279ecfad670be03b00210e">llvm::EVT::bitsLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ad859786d7e54bdc5c568ac20c69816e0">llvm::TargetLoweringBase::getTypeAction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a77f7add8733417370a56154e8b560617">llvm::TargetLoweringBase::getTypeToTransformTo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8e1c8a5721df02cd26c1ffd04320b02c">llvm::TargetLoweringBase::isFreeAddrSpaceCast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a>, <a href="#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a35dc101b509721ffbfb58aba316de681a26f35604723482a1aee6514940c2987d">llvm::TargetLoweringBase::TypePromoteInteger</a>.</p>

</div>
</div>

### replaceAllUsesWith() {#a19e092ecf7889abf7277f13824e0c601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceAllUsesWith (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * New, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 32 &gt; &amp; FreshBBs, bool IsHuge)</td>
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

<p>Replace all old uses with new ones, and push the updated BBs into FreshBBs.</p>

<p>Definition at line 1112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a>.</p>


<p>Referenced by <a href="#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a> and <a href="#ad2bfc3e2f7b1661868517e662ac7496c">optimizeBranch</a>.</p>

</div>
</div>

### scaleWeights() {#a25c5d0cb41bbb1777e779a8da35e7bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void scaleWeights (uint64_t &amp; NewTrue, uint64_t &amp; NewFalse)</td>
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

<p>Scale down both weights to fit into uint32_t.</p>

<p>Definition at line 9020 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### simplifyRelocatesOffABase() {#a9364799319bac519aa565ec882986e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool simplifyRelocatesOffABase (<a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst">GCRelocateInst</a> * RelocatedBase, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst">GCRelocateInst</a> * &gt; &amp; Targets)</td>
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



<p>Definition at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst/#ae33641b6538b4ab4f3aa3dad2926860f">llvm::GCRelocateInst::getBasePtrIndex</a>, <a href="#a0e431b29d5cd842ab00f85ec2cdab8b2">getGEPSmallConstantIntOffsetV</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/gcprojectioninst/#a6cffcfabac72ca61185ea24c1208b937">llvm::GCProjectionInst::getStatepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af67d1f3a518964d80a109bb3d9d5cf1e">llvm::Instruction::moveBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ae855357b6c5e6e7ed1869272708a3a84">llvm::Value::takeName</a>.</p>

</div>
</div>

### sinkAndCmp0Expression() {#a0049977ff1075a98e9f512bbf4d181a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sinkAndCmp0Expression (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * AndI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, SetOfInstrs &amp; InsertedInsts)</td>
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

<p>Duplicate and sink the given 'and' instruction into user blocks where it is used in a compare to allow isel to generate better code for targets where this operation can be combined.</p>


<p>Return true if any changes are made.</p>


<p>Definition at line 2207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#af7dca9a9e816ef69fd9e9467f64f72b4">llvm::Value::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1f8d2859994eb10cdca39be26aa929bc">llvm::TargetLoweringBase::isMaskAndCmp0FoldingBeneficial</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#aa22118b2b3f206bfda2ffab4cda94d64">llvm::Value::user_end</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

### SinkCast() {#a3cc8a3a2506bf528398d0aef0850f31a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SinkCast (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> * CI)</td>
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

<p>Sink the specified cast instruction into its user blocks.</p>

<p>Definition at line 1397 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0a4d51e372293abe5e5f6dac133e80a6">llvm::Instruction::clone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5d3d315f678bc76e43b27d18e5d72829">llvm::Instruction::isEHPad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26be1141b23850a2b4eb78021d99e862">llvm::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#aa22118b2b3f206bfda2ffab4cda94d64">llvm::Value::user_end</a>.</p>


<p>Referenced by <a href="#a3b82cff474790446f1288f1a086c1cd6">OptimizeNoopCopyExpression</a>.</p>

</div>
</div>

### sinkCmpExpression() {#a24a3e4aad4cb2fdde7ce294a531cd52a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sinkCmpExpression (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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

<p>Sink the given <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> into user blocks to reduce the number of virtual registers that must be created and coalesced.</p>


<p>This is a clear win except on targets with multiple condition code registers (PowerPC), where it might lose; some adjustment may be wanted there.</p>


<p>Return true if any changes are made.</p>


<p>Definition at line 1772 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a62e2cf3675b93f0e6c07a4a00852f7cd">llvm::CmpInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa00abc9ed22bfa32ebd68531b619b005">llvm::TargetLoweringBase::hasMultipleConditionRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aca632fc83dfd8f23f3456ef50a49e31a">llvm::TargetLoweringBase::useSoftFloat</a>.</p>

</div>
</div>

### sinkSelectOperand() {#a10ece31d94cdd66e58cef49d73f2263f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sinkSelectOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if V (an operand of a select instruction) is an expensive instruction that is only used once.</p>

<p>Definition at line 7276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8601ff0320b6e29a13a2194200853425">llvm::isSafeToSpeculativelyExecute</a>.</p>


<p>Referenced by <a href="#a4bde686b6506cc9e63919272711713f4">isFormingBranchFromSelectProfitable</a>.</p>

</div>
</div>

### SinkShiftAndTruncate() {#a0327169186859791aafa580e4fb547e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SinkShiftAndTruncate (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * ShiftI, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User, <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * &gt; &amp; InsertedShifts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Sink both shift and truncate instruction to the use of truncate's BB.</p>

<p>Definition at line 2299 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ad2e0ab6d7096fe67a2216fe349044387">llvm::CastInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a126c61d55fb4d2e509537ce68e8b6400">llvm::TargetLoweringBase::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a025e6664b2f55d2c217543c34eb1f64e">llvm::TargetLoweringBase::InstructionOpcodeToISD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa93fbbc66d52a51d178af8ac4398ec05">llvm::TargetLoweringBase::isOperationLegalOrCustom</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>.</p>


<p>Referenced by <a href="#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>.</p>

</div>
</div>

### splitMergedValStore() {#a3c7e1486d1d466b3be981adcb21a6359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool splitMergedValStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; SI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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

<p>For the instruction sequence of store below, F and I values are bundled together as an i64 value before being stored into memory.</p>


<p>Sometimes it is more efficient to generate separate stores for F and I, which can remove the bitwise instructions or sink them to colder places.</p>


<p>(store (or (zext (bitcast F to i32) to i64), (shl (zext I to i64), 32)), addr) --&gt; (store F, addr) and (store I, addr+4)</p>


<p>Similarly, splitting for other merged store can also be beneficial, like: For pair of {i32, i32}, i64 store --&gt; two i32 stores. For pair of {i32, i16}, i64 store --&gt; two i32 stores. For pair of {i16, i16}, i32 store --&gt; two i16 stores. For pair of {i16, i8}, i32 store --&gt; two i16 stores. For pair of {i8, i8}, i16 store --&gt; two i8 stores.</p>


<p>We allow each target to determine specifically which kind of splitting is supported.</p>


<p>The store patterns are commonly seen from the simple code snippet below if only std::make_pair(...) is sroa transformed before inlined into hoo. void goo(const std::pair&lt;int, float&gt; &amp;); hoo() { ... goo(std::make_pair(tmp, ftmp)); ... }</p>


<p>Although we already have similar splitting in DAG Combine, we duplicate it in <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare">CodeGenPrepare</a> to catch the case in which pattern is across multiple BBs. The logic in DAG Combine is kept to catch case generated during code expansion.</p>


<p>Definition at line 8266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad4e4b11a1bf18be51b28b7fadfaa97d6">llvm::IRBuilderBase::CreateAlignedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73e0482b96d9d0cdfcc90c0a34f5b0db">llvm::IRBuilderBase::CreateGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0032ae544ae429aaf1053767da90426d">llvm::IRBuilderBase::CreateZExtOrBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a8ac7126af5085fb735db4c727a0ab4e9">ForceSplitStore</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a5db8faf73cf29bcefdb3bdfadf3dc2c1">llvm::EVT::getEVT</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ab068741575ed8c7f6bd4fe059edabd14">llvm::TargetLoweringBase::isMultiStoresCheaperThanBitsMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2ff127c9924cd3337080c4445c324aea">llvm::Type::isScalableTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ab67ef02b75c3226cfe0b2791e2b48b06a74accfde3d3f8e8a27c326eba229d16c">LValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae80cbfea2025ff7bd0770f30be6e050a">llvm::PatternMatch::m_c_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ac1c7b78fe67245930be18441b77de500">llvm::PatternMatch::m_Shl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2471be3f1b50002f54bf45c590d8d41b">llvm::PatternMatch::m_SpecificInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a6ba4022cd30993a84d111871dd0f6ba6">llvm::PatternMatch::m_ZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>

</div>
</div>

### STATISTIC() {#a6059e0984be477af12647e0574a01af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumBlocksElim, "Number of <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> eliminated")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aa30f41b73332156614f88439d24da8ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPHIsElim, "Number of trivial PHIs eliminated")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ab4aba4ac8014186037d27ffc57196ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumGEPsElim, "Number of GEPs converted to casts")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ac922eae769aaa3ee158e915f036129e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCmpUses, "Number of uses of Cmp expressions replaced with uses of " "sunken Cmps")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a09f1c42adaebc495651949c7d4e64c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCastUses, "Number of uses of Cast expressions replaced with uses " "of sunken Casts")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a6853dee9da71b8737b7c731c505988d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumMemoryInsts, "Number of memory <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> whose address " "computations were sunk")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aff39dc0be076dc904665065cf5c6ede2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumMemoryInstsPhiCreated, "Number of phis created when address " "computations were sunk to memory instructions")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a3c487b469e600b10b65c400de3741735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumMemoryInstsSelectCreated, "Number of select created when address " "computations were sunk to memory instructions")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a382d2cdafa179d7c4561bfe746d2a4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumExtsMoved, "Number of ext <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> combined with loads")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a1c84a6266af376a7dc168db6dd0e1ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumExtUses, "Number of uses of ext <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> optimized")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#abc95b24e3dc47ccf0a7afcc846d82c34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumAndsAdded, "Number of and mask <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> added to form ext loads")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aaf676a4c39b6a1c7019dbbec6fc89500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumAndUses, "Number of uses of and mask <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> optimized")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a05852bdf4c63ca1e5306e1422db248f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumRetsDup, "Number of return <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> duplicated")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ad8d62a4d9ff57ddca8ab070f4e396c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumDbgValueMoved, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae0228f36529f75f692753ef96d725012">debug</a> value <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> moved")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aee5e95a01071c306a5fa9e6e3e07183c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumSelectsExpanded, "Number of <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp/#a3d495d9a0daf7fe32f1b1fb0aa153929">selects</a> turned into branches")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a4644887cd2ba8fba1a1c6f97d234e7e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumStoreExtractExposed, "Number of store(extractelement) exposed")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### swapICmpOperandsToExposeCSEOpportunities() {#a3fb33a8a29e076405285e5282eba81fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool swapICmpOperandsToExposeCSEOpportunities (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp)</td>
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

<p>Many architectures use the same instruction for both subtract and cmp.</p>


<p>Try to swap cmp operands to match subtract operations to allow for CSE.</p>


<p>Definition at line 1921 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

### tryUnmergingGEPsAcrossIndirectBr() {#a8528dea79f0940669c4fcb751940ca94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryUnmergingGEPsAcrossIndirectBr (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> * GEPI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI)</td>
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



<p>Definition at line 8427 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac3e586008202db1f802e906a489d7574">GEPSequentialConstIndexed</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272cae46c9eecc49bd2dc253c607e78a0fb86">llvm::TargetTransformInfo::TCC_Basic</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba7f80055e1969cb850739546467460ad8">llvm::TargetTransformInfo::TCK_SizeAndLatency</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AddrSinkCombineBaseGV {#a51f303fd2cc8c48e50ab97c59f3558cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AddrSinkCombineBaseGV("addr-sink-combine-base-gv", cl::Hidden, cl::init(true), cl::desc("Allow combining of BaseGV field in Address sinking."))</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AddrSinkCombineBaseOffs {#a3a00df51e1fa276c0c8860fe5ac1f95c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AddrSinkCombineBaseOffs("addr-sink-combine-base-offs", cl::Hidden, cl::init(true), cl::desc("Allow combining of BaseOffs field in Address sinking."))</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AddrSinkCombineBaseReg {#a44b23d217bd678cd7aef7d152d945537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AddrSinkCombineBaseReg("addr-sink-combine-base-reg", cl::Hidden, cl::init(true), cl::desc("Allow combining of BaseReg field in Address sinking."))</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AddrSinkCombineScaledReg {#a984c73ae4b3ecbd1c9a237c11e38ac62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AddrSinkCombineScaledReg("addr-sink-combine-scaled-reg", cl::Hidden, cl::init(true), cl::desc("Allow combining of ScaledReg field in Address sinking."))</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AddrSinkNewPhis {#afedfbc99c6b04e20643eb77da796d522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AddrSinkNewPhis("addr-sink-new-phis", cl::Hidden, cl::init(false), cl::desc("Allow creation of Phis in Address sinking."))</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AddrSinkNewSelects {#a732a4fb41e78c56627fb9748f00935ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AddrSinkNewSelects("addr-sink-new-select", cl::Hidden, cl::init(true), cl::desc("Allow creation of selects in Address sinking."))</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### AddrSinkUsingGEPs {#a5410093a9a86bd6e68eb3ffb32cbce13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AddrSinkUsingGEPs("addr-sink-using-gep", cl::Hidden, cl::init(true), cl::desc("Address sinking in CGP using GEPs."))</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### BBSectionsGuidedSectionPrefix {#aaabb67aa574169b8cf2db8baf993b9ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; BBSectionsGuidedSectionPrefix("bbsections-guided-section-prefix", cl::Hidden, cl::init(true), cl::desc("Use the basic-block-sections profile to determine the text " "section prefix for hot functions. Functions with " "basic-block-sections profile will be placed in `.text.hot` " "regardless of their FDO profile info. Other functions won't be " "impacted, i.e., their prefixes will be decided by FDO/sampleFDO " "profiles."))</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DisableBranchOpts {#a62cd718328addb93b7bfbfd788fa9c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableBranchOpts("disable-cgp-branch-opts", cl::Hidden, cl::init(false), cl::desc("Disable branch optimizations in CodeGenPrepare"))</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DisableComplexAddrModes {#aa653d45524ba8feb6e97dd4f961b7c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableComplexAddrModes("disable-complex-addr-modes", cl::Hidden, cl::init(false), cl::desc("Disables combining addressing modes with different parts " "in optimizeMemoryInst."))</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DisableDeletePHIs {#af6d9ea3fbe9aad1268fdabb3863c336c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableDeletePHIs("disable-cgp-delete-phis", cl::Hidden, cl::init(false), cl::desc("Disable elimination of dead PHI nodes."))</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DisableExtLdPromotion {#a337eb74e6c82771bb21ce598a8d3090c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableExtLdPromotion("disable-cgp-ext-ld-promotion", cl::Hidden, cl::init(false), cl::desc("Disable ext(promotable(ld)) -&gt; promoted(ext(ld)) optimization in " "CodeGenPrepare"))</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DisableGCOpts {#ac23f3d86779d204fbf6db71ce8f41d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableGCOpts("disable-cgp-gc-opts", cl::Hidden, cl::init(false), cl::desc("Disable GC optimizations in CodeGenPrepare"))</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DisablePreheaderProtect {#a346da4fb7a62e95531402c0b2a85c4fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisablePreheaderProtect("disable-preheader-prot", cl::Hidden, cl::init(false), cl::desc("Disable protection against removing loop preheaders"))</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DisableSelectToBranch {#af42b66ae716b910d032498490940ae08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableSelectToBranch("disable-cgp-select2branch", cl::Hidden, cl::init(false), cl::desc("Disable select to branch conversion."))</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DisableStoreExtract {#a1e6cf6a2bf01ee44a0f0843d8c3512cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableStoreExtract("disable-cgp-store-extract", cl::Hidden, cl::init(false), cl::desc("Disable store(extract) optimizations in CodeGenPrepare"))</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### EnableAndCmpSinking {#add2019bfb348f5241b4110eb77775410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableAndCmpSinking("enable-andcmp-sinking", cl::Hidden, cl::init(true), cl::desc("Enable sinking and/cmp into branches."))</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### EnableGEPOffsetSplit {#aa139a070bbd3c66bb6fd2dbdee1dd893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGEPOffsetSplit("cgp-split-large-offset-gep", cl::Hidden, cl::init(true), cl::desc("Enable splitting large offset of GEP."))</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### EnableICMP\_EQToICMP\_ST {#aa667cc0d6f6fc39b8d40b9b9828b81bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableICMP_EQToICMP_ST("cgp-icmp-eq2icmp-st", cl::Hidden, cl::init(false), cl::desc("Enable ICMP_EQ to ICMP_S(L|G)T conversion."))</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a98c59bcf49cb7343886e8f425d6d877b">foldICmpWithDominatingICmp</a>.</p>

</div>
</div>

### EnableTypePromotionMerge {#a6412f4a5842ffe108c2aa493fa0fe1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableTypePromotionMerge("cgp-type-promotion-merge", cl::Hidden, cl::desc("Enable merging of redundant sexts when one is dominating" " the other."), cl::init(true))</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### false {#a82626751cd03ec5db2cc4939a10ad956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Optimize for code false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### ForceSplitStore {#a8ac7126af5085fb735db4c727a0ab4e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ForceSplitStore("force-split-store", cl::Hidden, cl::init(false), cl::desc("Force store splitting no matter what the target query says."))</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a3c7e1486d1d466b3be981adcb21a6359">splitMergedValStore</a>.</p>

</div>
</div>

### FreqRatioToSkipMerge {#acb1402a601e394cbb3a7b1a1c4e4634f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; uint64_t &gt; FreqRatioToSkipMerge("cgp-freq-ratio-to-skip-merge", cl::Hidden, cl::init(2), cl::desc("Skip merging empty blocks if (frequency of empty block) / " "(frequency of destination block) is greater than this ratio"))</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### generation {#a109eb00135035c7badb12cece015c58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Optimize for code generation</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/stacknode/#a061e4d504e66737c08a6e20f0633198c">StackNode::childGeneration</a>.</p>

</div>
</div>

### HugeFuncThresholdInCGPP {#a6eff5790402995c83be65f9260826b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; HugeFuncThresholdInCGPP("cgpp-huge-func", cl::init(10000), cl::Hidden, cl::desc("Least BB number of huge function."))</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### MaxAddressUsersToScan {#a1a31871450a2ceec97ef89dbdae54921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxAddressUsersToScan("cgp-max-address-users-to-scan", cl::init(100), cl::Hidden, cl::desc("Max number of address users to look at"))</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a498962c0029b14cf3cc8fb08c5e20ab2">FindAllMemoryUses</a>.</p>

</div>
</div>

### OptimizePhiTypes {#a1d7858eecb954b54795df357b6935414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; OptimizePhiTypes("cgp-optimize-phi-types", cl::Hidden, cl::init(true), cl::desc("Enable converting phi types in CodeGenPrepare"))</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### ProfileGuidedSectionPrefix {#a6cdb6fbcff4780503fef226b46b6f10b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ProfileGuidedSectionPrefix("profile-guided-section-prefix", cl::Hidden, cl::init(true), cl::desc("Use profile info to add section prefix for hot/cold functions"))</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### ProfileUnknownInSpecialSection {#a276112f96ea0d245fec9eaa1306712c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ProfileUnknownInSpecialSection("profile-unknown-in-special-section", cl::Hidden, cl::desc("In profiling mode like sampleFDO, if a function doesn't have " "profile, we cannot tell the function is cold for sure because " "it may be a function newly added without ever being sampled. " "With the flag enabled, compiler can put such profile unknown " "functions into a special section, so runtime system can choose " "to handle it in a different way than .text section, to save " "RAM for example. "))</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### StressExtLdPromotion {#aeabb375be2dc51a3d518b9d2a1140fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; StressExtLdPromotion("stress-cgp-ext-ld-promotion", cl::Hidden, cl::init(false), cl::desc("Stress test ext(promotable(ld)) -&gt; promoted(ext(ld)) " "optimization in CodeGenPrepare"))</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### StressStoreExtract {#a4a686688e72eafe6375f8ae1ed184123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; StressStoreExtract("stress-cgp-store-extract", cl::Hidden, cl::init(false), cl::desc("Stress test store(extract) optimizations in CodeGenPrepare"))</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/vectorpromotehelper/#ac167b63805ec9effafeefa7b6d7e4777">anonymous{CodeGenPrepare.cpp}::VectorPromoteHelper::promote</a> and <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/vectorpromotehelper/#aa46482c59b5d71b890df4cfaada1e6c7">anonymous{CodeGenPrepare.cpp}::VectorPromoteHelper::shouldPromote</a>.</p>

</div>
</div>

### VerifyBFIUpdates {#aa67824c7146db82e49933e0a1ac1d3b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; VerifyBFIUpdates("cgp-verify-bfi-updates", cl::Hidden, cl::init(false), cl::desc("Enable BFI update verification for " "CodeGenPrepare."))</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"codegenprepare"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
