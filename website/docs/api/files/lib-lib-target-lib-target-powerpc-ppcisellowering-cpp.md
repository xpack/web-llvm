---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PPCISelLowering.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-h">PPCISelLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">MCTargetDesc/PPCMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcpredicates-h">MCTargetDesc/PPCPredicates.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppc-h">PPC.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcccstate-h">PPCCCState.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-h">PPCCallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-h">PPCFrameLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-h">PPCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmachinefunctioninfo-h">PPCMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcperfectshuffle-h">PPCPerfectShuffle.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcregisterinfo-h">PPCRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetmachine-h">PPCTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">llvm/ADT/APSInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/callingconvlower-h">llvm/CodeGen/CallingConvLower.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">llvm/CodeGen/ISDOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinejumptableinfo-h">llvm/CodeGen/MachineJumpTableInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">llvm/CodeGen/SelectionDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">llvm/CodeGen/TargetLoweringObjectFileImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/machinevaluetype-h">llvm/CodeGenTypes/MachineValueType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">llvm/IR/CallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "llvm/IR/IntrinsicsPowerPC.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionxcoff-h">llvm/MC/MCSectionXCOFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolxcoff-h">llvm/MC/MCSymbolXCOFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/atomicordering-h">llvm/Support/AtomicOrdering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">llvm/Support/BranchProbability.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;list&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
#include "PPCGenAsmMatcher.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-ppcisellowering-cpp-">anonymous{PPCISelLowering.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-ppcisellowering-cpp-/tailcallargumentinfo">TailCallArgumentInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e4db8f05f5d3fe014af90a4fe9993b">STATISTIC</a> (NumTailCalls, "Number of tail calls")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad89fe8718f04da908187186854950506">STATISTIC</a> (NumSiblingCalls, "Number of sibling calls")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b04c638fcba2a789cc9df87645a5e5">STATISTIC</a> (ShufflesHandledWithVPERM, "Number of shuffles lowered to a VPERM or XXPERM")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26daa6fb86359a50ab880638fc1defcf">STATISTIC</a> (NumDynamicAllocaProbed, "Number of dynamic stack allocation probed")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7dd03e8ef59be43553b3168e2293f33">isNByteElemShuffleMask</a> (ShuffleVectorSDNode *N, unsigned Width, int StepLen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that the mask is shuffling N byte elements. <a href="#af7dd03e8ef59be43553b3168e2293f33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c026bf7b5362d2b79a43bd04e769a7">widenVec</a> (SelectionDAG &amp;DAG, SDValue Vec, const SDLoc &amp;dl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8baa555a40ec02c58a1e0455237f65f9">getMaxByValAlign</a> (Type *Ty, Align &amp;MaxAlign, Align MaxMaxAlign)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getMaxByValAlign - Helper for getByValTypeAlignment to determine the desired ByVal argument alignment. <a href="#a8baa555a40ec02c58a1e0455237f65f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4674b301fdc98e0a729a8d4690e45f2">isFloatingPointZero</a> (SDValue Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFloatingPointZero - Return true if this is 0.0 or -0.0. <a href="#af4674b301fdc98e0a729a8d4690e45f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa657a6a85ab82917c254bc085416bd">isConstantOrUndef</a> (int Op, int Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isConstantOrUndef - <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is either an undef node or a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a>. <a href="#a0aa657a6a85ab82917c254bc085416bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941eb33c376cb0192d0d7e52e21c0c11">isVMerge</a> (ShuffleVectorSDNode *N, unsigned UnitSize, unsigned LHSStart, unsigned RHSStart)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isVMerge - Common function, used to match vmrg* shuffles. <a href="#a941eb33c376cb0192d0d7e52e21c0c11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a8b9d3036f888a5dfcc7ded26353005">isVMerge</a> (ShuffleVectorSDNode *N, unsigned IndexOffset, unsigned RHSStartValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common function used to match vmrgew and vmrgow shuffles. <a href="#a7a8b9d3036f888a5dfcc7ded26353005">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15ce5608e9ea5ba89ae7deb2e8895c7">isXXBRShuffleMaskHelper</a> (ShuffleVectorSDNode *N, int Width)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c48cdb4fcbd71e51a4ec4c1d5c6a99a">provablyDisjointOr</a> (SelectionDAG &amp;DAG, const SDValue &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used when computing address flags for selecting loads and stores. <a href="#a3c48cdb4fcbd71e51a4ec4c1d5c6a99a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45779e6cfae9dac4c65a6aa4bbdab74">fixupFuncForFI</a> (SelectionDAG &amp;DAG, int FrameIdx, EVT VT)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Ty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa8da6f68560141aad9b3bb3e333a2c3">isValidPCRelNode</a> (SDValue N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b97177f4c89df3fd0a2f05deec3378f">usePartialVectorLoads</a> (SDNode *N, const PPCSubtarget &amp;ST)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we should use a direct load into vector instruction (such as lxsd or lfd), instead of a load into gpr + direct move sequence. <a href="#a9b97177f4c89df3fd0a2f05deec3378f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97dcf046ecd8a70a4ff620b38f187bd4">getLabelAccessInfo</a> (bool IsPIC, const PPCSubtarget &amp;Subtarget, unsigned &amp;HiOpFlags, unsigned &amp;LoOpFlags, const GlobalValue *GV=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we should reference labels using a PICBase, set the HiOpFlags and LoOpFlags to the target MO flags. <a href="#a97dcf046ecd8a70a4ff620b38f187bd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5d4759731e493988eda569efb67233f">LowerLabelRef</a> (SDValue HiPart, SDValue LoPart, bool isPIC, SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65426f2f59cffd6edeb85831b24dbc48">setUsesTOCBasePtr</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad648f72325a440d58b24e5071c360fe2">setUsesTOCBasePtr</a> (SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3986f0787e3292ba216eb027846bb42b">updateForAIXShLibTLSModelOpt</a> (TLSModel::Model &amp;Model, SelectionDAG &amp;DAG, const TargetMachine &amp;TM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>updateForAIXShLibTLSModelOpt - Helper to initialize TLS model opt settings, and then apply the update. <a href="#a3986f0787e3292ba216eb027846bb42b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd7e508c9e6dd17afc738da27b87bc2">CalculateStackSlotSize</a> (EVT ArgVT, ISD::ArgFlagsTy Flags, unsigned PtrByteSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CalculateStackSlotSize - Calculates the size reserved for this argument on the stack. <a href="#aacd7e508c9e6dd17afc738da27b87bc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e0048496768e682947aedca8e3aa3d9">CalculateStackSlotAlignment</a> (EVT ArgVT, EVT OrigVT, ISD::ArgFlagsTy Flags, unsigned PtrByteSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CalculateStackSlotAlignment - Calculates the alignment of this argument on the stack. <a href="#a5e0048496768e682947aedca8e3aa3d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf413c8efe075d4666f4d526c527ffd">CalculateStackSlotUsed</a> (EVT ArgVT, EVT OrigVT, ISD::ArgFlagsTy Flags, unsigned PtrByteSize, unsigned LinkageSize, unsigned ParamAreaSize, unsigned &amp;ArgOffset, unsigned &amp;AvailableFPRs, unsigned &amp;AvailableVRs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CalculateStackSlotUsed - Return whether this argument will use its stack slot (instead of being passed in registers). <a href="#aeaf413c8efe075d4666f4d526c527ffd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d38e4f90c68ce910c9f3c303fcb5b9e">EnsureStackAlignment</a> (const PPCFrameLowering *Lowering, unsigned NumBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EnsureStackAlignment - Round stack frame size up from NumBytes to ensure minimum alignment required for target. <a href="#a6d38e4f90c68ce910c9f3c303fcb5b9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf0bcfcb9ee7e078bec6074304e31cb0">CalculateTailCallSPDiff</a> (SelectionDAG &amp;DAG, bool isTailCall, unsigned ParamSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CalculateTailCallSPDiff - Get the amount the stack pointer has to be adjusted to accommodate the arguments for the tailcall. <a href="#aaf0bcfcb9ee7e078bec6074304e31cb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1ef95140ed897d441343e4a93d37726">isFunctionGlobalAddress</a> (const GlobalValue *CalleeGV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43a17d867ea4d3bca00dfb065f8cc811">callsShareTOCBase</a> (const Function *Caller, const GlobalValue *CalleeGV, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ccb1948e466b25257ec5f95a2b8e11e">needStackSlotPassParameters</a> (const PPCSubtarget &amp;Subtarget, const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c7e7972f2cde9531b9f9d71196cfc5">hasSameArgumentList</a> (const Function *CallerFn, const CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582533c1a8f8a0a26833f84f2c2fc082">areCallingConvEligibleForTCO_64SVR4</a> (CallingConv::ID CallerCC, CallingConv::ID CalleeCC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bbcfdc24a57cc8268f0278e0a03c156">isBLACompatibleAddress</a> (SDValue Op, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isCallCompatibleAddress - Return the immediate to use if the specified 32-bit value is representable in the immediate field of a BxA instruction. <a href="#a5bbcfdc24a57cc8268f0278e0a03c156">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fcdf2ea020f761f9857bebbc35a2ca3">StoreTailCallArgumentsToStackSlot</a> (SelectionDAG &amp;DAG, SDValue Chain, const SmallVectorImpl&lt; TailCallArgumentInfo &gt; &amp;TailCallArgs, SmallVectorImpl&lt; SDValue &gt; &amp;MemOpChains, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>StoreTailCallArgumentsToStackSlot - Stores arguments to their stack slot. <a href="#a7fcdf2ea020f761f9857bebbc35a2ca3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca11c9d64a646da497e82dcf6e9636e">EmitTailCallStoreFPAndRetAddr</a> (SelectionDAG &amp;DAG, SDValue Chain, SDValue OldRetAddr, SDValue OldFP, int SPDiff, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitTailCallStoreFPAndRetAddr - Move the frame pointer and return address to the appropriate stack slot for the tail call optimized function call. <a href="#acca11c9d64a646da497e82dcf6e9636e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d6b4ddc639fabd7fed767dbedfecc2">CalculateTailCallArgDest</a> (SelectionDAG &amp;DAG, MachineFunction &amp;MF, bool IsPPC64, SDValue Arg, int SPDiff, unsigned ArgOffset, SmallVectorImpl&lt; TailCallArgumentInfo &gt; &amp;TailCallArguments)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CalculateTailCallArgDest - Remember <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> for later processing. <a href="#a24d6b4ddc639fabd7fed767dbedfecc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c9ebb68837f38cc7f83ab4fb11b3267">CreateCopyOfByValArgument</a> (SDValue Src, SDValue Dst, SDValue Chain, ISD::ArgFlagsTy Flags, SelectionDAG &amp;DAG, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CreateCopyOfByValArgument - Make a copy of an aggregate at address specified by "Src" to address "Dst" of size "Size". <a href="#a8c9ebb68837f38cc7f83ab4fb11b3267">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505cc141300c7ce5f68734af974b0961">LowerMemOpCallTo</a> (SelectionDAG &amp;DAG, MachineFunction &amp;MF, SDValue Chain, SDValue Arg, SDValue PtrOff, int SPDiff, unsigned ArgOffset, bool isPPC64, bool isTailCall, bool isVector, SmallVectorImpl&lt; SDValue &gt; &amp;MemOpChains, SmallVectorImpl&lt; TailCallArgumentInfo &gt; &amp;TailCallArguments, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LowerMemOpCallTo - Store the argument to the stack or remember it in case of tail calls. <a href="#a505cc141300c7ce5f68734af974b0961">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc71b3922c4a5138a77520c4e90f48bc">PrepareTailCall</a> (SelectionDAG &amp;DAG, SDValue &amp;InGlue, SDValue &amp;Chain, const SDLoc &amp;dl, int SPDiff, unsigned NumBytes, SDValue LROp, SDValue FPOp, SmallVectorImpl&lt; TailCallArgumentInfo &gt; &amp;TailCallArguments)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed64046c04e9e3d1c58346b9754ca258">isIndirectCall</a> (const SDValue &amp;Callee, SelectionDAG &amp;DAG, const PPCSubtarget &amp;Subtarget, bool isPatchPoint)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31220864cbe46fe951bcf083015c5456">isTOCSaveRestoreRequired</a> (const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04db783920e3a77ee7d48c5bc4d10b9a">getCallOpcode</a> (PPCTargetLowering::CallFlags CFlags, const Function &amp;Caller, const SDValue &amp;Callee, const PPCSubtarget &amp;Subtarget, const TargetMachine &amp;TM, bool IsStrictFPCall=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a> (const SDValue &amp;Callee, SelectionDAG &amp;DAG, const SDLoc &amp;dl, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5e8c9dbcb859012df08536bd29da15">getOutputChainFromCallSeq</a> (SDValue CallSeqStart)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab168199965da793c664f4cff94912e32">prepareIndirectCall</a> (SelectionDAG &amp;DAG, SDValue &amp;Callee, SDValue &amp;Glue, SDValue &amp;Chain, const SDLoc &amp;dl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a> (SelectionDAG &amp;DAG, SDValue &amp;Callee, SDValue &amp;Glue, SDValue &amp;Chain, SDValue CallSeqStart, const CallBase *CB, const SDLoc &amp;dl, bool hasNest, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980b47a164c04c64274ef41dba790718">buildCallOperands</a> (SmallVectorImpl&lt; SDValue &gt; &amp;Ops, PPCTargetLowering::CallFlags CFlags, const SDLoc &amp;dl, SelectionDAG &amp;DAG, SmallVector&lt; std::pair&lt; unsigned, SDValue &gt;, 8 &gt; &amp;RegsToPass, SDValue Glue, SDValue Chain, SDValue &amp;Callee, int SPDiff, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a4718b6006abc33142947dd02f514c8">isGPRShadowAligned</a> (MCPhysReg Reg, Align RequiredAlign)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a> (unsigned ValNo, MVT ValVT, MVT LocVT, CCValAssign::LocInfo LocInfo, ISD::ArgFlagsTy ArgFlags, CCState &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099b7b63cc740087f30c454001830e64">getRegClassForSVT</a> (MVT::SimpleValueType SVT, bool IsPPC64, bool HasP8Vector, bool HasVSX)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adafeb00ea78374224e3589c91b88f02e">truncateScalarIntegerArg</a> (ISD::ArgFlagsTy Flags, EVT ValVT, SelectionDAG &amp;DAG, SDValue ArgValue, MVT LocVT, const SDLoc &amp;dl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239d964ac9520cb492a050586bab9d35">mapArgRegToOffsetAIX</a> (unsigned Reg, const PPCFrameLowering *FL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc745e417d5815b8bddcf4081ff4047">getPPCStrictOpcode</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8731851366e0258bc7a96535eb33a91">convertFPToInt</a> (SDValue Op, SelectionDAG &amp;DAG, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad8af7f88fb14d1962f65ab4d2d44cd">convertIntToFP</a> (SDValue Op, SDValue Src, SelectionDAG &amp;DAG, const PPCSubtarget &amp;Subtarget, SDValue Chain=SDValue())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02f74d10de6f047ef79ac40cd5cfeea0">getCanonicalConstSplat</a> (uint64_t Val, unsigned SplatSize, EVT VT, SelectionDAG &amp;DAG, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCanonicalConstSplat - Build a canonical splat immediate of Val with an element size of SplatSize. <a href="#a02f74d10de6f047ef79ac40cd5cfeea0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b41ee83365bacbeb6829da71fd2331d">BuildIntrinsicOp</a> (unsigned IID, SDValue Op, SelectionDAG &amp;DAG, const SDLoc &amp;dl, EVT DestVT=MVT::Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BuildIntrinsicOp - Return a unary operator intrinsic node with the specified intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a7b41ee83365bacbeb6829da71fd2331d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af46b4d16e39c0322d1cc8f97f06e9aa9">BuildIntrinsicOp</a> (unsigned IID, SDValue LHS, SDValue RHS, SelectionDAG &amp;DAG, const SDLoc &amp;dl, EVT DestVT=MVT::Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BuildIntrinsicOp - Return a binary operator intrinsic node with the specified intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#af46b4d16e39c0322d1cc8f97f06e9aa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e79d872499713794b6d7471257e853">BuildIntrinsicOp</a> (unsigned IID, SDValue Op0, SDValue Op1, SDValue Op2, SelectionDAG &amp;DAG, const SDLoc &amp;dl, EVT DestVT=MVT::Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BuildIntrinsicOp - Return a ternary operator intrinsic node with the specified intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a27e79d872499713794b6d7471257e853">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd4d13d2870aab5355ab9b462573c193">BuildVSLDOI</a> (SDValue LHS, SDValue RHS, unsigned Amt, EVT VT, SelectionDAG &amp;DAG, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BuildVSLDOI - Return a VECTOR_SHUFFLE that is a vsldoi of the specified amount. <a href="#acd4d13d2870aab5355ab9b462573c193">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d1f680d02d55bbd8ac9bbd62dcfe01">haveEfficientBuildVectorPattern</a> (BuildVectorSDNode *V, bool HasDirectMove, bool HasP8Vector)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do we have an efficient pattern in a .td file for this node? <a href="#a62d1f680d02d55bbd8ac9bbd62dcfe01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5504ff57aff2070132ce601e1a25924">getNormalLoadInput</a> (const SDValue &amp;Op, bool &amp;IsPermuted)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca34d64e6bca0d10314f1308d636ecf8">isValidSplatLoad</a> (const PPCSubtarget &amp;Subtarget, const SDValue &amp;Op, unsigned &amp;Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab412ed28f090cbd85f13e2dbf3a52377">GeneratePerfectShuffle</a> (unsigned PFEntry, SDValue LHS, SDValue RHS, SelectionDAG &amp;DAG, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GeneratePerfectShuffle - Given an entry in the perfect-shuffle table, emit the specified operations to build the shuffle. <a href="#ab412ed28f090cbd85f13e2dbf3a52377">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac06076876542c9f3f22c47f36c2edb9d">getVectorCompareInfo</a> (SDValue Intrin, int &amp;CompareOpc, bool &amp;isDot, const PPCSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getVectorCompareInfo - Given an intrinsic, return false if it is not a vector comparison. <a href="#ac06076876542c9f3f22c47f36c2edb9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c14200e1f694991be37e9f9c9d9d576">getDataClassTest</a> (SDValue Op, FPClassTest Mask, const SDLoc &amp;Dl, SelectionDAG &amp;DAG, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3ff3fef7a854e7b213f166670c2aca">callIntrinsic</a> (IRBuilderBase &amp;Builder, Intrinsic::ID Id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acacabd3f0f046363943532ed7100dacc">isSignExtended</a> (MachineInstr &amp;MI, const PPCInstrInfo *TII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c194c51d42f6cb99a5495af70cfb65">IsSelectCC</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e8a1ef711294cc52d6e2c41279f4c0f">IsSelect</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb8ed05f5ebe5a8e1b2805675e61a8db">getEstimateRefinementSteps</a> (EVT VT, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6300a9ba945a7f25b504a3213c4acea5">getBaseWithConstantOffset</a> (SDValue Loc, SDValue &amp;Base, int64_t &amp;Offset, SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d9494014ff9dbd992928542dee2e477">isConsecutiveLSLoc</a> (SDValue Loc, EVT VT, LSBaseSDNode *Base, unsigned Bytes, int Dist, SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915e43885fb2c475d2618dd41c58ed5d">isConsecutiveLS</a> (SDNode *N, LSBaseSDNode *Base, unsigned Bytes, int Dist, SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a> (LoadSDNode *LD, SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f3670e08c57a95d0a5d9e442d9f322f">generateEquivalentSub</a> (SDNode *N, int Size, bool Complement, bool Swap, SDLoc &amp;DL, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is called when we have proved that a SETCC node can be replaced by subtraction (and other supporting instructions) so that the result of comparison is kept in a GPR instead of CR. <a href="#a1f3670e08c57a95d0a5d9e442d9f322f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a489ebd3081c2386cf2f4c5bbee8fd3">isFPExtLoad</a> (SDValue Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8092b588e16c93a54d21da99af4814c">combineBVOfConsecutiveLoads</a> (SDNode *N, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reduce the number of loads when building a vector. <a href="#af8092b588e16c93a54d21da99af4814c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a0cd3e4178d08fadb03d4e4e9404dcd">addShuffleForVecExtend</a> (SDNode *N, SelectionDAG &amp;DAG, SDValue Input, uint64_t Elems, uint64_t CorrectElems)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af31a972f3279158ab9801b78f1f92e1f">combineBVOfVecSExt</a> (SDNode *N, SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6651de6f4b40c5d58ecbf97fad85374">combineBVZEXTLOAD</a> (SDNode *N, SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15282d1ec89ab282e4bc3294aeee327d">isAlternatingShuffMask</a> (const ArrayRef&lt; int &gt; &amp;Mask, int NumElts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2dfc377679a894a30550de4dd545010">isSplatBV</a> (SDValue Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9bc3395487329e5c33cb362b712a371">isScalarToVec</a> (SDValue Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df1b82e469730d220e3a8d28eb985e8">fixupShuffleMaskForPermutedSToV</a> (SmallVectorImpl&lt; int &gt; &amp;ShuffV, int LHSFirstElt, int LHSLastElt, int RHSFirstElt, int RHSLastElt, int HalfVec, unsigned LHSNumValidElts, unsigned RHSNumValidElts, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6388d46f1b629bc93ef3a8b25d61c141">getSToVPermuted</a> (SDValue OrigSToV, SelectionDAG &amp;DAG, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15284c7be03d0a67993cbb5024de85cf">isShuffleMaskInRange</a> (const SmallVectorImpl&lt; int &gt; &amp;ShuffV, int HalfVec, int LHSLastElementDefined, int RHSLastElementDefined)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4809cfaa4940985ecc6dd5f78d24ffc4">generateSToVPermutedForVecShuffle</a> (int ScalarSize, uint64_t ShuffleEltWidth, unsigned &amp;NumValidElts, int FirstElt, int &amp;LastElt, SDValue VecShuffOperand, SDValue SToVNode, SelectionDAG &amp;DAG, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e897dd9e9942885e377bfdc0fb746c">isStoreConditional</a> (SDValue Intrin, unsigned &amp;StoreWidth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac285b8758124348fb08b040c03d672dd">invertFMAOpcode</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0cac8b7a7acd364d34649335444ceb">stripModuloOnShift</a> (const TargetLowering &amp;TLI, SDNode *N, SelectionDAG &amp;DAG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb8184c9c7806da491d6facc22a7fba">combineADDToADDZE</a> (SDNode *N, SelectionDAG &amp;DAG, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc82b70727afff2c18b36c0a6c280cd">combineADDToMAT_PCREL_ADDR</a> (SDNode *N, SelectionDAG &amp;DAG, const PPCSubtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a310a2b4f7197b620ecb3babef5637cc2">setAlignFlagsForFI</a> (SDValue N, unsigned &amp;FlagSet, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set alignment flags based on whether or not the Frame Index is aligned. <a href="#a310a2b4f7197b620ecb3babef5637cc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd35cd6dd267ca162a87fac0acb4925">computeFlagsForAddressComputation</a> (SDValue N, unsigned &amp;FlagSet, SelectionDAG &amp;DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a node, compute flags that are used for address computation when selecting load and store instructions. <a href="#adcd35cd6dd267ca162a87fac0acb4925">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bbe57bdaf29b707d8015c6268016aaa">isPCRelNode</a> (SDValue N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a853a1693caf74a6f250655800e136595">setXFormForUnalignedFI</a> (SDValue N, unsigned Flags, PPC::AddrMode &amp;Mode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f6e181466687153766e195e20fea37">getIntrinsicForAtomicRMWBinOp128</a> (AtomicRMWInst::BinOp BinOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0201c87e6816e6372f163c9ee04a4ed">DisableP10StoreForward</a>("disable-p10-store-forward", cl::desc("disable P10 store forward-friendly conversion"), cl::Hidden, cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4abb7e9879643e764ba92b14f2802d0">DisablePPCPreinc</a>("disable-ppc-preinc", cl::desc("disable preincrement load/store generation on PPC"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af35d4876c650d69c3ae5fa79c5e32672">DisableILPPref</a>("disable-ppc-ilp-pref", cl::desc("disable setting the node scheduling preference to ILP on PPC"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c09895eaf1069239b0494b5e5c10187">DisablePPCUnaligned</a>("disable-ppc-unaligned", cl::desc("disable unaligned load/store generation on PPC"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1f5818dff822f8a19c08c6059b0e6f5">DisableSCO</a>("disable-ppc-sco", cl::desc("disable sibling call optimization on ppc"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a81754664d4a526243dfdb8d26fec3b">DisableInnermostLoopAlign32</a>("disable-ppc-innermost-loop-align32", cl::desc("don't always align innermost loop to 32 bytes on ppc"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8486eb6b484e597fa39976e4b191daa5">UseAbsoluteJumpTables</a>("ppc-use-absolute-jumptables", cl::desc("use absolute jump tables on ppc"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba437396b90a72b15d89706bab223dfb">DisablePerfectShuffle</a>("ppc-disable-perfect-shuffle", cl::desc("disable vector permute decomposition"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97df817420072d29fd6c0a0f6cae83ab">DisableAutoPairedVecSt</a>("disable-auto-paired-vec-st", cl::desc("disable automatically generated 32byte paired vector stores"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a4451494d89396b365cb9a16b4543f">PPCMinimumJumpTableEntries</a>("ppc-min-jump-table-entries", cl::init(64), cl::Hidden, cl::desc("Set minimum number of entries to use a jump table on PPC"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507e89e4a7eefc0b875817f3f3362dc6">PPCGatherAllAliasesMaxDepth</a>("ppc-gather-alias-max-depth", cl::init(18), cl::Hidden, cl::desc("max depth when checking alias info in GatherAllAliases()"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc346a4ca386d721f3e30ed2ba23f9d">PPCAIXTLSModelOptUseIEForLDLimit</a>("ppc-aix-shared-lib-tls-model-opt-limit", cl::init(1), cl::Hidden, cl::desc("Set inclusive limit count of TLS local-dynamic access(es) in a " "function to use initial-exec"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80083daf41bf6d643ef8e00f171955f5">AIXSSPCanaryWordName</a>[] = "__ssp_canary_word"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af8c1082c0cbfb29e01b28814af0b73">AIXSmallTlsPolicySizeLimit</a> = 32751</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4395aff483110443e2b003a6f525d05">ANDIGlueBug</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587c39adeaa08f2c374d7bc55731513a">FPR</a>[] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FPR - The set of FP registers that should be allocated for arguments on Darwin and AIX. <a href="#a587c39adeaa08f2c374d7bc55731513a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"ppc-lowering"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97de2baad077d3029a9cb8f211cf67c1">GET_REGISTER_MATCHER</a></td>
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

### addShuffleForVecExtend() {#a1a0cd3e4178d08fadb03d4e4e9404dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue addShuffleForVecExtend (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Input, uint64_t Elems, uint64_t CorrectElems)</td>
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



<p>Definition at line 15168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>.</p>


<p>Referenced by <a href="#af31a972f3279158ab9801b78f1f92e1f">combineBVOfVecSExt</a>.</p>

</div>
</div>

### areCallingConvEligibleForTCO\_64SVR4() {#a582533c1a8f8a0a26833f84f2c2fc082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areCallingConvEligibleForTCO_64SVR4 (CallingConv::ID CallerCC, CallingConv::ID CalleeCC)</td>
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



<p>Definition at line 5056 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>.</p>

</div>
</div>

### buildCallOperands() {#a980b47a164c04c64274ef41dba790718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void buildCallOperands (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags">PPCTargetLowering::CallFlags</a> CFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;, 8 &gt; &amp; RegsToPass, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Glue, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Callee, int SPDiff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 5724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags/#af2db3e19dc2ffa8c67cf481a8f197dd5">llvm::PPCTargetLowering::CallFlags::CallConv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a83ffd45d02f1a8d9920e4508c5ec0970">llvm::PPCSubtarget::getEnvironmentPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a575f4bd95265cbe937901965fe1a53af">llvm::PPCSubtarget::getFrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab85f5fcb2f3bb0aaf83041a41182a2d4">llvm::SelectionDAG::getIntPtrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#aeefe52b8561be26c1281d79be439cd26">llvm::PPCSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acfe1250a2214797a59c6457dd2180df9">llvm::SelectionDAG::getRegisterMask</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3e8f6570461d1fd818dbfbf7ff03283a">llvm::PPCSubtarget::getScalarIntVT</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ac3d33dfd2b7568f38f08c7e6a60496b6">llvm::PPCSubtarget::getStackPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ac1ff4a166a708dddd7c3df1d2fac540f">llvm::PPCSubtarget::getTOCPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af2c21693e6284bea34b3ebbece45efdd">llvm::PPCFrameLowering::getTOCSaveOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags/#a74e18bdef06bd9e6b703302ba5ccbdee">llvm::PPCTargetLowering::CallFlags::HasNest</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a137ee29e981a9a091e81b79888d8b4a6">llvm::PPCSubtarget::is32BitELFABI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ad1a6a1f934a55d58ec73ea20aacbbb68">llvm::PPCSubtarget::is64BitELFABI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3ff0ba05eddb8771ac2f2ff7e56aa054">llvm::PPCSubtarget::isAIXABI</a>, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags/#a2c9e4ca12154076c8da225efd722b48e">llvm::PPCTargetLowering::CallFlags::IsIndirect</a>, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags/#a103e605f56024aed192adba2dbb72316">llvm::PPCTargetLowering::CallFlags::IsPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags/#ade4d56b32521a7e9beee5827a349baa4">llvm::PPCTargetLowering::CallFlags::IsTailCall</a>, <a href="#a31220864cbe46fe951bcf083015c5456">isTOCSaveRestoreRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6a2a00931f022fa78f6cdadb07e6d775">llvm::PPCSubtarget::isUsingPCRelativeCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags/#a35f9d611fd81427bb77bed0744af981e">llvm::PPCTargetLowering::CallFlags::IsVarArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">llvm::PPCSubtarget::usesFunctionDescriptors</a>.</p>

</div>
</div>

### BuildIntrinsicOp() {#a7b41ee83365bacbeb6829da71fd2331d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BuildIntrinsicOp (unsigned IID, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DestVT=MVT::Other)</td>
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

<p>BuildIntrinsicOp - Return a unary operator intrinsic node with the specified intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 9408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### BuildIntrinsicOp() {#af46b4d16e39c0322d1cc8f97f06e9aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BuildIntrinsicOp (unsigned IID, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DestVT=MVT::Other)</td>
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

<p>BuildIntrinsicOp - Return a binary operator intrinsic node with the specified intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 9417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### BuildIntrinsicOp() {#a27e79d872499713794b6d7471257e853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BuildIntrinsicOp (unsigned IID, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op0, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op1, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op2, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DestVT=MVT::Other)</td>
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

<p>BuildIntrinsicOp - Return a ternary operator intrinsic node with the specified intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 9427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>.</p>

</div>
</div>

### BuildVSLDOI() {#acd4d13d2870aab5355ab9b462573c193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue BuildVSLDOI (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, unsigned Amt, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>BuildVSLDOI - Return a VECTOR_SHUFFLE that is a vsldoi of the specified amount.</p>


<p>The result has the specified value type.</p>


<p>Definition at line 9437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ab412ed28f090cbd85f13e2dbf3a52377">GeneratePerfectShuffle</a>.</p>

</div>
</div>

### CalculateStackSlotAlignment() {#a5e0048496768e682947aedca8e3aa3d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align CalculateStackSlotAlignment (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ArgVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OrigVT, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, unsigned PtrByteSize)</td>
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

<p>CalculateStackSlotAlignment - Calculates the alignment of this argument on the stack.</p>

<p>Definition at line 4141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#aeaf413c8efe075d4666f4d526c527ffd">CalculateStackSlotUsed</a>.</p>

</div>
</div>

### CalculateStackSlotSize() {#aacd7e508c9e6dd17afc738da27b87bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CalculateStackSlotSize (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ArgVT, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, unsigned PtrByteSize)</td>
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

<p>CalculateStackSlotSize - Calculates the size reserved for this argument on the stack.</p>

<p>Definition at line 4125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>.</p>


<p>Referenced by <a href="#aeaf413c8efe075d4666f4d526c527ffd">CalculateStackSlotUsed</a>.</p>

</div>
</div>

### CalculateStackSlotUsed() {#aeaf413c8efe075d4666f4d526c527ffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CalculateStackSlotUsed (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ArgVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OrigVT, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, unsigned PtrByteSize, unsigned LinkageSize, unsigned ParamAreaSize, unsigned &amp; ArgOffset, unsigned &amp; AvailableFPRs, unsigned &amp; AvailableVRs)</td>
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

<p>CalculateStackSlotUsed - Return whether this argument will use its stack slot (instead of being passed in registers).</p>


<p>ArgOffset, AvailableFPRs, and AvailableVRs must hold the current argument position, and will be updated to account for this argument.</p>


<p>Definition at line 4183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="#a5e0048496768e682947aedca8e3aa3d9">CalculateStackSlotAlignment</a> and <a href="#aacd7e508c9e6dd17afc738da27b87bc2">CalculateStackSlotSize</a>.</p>


<p>Referenced by <a href="#a0ccb1948e466b25257ec5f95a2b8e11e">needStackSlotPassParameters</a>.</p>

</div>
</div>

### CalculateTailCallArgDest() {#a24d6b4ddc639fabd7fed767dbedfecc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CalculateTailCallArgDest (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, bool IsPPC64, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Arg, int SPDiff, unsigned ArgOffset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; TailCallArgumentInfo &gt; &amp; TailCallArguments)</td>
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

<p>CalculateTailCallArgDest - Remember <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> for later processing.</p>


<p>Calculate the position of the argument.</p>


<p>Definition at line 5259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a8915297f72f1020167562805827f7160">llvm::SDValue::getValueSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a505cc141300c7ce5f68734af974b0961">LowerMemOpCallTo</a>.</p>

</div>
</div>

### CalculateTailCallSPDiff() {#aaf0bcfcb9ee7e078bec6074304e31cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int CalculateTailCallSPDiff (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, bool isTailCall, unsigned ParamSize)</td>
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

<p>CalculateTailCallSPDiff - Get the amount the stack pointer has to be adjusted to accommodate the arguments for the tailcall.</p>

<p>Definition at line 4894 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#aacbb35468239038634c099ca495dcaab">llvm::PPCFunctionInfo::getMinReservedArea</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a7780eaaa923683ff9eac5b49916136bc">llvm::PPCFunctionInfo::setTailCallSPDelta</a>.</p>

</div>
</div>

### callIntrinsic() {#aaf3ff3fef7a854e7b213f166670c2aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * callIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> Id)</td>
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



<p>Definition at line 12316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a80eec4efbded89b11092babf42a65b82">llvm::IRBuilderBase::CreateIntrinsic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#aff4c3b2eec63855bda40615dece5853f">llvm::PPCTargetLowering::emitLeadingFence</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a1c68a6f0cdbdeb8a431791ad286109a0">llvm::PPCTargetLowering::emitTrailingFence</a>.</p>

</div>
</div>

### callsShareTOCBase() {#a43a17d867ea4d3bca00dfb065f8cc811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool callsShareTOCBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * CalleeGV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Definition at line 4911 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a311a097af4f0f77da22ac7acddc496f5">llvm::GlobalAlias::getAliaseeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a7215706ede5f29b81e4f99af35e87aa6">llvm::GlobalValue::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa9e5c8e6f11bf0df2b3e220bb6557418">llvm::GlobalValue::hasComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a904b8b68c7e4e888158b03f0eae0e4d5">llvm::GlobalValue::isStrongDefinitionForLinker</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6a2a00931f022fa78f6cdadb07e6d775">llvm::PPCSubtarget::isUsingPCRelativeCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>.</p>


<p>Referenced by <a href="#a04db783920e3a77ee7d48c5bc4d10b9a">getCallOpcode</a>.</p>

</div>
</div>

### CC\_AIX() {#a63e41a021ab399fe0054faade8a184b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_AIX (unsigned ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; S)</td>
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



<p>Definition at line 6865 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a587c39adeaa08f2c374d7bc55731513a">FPR</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#ab366d3f0cbcf25efa33e8406c851be4f">llvm::ISD::ArgFlagsTy::getByValSize</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab3ca02e9c44d57c994cc5351c24f6223">llvm::CCValAssign::getCustomMem</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a3213a94802bb4f87a3e388af6cdd9d7f">llvm::CCValAssign::getCustomReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a874fbbec4937797974c9d5056769421a">llvm::MVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a36d9dd26dea75ebba5b55516b52e0752">llvm::CCValAssign::getMem</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#af9b5cd986cb3591eeb24b5448fb66142">llvm::ISD::ArgFlagsTy::getNonZeroByValAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a29708e79e029f1029d46d65e7631b778">llvm::CCValAssign::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3e8f6570461d1fd818dbfbf7ff03283a">llvm::PPCSubtarget::getScalarIntVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ab8e1af73424a59a00656c9ffd505c03f">llvm::MVT::getStoreSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64daf4f312520aaba4506b874a3f83fe2464">llvm::MVT::INVALID_SIMPLE_VALUE_TYPE</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#abaf9cc57d53cc8554954965b74037ad3">llvm::ISD::ArgFlagsTy::isByVal</a>, <a href="#a0a4718b6006abc33142947dd02f514c8">isGPRShadowAligned</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#a009d7b979b89268cdf5040286d883b1d">llvm::ISD::ArgFlagsTy::isNest</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty/#aaa6158ce48c81c608caeaf2317a43244">llvm::ISD::ArgFlagsTy::isSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a7fd25972cdb14499949c7726499e0cb6">llvm::CCValAssign::SExt</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">llvm::CCValAssign::ZExt</a>.</p>

</div>
</div>

### combineADDToADDZE() {#a1cb8184c9c7806da491d6facc22a7fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue combineADDToADDZE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 18206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a20084f62caecb0db80ad71bdabda73c2">llvm::ISD::ADDC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad116e32876f2275acf60ffb1651c9256">llvm::ISD::ADDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2ab6db512a611d1ef4ff8069e2bbfd0d">llvm::ISD::SUBC</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### combineADDToMAT\_PCREL\_ADDR() {#a2fc82b70727afff2c18b36c0a6c280cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue combineADDToMAT_PCREL_ADDR (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 18292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#aac749351927cd1732994a39d40fdd4f2">llvm::GlobalAddressSDNode::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#a28a0dd6ccd1cfe2a3d171685b02adab2">llvm::GlobalAddressSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a75d113cb1b8cc3c14b601d928dccee40">llvm::ConstantSDNode::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#aaa872c53c94e16365bccd1de26fda44a">llvm::GlobalAddressSDNode::getTargetFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a05c0ae3eb411a8c53a6ce48b66c0d3f8">llvm::SelectionDAG::getTargetGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac0a534d63ac5c5b87f36acdade953fbe">llvm::SDNode::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6a2a00931f022fa78f6cdadb07e6d775">llvm::PPCSubtarget::isUsingPCRelativeCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a57dec08b9c245de78b203b5ce73a85a3">llvm::PPCISD::MAT_PCREL_ADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### combineBVOfConsecutiveLoads() {#af8092b588e16c93a54d21da99af4814c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue combineBVOfConsecutiveLoads (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Reduce the number of loads when building a vector.</p>


<p>Building a vector out of multiple loads can be converted to a load of the vector type if the loads are consecutive. If the loads are consecutive but in descending order, a shuffle is added at the end to reorder the vector.</p>


<p>Definition at line 15070 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a776d43d877fa5cb4d75783e63990cc58">llvm::SelectionDAG::areNonVolatileConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#a5ba669acfce53f64119001f5d46e162f">llvm::MemSDNode::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a20fd5ba47db6a4cc8ad9d197fc1bbbee">llvm::LoadSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab858661e16a61c4fc6b27b6b26aac17b">llvm::MemSDNode::getChain</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#ad85ec82447c2f1824538de9b449ffed0">llvm::LoadSDNode::getExtensionType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab58a98ad2eb07046ef0584d2bc8f1d2d">llvm::MemSDNode::getPointerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a25c0550227f31c7368fcefb62d72fcf1">llvm::SelectionDAG::makeEquivalentMemoryOrdering</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### combineBVOfVecSExt() {#af31a972f3279158ab9801b78f1f92e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue combineBVOfVecSExt (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 15207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="#a1a0cd3e4178d08fadb03d4e4e9404dcd">addShuffleForVecExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a5cb49674ec65724b4d9aecb48588a13a">llvm::ConstantSDNode::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a377365b0288a4d06a07e09252d7d583f">llvm::DataLayout::isLittleEndian</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>.</p>

</div>
</div>

### combineBVZEXTLOAD() {#ad6651de6f4b40c5d58ecbf97fad85374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue combineBVZEXTLOAD (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 15305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab85f5fcb2f3bb0aaf83041a41182a2d4">llvm::SelectionDAG::getIntPtrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ae507654c72e23edbb1c74349cb5cfe33">llvm::PPCISD::LXVRZX</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a8d89c7da4444d9ec11667aa369abc5f7">llvm::ISD::ZEXTLOAD</a>.</p>

</div>
</div>

### computeFlagsForAddressComputation() {#adcd35cd6dd267ca162a87fac0acb4925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeFlagsForAddressComputation (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned &amp; FlagSet, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Given a node, compute flags that are used for address computation when selecting load and store instructions.</p>


<p>The flags computed are stored in FlagSet. This function takes into account whether the node is a constant, an ADD, OR, or a constant, and computes the address flags accordingly.</p>


<p>Definition at line 18621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a87d50d10274efe9688166584391ae489">llvm::APInt::isSignedIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19abcb9c462158b362a5edc6a1d754c9edb">llvm::PPCISD::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80ad344a01b52e5179abac75ab1b8dd1206">llvm::PPC::MOF_AddrIsSImm32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a39dce6c6e9c3f0bca83f48faf02267a3">llvm::PPC::MOF_NotAddNorCst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80ad559259939478cfc1e6b96bffd48e984">llvm::PPC::MOF_RPlusLo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a8ab07220ca2843f4957418b71b270feb">llvm::PPC::MOF_RPlusR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a3d549266ccdcd583d15c88dfaa9e7e4a">llvm::PPC::MOF_RPlusSImm16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a24a8014075c447b950e6ae5b5dec8587">llvm::PPC::MOF_RPlusSImm16Mult16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a9da404662425b672e194e163961479a3">llvm::PPC::MOF_RPlusSImm16Mult4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a9b668ad2bc8ce251393fad3ee3243948">llvm::PPC::MOF_RPlusSImm34</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a3c48cdb4fcbd71e51a4ec4c1d5c6a99a">provablyDisjointOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a310a2b4f7197b620ecb3babef5637cc2">setAlignFlagsForFI</a>.</p>

</div>
</div>

### convertFPToInt() {#aa8731851366e0258bc7a96535eb33a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue convertFPToInt (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 8383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a062083eb3ff8c441c73d3bf42ca09bba">llvm::ISD::DELETED_NODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a043df81d8fc961c94e42fc8fa2c71331">llvm::PPCISD::FCTIDUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2a79156c141fbb0faadd358c767b906b">llvm::PPCISD::FCTIDZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a88c7793fdfe5003a35e5cac9a3527eb9">llvm::PPCISD::FCTIWUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2a6e33357fd46c15294432ab65adecec">llvm::PPCISD::FCTIWZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aadfdefcb133a7f0262a05934aba8ce5d">llvm::ISD::FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="#aefc745e417d5815b8bddcf4081ff4047">getPPCStrictOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3e8f6570461d1fd818dbfbf7ff03283a">llvm::PPCSubtarget::getScalarIntVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a3c1975d73b1b774848a55f2996d28a8f">llvm::SDNodeFlags::setNoFPExcept</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>.</p>

</div>
</div>

### convertIntToFP() {#acad8af7f88fb14d1962f65ab4d2d44cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue convertIntToFP (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Src, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>())</td>
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



<p>Definition at line 8710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a7d46bc38a9f3de58adde307de9c5e892">llvm::PPCISD::FCFID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a7e06dc9bf94c1b690b4379bec9d64962">llvm::PPCISD::FCFIDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aea46f7cc94ac666cf413d686484ce45d">llvm::PPCISD::FCFIDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa52f8d0b1001830d27a193285d4a7090">llvm::PPCISD::FCFIDUS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="#aefc745e417d5815b8bddcf4081ff4047">getPPCStrictOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a196c23d6cb4d768d037970f1f35bbf66">llvm::SelectionDAG::getVTList</a>, <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags/#a3c1975d73b1b774848a55f2996d28a8f">llvm::SDNodeFlags::setNoFPExcept</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a315004656a75a3c3a9d7294f105a8da2">llvm::ISD::SINT_TO_FP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab38d2af541b99492acf69c041c98bcb6">llvm::ISD::STRICT_SINT_TO_FP</a>.</p>

</div>
</div>

### CreateCopyOfByValArgument() {#a8c9ebb68837f38cc7f83ab4fb11b3267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue CreateCopyOfByValArgument (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Src, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>CreateCopyOfByValArgument - Make a copy of an aggregate at address specified by "Src" to address "Dst" of size "Size".</p>


<p>Alignment information is specified by the specific parameter attribute. The copy will be passed as a byval function parameter. Sometimes what we are copying is the end of a larger object, the part that does not fit in registers.</p>


<p>Definition at line 5297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>.</p>

</div>
</div>

### EmitTailCallStoreFPAndRetAddr() {#acca11c9d64a646da497e82dcf6e9636e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue EmitTailCallStoreFPAndRetAddr (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> OldRetAddr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> OldFP, int SPDiff, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>EmitTailCallStoreFPAndRetAddr - Move the frame pointer and return address to the appropriate stack slot for the tail call optimized function call.</p>

<p>Definition at line 5237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a575f4bd95265cbe937901965fe1a53af">llvm::PPCSubtarget::getFrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3e8f6570461d1fd818dbfbf7ff03283a">llvm::PPCSubtarget::getScalarIntVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>.</p>


<p>Referenced by <a href="#acc71b3922c4a5138a77520c4e90f48bc">PrepareTailCall</a>.</p>

</div>
</div>

### EnsureStackAlignment() {#a6d38e4f90c68ce910c9f3c303fcb5b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned EnsureStackAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering">PPCFrameLowering</a> * Lowering, unsigned NumBytes)</td>
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

<p>EnsureStackAlignment - Round stack frame size up from NumBytes to ensure minimum alignment required for target.</p>

<p>Definition at line 4231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#a77cabd8c10802136c4ab03db0156e41e">Lowering</a>.</p>

</div>
</div>

### findConsecutiveLoad() {#a1e2f76e32afeff50a4cae3055b365099}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool findConsecutiveLoad (<a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * LD, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 14248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a76b3fc7c102561fb5210d5151531e409">llvm::SmallSet&lt; T, N, C &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a1572b31fadbd0d758314b8d35a050410">llvm::EVT::getStoreSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a915e43885fb2c475d2618dd41c58ed5d">isConsecutiveLS</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a0cdd5176dc41b96586448ecc59770250">llvm::SDNode::ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a> and <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad5596cf1822f4cc9e37fb75b6dff630f">llvm::SDNode::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### fixupFuncForFI() {#aa45779e6cfae9dac4c65a6aa4bbdab74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fixupFuncForFI (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, int FrameIdx, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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



<p>Definition at line 2784 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a312de8232fec3e0e128f4a34b7ddc55d">llvm::PPCTargetLowering::SelectAddressRegImm</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ae058898e63ec72af7e4ed9b50ac8fbec">llvm::PPCTargetLowering::SelectOptimalAddrMode</a>.</p>

</div>
</div>

### fixupShuffleMaskForPermutedSToV() {#a9df1b82e469730d220e3a8d28eb985e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void fixupShuffleMaskForPermutedSToV (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; ShuffV, int LHSFirstElt, int LHSLastElt, int RHSFirstElt, int RHSLastElt, int HalfVec, unsigned LHSNumValidElts, unsigned RHSNumValidElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 15770 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ab9ff1051f03e5d6cb2ab582a0ff90409">llvm::PPCSubtarget::isLittleEndian</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### generateEquivalentSub() {#a1f3670e08c57a95d0a5d9e442d9f322f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue generateEquivalentSub (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, int Size, bool Complement, bool Swap, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>This function is called when we have proved that a SETCC node can be replaced by subtraction (and other supporting instructions) so that the result of comparison is kept in a GPR instead of CR.</p>


<p>This function is purely for codegen purposes and has some flags to guide the codegen process.</p>


<p>Definition at line 14314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### GeneratePerfectShuffle() {#ab412ed28f090cbd85f13e2dbf3a52377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue GeneratePerfectShuffle (unsigned PFEntry, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>GeneratePerfectShuffle - Given an entry in the perfect-shuffle table, emit the specified operations to build the shuffle.</p>

<p>Definition at line 9915 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="#acd4d13d2870aab5355ab9b462573c193">BuildVSLDOI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7266504e88c036bd48704ba439eababb">GeneratePerfectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6573bdc82df766157d1f225d13a527e4ac70742254f766c239332e57a2cb91041">OP_COPY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd6bd47b0848ff6057b0fe117cffd1db">llvm::PerfectShuffleTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### generateSToVPermutedForVecShuffle() {#a4809cfaa4940985ecc6dd5f78d24ffc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue generateSToVPermutedForVecShuffle (int ScalarSize, uint64_t ShuffleEltWidth, unsigned &amp; NumValidElts, int FirstElt, int &amp; LastElt, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> VecShuffOperand, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> SToVNode, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 15840 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="#a6388d46f1b629bc93ef3a8b25d61c141">getSToVPermuted</a> and <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>.</p>

</div>
</div>

### getBaseWithConstantOffset() {#a6300a9ba945a7f25b504a3213c4acea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getBaseWithConstantOffset (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Loc, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, int64_t &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 14119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a51e652265b0217f8fdba9f95129c0d47">getBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac520c40bfb7047936bcc2709c2153ebf">llvm::SelectionDAG::isBaseWithConstantOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getCallOpcode() {#a04db783920e3a77ee7d48c5bc4d10b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCallOpcode (<a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags">PPCTargetLowering::CallFlags</a> CFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Caller, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, bool IsStrictFPCall=false)</td>
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



<p>Definition at line 5462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a453b3ee2482b8a61bbcf5ce1cd6e395e">llvm::PPCISD::BCTRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a7382bd1ceab96ffedb276ad49b4308ca">llvm::PPCISD::BCTRL_LOAD_TOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8733bcf440af126f3cd4df36ec026da6">llvm::PPCISD::BCTRL_LOAD_TOC_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa82b0f1a7296f1ae77fe7a79dcd8631c">llvm::PPCISD::BCTRL_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa09dfd0e28e0ffea73ccfc88fb2fd95c">llvm::PPCISD::CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ada865a374b524adeca1892f0eed6eb0e">llvm::PPCISD::CALL_NOP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0a587e32cccf298ed32dfcefa59d08d9">llvm::PPCISD::CALL_NOP_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ab9d1ecf80764a45e6761396dfb71efdb">llvm::PPCISD::CALL_NOTOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a01495b70fc5bd028897c0b297fa2438f">llvm::PPCISD::CALL_NOTOC_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0ca86fac87a16ac9aa26f6ab3625a5aa">llvm::PPCISD::CALL_RM</a>, <a href="#a43a17d867ea4d3bca00dfb065f8cc811">callsShareTOCBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ad1a6a1f934a55d58ec73ea20aacbbb68">llvm::PPCSubtarget::is64BitELFABI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3ff0ba05eddb8771ac2f2ff7e56aa054">llvm::PPCSubtarget::isAIXABI</a>, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags/#a2c9e4ca12154076c8da225efd722b48e">llvm::PPCTargetLowering::CallFlags::IsIndirect</a>, <a href="/web-llvm/docs/api/structs/llvm/ppctargetlowering/callflags/#ade4d56b32521a7e9beee5827a349baa4">llvm::PPCTargetLowering::CallFlags::IsTailCall</a>, <a href="#a31220864cbe46fe951bcf083015c5456">isTOCSaveRestoreRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6a2a00931f022fa78f6cdadb07e6d775">llvm::PPCSubtarget::isUsingPCRelativeCalls</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa4dc9f480c199614ca9475c7969ead06">llvm::PPCISD::TC_RETURN</a>.</p>

</div>
</div>

### getCanonicalConstSplat() {#a02f74d10de6f047ef79ac40cd5cfeea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue getCanonicalConstSplat (uint64_t Val, unsigned SplatSize, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>getCanonicalConstSplat - Build a canonical splat immediate of Val with an element size of SplatSize.</p>


<p>Cast the result to VT.</p>


<p>Definition at line 9382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>.</p>

</div>
</div>

### getDataClassTest() {#a9c14200e1f694991be37e9f9c9d9d576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue getDataClassTest (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a> Mask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; Dl, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 11497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7e6dca8262a3de788d1bab4ba184d675">llvm::ISD::EXTRACT_ELEMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabf7829a22591343ad790b1357955a7df">llvm::fcAllFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da3ab665df1666568d7eac3b1373106638">llvm::fcNegInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab003a118cd0b76a814ba4dfc7077034a">llvm::fcNegNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da023ad3d9b33a1af5eb90b8b543fb3ccb">llvm::fcNegSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da1e8072411cd3959aa091c3cae8006dc0">llvm::fcNegZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dadb8c9ce3197adf47c7f889bab120b77c">llvm::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dada0d259988860d7a2f882aa40b25fee1">llvm::fcPosInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da052ace75708c251359ff22dd036417a6">llvm::fcPosNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dad0940edb5f5bf512669b72928b527d0c">llvm::fcPosSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da7ace586671df3e62fa392d5144a8b3da">llvm::fcPosZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da05bb099c0a65e5b835ed8cd0b326df7c">llvm::fcQNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da9d366dced7a639841b0ced40c82ccb28">llvm::fcSNan</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a64f6469ab95c4eec77e4ccf303619a81">llvm::SelectionDAG::getBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac2624b648ddca964183d631c8d189595">llvm::SelectionDAG::getBoolConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="#a9c14200e1f694991be37e9f9c9d9d576">getDataClassTest</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1c04c72abd24de2572a03ef686a36dd6">llvm::SelectionDAG::getMachineNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4adb0d9a6a73d75706dca1960dd7ec32">llvm::SelectionDAG::getNOT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2c237b0f007548cb6bc021d00ffee87f">llvm::SelectionDAG::getSetCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abf892d1e00a3d79026c5ab518c187c45">llvm::SelectionDAG::getTargetConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac597f2b1601a3acbac07347251e588f8">llvm::SelectionDAG::getVectorIdxConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ab9ff1051f03e5d6cb2ab582a0ff90409">llvm::PPCSubtarget::isLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6405223942a3a52775bb99d512dca2ada960b44c579bc2f6818d2daaf9e4c16f0">llvm::Normal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>.</p>


<p>Referenced by <a href="#a9c14200e1f694991be37e9f9c9d9d576">getDataClassTest</a>.</p>

</div>
</div>

### getEstimateRefinementSteps() {#acb8ed05f5ebe5a8e1b2805675e61a8db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getEstimateRefinementSteps (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 14007 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#aa85c75e8eb097f02caeb5b9119eebfef">llvm::EVT::getScalarType</a>.</p>

</div>
</div>

### getIntrinsicForAtomicRMWBinOp128() {#aa7f6e181466687153766e195e20fea37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID getIntrinsicForAtomicRMWBinOp128 (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> BinOp)</td>
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



<p>Definition at line 19157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0794c42b44989f9d9f1454d79ca0dd88">llvm::AtomicRMWInst::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b">llvm::AtomicRMWInst::Nand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5db6ca0c3e18acd87290f22ccb2ce564">llvm::AtomicRMWInst::Sub</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e">llvm::AtomicRMWInst::Xor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a0e0d3c023e19c20fbf01b40d36aced80">llvm::PPCTargetLowering::emitMaskedAtomicRMWIntrinsic</a>.</p>

</div>
</div>

### getLabelAccessInfo() {#a97dcf046ecd8a70a4ff620b38f187bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getLabelAccessInfo (bool IsPIC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget, unsigned &amp; HiOpFlags, unsigned &amp; LoOpFlags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV=nullptr)</td>
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

<p>Return true if we should reference labels using a PICBase, set the HiOpFlags and LoOpFlags to the target MO flags.</p>

<p>Definition at line 3157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffaf3ceb6d8d3d044088a869d52777a6ed6">llvm::PPCII::MO_HA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffacfbc322d45d593103140a6a0dd75e9cd">llvm::PPCII::MO_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffad28153a155549829b1d3c7c2c1f94eb3">llvm::PPCII::MO_PIC_HA_FLAG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffa374d4accc53d2911f6b45d9ae3c35941">llvm::PPCII::MO_PIC_LO_FLAG</a>.</p>

</div>
</div>

### getMaxByValAlign() {#a8baa555a40ec02c58a1e0455237f65f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getMaxByValAlign (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; MaxAlign, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> MaxMaxAlign)</td>
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

<p>getMaxByValAlign - Helper for getByValTypeAlignment to determine the desired ByVal argument alignment.</p>

<p>Definition at line 1618 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a8baa555a40ec02c58a1e0455237f65f9">getMaxByValAlign</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a51b3288a078ec78d279a486db1946b31">llvm::PPCTargetLowering::getByValTypeAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4fcc58c4d285835e0ac6fc644012b0be">llvm::X86TargetLowering::getByValTypeAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a79c9c6945a82cfdf0cd02fe49f3a4107">getMaxByValAlign</a> and <a href="#a8baa555a40ec02c58a1e0455237f65f9">getMaxByValAlign</a>.</p>

</div>
</div>

### getNormalLoadInput() {#ac5504ff57aff2070132ce601e1a25924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SDValue * getNormalLoadInput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, bool &amp; IsPermuted)</td>
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



<p>Definition at line 9524 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#afaaeadcd82b42fc0d385a6247bf7bb52">llvm::ISD::isNormalLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4b53fee9c411b207317f688e141e9128">llvm::PPCISD::SCALAR_TO_VECTOR_PERMUTED</a>.</p>

</div>
</div>

### getOutputChainFromCallSeq() {#aea5e8c9dbcb859012df08536bd29da15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue getOutputChainFromCallSeq (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> CallSeqStart)</td>
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



<p>Definition at line 5604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af423387cec5c9f7be16028b25a0dcfe7">llvm::ISD::CALLSEQ_START</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7f06dbaee5fa2b239de548d0a775b25b">llvm::SDNode::getNumValues</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a> and <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>.</p>


<p>Referenced by <a href="#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>.</p>

</div>
</div>

### getPPCStrictOpcode() {#aefc745e417d5815b8bddcf4081ff4047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getPPCStrictOpcode (unsigned Opc)</td>
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



<p>Definition at line 8360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a7d46bc38a9f3de58adde307de9c5e892">llvm::PPCISD::FCFID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a7e06dc9bf94c1b690b4379bec9d64962">llvm::PPCISD::FCFIDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aea46f7cc94ac666cf413d686484ce45d">llvm::PPCISD::FCFIDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa52f8d0b1001830d27a193285d4a7090">llvm::PPCISD::FCFIDUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a043df81d8fc961c94e42fc8fa2c71331">llvm::PPCISD::FCTIDUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2a79156c141fbb0faadd358c767b906b">llvm::PPCISD::FCTIDZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a88c7793fdfe5003a35e5cac9a3527eb9">llvm::PPCISD::FCTIWUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2a6e33357fd46c15294432ab65adecec">llvm::PPCISD::FCTIWZ</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a07c87149008709f85754a38b4f22adaf">llvm::PPCISD::STRICT_FCFID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a746850a5fa94a4ce3e8071b6219121f6">llvm::PPCISD::STRICT_FCFIDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a72a662f3bbd13bf94bf0262ac1d4e868">llvm::PPCISD::STRICT_FCFIDU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ab58ea28e66ebad19b7718055fc998f08">llvm::PPCISD::STRICT_FCFIDUS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8a5acab2f34e1b806efaa3ee64c5a3aa">llvm::PPCISD::STRICT_FCTIDUZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad00a593b7d71618f307d171781f5558d">llvm::PPCISD::STRICT_FCTIDZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a553b2f3eaf318b2455673f16cb396baf">llvm::PPCISD::STRICT_FCTIWUZ</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a8a852db39a510adbbbadbbdede7aa648">llvm::PPCISD::STRICT_FCTIWZ</a>.</p>


<p>Referenced by <a href="#aa8731851366e0258bc7a96535eb33a91">convertFPToInt</a> and <a href="#acad8af7f88fb14d1962f65ab4d2d44cd">convertIntToFP</a>.</p>

</div>
</div>

### getRegClassForSVT() {#a099b7b63cc740087f30c454001830e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * getRegClassForSVT (<a href="/web-llvm/docs/api/classes/llvm/mvt/#a184043a6ab3a9922618b34117003e64d">MVT::SimpleValueType</a> SVT, bool IsPPC64, bool HasP8Vector, bool HasVSX)</td>
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



<p>Definition at line 7107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getSToVPermuted() {#a6388d46f1b629bc93ef3a8b25d61c141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue getSToVPermuted (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> OrigSToV, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 15792 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a5cb49674ec65724b4d9aecb48588a13a">llvm::ConstantSDNode::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ab9ff1051f03e5d6cb2ab582a0ff90409">llvm::PPCSubtarget::isLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4b53fee9c411b207317f688e141e9128">llvm::PPCISD::SCALAR_TO_VECTOR_PERMUTED</a>.</p>


<p>Referenced by <a href="#a4809cfaa4940985ecc6dd5f78d24ffc4">generateSToVPermutedForVecShuffle</a>.</p>

</div>
</div>

### getVectorCompareInfo() {#ac06076876542c9f3f22c47f36c2edb9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getVectorCompareInfo (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Intrin, int &amp; CompareOpc, bool &amp; isDot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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

<p>getVectorCompareInfo - Given an intrinsic, return false if it is not a vector comparison.</p>


<p>If it is, return true and fill in Opc/isDot with information about the intrinsic.</p>


<p>Definition at line 10740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### hasSameArgumentList() {#a78c7e7972f2cde9531b9f9d71196cfc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasSameArgumentList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * CallerFn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 5025 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4fb513d744ca72275932b2c7003f16f6">llvm::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a8bf193a781a92cae52d7f9216d0824f8">llvm::Function::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### haveEfficientBuildVectorPattern() {#a62d1f680d02d55bbd8ac9bbd62dcfe01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool haveEfficientBuildVectorPattern (<a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode">BuildVectorSDNode</a> * V, bool HasDirectMove, bool HasP8Vector)</td>
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

<p>Do we have an efficient pattern in a .td file for this node?</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p>- pointer to the <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode">BuildVectorSDNode</a> being matched</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasDirectMove</td>
<td class="doxyParamItemDescription"><p>- does this subtarget have VSR &lt;-&gt; GPR direct moves?</p></td>
</tr>
</table>
</dd>
</dl>

<p>There are some patterns where it is beneficial to keep a BUILD_VECTOR node as a BUILD_VECTOR node rather than expanding it. The patterns where the opposite is true (expansion is beneficial) are:</p>


<ul class="doxyList ">
<li>The node builds a vector out of integers that are not 32 or 64-bits</li>
<li>The node builds a vector out of constants</li>
<li>The node is a "load-and-splat" In all other cases, we will choose to keep the BUILD_VECTOR.</li>
</ul>

<p>Definition at line 9462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>.</p>

</div>
</div>

### invertFMAOpcode() {#ac285b8758124348fb08b040c03d672dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned invertFMAOpcode (unsigned Opc)</td>
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



<p>Definition at line 17992 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a293ca68b3b2ce80eef991de822822254">llvm::ISD::FMA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a24c65ae2b770c0b178a4c2458586b058">llvm::PPCISD::FNMSUB</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isAlternatingShuffMask() {#a15282d1ec89ab282e4bc3294aeee327d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAlternatingShuffMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; &amp; Mask, int NumElts)</td>
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



<p>Definition at line 15718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### isBLACompatibleAddress() {#a5bbcfdc24a57cc8268f0278e0a03c156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * isBLACompatibleAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>isCallCompatibleAddress - Return the immediate to use if the specified 32-bit value is representable in the immediate field of a BxA instruction.</p>

<p>Definition at line 5191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8a2567d305d0f9929660220a4d6f916a">llvm::SelectionDAG::getSignedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abd6925150e1774fabfaff17efd3f9b9e">llvm::SignExtend32</a>.</p>


<p>Referenced by <a href="#aed64046c04e9e3d1c58346b9754ca258">isIndirectCall</a> and <a href="#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a>.</p>

</div>
</div>

### isConsecutiveLS() {#a915e43885fb2c475d2618dd41c58ed5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConsecutiveLS (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode">LSBaseSDNode</a> * Base, unsigned Bytes, int Dist, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 14171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc09e0bddd693dcf9923e4df42473bd9">llvm::ISD::INTRINSIC_W_CHAIN</a>, <a href="#a7d9494014ff9dbd992928542dee2e477">isConsecutiveLSLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a1e2f76e32afeff50a4cae3055b365099">findConsecutiveLoad</a>.</p>

</div>
</div>

### isConsecutiveLSLoc() {#a7d9494014ff9dbd992928542dee2e477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConsecutiveLSLoc (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Loc, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode">LSBaseSDNode</a> * Base, unsigned Bytes, int Dist, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 14131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4b437632fd9b97dd36010d85eb363efe">llvm::ISD::FrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a51e652265b0217f8fdba9f95129c0d47">getBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a9284fd53296d2a2f8ae654d000971000">llvm::MachineFrameInfo::getObjectSize</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#abe66a168970ddd74cce6fbc9a40589c7">llvm::TargetLowering::isGAPlusOffset</a>.</p>


<p>Referenced by <a href="#a915e43885fb2c475d2618dd41c58ed5d">isConsecutiveLS</a>.</p>

</div>
</div>

### isConstantOrUndef() {#a0aa657a6a85ab82917c254bc085416bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstantOrUndef (int Op, int Val)</td>
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

<p>isConstantOrUndef - <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is either an undef node or a <a href="/web-llvm/docs/api/classes/llvm/constantsdnode">ConstantSDNode</a>.</p>


<p>Return true if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is undef or if it matches the specified value.</p>


<p>Definition at line 1899 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### isFloatingPointZero() {#af4674b301fdc98e0a729a8d4690e45f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFloatingPointZero (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
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

<p>isFloatingPointZero - Return true if this is 0.0 or -0.0.</p>

<p>Definition at line 1885 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a910795e8d77c1545da0683c0e1cb81ee">llvm::ISD::isEXTLoad</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a15623094a1ed0cd7163dc786e44c87c9">llvm::ISD::isNON_EXTLoad</a>.</p>

</div>
</div>

### isFPExtLoad() {#a7a489ebd3081c2386cf2f4c5bbee8fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFPExtLoad (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
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



<p>Definition at line 14969 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>.</p>

</div>
</div>

### isFunctionGlobalAddress() {#af1ef95140ed897d441343e4a93d37726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFunctionGlobalAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * CalleeGV)</td>
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



<p>Definition at line 5357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aba930e0564c4207f112d9243eb2fc13a">llvm::Type::isFunctionTy</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a239427c2c3a01e23bd15b29633696536">llvm::GlobalValue::isThreadLocal</a>.</p>


<p>Referenced by <a href="#aed64046c04e9e3d1c58346b9754ca258">isIndirectCall</a> and <a href="#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a>.</p>

</div>
</div>

### isGPRShadowAligned() {#a0a4718b6006abc33142947dd02f514c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isGPRShadowAligned (<a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> RequiredAlign)</td>
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



<p>Definition at line 6834 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a>.</p>

</div>
</div>

### isIndirectCall() {#aed64046c04e9e3d1c58346b9754ca258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIndirectCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Callee, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget, bool isPatchPoint)</td>
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



<p>Definition at line 5432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a5bbcfdc24a57cc8268f0278e0a03c156">isBLACompatibleAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ad49c3ce74dc865eec4728be0850a7697">llvm::PPCSubtarget::isELFv2ABI</a>, <a href="#af1ef95140ed897d441343e4a93d37726">isFunctionGlobalAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">llvm::PPCSubtarget::usesFunctionDescriptors</a>.</p>

</div>
</div>

### isNByteElemShuffleMask() {#af7dd03e8ef59be43553b3168e2293f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNByteElemShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned Width, int StepLen)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that the mask is shuffling N byte elements.</p>


<p>Within each N byte element of the mask, the indices could be either in increasing or decreasing order as long as they are consecutive.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] N</td>
<td class="doxyParamItemDescription"><p>the shuffle vector SD <a href="/web-llvm/docs/api/classes/node">Node</a> to analyze</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Width</td>
<td class="doxyParamItemDescription"><p>the element width in bytes, could be 2/4/8/16 (HalfWord/ Word/DoubleWord/QuadWord).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] StepLen</td>
<td class="doxyParamItemDescription"><p>the delta indices number among the N byte element, if the mask is in increasing/decreasing order then it is 1/-1.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff the mask is shuffling N byte elements.</p></dd>
</dl>


<p>Definition at line 2277 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#af15ce5608e9ea5ba89ae7deb2e8895c7">isXXBRShuffleMaskHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#acb2d86096213925077b7a8b248745e34">llvm::PPC::isXXINSERTWMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a8bbd98a4e85245f40c2ef2ea6f14e7c6">llvm::PPC::isXXPERMDIShuffleMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a96447619c3b90a88e75aed44d332114c">llvm::PPC::isXXSLDWIShuffleMask</a>.</p>

</div>
</div>

### isPCRelNode() {#a4bbe57bdaf29b707d8015c6268016aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPCRelNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 18673 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="#afa8da6f68560141aad9b3bb3e333a2c3">isValidPCRelNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a57dec08b9c245de78b203b5ce73a85a3">llvm::PPCISD::MAT_PCREL_ADDR</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ae058898e63ec72af7e4ed9b50ac8fbec">llvm::PPCTargetLowering::SelectOptimalAddrMode</a>.</p>

</div>
</div>

### isScalarToVec() {#ab9bc3395487329e5c33cb362b712a371}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue isScalarToVec (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
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



<p>Definition at line 15751 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a412ddf522b53f07690a86bffba1278e7">llvm::ISD::BITCAST</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>.</p>

</div>
</div>

### IsSelect() {#a5e8a1ef711294cc52d6e2c41279f4c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsSelect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 13192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ab98cb2aaf6e757aac9c471f85f113a50">llvm::InstCombiner::getFreelyInvertedImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7bd7a084a808c1f12f4cdc5e1a67aa70">isReductionCandidate</a>.</p>

</div>
</div>

### IsSelectCC() {#a04c194c51d42f6cb99a5495af70cfb65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsSelectCC (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 13173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>.</p>

</div>
</div>

### isShuffleMaskInRange() {#a15284c7be03d0a67993cbb5024de85cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isShuffleMaskInRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; ShuffV, int HalfVec, int LHSLastElementDefined, int RHSLastElementDefined)</td>
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



<p>Definition at line 15822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### isSignExtended() {#acacabd3f0f046363943532ed7100dacc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSignExtended (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo">PPCInstrInfo</a> * TII)</td>
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



<p>Definition at line 12468 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### isSplatBV() {#af2dfc377679a894a30550de4dd545010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSplatBV (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
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



<p>Definition at line 15732 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aff6f73b624fecca7dbe94259f9437e32">llvm::ISD::BUILD_VECTOR</a> and <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a1c861a21f795c3108ab690f3a45c881a">llvm::SDValue::isUndef</a>.</p>

</div>
</div>

### isStoreConditional() {#a72e897dd9e9942885e377bfdc0fb746c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isStoreConditional (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Intrin, unsigned &amp; StoreWidth)</td>
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



<p>Definition at line 16119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>.</p>

</div>
</div>

### isTOCSaveRestoreRequired() {#a31220864cbe46fe951bcf083015c5456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isTOCSaveRestoreRequired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ad1a6a1f934a55d58ec73ea20aacbbb68">llvm::PPCSubtarget::is64BitELFABI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3ff0ba05eddb8771ac2f2ff7e56aa054">llvm::PPCSubtarget::isAIXABI</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6a2a00931f022fa78f6cdadb07e6d775">llvm::PPCSubtarget::isUsingPCRelativeCalls</a>.</p>


<p>Referenced by <a href="#a980b47a164c04c64274ef41dba790718">buildCallOperands</a> and <a href="#a04db783920e3a77ee7d48c5bc4d10b9a">getCallOpcode</a>.</p>

</div>
</div>

### isValidPCRelNode() {#afa8da6f68560141aad9b3bb3e333a2c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Ty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidPCRelNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 3003 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adfdfb329c3828aee136f7861268a3bd3">llvm::PPCInstrInfo::hasPCRelFlag</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a4bbe57bdaf29b707d8015c6268016aaa">isPCRelNode</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ae882b4864ba6e86e417710e0b990b6d6">llvm::PPCTargetLowering::SelectAddressPCRel</a>.</p>

</div>
</div>

### isValidSplatLoad() {#aca34d64e6bca0d10314f1308d636ecf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidSplatLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, unsigned &amp; Opcode)</td>
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



<p>Definition at line 9579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aee0e58997cd08983518f051e79b855d9">llvm::MemSDNode::getMemoryVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a910795e8d77c1545da0683c0e1cb81ee">llvm::ISD::isEXTLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a15623094a1ed0cd7163dc786e44c87c9">llvm::ISD::isNON_EXTLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac174dc465cbe0e04a0f5e41c0a422124">llvm::ISD::isSEXTLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a7da84980dd2ee06405d74303cfb90485">llvm::ISD::isUNINDEXEDLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a35edacef22fcaed7a8681fa573476131">llvm::ISD::isZEXTLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a01e7f48b2ccc0aed9c6f66314b23af32">llvm::PPCISD::SEXT_LD_SPLAT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad423fc6dce425d3b017dea23db96a20b">llvm::PPCISD::ZEXT_LD_SPLAT</a>.</p>

</div>
</div>

### isVMerge() {#a941eb33c376cb0192d0d7e52e21c0c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isVMerge (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned UnitSize, unsigned LHSStart, unsigned RHSStart)</td>
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

<p>isVMerge - Common function, used to match vmrg* shuffles.</p>

<p>Definition at line 2020 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab76d3f2c65ed0c127e4d19beb6fc48e3">isConstantOrUndef</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a5abe83e8c9d9553cfc708a024c204807">llvm::PPC::isVMRGEOShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a3f48ceee4d4e7b13efb21c415b8fc330">llvm::PPC::isVMRGHShuffleMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#ab27448838ea5635fa836a68c3aa97b29">llvm::PPC::isVMRGLShuffleMask</a>.</p>

</div>
</div>

### isVMerge() {#a7a8b9d3036f888a5dfcc7ded26353005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isVMerge (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, unsigned IndexOffset, unsigned RHSStartValue)</td>
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

<p>Common function used to match vmrgew and vmrgow shuffles.</p>


<p>The indexOffset determines whether to look for even or odd words in the shuffle mask. This is based on the of the endianness of the target machine.</p>


<ul class="doxyList ">
<li>Little Endian:

<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> offset of 0 to check for odd elements</li>
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> offset of 4 to check for even elements</li>
</ul></li>
<li>Big Endian:

<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> offset of 0 to check for even elements</li>
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> offset of 4 to check for odd elements A detailed description of the vector element ordering for little endian and big endian can be found at <a href="http://www.ibm.com/developerworks/library/l-ibm-xl-c-cpp-compiler/index.html">http://www.ibm.com/developerworks/library/l-ibm-xl-c-cpp-compiler/index.html</a> Targeting your applications - what little endian and big endian IBM XL C/C++ compiler differences mean to you</li>
</ul></li>
</ul>

<p>The mask to the shuffle vector instruction specifies the indices of the elements from the two input vectors to place in the result. The elements are numbered in array-access order, starting with the first vector. These vectors are always of type v16i8, thus each vector will contain 16 elements of size</p>


<ol class="doxyList" type="1">
<li>More info on the shuffle vector can be found in the <a href="http://llvm.org/docs/LangRef.html#shufflevector-instruction">http://llvm.org/docs/LangRef.html#shufflevector-instruction</a> Language Reference.</li>
</ol>

<p>The RHSStartValue indicates whether the same input vectors are used (unary) or two different input vectors are used, based on the following:</p>


<ul class="doxyList ">
<li>If the instruction uses the same vector for both inputs, the range of the indices will be 0 to 15. In this case, the RHSStart value passed should be 0.</li>
<li>If the instruction has two different vectors then the range of the indices will be 0 to 31. In this case, the RHSStart value passed should be 16 (indices 0-15 specify elements in the first vector while indices 16 to 31 specify elements in the second vector).</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] N</td>
<td class="doxyParamItemDescription"><p>The shuffle vector SD <a href="/web-llvm/docs/api/classes/node">Node</a> to analyze</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] IndexOffset</td>
<td class="doxyParamItemDescription"><p>Specifies whether to look for even or odd elements</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] RHSStartValue</td>
<td class="doxyParamItemDescription"><p>Specifies the starting index for the righthand input vector to the shuffle_vector instruction</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff this shuffle vector represents an even or odd word merge</p></dd>
</dl>


<p>Definition at line 2130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab76d3f2c65ed0c127e4d19beb6fc48e3">isConstantOrUndef</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### isXXBRShuffleMaskHelper() {#af15ce5608e9ea5ba89ae7deb2e8895c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isXXBRShuffleMaskHelper (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode">ShuffleVectorSDNode</a> * N, int Width)</td>
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



<p>Definition at line 2441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af7dd03e8ef59be43553b3168e2293f33">isNByteElemShuffleMask</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a2a25cc9341eead72b29eb9646e631244">llvm::PPC::isXXBRDShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a8bc23d2b734425aad94289c4dc5df21f">llvm::PPC::isXXBRHShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6e40fdad18c650272628e91ecadce173">llvm::PPC::isXXBRQShuffleMask</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a88c93b88a2a89e226d5312299a4e1790">llvm::PPC::isXXBRWShuffleMask</a>.</p>

</div>
</div>

### LowerLabelRef() {#ab5d4759731e493988eda569efb67233f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue LowerLabelRef (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> HiPart, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LoPart, bool isPIC, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 3170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a9e4500d93af7f70fdff992d9d748559d">llvm::PPCISD::GlobalBaseReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19afaa3b6d013f5589d52186fb31c1507de">llvm::PPCISD::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19abcb9c462158b362a5edc6a1d754c9edb">llvm::PPCISD::Lo</a>.</p>

</div>
</div>

### LowerMemOpCallTo() {#a505cc141300c7ce5f68734af974b0961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LowerMemOpCallTo (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Arg, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> PtrOff, int SPDiff, unsigned ArgOffset, bool isPPC64, bool isTailCall, bool isVector, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; MemOpChains, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; TailCallArgumentInfo &gt; &amp; TailCallArguments, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>LowerMemOpCallTo - Store the argument to the stack or remember it in case of tail calls.</p>

<p>Definition at line 5308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="#a24d6b4ddc639fabd7fed767dbedfecc2">CalculateTailCallArgDest</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7d26e2f2179b5a8a53381f8046e9d117">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### mapArgRegToOffsetAIX() {#a239d964ac9520cb492a050586bab9d35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned mapArgRegToOffsetAIX (unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering">PPCFrameLowering</a> * FL)</td>
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



<p>Definition at line 7152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a50ec4d7eb2c3cc1d2d6cac266d4ea3eb">llvm::PPCFrameLowering::getLinkageSize</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### needStackSlotPassParameters() {#a0ccb1948e466b25257ec5f95a2b8e11e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool needStackSlotPassParameters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs)</td>
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



<p>Definition at line 4989 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeaf413c8efe075d4666f4d526c527ffd">CalculateStackSlotUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a575f4bd95265cbe937901965fe1a53af">llvm::PPCSubtarget::getFrameLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a50ec4d7eb2c3cc1d2d6cac266d4ea3eb">llvm::PPCFrameLowering::getLinkageSize</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ad1a6a1f934a55d58ec73ea20aacbbb68">llvm::PPCSubtarget::is64BitELFABI</a>.</p>

</div>
</div>

### prepareDescriptorIndirectCall() {#aefc8b558bcaf81b735d0f6e634279aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void prepareDescriptorIndirectCall (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Callee, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Glue, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> CallSeqStart, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, bool hasNest, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 5631 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#af2f4a081a9b592223710411a8365bd7b">llvm::PPCSubtarget::descriptorEnvironmentPointerOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a359e26a7b0adfd51f672f641ee8abaad">llvm::PPCSubtarget::descriptorTOCAnchorOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8d13199cbf4d080d3b5dcf330dad5d2c">llvm::CallBase::getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a83ffd45d02f1a8d9920e4508c5ec0970">llvm::PPCSubtarget::getEnvironmentPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab85f5fcb2f3bb0aaf83041a41182a2d4">llvm::SelectionDAG::getIntPtrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3c3b16945cf064f59363bdefdfe2b492">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="#aea5e8c9dbcb859012df08536bd29da15">getOutputChainFromCallSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3e8f6570461d1fd818dbfbf7ff03283a">llvm::PPCSubtarget::getScalarIntVT</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ac1ff4a166a708dddd7c3df1d2fac540f">llvm::PPCSubtarget::getTOCPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a9459055a98e20980521289e8d20fcc7e">llvm::MachinePointerInfo::getWithOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3ff0ba05eddb8771ac2f2ff7e56aa054">llvm::PPCSubtarget::isAIXABI</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6622b99b3c00a3938d969957312b1b52">llvm::PPCSubtarget::isPPC64</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7b999a936bc7a4d45dfadbe356e77b3f">llvm::MachineMemOperand::MODereferenceable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac63dd9c4fe69bfeaac7a363fda846ac6">llvm::MachineMemOperand::MOInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a> and <a href="#ab168199965da793c664f4cff94912e32">prepareIndirectCall</a>.</p>

</div>
</div>

### prepareIndirectCall() {#ab168199965da793c664f4cff94912e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void prepareIndirectCall (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Callee, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Glue, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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



<p>Definition at line 5620 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa48a0d892596a0da3cf4a82c6ff5a91f">llvm::PPCISD::MTCTR</a>.</p>


<p>Referenced by <a href="#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>.</p>

</div>
</div>

### PrepareTailCall() {#acc71b3922c4a5138a77520c4e90f48bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrepareTailCall (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; InGlue, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, int SPDiff, unsigned NumBytes, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LROp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> FPOp, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; TailCallArgumentInfo &gt; &amp; TailCallArguments)</td>
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



<p>Definition at line 5333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="#acca11c9d64a646da497e82dcf6e9636e">EmitTailCallStoreFPAndRetAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b631ac3ef73be923372fb2fb1de405e">llvm::SelectionDAG::getCALLSEQ_END</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="#a7fcdf2ea020f761f9857bebbc35a2ca3">StoreTailCallArgumentsToStackSlot</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>.</p>

</div>
</div>

### provablyDisjointOr() {#a3c48cdb4fcbd71e51a4ec4c1d5c6a99a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool provablyDisjointOr (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; N)</td>
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

<p>Used when computing address flags for selecting loads and stores.</p>


<p>If we have an OR, check if the LHS and RHS are provably disjoint. An OR of two provably disjoint values is equivalent to an ADD. Most <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> load/store instructions compute the effective address as a sum, so doing this conversion is useful.</p>


<p>Definition at line 2681 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acf82847f1e6fae251ba4183cffd4a3d5">llvm::SelectionDAG::computeKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ac0e942dde4b113c4c0b1fd76333db93a">llvm::APInt::getBoolValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>


<p>Referenced by <a href="#adcd35cd6dd267ca162a87fac0acb4925">computeFlagsForAddressComputation</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a19ee5344b14a547e1ede7370b62402ce">llvm::PPCTargetLowering::SelectForceXFormMode</a>.</p>

</div>
</div>

### setAlignFlagsForFI() {#a310a2b4f7197b620ecb3babef5637cc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setAlignFlagsForFI (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned &amp; FlagSet, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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

<p>Set alignment flags based on whether or not the Frame Index is aligned.</p>


<p>Utilized when computing flags for address computation when selecting load and store instructions.</p>


<p>Definition at line 18592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/frameindexsdnode/#a1cf719b8c945859e29131c892774b21c">llvm::FrameIndexSDNode::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a8320a54de0a273478de910ac3795058b">llvm::MachineFrameInfo::getObjectAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a24a8014075c447b950e6ae5b5dec8587">llvm::PPC::MOF_RPlusSImm16Mult16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a9da404662425b672e194e163961479a3">llvm::PPC::MOF_RPlusSImm16Mult4</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#adcd35cd6dd267ca162a87fac0acb4925">computeFlagsForAddressComputation</a>.</p>

</div>
</div>

### setUsesTOCBasePtr() {#a65426f2f59cffd6edeb85831b24dbc48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setUsesTOCBasePtr (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 3189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a056f22c11083630d8bcc82299cb783af">llvm::PPCTargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a> and <a href="#ad648f72325a440d58b24e5071c360fe2">setUsesTOCBasePtr</a>.</p>

</div>
</div>

### setUsesTOCBasePtr() {#ad648f72325a440d58b24e5071c360fe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setUsesTOCBasePtr (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 3194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a> and <a href="#a65426f2f59cffd6edeb85831b24dbc48">setUsesTOCBasePtr</a>.</p>

</div>
</div>

### setXFormForUnalignedFI() {#a853a1693caf74a6f250655800e136595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setXFormForUnalignedFI (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, unsigned Flags, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcd">PPC::AddrMode</a> &amp; Mode)</td>
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



<p>Definition at line 18967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcda40a73e5d0d8196bfe33b2866c06d870d">llvm::PPC::AM_DQForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdafbe45acde65a4870e22102ab63f4643c">llvm::PPC::AM_DSForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdaaac3056a5c906602555ed94a3636077c">llvm::PPC::AM_XForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a24a8014075c447b950e6ae5b5dec8587">llvm::PPC::MOF_RPlusSImm16Mult16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#abdd78226dbbe3ffe081cffb3c9e76d80a9da404662425b672e194e163961479a3">llvm::PPC::MOF_RPlusSImm16Mult4</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ae058898e63ec72af7e4ed9b50ac8fbec">llvm::PPCTargetLowering::SelectOptimalAddrMode</a>.</p>

</div>
</div>

### STATISTIC() {#a38e4db8f05f5d3fe014af90a4fe9993b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumTailCalls, "Number of tail calls")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ad89fe8718f04da908187186854950506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumSiblingCalls, "Number of sibling calls")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a58b04c638fcba2a789cc9df87645a5e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (ShufflesHandledWithVPERM, "Number of shuffles lowered to a VPERM or XXPERM")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a26daa6fb86359a50ab880638fc1defcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumDynamicAllocaProbed, "Number of dynamic stack <a href="/web-llvm/docs/api/files/lib/lib/codegen/phielimination-cpp/#a6058ea3bdb60defe0ccd652f1a08131c">allocation</a> probed")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### StoreTailCallArgumentsToStackSlot() {#a7fcdf2ea020f761f9857bebbc35a2ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StoreTailCallArgumentsToStackSlot (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; TailCallArgumentInfo &gt; &amp; TailCallArgs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; MemOpChains, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>StoreTailCallArgumentsToStackSlot - Stores arguments to their stack slot.</p>

<p>Definition at line 5220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a89ed6b26ee4f62aec32468329f828a2f">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#acc71b3922c4a5138a77520c4e90f48bc">PrepareTailCall</a>.</p>

</div>
</div>

### stripModuloOnShift() {#a6f0cac8b7a7acd364d34649335444ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue stripModuloOnShift (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG)</td>
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



<p>Definition at line 18126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb4484ddcdad2576d97870230db05ed8">llvm::isConstOrConstSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9245ed740fe76aaad3e5b0650da21c98">llvm::TargetLoweringBase::isOperationLegal</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a56a6aa00c6f25ef2c1f51277099a78a4">llvm::PPCISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aad0d80bf5cf5a07b271e4357ed436f62">llvm::PPCISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a1b0abca17bd696928f9399acfd3d1522">llvm::PPCISD::SRL</a>.</p>

</div>
</div>

### transformCallee() {#a6a3e2feaa7c55f28c3095ef8a747ae7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue transformCallee (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Callee, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 5525 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b442ac8a9fc6147b95ccfb2c3322121">llvm::SelectionDAG::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#ac2e3ca80e41d92e19fd7500793d45369">llvm::TargetLoweringObjectFile::getFunctionEntryPointSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae78ec4c2d770f86bacd6b337e1bd80e5">llvm::SelectionDAG::getMCSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a13a2c76a48665ee3f4782fba7ddd72e1">llvm::SectionKind::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8aabf5d0aa80038973255ff2d1e1a9fc">llvm::TargetLoweringBase::getPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#a8681532d1e34a00500cd1da99179878f">llvm::MCSectionXCOFF::getQualNameSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a846a6b6b666a842d3a17f128e1826bc4">llvm::TargetMachine::getRelocationModel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa99670b16fe6d370e306896cd91b6fa6">llvm::SelectionDAG::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6f9eed3ec877628ac2b052733cee4d4">llvm::SelectionDAG::getTargetExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a05c0ae3eb411a8c53a6ce48b66c0d3f8">llvm::SelectionDAG::getTargetGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4c20c587f89ae2926f9e8a99093e8419">llvm::SelectionDAG::getTargetLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ae11f695a5e7b6ec5a3c360ecc426ba45">llvm::PPCSubtarget::getTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a137ee29e981a9a091e81b79888d8b4a6">llvm::PPCSubtarget::is32BitELFABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a3ff0ba05eddb8771ac2f2ff7e56aa054">llvm::PPCSubtarget::isAIXABI</a>, <a href="#a5bbcfdc24a57cc8268f0278e0a03c156">isBLACompatibleAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ad49c3ce74dc865eec4728be0850a7697">llvm::PPCSubtarget::isELFv2ABI</a>, <a href="#af1ef95140ed897d441343e4a93d37726">isFunctionGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffab055ede9c173349e17e7aada20410b93">llvm::PPCII::MO_PLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">llvm::Reloc::PIC_</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aa3f0dc829be1fe9aa1c7d5151db1bf21">llvm::TargetMachine::shouldAssumeDSOLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6b7e50f5c53f9dd5d5ebbb3a0bfb434c">llvm::PPCSubtarget::usesFunctionDescriptors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502cac7850ad5e926ed392928b68832be764e">llvm::XCOFF::XMC_PR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fad8a6731bed03a3891075d7ba162f83ba">llvm::XCOFF::XTY_ER</a>.</p>

</div>
</div>

### truncateScalarIntegerArg() {#adafeb00ea78374224e3589c91b88f02e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue truncateScalarIntegerArg (<a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ValVT, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ArgValue, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> LocVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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



<p>Definition at line 7136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aee4f13218bdbb5c5697f7e786618ecb2">llvm::ISD::AssertSext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af23301e60475124fd80a2cb51f6ba863">llvm::ISD::AssertZext</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a7712dd4392b7eb944b709ac8442634d9">llvm::EVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a874fbbec4937797974c9d5056769421a">llvm::MVT::getFixedSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ad958859a7af278dd5ea2b593c2b25050">llvm::EVT::isScalarInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abdeb0e345d1884804b99c02dafb2eb08">llvm::MVT::isScalarInteger</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae690127648393001a7d5b93dc23da7b3">llvm::ISD::TRUNCATE</a>.</p>

</div>
</div>

### updateForAIXShLibTLSModelOpt() {#a3986f0787e3292ba216eb027846bb42b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateForAIXShLibTLSModelOpt (<a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120">TLSModel::Model</a> &amp; Model, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>updateForAIXShLibTLSModelOpt - Helper to initialize TLS model opt settings, and then apply the update.</p>

<p>Definition at line 3384 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac64ec73b0617befef1fb2eae78d12b5f">llvm::SelectionDAG::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a3cae4242c478d473bfa1af350f126545">llvm::TLSModel::InitialExec</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/tlsmodel/#a8911c5bfb68fc4ed3ac824f04f150120a110e377ad85dc311cb9bce1e32bea8aa">llvm::TLSModel::LocalDynamic</a>, <a href="#aecc346a4ca386d721f3e30ed2ba23f9d">PPCAIXTLSModelOptUseIEForLDLimit</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>.</p>

</div>
</div>

### usePartialVectorLoads() {#a9b97177f4c89df3fd0a2f05deec3378f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool usePartialVectorLoads (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; ST)</td>
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

<p>Returns true if we should use a direct load into vector instruction (such as lxsd or lfd), instead of a load into gpr + direct move sequence.</p>

<p>Definition at line 3026 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/use/#a53a48d67682705c5f7f06ffc850fd622">llvm::Use::getUser</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a19738f4334d4de357b22349bbb56fb5c">llvm::EVT::isSimple</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4b53fee9c411b207317f688e141e9128">llvm::PPCISD::SCALAR_TO_VECTOR_PERMUTED</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a7e08a461c58c82e0564d2cd25c6d9990">llvm::PPCTargetLowering::getPreIndexedAddressParts</a>.</p>

</div>
</div>

### widenVec() {#ab9c026bf7b5362d2b79a43bd04e769a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue widenVec (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Vec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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



<p>Definition at line 8756 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a320898056eadc3254fc601e1362eb9f5">llvm::ISD::CONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adecf615928faed0c8a082ffdb65dfea0">llvm::SelectionDAG::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5b0e59823444a55c295af279611a9d24">llvm::SelectionDAG::getUNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AIXSmallTlsPolicySizeLimit {#a4af8c1082c0cbfb29e01b28814af0b73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t AIXSmallTlsPolicySizeLimit = 32751</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### AIXSSPCanaryWordName {#a80083daf41bf6d643ef8e00f171955f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char AIXSSPCanaryWordName[] = "__ssp_canary_word"</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ae56627ff3e9d2a5c7fdde625fd55fb97">llvm::PPCTargetLowering::getSDagStackGuard</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a6651f5dc988cb00064896052b5f7a42d">llvm::PPCTargetLowering::insertSSPDeclarations</a>.</p>

</div>
</div>

### ANDIGlueBug {#ae4395aff483110443e2b003a6f525d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; ANDIGlueBug</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### DisableAutoPairedVecSt {#a97df817420072d29fd6c0a0f6cae83ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableAutoPairedVecSt("disable-auto-paired-vec-st", cl::desc("disable automatically generated 32byte paired vector stores"), cl::init(true), cl::Hidden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a3a48db1e7d2f40e7a4ce6aed74b35d6d">llvm::PPCRegisterInfo::lowerACCSpilling</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ae9e97e19c06502185a9f18648de069eb">llvm::PPCRegisterInfo::lowerOctWordSpilling</a>.</p>

</div>
</div>

### DisableILPPref {#af35d4876c650d69c3ae5fa79c5e32672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableILPPref("disable-ppc-ilp-pref", cl::desc("disable setting the node scheduling preference to ILP on PPC"), cl::Hidden)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#afdf7d53d8e2b25e7b5c7981da1f11bcf">llvm::PPCTargetLowering::getSchedulingPreference</a>.</p>

</div>
</div>

### DisableInnermostLoopAlign32 {#a9a81754664d4a526243dfdb8d26fec3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableInnermostLoopAlign32("disable-ppc-innermost-loop-align32", cl::desc("don't always align innermost loop to 32 bytes on ppc"), cl::Hidden)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#af601ca614bf9dbae090272eddc645f50">llvm::PPCTargetLowering::getPrefLoopAlignment</a>.</p>

</div>
</div>

### DisableP10StoreForward {#af0201c87e6816e6372f163c9ee04a4ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableP10StoreForward("disable-p10-store-forward", cl::desc("disable P10 store forward-friendly conversion"), cl::Hidden, cl::init(false))</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ac6cddb4c330de0e51a5977de243a3ded">llvm::PPCTargetLowering::PPCTargetLowering</a>.</p>

</div>
</div>

### DisablePerfectShuffle {#aba437396b90a72b15d89706bab223dfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisablePerfectShuffle("ppc-disable-perfect-shuffle", cl::desc("disable vector permute decomposition"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### DisablePPCPreinc {#aa4abb7e9879643e764ba92b14f2802d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisablePPCPreinc("disable-ppc-preinc", cl::desc("disable preincrement load/store generation on PPC"), cl::Hidden)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a7e08a461c58c82e0564d2cd25c6d9990">llvm::PPCTargetLowering::getPreIndexedAddressParts</a>.</p>

</div>
</div>

### DisablePPCUnaligned {#a1c09895eaf1069239b0494b5e5c10187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisablePPCUnaligned("disable-ppc-unaligned", cl::desc("disable unaligned load/store generation on PPC"), cl::Hidden)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ad5d9213c39b2fc64eaed3639539e8f65">llvm::PPCTargetLowering::allowsMisalignedMemoryAccesses</a>.</p>

</div>
</div>

### DisableSCO {#aa1f5818dff822f8a19c08c6059b0e6f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableSCO("disable-ppc-sco", cl::desc("disable sibling call optimization on ppc"), cl::Hidden)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### FPR {#a587c39adeaa08f2c374d7bc55731513a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg FPR[]</td>
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

<p>FPR - The set of FP registers that should be allocated for arguments on Darwin and AIX.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {PPC::F1,  PPC::F2,  PPC::F3, PPC::F4, PPC::F5,
                                PPC::F6,  PPC::F7,  PPC::F8, PPC::F9, PPC::F10,
                                PPC::F11, PPC::F12, PPC::F13}
</div>
</dd>
</dl>

<p>Definition at line 4119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a8c46e5a35a9df5b131a85976d8d70af0">llvm::AArch64RegisterBankInfo::AArch64RegisterBankInfo</a>, <a href="#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#ab17feef922293aad8a0c0119889dea16">llvm::SystemZMachineFunctionInfo::setVarArgsFirstFPR</a>.</p>

</div>
</div>

### PPCAIXTLSModelOptUseIEForLDLimit {#aecc346a4ca386d721f3e30ed2ba23f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; PPCAIXTLSModelOptUseIEForLDLimit("ppc-aix-shared-lib-tls-model-opt-limit", cl::init(1), cl::Hidden, cl::desc("Set inclusive limit count of TLS local-dynamic access(es) in a " "function to use initial-exec"))</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="#a3986f0787e3292ba216eb027846bb42b">updateForAIXShLibTLSModelOpt</a>.</p>

</div>
</div>

### PPCGatherAllAliasesMaxDepth {#a507e89e4a7eefc0b875817f3f3362dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; PPCGatherAllAliasesMaxDepth("ppc-gather-alias-max-depth", cl::init(18), cl::Hidden, cl::desc("max depth when checking alias info in GatherAllAliases()"))</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ac6cddb4c330de0e51a5977de243a3ded">llvm::PPCTargetLowering::PPCTargetLowering</a>.</p>

</div>
</div>

### PPCMinimumJumpTableEntries {#ac8a4451494d89396b365cb9a16b4543f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; PPCMinimumJumpTableEntries("ppc-min-jump-table-entries", cl::init(64), cl::Hidden, cl::desc("Set minimum number of entries to use a jump table on PPC"))</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ac6cddb4c330de0e51a5977de243a3ded">llvm::PPCTargetLowering::PPCTargetLowering</a>.</p>

</div>
</div>

### UseAbsoluteJumpTables {#a8486eb6b484e597fa39976e4b191daa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseAbsoluteJumpTables("ppc-use-absolute-jumptables", cl::desc("use absolute jump tables on ppc"), cl::Hidden)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#adf6c939e7121ecf6c9339ef40eb8bbde">llvm::PPCTargetLowering::isJumpTableRelative</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"ppc-lowering"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

### GET\_REGISTER\_MATCHER {#a97de2baad077d3029a9cb8f211cf67c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_REGISTER_MATCHER</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp">PPCISelLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
