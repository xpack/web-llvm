---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARMBaseInstrInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-h">ARMBaseRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantpoolvalue-h">ARMConstantPoolValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armfeatures-h">ARMFeatures.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armhazardrecognizer-h">ARMHazardRecognizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armaddressingmodes-h">MCTargetDesc/ARMAddressingModes.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armbaseinfo-h">MCTargetDesc/ARMBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredutils-h">MVETailPredUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dfapacketizer-h">llvm/CodeGen/DFAPacketizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">llvm/CodeGen/LiveVariables.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">llvm/CodeGen/MachineConstantPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">llvm/CodeGen/MachinePipeliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/multihazardrecognizer-h">llvm/CodeGen/MultiHazardRecognizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scoreboardhazardrecognizer-h">llvm/CodeGen/ScoreboardHazardRecognizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">llvm/CodeGen/TargetSchedule.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstritineraries-h">llvm/MC/MCInstrItineraries.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">llvm/Support/BranchProbability.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;new&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
#include "ARMGenInstrInfo.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armbaseinstrinfo-cpp-">anonymous{ARMBaseInstrInfo.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/arm-mlxentry">ARM_MLxEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/arm-mlxentry">ARM_MLxEntry</a> - <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> information about MLA / MLS instructions. <a href="/web-llvm/docs/api/structs/arm-mlxentry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/addsubflagsopcodepair">AddSubFlagsOpcodePair</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map pseudo instructions that imply an 'S' bit onto real opcodes. <a href="/web-llvm/docs/api/structs/addsubflagsopcodepair/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/outlinercosts">OutlinerCosts</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armbaseinstrinfo-cpp-/armpipelinerloopinfo">ARMPipelinerLoopInfo</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ARMExeDomain { <a href="#a9716711ecfa12e9b08bf9bca20b52429">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MachineOutlinerClass { <a href="#ae25253bd68535ed8bdcb98a751098fe4">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constants defining how certain sequences should be outlined. <a href="#ae25253bd68535ed8bdcb98a751098fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MachineOutlinerMBBFlags { <a href="#ab0b0a572164f8fccd5474cb6babed129">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70f4425ddecde73ce7618b5513220ba4">isEligibleForITBlock</a> (const MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c263d194af0af601f8fe37e10f1ea74">duplicateCPV</a> (MachineFunction &amp;MF, unsigned &amp;CPI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a copy of a const pool value. <a href="#a2c263d194af0af601f8fe37e10f1ea74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c645e5ca492fdaeaf12f389528f48fb">isSuitableForMask</a> (MachineInstr *&amp;MI, Register SrcReg, int CmpMask, bool CommonUse)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSuitableForMask - Identify a suitable 'and' instruction that operates on the given source register and applies the same mask as a 'tst' instruction. <a href="#a2c645e5ca492fdaeaf12f389528f48fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6">ARMCC::CondCodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b4dd2f8fa26445ea60946df0e7a87f7">getCmpToAddCondition</a> (ARMCC::CondCodes CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCmpToAddCondition - assume the flags are set by CMP(a,b), return the condition code if we modify the instructions such that flags are set by ADD(a,b,X). <a href="#a7b4dd2f8fa26445ea60946df0e7a87f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1deebfd7340543a82ffa0e8303fd8a7">isRedundantFlagInstr</a> (const MachineInstr *CmpI, Register SrcReg, Register SrcReg2, int64_t ImmValue, const MachineInstr *OI, bool &amp;IsThumb1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isRedundantFlagInstr - check whether the first instruction, whose only purpose is to update flags, can be made redundant. <a href="#aa1deebfd7340543a82ffa0e8303fd8a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a873fc496ea9eab446c2aea3723936a8a">isOptimizeCompareCandidate</a> (MachineInstr *MI, bool &amp;IsThumb1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a546b8cefb687c85f2a1383240bb5f4da">getNumMicroOpsSwiftLdSt</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4b5497264eedd6889f04a4253ca2587">getNumMicroOpsSingleIssuePlusExtras</a> (unsigned Opc, unsigned NumRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6bfa18127f16dd84301143202b34ee1">getBundledDefMI</a> (const TargetRegisterInfo *TRI, const MachineInstr *MI, unsigned Reg, unsigned &amp;DefIdx, unsigned &amp;Dist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a0d637eafda3140c5ba8f8c17ba25d9">getBundledUseMI</a> (const TargetRegisterInfo *TRI, const MachineInstr &amp;MI, unsigned Reg, unsigned &amp;UseIdx, unsigned &amp;Dist)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab21c6ee9d6c29942b0bb3e7f2c2806">adjustDefLatency</a> (const ARMSubtarget &amp;Subtarget, const MachineInstr &amp;DefMI, const MCInstrDesc &amp;DefMCID, unsigned DefAlign)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of cycles to add to (or subtract from) the static itinerary based on the def opcode and alignment. <a href="#a3ab21c6ee9d6c29942b0bb3e7f2c2806">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596b52704a2d5f9e2dfff04400eef99f">getCorrespondingDRegAndLane</a> (const TargetRegisterInfo *TRI, unsigned SReg, unsigned &amp;Lane)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a019faf4f933d37d46d1fb3e7a37dccd5">getImplicitSPRUseForDPRUse</a> (const TargetRegisterInfo *TRI, MachineInstr &amp;MI, MCRegister DReg, unsigned Lane, MCRegister &amp;ImplicitSReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getImplicitSPRUseForDPRUse - Given a use of a DPR register and lane, set ImplicitSReg to a register number that must be marked as implicit-use or zero if no register needs to be defined as implicit-use. <a href="#a019faf4f933d37d46d1fb3e7a37dccd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8edbf608fa301aa44ce994dd5ea0a874">isLRAvailable</a> (const TargetRegisterInfo &amp;TRI, MachineBasicBlock::reverse_iterator I, MachineBasicBlock::reverse_iterator E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ded33b22d7f9418072a169b593ec4d">EnableARM3Addr</a>("enable-arm-3-addr-conv", cl::Hidden, cl::desc("Enable ARM 2-addr to 3-addr conv"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/arm-mlxentry">ARM_MLxEntry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97de685f215df81fe66267171364ab6b">ARM_MLxTable</a>[] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/addsubflagsopcodepair">AddSubFlagsOpcodePair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6282aa121bbcfb3d8a25be63c0b3dc33">AddSubFlagsOpcodeMap</a>[]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"arm-instrinfo"</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d99008fb7e5cdc4774786d0743a2c4f">GET_INSTRINFO_CTOR_DTOR</a></td>
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

## Enumerations

### ARMExeDomain {#a9716711ecfa12e9b08bf9bca20b52429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum ARMExeDomain </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExeGeneric<a id="a9716711ecfa12e9b08bf9bca20b52429afbe482a8b25c7219e7cf97a031e42eb0"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExeVFP<a id="a9716711ecfa12e9b08bf9bca20b52429a15d6a46113ff3279d6a41d41c6f57e01"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExeNEON<a id="a9716711ecfa12e9b08bf9bca20b52429a38642eed189597cd4b0c90fe46f2bcd2"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 5048 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### MachineOutlinerClass {#ae25253bd68535ed8bdcb98a751098fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum MachineOutlinerClass </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constants defining how certain sequences should be outlined.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachineOutlinerTailCall<a id="ae25253bd68535ed8bdcb98a751098fe4a0f5f89e2a0973bd42b48aa3ab23bc4a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachineOutlinerThunk<a id="ae25253bd68535ed8bdcb98a751098fe4ae4ec11c9120413385aef372aaa2a390c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachineOutlinerNoLRSave<a id="ae25253bd68535ed8bdcb98a751098fe4a91f63a4449fb0a4504497465cc2f4c9a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachineOutlinerRegSave<a id="ae25253bd68535ed8bdcb98a751098fe4a428eb3c2a256781b5e0589b47427e585"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachineOutlinerDefault<a id="ae25253bd68535ed8bdcb98a751098fe4ae6d079724e013e1fd057cf6fcb57675a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>This encompasses how an outlined function should be called, and what kind of frame should be emitted for that outlined function.</p>


<p><span class="doxyComputerOutput">MachineOutlinerTailCall</span> implies that the function is being created from a sequence of instructions ending in a return.</p>


<p>That is,</p>


<p>I1 OUTLINED_FUNCTION: I2 --&gt; B OUTLINED_FUNCTION I1 BX LR I2 BX LR</p>


<p>+----------------------—+-----—+--—+ | | Thumb2 | <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> | +----------------------—+-----—+--—+ | Call overhead in Bytes | 4 | 4 | | Frame overhead in Bytes | 0 | 0 | | Stack fixup required | No | No | +----------------------—+-----—+--—+</p>


<p><span class="doxyComputerOutput">MachineOutlinerThunk</span> implies that the function is being created from a sequence of instructions ending in a call. The outlined function is called with a BL instruction, and the outlined function tail-calls the original call destination.</p>


<p>That is,</p>


<p>I1 OUTLINED_FUNCTION: I2 --&gt; BL OUTLINED_FUNCTION I1 BL f I2 B f</p>


<p>+----------------------—+-----—+--—+ | | Thumb2 | <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> | +----------------------—+-----—+--—+ | Call overhead in Bytes | 4 | 4 | | Frame overhead in Bytes | 0 | 0 | | Stack fixup required | No | No | +----------------------—+-----—+--—+</p>


<p><span class="doxyComputerOutput">MachineOutlinerNoLRSave</span> implies that the function should be called using a BL instruction, but doesn't require LR to be saved and restored. This happens when LR is known to be dead.</p>


<p>That is,</p>


<p>I1 OUTLINED_FUNCTION: I2 --&gt; BL OUTLINED_FUNCTION I1 I3 I2 I3 BX LR</p>


<p>+----------------------—+-----—+--—+ | | Thumb2 | <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> | +----------------------—+-----—+--—+ | Call overhead in Bytes | 4 | 4 | | Frame overhead in Bytes | 2 | 4 | | Stack fixup required | No | No | +----------------------—+-----—+--—+</p>


<p><span class="doxyComputerOutput">MachineOutlinerRegSave</span> implies that the function should be called with a save and restore of LR to an available register. This allows us to avoid stack fixups. Note that this outlining variant is compatible with the NoLRSave case.</p>


<p>That is,</p>


<p>I1 Save LR OUTLINED_FUNCTION: I2 --&gt; BL OUTLINED_FUNCTION I1 I3 Restore LR I2 I3 BX LR</p>


<p>+----------------------—+-----—+--—+ | | Thumb2 | <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> | +----------------------—+-----—+--—+ | Call overhead in Bytes | 8 | 12 | | Frame overhead in Bytes | 2 | 4 | | Stack fixup required | No | No | +----------------------—+-----—+--—+</p>


<p><span class="doxyComputerOutput">MachineOutlinerDefault</span> implies that the function should be called with a save and restore of LR to the stack.</p>


<p>That is,</p>


<p>I1 Save LR OUTLINED_FUNCTION: I2 --&gt; BL OUTLINED_FUNCTION I1 I3 Restore LR I2 I3 BX LR</p>


<p>+----------------------—+-----—+--—+ | | Thumb2 | <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> | +----------------------—+-----—+--—+ | Call overhead in Bytes | 8 | 12 | | Frame overhead in Bytes | 2 | 4 | | Stack fixup required | Yes | Yes | +----------------------—+-----—+--—+</p>


<p>Definition at line 5801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### MachineOutlinerMBBFlags {#ab0b0a572164f8fccd5474cb6babed129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum MachineOutlinerMBBFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LRUnavailableSomewhere<a id="ab0b0a572164f8fccd5474cb6babed129a4833a7f75545b7500185a9ececd92b08"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HasCalls<a id="ab0b0a572164f8fccd5474cb6babed129a4f2a846b62b36aa105ec3ddfd151a482"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnsafeRegsDead<a id="ab0b0a572164f8fccd5474cb6babed129ac7d6a08b9442af3460a55305a35fd823"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 5809 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### adjustDefLatency() {#a3ab21c6ee9d6c29942b0bb3e7f2c2806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int adjustDefLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; DefMCID, unsigned DefAlign)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of cycles to add to (or subtract from) the static itinerary based on the def opcode and alignment.</p>


<p>The caller will ensure that adjusted latency is at least one cycle.</p>


<p>Definition at line 4201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a29a2545f60f5e7f7cffd5e66b0d4cf87">llvm::ARM_AM::getAM2Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#acda0e957b0c23c9beaa0d98238e140f3">llvm::ARM_AM::getAM2Op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f978e0398d511ac5d13a41269b2f5fe">llvm::ARM_AM::getAM2ShiftOpc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#aee50fcacb786c1fc56168a0c55a4e934">llvm::MCInstrDesc::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a08caeec4314d2a3983d98789d7559e80">llvm::ARMSubtarget::isCortexA7</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#ac43b07f1b3f6ed64f7bfc6d864bd7465">llvm::ARMSubtarget::isCortexA8</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a60117a5fbb52ea9f70b5015e7740f7ca">llvm::ARMSubtarget::isLikeA9</a>, <a href="/web-llvm/docs/api/classes/llvm/armsubtarget/#a0eef6de6958d76e6b151164c5b419650">llvm::ARMSubtarget::isSwift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a76f5f9f36bbd9f03c844c5b565f239efaafeb1424944dafbde8a990bce1f5bd84">llvm::ARM_AM::lsl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a76f5f9f36bbd9f03c844c5b565f239efa25f26a9f4d00c9ac425953111519c041">llvm::ARM_AM::lsr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">llvm::ARM_AM::sub</a>.</p>

</div>
</div>

### duplicateCPV() {#a2c263d194af0af601f8fe37e10f1ea74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned duplicateCPV (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned &amp; CPI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a copy of a const pool value.</p>


<p>Update CPI to the new index and return the label UID.</p>


<p>Definition at line 1782 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaabac6721b50294fd164c5861cb82e938e10">llvm::ARMCP::CPBlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaaba7266a79b029f9dc90109a374fe43c64f">llvm::ARMCP::CPLSDA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcp/#ad7299e03746a8bdbbff1d3aaf03eaaabad4206f41cccb7d5c78d6d642b4b35e1f">llvm::ARMCP::CPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolconstant/#a42ce6739c10696336d46591fec3e12ac">llvm::ARMConstantPoolConstant::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolmbb/#a6c19796f37809c5c4b35674958d7dde8">llvm::ARMConstantPoolMBB::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolsymbol/#ab62de7c856026cf2bda78e18e95bcd99">llvm::ARMConstantPoolSymbol::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#a35e5226e31619a535b692b702a2990a6">llvm::ARMFunctionInfo::createPICLabelUId</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba1fee9e9c9b537fd2a02f33f714ca68">llvm::MachineFunction::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool/#afd6691ddb5d4adf50d744297e18a1c6d">llvm::MachineConstantPool::getConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool/#a906c142ea808e1bf1a66f59c4fb51048">llvm::MachineConstantPool::getConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#abe4a46d23b1ab79b5dc190ac58f22eae">llvm::ARMConstantPoolValue::getModifier</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#ae603ba203d2cb8f2d58d8ba8b296f468">llvm::ARMConstantPoolValue::isBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a8b8d346c78a82437ac734e4ce1cb0553">llvm::ARMConstantPoolValue::isExtSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#aa6db6cf5d86094941ae641ceecf87318">llvm::ARMConstantPoolValue::isGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#ae25500a7ac8ad50ba2773c8558e1deaa">llvm::ARMConstantPoolValue::isLSDA</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a8761e4a93682b13870657a5b83612ffc">llvm::ARMConstantPoolValue::isMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#accec0ab52fef914619e937abd7f85c8b">llvm::ARMConstantPoolValue::mustAddCurrentAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a7a4e4e4a8fa157eb9945d44717359bb1">llvm::ARMBaseInstrInfo::duplicate</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>.</p>

</div>
</div>

### getBundledDefMI() {#af6bfa18127f16dd84301143202b34ee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * getBundledDefMI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Reg, unsigned &amp; DefIdx, unsigned &amp; Dist)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a>.</p>

</div>
</div>

### getBundledUseMI() {#a2a0d637eafda3140c5ba8f8c17ba25d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * getBundledUseMI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Reg, unsigned &amp; UseIdx, unsigned &amp; Dist)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a>.</p>

</div>
</div>

### getCmpToAddCondition() {#a7b4dd2f8fa26445ea60946df0e7a87f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMCC::CondCodes getCmpToAddCondition (<a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6">ARMCC::CondCodes</a> CC)</td>
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

<p>getCmpToAddCondition - assume the flags are set by CMP(a,b), return the condition code if we modify the instructions such that flags are set by ADD(a,b,X).</p>

<p>Definition at line 2859 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a038249ad0a9ef6d79cc3506c96dd3c1f">llvm::ARMCC::HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a85a7716b3a259c91702bce293fb923df">llvm::ARMCC::LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6ad2c4e3875c38c36df4848049d50cc28d">llvm::ARMCC::VC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6abe109952a13e776b7b978e02e4f33427">llvm::ARMCC::VS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### getCorrespondingDRegAndLane() {#a596b52704a2d5f9e2dfff04400eef99f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister getCorrespondingDRegAndLane (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, unsigned SReg, unsigned &amp; Lane)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5091 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5b3180edf81915b106633986034d7a01">llvm::ARMBaseInstrInfo::setExecutionDomain</a>.</p>

</div>
</div>

### getImplicitSPRUseForDPRUse() {#a019faf4f933d37d46d1fb3e7a37dccd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getImplicitSPRUseForDPRUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> DReg, unsigned Lane, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; ImplicitSReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getImplicitSPRUseForDPRUse - Given a use of a DPR register and lane, set ImplicitSReg to a register number that must be marked as implicit-use or zero if no register needs to be defined as implicit-use.</p>


<p>If the function cannot determine if an SPR should be marked implicit use or not, it returns false.</p>


<p>This function handles cases where an instruction is being modified from taking an SPR to a DPR[Lane]. A use of the DPR is being added, which may conflict with an earlier def of an SPR corresponding to DPR[Lane^1] (i.e. the other lane of the DPR).</p>


<p>If the other SPR is defined, an implicit-use of it should be added. Else, (including the case where the DPR itself is defined), it should not.</p>


<p>Definition at line 5122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af0288e181965a5ff9f0c7a75201fd142accc15fa5c7a27d461dc9a884cc9a2dc8">llvm::MachineBasicBlock::LQR_Live</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af0288e181965a5ff9f0c7a75201fd142af64367be349b6e7672de902ebecae068">llvm::MachineBasicBlock::LQR_Unknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5b3180edf81915b106633986034d7a01">llvm::ARMBaseInstrInfo::setExecutionDomain</a>.</p>

</div>
</div>

### getNumMicroOpsSingleIssuePlusExtras() {#af4b5497264eedd6889f04a4253ca2587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getNumMicroOpsSingleIssuePlusExtras (unsigned Opc, unsigned NumRegs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a41289ca8ad61ff8ab86bc82a0afd8e1c">llvm::ARMBaseInstrInfo::getNumMicroOps</a>.</p>

</div>
</div>

### getNumMicroOpsSwiftLdSt() {#a546b8cefb687c85f2a1383240bb5f4da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getNumMicroOpsSwiftLdSt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a29a2545f60f5e7f7cffd5e66b0d4cf87">llvm::ARM_AM::getAM2Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#acda0e957b0c23c9beaa0d98238e140f3">llvm::ARM_AM::getAM2Op</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a0f978e0398d511ac5d13a41269b2f5fe">llvm::ARM_AM::getAM2ShiftOpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#acf54dffc0ef46cbffcaace8bcf2a3758">llvm::ARM_AM::getAM3Op</a>, <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata/#a035351039a05ded742d1958d3d63d92b">llvm::InstrItineraryData::getNumMicroOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a76f5f9f36bbd9f03c844c5b565f239efaafeb1424944dafbde8a990bce1f5bd84">llvm::ARM_AM::lsl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cda41a13f3ce88ed84e63003e32b18c1235">llvm::ARM_AM::sub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a41289ca8ad61ff8ab86bc82a0afd8e1c">llvm::ARMBaseInstrInfo::getNumMicroOps</a>.</p>

</div>
</div>

### isEligibleForITBlock() {#a70f4425ddecde73ce7618b5513220ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isEligibleForITBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a05e40e0592f6a3d97d6a86534e42f955">llvm::ARMBaseInstrInfo::isCPSRDefined</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8845a1756d587750a29c60cb382aa4e4">llvm::ARMBaseInstrInfo::isPredicable</a>.</p>

</div>
</div>

### isLRAvailable() {#a8edbf608fa301aa44ce994dd5ea0a874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLRAvailable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#abada92f8cd2854d2b747f14c4a7be0ed">MachineBasicBlock::reverse_iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#abada92f8cd2854d2b747f14c4a7be0ed">MachineBasicBlock::reverse_iterator</a> E)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5866 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a99791c9647b053fc872d35a3f0faafd7">llvm::ARMBaseInstrInfo::getOutliningCandidateInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aedba2e5f9aa7cb803611f295ad04b865">llvm::ARMBaseInstrInfo::isMBBSafeToOutlineFrom</a>.</p>

</div>
</div>

### isOptimizeCompareCandidate() {#a873fc496ea9eab446c2aea3723936a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isOptimizeCompareCandidate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, bool &amp; IsThumb1)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2937 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### isRedundantFlagInstr() {#aa1deebfd7340543a82ffa0e8303fd8a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRedundantFlagInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CmpI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg2, int64_t ImmValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OI, bool &amp; IsThumb1)</td>
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

<p>isRedundantFlagInstr - check whether the first instruction, whose only purpose is to update flags, can be made redundant.</p>


<p>CMPrr can be made redundant by SUBrr if the operands are the same. CMPri can be made redundant by SUBri if the operands are the same. CMPrr(r0, r1) can be made redundant by ADDr[ri](r0, r1, X). This function can be extended later on.</p>


<p>Definition at line 2875 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#afe08501833a78c86e99338e6fef0137c">llvm::ARMBaseInstrInfo::shouldSink</a>.</p>

</div>
</div>

### isSuitableForMask() {#a2c645e5ca492fdaeaf12f389528f48fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSuitableForMask (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, int CmpMask, bool CommonUse)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isSuitableForMask - Identify a suitable 'and' instruction that operates on the given source register and applies the same mask as a 'tst' instruction.</p>


<p>Provide a limited look-through for copies. When successful, MI will hold the found instruction.</p>


<p>Definition at line 2841 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AddSubFlagsOpcodeMap {#a6282aa121bbcfb3d8a25be63c0b3dc33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AddSubFlagsOpcodePair AddSubFlagsOpcodeMap[]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af38d3efc162ab4c4fc14f9220c142b91">llvm::convertAddSubFlagsOpcode</a>.</p>

</div>
</div>

### ARM\_MLxTable {#a97de685f215df81fe66267171364ab6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARM_MLxEntry ARM_MLxTable[]</td>
</tr>
</table>
</td>
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
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  { ARM::VMLAS,       ARM::VMULS,       ARM::VADDS,      false,  false },
  { ARM::VMLSS,       ARM::VMULS,       ARM::VSUBS,      false,  false },
  { ARM::VMLAD,       ARM::VMULD,       ARM::VADDD,      false,  false },
  { ARM::VMLSD,       ARM::VMULD,       ARM::VSUBD,      false,  false },
  { ARM::VNMLAS,      ARM::VNMULS,      ARM::VSUBS,      <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>,   false },
  { ARM::VNMLSS,      ARM::VMULS,       ARM::VSUBS,      <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>,   false },
  { ARM::VNMLAD,      ARM::VNMULD,      ARM::VSUBD,      <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>,   false },
  { ARM::VNMLSD,      ARM::VMULD,       ARM::VSUBD,      <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>,   false },
  { ARM::VMLAfd,      ARM::VMULfd,      ARM::VADDfd,     false,  false },
  { ARM::VMLSfd,      ARM::VMULfd,      ARM::VSUBfd,     false,  false },
  { ARM::VMLAfq,      ARM::VMULfq,      ARM::VADDfq,     false,  false },
  { ARM::VMLSfq,      ARM::VMULfq,      ARM::VSUBfq,     false,  false },
  { ARM::VMLAslfd,    ARM::VMULslfd,    ARM::VADDfd,     false,  <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>  },
  { ARM::VMLSslfd,    ARM::VMULslfd,    ARM::VSUBfd,     false,  <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>  },
  { ARM::VMLAslfq,    ARM::VMULslfq,    ARM::VADDfq,     false,  <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>  },
  { ARM::VMLSslfq,    ARM::VMULslfq,    ARM::VSUBfq,     false,  <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>  },
}
</div>
</dd>
</dl>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a7e82ffc3423eb67eef1e1a43f0b75ce7">llvm::ARMBaseInstrInfo::ARMBaseInstrInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a168380fa7a6b64cf46cdb6a249137966">llvm::ARMBaseInstrInfo::isFpMLxInstruction</a>.</p>

</div>
</div>

### EnableARM3Addr {#a34ded33b22d7f9418072a169b593ec4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableARM3Addr("enable-arm-3-addr-conv", cl::Hidden, cl::desc("Enable ARM 2-addr to 3-addr conv"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"arm-instrinfo"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

### GET\_INSTRINFO\_CTOR\_DTOR {#a5d99008fb7e5cdc4774786d0743a2c4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_INSTRINFO_CTOR_DTOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp">ARMBaseInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
