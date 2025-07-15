---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/machinesink-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MachineSink.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/depthfirstiterator-h">llvm/ADT/DepthFirstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">llvm/ADT/PointerIntPair.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cfg-h">llvm/Analysis/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">llvm/CodeGen/MachineBranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinecycleanalysis-h">llvm/CodeGen/MachineCycleAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedomtreeupdater-h">llvm/CodeGen/MachineDomTreeUpdater.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">llvm/CodeGen/MachinePostDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinesizeopts-h">llvm/CodeGen/MachineSizeOpts.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerclassinfo-h">llvm/CodeGen/RegisterClassInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">llvm/CodeGen/RegisterPressure.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetschedule-h">llvm/CodeGen/TargetSchedule.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/branchprobability-h">llvm/Support/BranchProbability.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-machinesink-cpp-">anonymous{MachineSink.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking">MachineSinking</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/postramachinesinking">PostRAMachineSinking</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16005492b382a6a76abae848b4af2b83">RegSubRegPair</a> = <a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5758149387a098afa23bf386888618">MIRegs</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 2 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1eec7baf4531f508771c495a4b07b3">STATISTIC</a> (NumSunk, "Number of machine instructions sunk")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73fca6bc11b2eeecbad426a56359ceb">STATISTIC</a> (NumCycleSunk, "Number of machine instructions sunk into a cycle")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b2bd388e695f08c38030c6892a183b">STATISTIC</a> (NumSplit, "Number of critical edges split")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e5a26098d540497ef0e5df892f774ba">STATISTIC</a> (NumCoalesces, "Number of copies coalesced")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a52f2b42a1961a70cd0a2a12e5ad278">STATISTIC</a> (NumPostRACopySink, "Number of copies sunk after RA")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ecbf0fad9948bab3c145b46cbf244f4">INITIALIZE_PASS_BEGIN</a> (MachineSinking, DEBUG_TYPE, "Machine code sinking", false, false) INITIALIZE_PASS_END(MachineSinking</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> code static false bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854df6024334d02ea223f70a543940fc">blockPrologueInterferes</a> (const MachineBasicBlock *BB, MachineBasicBlock::const_iterator End, const MachineInstr &amp;MI, const TargetRegisterInfo *TRI, const TargetInstrInfo *TII, const MachineRegisterInfo *MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a target defined block prologue instruction interferes with a sink candidate. <a href="#a854df6024334d02ea223f70a543940fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304f762123a019d38d531483c00c796b">mayLoadFromGOTOrConstantPool</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this machine instruction loads from global offset table or constant pool. <a href="#a304f762123a019d38d531483c00c796b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316803c463af8ba2c38182332fb3c8a4">SinkingPreventsImplicitNullCheck</a> (MachineInstr &amp;MI, const TargetInstrInfo *TII, const TargetRegisterInfo *TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MI is likely to be usable as a memory operation by the implicit null check optimization. <a href="#a316803c463af8ba2c38182332fb3c8a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab07fa640d6b044c04371e8cc8bde6a02">attemptDebugCopyProp</a> (MachineInstr &amp;SinkInst, MachineInstr &amp;DbgMI, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the sunk instruction is a copy, try to forward the copy instead of leaving an 'undef' DBG_VALUE in the original location. <a href="#ab07fa640d6b044c04371e8cc8bde6a02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e64ed92fc7b343fa59c28105e16b794">performSink</a> (MachineInstr &amp;MI, MachineBasicBlock &amp;SuccToSinkTo, MachineBasicBlock::iterator InsertPos, ArrayRef&lt; MIRegs &gt; DbgValuesToSink)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sink an instruction and its associated debug instructions. <a href="#a1e64ed92fc7b343fa59c28105e16b794">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1a94d15096ac1fd1fd21d1af9187761">INITIALIZE_PASS</a> (PostRAMachineSinking, "postra-machine-sink", "PostRA Machine Sink", false, false) static bool aliasWithRegsInLiveIn(MachineBasicBlock &amp;MBB</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LiveInRegUnits</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a074843b524f0a9bfd420219cd3cb10cd">addLiveIns</a> (MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">return !LiveInRegUnits</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40cc6a0e0895fa564ee013923209aa85">available</a> (Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf8fc7aec1c211309bcfdadf5471efc5">getSingleLiveInSuccBB</a> (MachineBasicBlock &amp;CurBB, const SmallPtrSetImpl&lt; MachineBasicBlock * &gt; &amp;SinkableBBs, unsigned Reg, const TargetRegisterInfo *TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a760cd0801dd2ecf5d8951c3c1db40ca8">getSingleLiveInSuccBB</a> (MachineBasicBlock &amp;CurBB, const SmallPtrSetImpl&lt; MachineBasicBlock * &gt; &amp;SinkableBBs, ArrayRef&lt; unsigned &gt; DefedRegsInCopy, const TargetRegisterInfo *TRI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084d504a7f8b42657e1c910ba098ad94">clearKillFlags</a> (MachineInstr *MI, MachineBasicBlock &amp;CurBB, SmallVectorImpl&lt; unsigned &gt; &amp;UsedOpsInCopy, LiveRegUnits &amp;UsedRegUnits, const TargetRegisterInfo *TRI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1da13a967ff01e9076c55b0b6d158c">updateLiveIn</a> (MachineInstr *MI, MachineBasicBlock *SuccBB, SmallVectorImpl&lt; unsigned &gt; &amp;UsedOpsInCopy, SmallVectorImpl&lt; unsigned &gt; &amp;DefedRegsInCopy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5523ffd2d5ced60566f3493c2b48e0e3">hasRegisterDependency</a> (MachineInstr *MI, SmallVectorImpl&lt; unsigned &gt; &amp;UsedOpsInCopy, SmallVectorImpl&lt; unsigned &gt; &amp;DefedRegsInCopy, LiveRegUnits &amp;ModifiedRegUnits, LiveRegUnits &amp;UsedRegUnits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a222c2bec99b5fc7d68f675248e085cd2">SplitEdges</a>("machine-sink-split", cl::desc("Split critical edges during machine sinking"), cl::init(true), cl::Hidden)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8a57b53e1029a66423f1c8beeee72b8">UseBlockFreqInfo</a>("machine-sink-bfi", cl::desc("Use block frequency info to find successors to sink"), cl::init(true), cl::Hidden)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e692ddc4d0481e2ca501d7600f8b328">SplitEdgeProbabilityThreshold</a>("machine-sink-split-probability-threshold", cl::desc("Percentage threshold for splitting single-instruction critical edge. " "If the branch threshold is higher than this threshold, we allow " "speculative execution of up to 1 instruction to avoid branching to " "splitted critical edge"), cl::init(40), cl::Hidden)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a001e53bb2ff322656f27e267f2409a06">SinkLoadInstsPerBlockThreshold</a>("machine-sink-load-instrs-threshold", cl::desc("Do not try to find alias store for a load if there is a in-path " "block whose instruction number is higher than this threshold."), cl::init(2000), cl::Hidden)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341405fd2cb2dfad3d03b4f76b1a577b">SinkLoadBlocksThreshold</a>("machine-sink-load-blocks-threshold", cl::desc("Do not try to find alias store for a load if the block number in " "the straight line is higher than this threshold."), cl::init(20), cl::Hidden)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ac72ad86d97fe56d3ef6668df30680">SinkInstsIntoCycle</a>("sink-insts-to-avoid-spills", cl::desc("Sink instructions into cycles to avoid " "register spills"), cl::init(false), cl::Hidden)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084ec12a6f4a9e62a9fef7d321250c12">SinkIntoCycleLimit</a>("machine-sink-cycle-limit", cl::desc("The maximum number of instructions considered for cycle sinking."), cl::init(50), cl::Hidden)</td>
</tr>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b48f4c83665c4a2ece4938ffc9ffbcd">sinking</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1b68e45590816c3156869e7915c269">false</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a359e1ff26f6d466d927a61aae45b05c3">Reg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"machine-sink"</td>
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

### MIRegs {#a1f5758149387a098afa23bf386888618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MIRegs =  std::pair&lt;MachineInstr *, SmallVector&lt;unsigned, 2&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### RegSubRegPair {#a16005492b382a6a76abae848b4af2b83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using RegSubRegPair =  TargetInstrInfo::RegSubRegPair</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addLiveIns() {#a074843b524f0a9bfd420219cd3cb10cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInRegUnits addLiveIns (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2031 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### attemptDebugCopyProp() {#ab07fa640d6b044c04371e8cc8bde6a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool attemptDebugCopyProp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; SinkInst, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DbgMI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the sunk instruction is a copy, try to forward the copy instead of leaving an 'undef' DBG_VALUE in the original location.</p>


<p>Don't do this if there's any subregister weirdness involved. Returns true if copy propagation occurred.</p>


<p>Definition at line 1471 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a05c54bfb75dbb555ab457e768bbcfe73">llvm::MachineInstr::getDebugOperandsForReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#a1e64ed92fc7b343fa59c28105e16b794">performSink</a>.</p>

</div>
</div>

### available() {#a40cc6a0e0895fa564ee013923209aa85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">return !LiveInRegUnits available (<a href="#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2032 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>Reference <a href="#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### blockPrologueInterferes() {#a854df6024334d02ea223f70a543940fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Machine code static false bool blockPrologueInterferes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> End, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a target defined block prologue instruction interferes with a sink candidate.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="#a854df6024334d02ea223f70a543940fc">blockPrologueInterferes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a854df6024334d02ea223f70a543940fc">blockPrologueInterferes</a>.</p>

</div>
</div>

### clearKillFlags() {#a084d504a7f8b42657e1c910ba098ad94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void clearKillFlags (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; CurBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; UsedOpsInCopy, <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> &amp; UsedRegUnits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2078 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#a3996f7c3774880bfe32422602fe34f9c">llvm::LiveRegUnits::available</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a> and <a href="#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getSingleLiveInSuccBB() {#acf8fc7aec1c211309bcfdadf5471efc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * getSingleLiveInSuccBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; CurBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; SinkableBBs, unsigned Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2036 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a> and <a href="#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a760cd0801dd2ecf5d8951c3c1db40ca8">getSingleLiveInSuccBB</a>.</p>

</div>
</div>

### getSingleLiveInSuccBB() {#a760cd0801dd2ecf5d8951c3c1db40ca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * getSingleLiveInSuccBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; CurBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; SinkableBBs, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; DefedRegsInCopy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2063 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="#acf8fc7aec1c211309bcfdadf5471efc5">getSingleLiveInSuccBB</a> and <a href="#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### hasRegisterDependency() {#a5523ffd2d5ced60566f3493c2b48e0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasRegisterDependency (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; UsedOpsInCopy, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; DefedRegsInCopy, <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> &amp; ModifiedRegUnits, <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> &amp; UsedRegUnits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#a3996f7c3774880bfe32422602fe34f9c">llvm::LiveRegUnits::available</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a69544ec8658eadeed98245dc37c3a541">llvm::MachineOperand::isUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#aa1a94d15096ac1fd1fd21d1af9187761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (PostRAMachineSinking, "postra-machine-sink", "PostRA <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> Sink", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2025 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a8ecbf0fad9948bab3c145b46cbf244f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (MachineSinking, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Machine code sinking", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### mayLoadFromGOTOrConstantPool() {#a304f762123a019d38d531483c00c796b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool mayLoadFromGOTOrConstantPool (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this machine instruction loads from global offset table or constant pool.</p>

<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### performSink() {#a1e64ed92fc7b343fa59c28105e16b794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void performSink (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; SuccToSinkTo, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPos, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#a1f5758149387a098afa23bf386888618">MIRegs</a> &gt; DbgValuesToSink)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sink an instruction and its associated debug instructions.</p>

<p>Definition at line 1523 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="#ab07fa640d6b044c04371e8cc8bde6a02">attemptDebugCopyProp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a095ce2d870dadf620a4c887ecc0efef8">llvm::MachineBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a78cc51c415c7e64b5efe2c8458fbd35a">llvm::DILocation::getMergedLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a067c1c89704407541cbed8d65ac8dd66">llvm::MachineInstr::hasDebugOperandForReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3435a2381e60e842e915f85c931b7dde">llvm::MachineBasicBlock::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0cf83915bd66f2a610c72f3d028f8704">llvm::MachineInstr::setDebugValueUndef</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>.</p>

</div>
</div>

### SinkingPreventsImplicitNullCheck() {#a316803c463af8ba2c38182332fb3c8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SinkingPreventsImplicitNullCheck (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if MI is likely to be usable as a memory operation by the implicit null check optimization.</p>


<p>This is a "best effort" heuristic, and should not be relied upon for correctness. This returning true does not guarantee that the implicit null check optimization is legal over MI, and this returning false does not guarantee MI cannot possibly be used to do a null check.</p>


<p>Definition at line 1426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### STATISTIC() {#a3d1eec7baf4531f508771c495a4b07b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumSunk, "Number of machine <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> sunk")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aa73fca6bc11b2eeecbad426a56359ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCycleSunk, "Number of machine <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> sunk into a cycle")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ac0b2bd388e695f08c38030c6892a183b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumSplit, "Number of critical edges split")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a0e5a26098d540497ef0e5df892f774ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCoalesces, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a1d5e606e23fdf432583aa8dc1f17ff55">copies</a> coalesced")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a2a52f2b42a1961a70cd0a2a12e5ad278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumPostRACopySink, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a1d5e606e23fdf432583aa8dc1f17ff55">copies</a> sunk after RA")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### updateLiveIn() {#a6c1da13a967ff01e9076c55b0b6d158c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateLiveIn (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; UsedOpsInCopy, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; DefedRegsInCopy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2098 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acce9c12cc977a88dc7bc51493ce7681c">llvm::MachineBasicBlock::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a668e2f48294f63416c8f28072e531c33">llvm::MachineBasicBlock::removeLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a9ff557f73ac8f2608369d70b3c73e525">llvm::MachineBasicBlock::sortUniqueLiveIns</a> and <a href="#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### false {#add1b68e45590816c3156869e7915c269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Machine code false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### Reg {#a359e1ff26f6d466d927a61aae45b05c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2028 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#a06c3c14971a6414e21bf3a0a2652de0f">llvm::LiveRegUnits::accumulateUsedDefed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorprint-cpp/#ac83650c39910df4efe637a37279fa674">addAsmInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#ad0cd3133a28b196d900d4a2fb49f19e2">llvm::X86MachineFunctionInfo::addCandidateForPush2Pop2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff98f30548a2233baed77a73408842a2">llvm::addDirectMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7b24fcad0f9310a088627066269508e2">addExclusiveRegPair</a>, <a href="/web-llvm/docs/api/structs/llvm/loc/entryvalue/#a01c50402331616f6b2606c9f7b1680da">llvm::Loc::EntryValue::addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#aaf08c51751e9ec671a84a92af1daab99">addHints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp/#a0cad575df04ef66a39c5d0d0501cf267">addImplicitDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ac889107f09b05137fd5964343a935a6c">llvm::MachineRegisterInfo::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a5afb7d50f639285c9ef082439615915e">llvm::FunctionLoweringInfo::AddLiveOutRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a522ad94e11633111eff2db3dff472d1a">llvm::PPCFunctionInfo::addMustSaveCR</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#adbf2afbb346e40106f344191309324fc">llvm::LivePhysRegs::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#ab2909dfae74e60e8dfd886b92e5a33e3">llvm::LiveRegUnits::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a2b9700052102985a61c9cf62b71d68f0">llvm::MCInstBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a6afe81a8562ad740b6edd4c536974067">addRegAndItsAliases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ad283cfc77268d18405882cb6588c337f">llvm::M68k::addRegIndirectWithDisp</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#a380627231bd554718dbc1e28f8875c49">llvm::LiveRegUnits::addRegMasked</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a752b9dfb94f917a9e494fc4ed8cb6208">llvm::addRegOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a6090242d02f8da5fef11db06af3c5783">addRegUnits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16instrinfo-cpp/#a8307fba45b5b2a7e89011a2a789a9a31">addSaveRestoreRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmachinefunctioninfo/#a29b9507fdbff560ffc3e064151fbe702">llvm::LoongArchMachineFunctionInfo::addSExt32Register</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a33b1d3e5b49c049ed08f90d38070a751">AddSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a278669a31bed59a4491aa93f70d0606f">addToFwdRegWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ae423245f144cc5fe3d50b2e6dde62c47">llvm::SIMachineFunctionInfo::addToPrologEpilogSGPRSpills</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#aae14937e233b1d930d6f040de852ff30">llvm::MipsInstrInfo::adjustStackPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#a57fb042780e3f9caed69dd8b3ab540bd">llvm::AggressiveAntiDepBreaker::AggressiveAntiDepBreaker</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aca0d8e94d5c4396182a393104312cd73">allocateFixedSGPRInputImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a2d13a28563f7bcce62ca94550c02f405">llvm::CCState::AllocateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ac91c138875449056b2b6201eadb4f63f">llvm::CCState::AllocateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a676595eca705be482ea3e77b9e3ea2ec">llvm::CCState::AllocateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ae8e9cf9c25b92ce99fbebe45fcc66e40">llvm::CCState::AllocateReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvcallingconv-cpp/#a1e4c374329ac8dd85a653f4880a6b0d5">allocateRVVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a8688cc0d4d5620a54a1d45bd3087de1f">allocateSGPR32InputImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a2379f210483c602f5d6c491d4f062da4">llvm::CCState::AllocateStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abcfc092d297e085e5b5390b5b1656236">allocateVGPR32Input</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#afe2ba453aa8039b2d52c9474d9f14bc0">Analyze_CC_Sparc64_Full</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#aefa9d9e14f365171f98e0a86d34c3c08">Analyze_CC_Sparc64_Half</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430isellowering-cpp/#ad996415c84f27a48afd2fd7dc653efea">AnalyzeArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8423e53bcc9782e23a4e48e8ef88d150">llvm::analyzeArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08acbbba5edd5a9d4090220358bc9305">llvm::analyzeReturnValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a65d34a1acd6c2473aab0fabe963fccfb">AnyAliasLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregset/#ad6d68ede26d8d5a0610c0630a03adc17">llvm::LiveRegSet::appendTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#abde55543f0bbb31306a6cd2af297fe9f">assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a349def858d7ff22474b3f9013486807f">llvm::RegScavenger::assignRegToScavengingIndex</a>, <a href="#ab07fa640d6b044c04371e8cc8bde6a02">attemptDebugCopyProp</a>, <a href="#a40cc6a0e0895fa564ee013923209aa85">available</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#a3996f7c3774880bfe32422602fe34f9c">llvm::LiveRegUnits::available</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/bind-helper-f9751d5435090874c5b33815d3b9dee0/#aacc2838ea638d9da87a40575ed1f4cce">llvm::MIPatternMatch::bind_helper&lt; const ConstantFP * &gt;::bind</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/bind-helper-54fd47fa7f6e6c428354f053a15b186e/#ac2b3b89e3aaa11718ad5667ea72d806a">llvm::MIPatternMatch::bind_helper&lt; LLT &gt;::bind</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/bind-helper-509a5449bc6b36165e6f7a8afbf56503/#a455fc5a602130cd4ba92fa08d91145d4">llvm::MIPatternMatch::bind_helper&lt; MachineInstr * &gt;::bind</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ab3cf0a47fd46d1e90659df084cad7945">llvm::BitTracker::BitValue::BitValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a191e4c250748ed5043795f6bf3caf4e9">llvm::buildBuiltinVariableLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0c5b9f0e5e1e90caa9c8def3d230ddbf">llvm::TargetInstrInfo::buildClearRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a28391c59e5f478e4513f021226549734">buildDefCFAReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a66ba876f71016493af6fd1dc6980d912">buildMUBUFOffsetLoadStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a985ab67fe6c5e51cb42dc97aaf6b300f">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a686587ed0b5b8437aa621630cf56d147">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec2c920f97cffa508fee51ee5e722056">llvm::buildOpSpirvDecorations</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a8d3e918d874e8e80cf9a403e8ea59e32">canBeFeederToNewValueJump</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a6a91ff524836d3fca6cabe37c8fb7dc5">canClobberPhysRegDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#ab7abda321d5032f60d06bb2095350682">canCreatePoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f0146c14f7935bc4a6e5967b02b192c">llvm::canCreatePoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a2a5ba8caf566b63bea759399eb58927f">canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#adecd02add3a8a4d49bc27c4a6910605c">canFoldAsPredicatedOp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a32583e70bd8c1b6ccb45a21129efac24">llvm::TargetInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp/#a7772892599289e46b96fc0f775fa0a24">canFoldIntoSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a78b51fef75563bb7e8f5398de1593396">canSpillOnFrameIndexAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a5e731292c2474865560219c29069c6de">canUseSiblingCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a63e41a021ab399fe0054faade8a184b3">CC_AIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae9fdb22bd3bd49303fbaf324c924f73c">llvm::CC_CSKY_ABIV2_SOFT_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7c58eb7c6cf6b55da864fe749fea62ad">CC_LoongArch_GHC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a90abcb97861455132a9ca451c19405f0">CC_LoongArchAssign2GRLen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab15d7687532864492d61498a0f24f98d">llvm::CC_M68k_Any_AssignToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a169d373fe5dc70c88b2a47ff825e3203">CC_MipsO32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp/#aa881d2e727e6a14013435af6691a598e">CC_PPC32_SPE_CustomSplitFP64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp/#a7a5fa20ecc7b5d7b962f4591ed563c17">CC_PPC32_SPE_RetF64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvcallingconv-cpp/#a10b000ebfe8f8018565e8180e73d3a7d">CC_RISCVAssign2XLen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a02b9ad5a7bd4edc9897926a8d1967db7">CC_Sparc_Assign_Ret_Split_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a0818113ef1e2baa976b60a563c589126">CC_Sparc_Assign_Split_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3624679803f9a11d8362aca440f744a6">llvm::CC_SystemZ_I128Indirect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a41dd5c8db0f0898d613b138097515474">CC_X86_32_MCUInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a4634e79ad97015aa93f2379f619cc6ae">CC_X86_32_RegCall_Assign2Regs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#af8687e6a4188d6843aebb24bf2944804">CC_X86_32_VectorCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#aaa1494436b6de4729389856e59276c98">CC_X86_64_VectorCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a14a88401fe6f00ed3b943fa7f0132d46">CC_X86_VectorCallAssignRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a45a05a932f80f51023592ff5131d56a5">llvm::GISelChangeObserver::changedInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#aa49d47a31cd6d7ac85e7aaa3753ccc48">llvm::SIMachineFunctionInfo::checkFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#abbaf6b527fda317964759a8917f436cd">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a37a1b9361cb4ed78aa4af0973696f7fb">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a7d574da13bc65b93810a42059eada04f">CheckForPhysRegDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyexplicitlocals-cpp/#a6f95f7127e378cb5b033191ab8cf2286">checkFrameBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a8e71614eed98b51939998f17268d534f">checkLowRegisterList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#ab9b158c8be77ccffdf26833564b4f37f">llvm::jitlink::aarch32::checkRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#ab99fc0d5b2464663274f43ac29b12fd8">llvm::jitlink::aarch32::checkRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a8380bda17afbeb9b1792136a17e55f74">clobberRegEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a4db3746fd517a6ce4e428b4ead57cb3d">CMSEPopCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#ada53f9e75a087c02dcea98064c69900b">CMSEPushCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armelfstreamer-cpp/#a89eed11a3755fb8d00e417d840ab102b">collectHWRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a08414c5d48fed44354cf4c4ea6ca464c">collectVirtualRegUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a3fb8c57a2275283cbb376004421318da">computeLiveOuts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp/#afdf1630cc583964ae0b965eb5ec72797">constrainRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a51f39da29f54df5f90a0752608d8f8c1">constrainRegToBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a1112b818386ec01ddfdf3a5d0024eb17">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#a05ce2aec67d9c398ce268ac0c33c5c7b">llvm::LivePhysRegs::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregset/#a4a4757440aca7a508e30da6a766d7a8d">llvm::LiveRegSet::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass/#ad183dc79953e350b769b1dcfda4f0f1c">llvm::MCRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a55a5d6755fad4bd4aa961d509a02f0fe">ContainsReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp/#a8ca7dcaaf79f3e6154ab5f666887de5e">convertFPR32ToFPR64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp/#a8ca7dcaaf79f3e6154ab5f666887de5e">convertFPR32ToFPR64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp/#ab02d828a4a8fe967389707fb682678a8">convertFPR64ToFPR16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp/#a9944b95e95f191f78ad0fac8ea521c59">convertFPR64ToFPR32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp/#a8f2fff4d55418f103def03e4b16e1ebf">convertGR16ToGR8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp/#a3b8f2c8dafaf2b1007b8661546ce5aca">convertPtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a08a17634afdbaf2ee268be6118014845">llvm::CCValAssign::convertToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp/#ae595490c22a7dee4fe405d5c91182591">convertVRToVRMx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ae215c9475e5b6a8ae5efa8ff60202dfe">createAArch64MCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#afb762c1cdb87a67e41a3ba53d47ceb45">llvm::LiveIntervals::createAndComputeVirtRegInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#af517e546ece4970a718601f99698bb82">createARMMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#ad68a92d238fff893e319960f0f041c2e">createCSKYMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad301df8bf0c11d0c17113d3c221025d8">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af7b1b04b85a4e865d887cbf6f5889a10">createDefCFAOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#acffbb09726d9e1a3af9ef69fcbbf0a24">llvm::LiveIntervals::createEmptyInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ab97aac84df43680850d552a2a42d7cc0">llvm::AMDGPUTargetLowering::CreateLiveInRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a7cac8f57dc664e3f6933cb4d060d7747">llvm::AMDGPUTargetLowering::CreateLiveInRegisterRaw</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#aec7962818f16c459fa68050e1dab39ff">createNewIdReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#ac87ba800a84c083b0ff262ecb6b7f2a4">createPPCMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/mcaoperand/#a5ca05a7b3d5e0b8c785146850f4cec1c">llvm::mca::MCAOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a1bc684eccb765b481edaf1bfa0de9897">createSparcMCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a2d97a732765b2f5e4ffc1541a191facb">createSparcV9MCAsmInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#a14864e8babd0d6b24342db6e6b2ca9fd">createVEMCAsmInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c02a62be344861d8a7598e08d1021b6">llvm::createVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#aec2fa7c07d3f8428a21ab34269b90456">CustomAssignInRegList</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgcallsiteparam/#a93938c7e9df46f6719931a93e7ef10cd">llvm::DbgCallSiteParam::DbgCallSiteParam</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#aa38e3d08d83d51968909ce4650414015">llvm::CCState::DeallocateReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ae842ed2431c16fad8837b6eee2963d08">DecodeACC64DSPRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#aaa816f0501f605b43ecfba1c1bbbc22a">DecodeAFGR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a48c971111ef9bca538397e06dc551e4b">DecodeARRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a1368f2caa6861be3a936552c8d45d5d8">DecodeCCRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a74fa34159304f5cc893d02ae5c7b8e87">DecodeCOP0RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15a9b5c3c2f47acc2bd00680d210f354">DecodeCOP2RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#ab2cb60ed0bd0e9c7801349baa1a5b791">DecodeCoprocRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a174e2fe8043752fc8b0b96be6c3cc8b7">DecodeDFPRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#a25e09a35ef1f2bfcc748f53f59d9e9f1">DecodeF128RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#abd0f9e6edce55bf345b87ec220c724e5">DecodeF32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a169bff9f64a6601d3a0cb2316e8328ad">DecodeFCCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a132b5510a16484e499d756f921457217">DecodeFGR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad762ebb8447883cc06cbcd8680b5e4d0">DecodeFGR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af6fa5d60a1634d3b27cec9dd185b3e35">DecodeFGRCCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a4a95f69f6c5c027fc46fa94fcd465045">DecodeFMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5506baa3dada53698432a211bb3b4289">DecodeFMem2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a6d0d0fbc04194d17d3039dfd16666715">DecodeFMem3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a01c88b37f10b149a379442567798c604">DecodeFMemCop2MMR6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#aeaf09a414c497b64bc8882d42c77f7d0">DecodeFMemCop2R6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#acfee40040ef185edd60491ec6e58687c">DecodeFMemMMR2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#aed550a5b0a70ab51519b9fc5ab7ea4d9">DecodeFPR16RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a650d6cb5d9207463a2b420afaff1f488">DecodeFPR32CRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a83b8262d9a6235e7f0707e9eab6b82a6">DecodeFPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#abdfa60ed3d8f1a5d58914d275709de02">DecodeFPR64CRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a3d490b02154a9841e63ebb6293176d26">DecodeFPR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a009e8c7d882053a25451365cf8e2100c">DecodeFPRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a9deefe6628459b5cbdd92a375df7e139">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#ad5c79fab583fc33e74dccc9bbbbd4d33">DecodeGPR32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad7b416d3b522e21404f78a1eab340af0">DecodeGPR64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a3b485500cc5254e9953c767f6cceb455">DecodeGPRCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a52685adb34dcf188c60c2ba51d525985">DecodeGPRF16RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#ac1ab8132c146da3c4dba810064ac142a">DecodeGPRF32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a27af225c6500f75cbfd1ebc92bc64187">DecodeGPRMM16MovePRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a1b1ee55c95d75f26f7d9bce0304bace9">DecodeGPRMM16RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5fa96194d9731f200e8a98eb57cdcdce">DecodeGPRMM16ZeroRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a92a882831081786f843c7c6576f3f07c">DecodeGPRPairRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#aedf05d82c0c624910fd446082c570568">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a43536c19f988be653313601406fe7270">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#af7b9010056da73f57af323bbbdb484cd">DecodeGPRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#aef924b245b8e7087df6d747fdfd3810d">DecodeGPRSeqPairsClassRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a3064c510d24cadb88ee0ba9bd478b2d5">DecodeGPRX1X5RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#af008c2190b43cc0f7b777e6efe35d894">DecodeGR16RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#acfb5083d3a9cb1e5815522d223c250a9">DecodeGR8RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a96ceb8c8ee42497bea9bec3713184d0f">DecodeGRRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ab3da98e8d7143c8431dba9e82dc2983b">DecodeHI32DSPRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#abb036651e7fc27cae114f365379a5f38">DecodeI32RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#a6301475864ccf3cb814dc7853cf15341">DecodeI64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#ab7c8b2ad6feda021ec9b6390f7c2ee26">DecodeIntRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ab311edf9208c4ecffd59d070b28acc9a">DecodeLO32DSPRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5226be2f481d1b712b374a6106eb05e7">DecodeLoadByte15</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af6be4e043e94b84a2f41ca62f43e2c33">DecodeMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a0846cbb46ed7dfb0fe8963f57e4e450c">DecodeMemEVA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#afc5d4d8f5a682f4c0ea86db0681099f0">DecodeMemMMGPImm7Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5cdc282caa88d2f28ce4792ad53d4471">DecodeMemMMImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad2f3f439d59b03ed49013e7aeaafd701">DecodeMemMMImm16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a97875810a5d927cedd5b85ab368caf67">DecodeMemMMImm4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a2a99cbe29aa769217b2e94ed6248575e">DecodeMemMMImm9</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ac3bab0bdce9c5d10efa38d46bd79271c">DecodeMemMMSPImm5Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#a7805e638ecb28d944b73a8227e16b323">DecodeMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#ae238e3463e82b7b4b67c04c9797c40dd">DecodeMISCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a9e6956193b81787eca9d4e84fa07d90d">DecodeMSA128BRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a93216f363b261e0c45c4fbb3c88f3b44">DecodeMSA128DRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#acf3299d43f5d2753e093d84f0d138c07">DecodeMSA128HRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a38cb0684cd1dac98218884dbd1ffbb85">DecodeMSA128Mem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a461387c78a2a6c203ecbd9979f651a06">DecodeMSA128WRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ac9553ad4a854ada48e9219742b3829b8">DecodeMSACtrlRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#aff3e7695c4f78d95357eeacbc558b67c">DecodeQFPRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a96b22eb76283ea544bc9c7be79086d62">DecodeRRegsRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#adf09a5323307968e37109f843ad1c115">DecodeSR07RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#acc1a655bd3be92cebaad9f904e63b1d8">DecodeSRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#a088edc17929842ef4841bfdcd36d5369">DecodeV64RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#ab4e01b6d719158aa7871aff1780be2bf">DecodeVM512RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#af066fcdb24a63946572929dd19609eb7">decodeVMaskReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#ac9e514c637e3b4a854e5bbdc335bb81e">DecodeVMRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a924863953fe38c5075ca2987a071b0b8">DecodeVRM2RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a88ce4565edd9e27d57d87c13811d631b">DecodeVRM4RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a8523dd0b2a00a817ecb488a195ea33cb">DecodeVRM8RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a91950ccc10b9478f3b9a2fb798a9abfe">DecodeVRRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ab5dbfcd8759c243a87ae147779edc32c">DecodeZPR2Mul2RegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a068c567d31464b292cd4a254e0cca751">DecodeZPRMul2_MinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a58eaab8d4f7a677b915d22694d73f286">decreaseSetPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/shapet/#a6ca0f8e7063c7877c83ee4f7812793a1">llvm::ShapeT::deduceImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ad269c6964062a546ea51482abf030796">llvm::MachineRegisterInfo::def_bundles</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a415a4642beaee4a3156251faaacab646">llvm::MachineRegisterInfo::def_instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a8c6432877c30fca6601db52f92573998">llvm::MachineRegisterInfo::def_operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#af30edca8f8a971b32190acd67f8dbd1d">definedBySignExtendingOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#a0c84571aa2288f85c80d91fe64f97926">definedByZeroExtendingOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#ac11097e2672b5d37ed48a38c9328142f">definesFullReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#ab3b7ba1740f19a026aa8c30f6057be58">definesOrUsesFPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9024bfb74506b66f45d153234a802000">llvm::MachineInstr::definesRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a02e130cc7c8eead6d7c19d6b4455a4ec">determineFPRegsToClear</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcframelowering-cpp/#af7eacb9dc874ff82d0adc0ebe891b1f0">determineLastCalleeSave</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aa3dfee03e12575026fa0a0461348a756">llvm::MachineRegisterInfo::disableCalleeSavedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a0bd30ba570d7cadf1358f8054ffe4af3">emitAligningInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a31d90fbdd0f4fc960f223f7a387948c8">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegD</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ac69253e4a7986e283df0a371a319bc18">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegDP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a1a1a3e34f65cdb3f4ea7d967d153003a">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegDPX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a1e77a6b019b5e924781835dd5f9e80cc">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegDX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a50e1e8be24fa73496f80007358d92bd8">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#afce8ec40bc4bd79a179048d37f415747">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegIP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ac87f7ff24156ef0fe203f78a922a0ac8">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegIPX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a02dfdb98a4f9996ad780bbcc7c0b8b30">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegIX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a28fe8e961b6089a703a0dfdae186cd8e">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegQ</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a31ba33e6b992f002b916b0224f900282">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegQP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ac1013120808337fef474c1264a592ba9">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegQPX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a15cd2c968655fb3cc3cab18184d7fb33">llvm::AArch64TargetStreamer::emitARM64WinCFISaveAnyRegQX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a44677421d479b0f5839d10e2ef35f299">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ab41f05f5b25ee7961c198f5f19002e16">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFRegP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a7314b9feb4a2f444de19656f2ec6b2c2">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFRegPX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ac2d469ec3052bb66b3d1c6dcd2ea93a9">llvm::AArch64TargetStreamer::emitARM64WinCFISaveFRegX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ae75c9f81c7fa8aee8813c6bd9023eee9">llvm::AArch64TargetStreamer::emitARM64WinCFISaveLRPair</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ae0235fe4ba101b9cdd00f83ed0044b7f">llvm::AArch64TargetStreamer::emitARM64WinCFISaveReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a105a5c8833b0af64cfa8b33929a26e99">llvm::AArch64TargetStreamer::emitARM64WinCFISaveRegP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a249025898dbac8185b1083fb3d33d163">llvm::AArch64TargetStreamer::emitARM64WinCFISaveRegPX</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#a7698b71bb0682ee226911926deded1b6">llvm::AArch64TargetStreamer::emitARM64WinCFISaveRegX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1886741049357a9b7cea7f8e8784a818">emitDefineCFAWithFP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetstreamer/#a1b6620ea0e0dfd2b9d7d316eb0fd0ded">llvm::X86TargetStreamer::emitFPOPushReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetstreamer/#ad2364c1c43f9e0178c8f7b5b67cc5cc6">llvm::X86TargetStreamer::emitFPOSetFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a1041b4042ad87c8a306b5e0edc9fced4">emitIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcframelowering-cpp/#a23d4062f31c06d23731cccff25e7eb44">emitRegUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcstreamer-cpp/#aa393c949f47f42880e9be43c46254ffe">encodeSEHRegNum</a>, <a href="/web-llvm/docs/api/structs/llvm/loc/entryvalue/#a9bc391387e6d491179b0dd06a469170b">llvm::Loc::EntryValue::EntryValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#a12db326dc5ce11745051db706e75a3e0">eraseGPOpnd</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a47d4233d9f4a5998d0b67ebd1414dc76">Expand2AddrKreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-cpp/#afee96ecb8e8588a068aa3c1743b63352">Expand2AddrUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#afee96ecb8e8588a068aa3c1743b63352">Expand2AddrUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1e962b46ba9784205ea3eba9c0b10ded">expandMOV32r1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a68b101df4798d06a20096c78748efeb2">f64AssignAAPCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#ac0bff44982ab88d486466e16c975d0b0">f64AssignAPCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a1fac48a8f131620a4eca64a2811befe9">f64RetAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#acc1e4ca49328979aa5ddd8e4285e23e3">llvm::FastISel::fastSelectInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a7636a283116b131c3d7722fbb31bf9db">findAssignTypeInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kframelowering-cpp/#ae82cb5b8bd04147ce1ebe063f447c718">findDeadCallerSavedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3c1b81d7f789e05649b45677872cb281">findFirstFreeSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#ae9089253a8c971c8429d201735c81ed6">findHoistingInsertPosAndDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/initundef-cpp/#aaa5adc9fa31e5b621e14ae1b2560534e">findImplictDefMIFromReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a8552801cb962041dbea8cc767b82e850">findIncDecAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a886abe92149e28e4a886f931b76d3960">findIncDecBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a8b1a8fc118e74550d4d11d8740ae10eb">findNextInsertLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afc1df0cb1a8c3103a4266def94c3a670">llvm::MachineInstr::findRegisterDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aedaafad0e3bea3243199613910e2a7ce">llvm::MachineInstr::findRegisterDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab692b90c6e0e9b450f407896cbbe4b02">llvm::MachineInstr::findRegisterUseOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a934c36cbb52619d7d75dfc0766e2b946">llvm::MachineInstr::findRegisterUseOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a4a8c56807dfa1a49f37218084fb6c044">findRenameRegForSameLdStRegPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a8705d5d3c895b6ddc6502220cbe3a965">findScratchNonCalleeSaveRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#ab3ccfafbeec394fdd258288cec644ce9">findScratchNonCalleeSaveRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a1d85560fff9b526eda51892cd899e098">findSingleRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a349ccb69c0901c3188afbce59873f56b">findSingleRegUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyexplicitlocals-cpp/#a125b8a4a3a9e2088275b98ed22e2378c">findStartOfTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a989e26280ba069ba20dd83144c3bd31a">findSurvivorBackwards</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#afb31367a4e0005968619f3418c0a03e1">findTemporariesForLR</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#aaa14e1721c0e785bf1ab1487c9920dc1">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::findUnmergeThatDefinesReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#aba0076206670f37e37855c8421061a3c">findUnusedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ac9883c9ec5baeee39d4215b9af8e0a70">findUseBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ab457e04adca93e5cb81989a2414b1a49">findUseBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a63bd353ca84282a830d803a6bf9e4c5e">flagsNeedToBePreservedBeforeTheTerminators</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa41c45a69f227ee71e5ced4e6e3fde18">llvm::TargetInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ac0ce44d8c76d29835fb8f68dd8b88742">FollowCopyChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad41786bff2f31140c40979fdd64b6769">forceReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a20afbbc02b58a57256a9ac9736d08838">llvm::MCRegisterInfo::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6c591a3ddfec09a0ab48cba4743417d5">getADAEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#a85c1ec2b6a80a274d6f070a19045d392">llvm::rdf::PhysicalRegisterInfo::getAliasSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86tileconfig-cpp/#aeb19e00fc85a145a41d2cb03726105c3">getAMXRegNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalize-cpp/#a7d4da10beff712762d6e9ebbf51b339a">getAnySgprS1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#ac427af237002cfffc36dea0729964774">getARClassRegisterMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a51e652265b0217f8fdba9f95129c0d47">getBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae3fea3a4db1d023b6ce5a3d33cb513e5">llvm::getBRegFromDReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#af6bfa18127f16dd84301143202b34ee1">getBundledDefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2a0d637eafda3140c5ba8f8c17ba25d9">getBundledUseMI</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#ab3cb7dbd484c6486df9845e4adaf074a">llvm::RAGreedy::ExtraRegInfo::getCascade</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#af1c8e47623a3267db631f4b84552217e">llvm::RAGreedy::ExtraRegInfo::getCascadeOrCurrentNext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#ac6fc5bd19383b302adec32a29dfc5be4">getComputePGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a0a8ec285561c2428cdcd450331e5aca7">getComputePGMRSrc2Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#ad096b6ca7076d1827209c213b7daef2d">getConstantZext32Val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96b61989528fd1061ce48169e066cd14">llvm::getConstFromIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a820eea71d5b67cf63757e49e3c55736d">llvm::TargetInstrInfo::getConstValDefinedInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6551350658729b36c93362fcff19abab">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a070b3f2797ba2b732632887a21831150">llvm::SelectionDAG::getCopyFromReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7c3f57225b086beb519a28087b4c2d3f">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7244306a62d6e9858ef3b1be958f9740">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a75eb4d99ebf26777f16034567505166b">GetCostForDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42932b5e23d28c3fefca0ab878a56a7c">llvm::getCRFromCRBit</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a3213a94802bb4f87a3e388af6cdd9d7f">llvm::CCValAssign::getCustomReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a59b9890650c2857c6688596e74fefef1">getDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a05c54bfb75dbb555ab457e768bbcfe73">llvm::MachineInstr::getDebugOperandsForReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa0e69cc2fdf3daec4ae61c572d71bf43">llvm::MachineInstr::getDebugOperandsForReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af06fa0062be2cb3feb58ad49814b9b2a">llvm::MachineInstr::getDebugOperandsForReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adbf6afc10ae6b65838f21620477623aa">llvm::getDRegFromBReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a6d17b1c87fb8acd3da00cdb7f2c86117">GetDSubRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp/#a5c1040e7ce3199cf1f9adfa1e7d7ad25">getDwarfRegNum</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a6ee72f197966e553de0811468858a7d3">llvm::MipsFunctionInfo::getEhDataRegFI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a88977138a65e44f5f302342e4a00b501">llvm::MCRegisterInfo::getEncodingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7326d1a0ae53d6dece409404840c5e6f">getFoldableImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#aa6438c766cdab5c1e26d802ef9ad14ff">getFPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a936aaf6ef49c9323820f22ce2288979d">getFrameHelperName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#aefb3b77455d0e0f2e1e8b56604c63c0c">llvm::TargetRegisterInfo::getFrameRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#aa974adedc988dcb5c7b9600781bec9f1">getHexagonRegisterPair</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a954d76fe761bb4014b2da81cac2360cf">llvm::SIRegisterInfo::getHWRegIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a72580c3c077be0ea41a3636088e0e9d0">getIndirectThunkSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a339e0ad5e938860dcbd0c510ce212c4b">getIndVarInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#af196b990f6f506c44a4512bad4a36cef">getInstReadLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorprint-cpp/#ad9cb065825ddca386eb816be1598e2cf">getInstrVecReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a8208eacaf02c9742c8ed7f09ec0837f3">llvm::LiveIntervals::getInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a5cd4eee1caa18a946143934b4d0220b1">llvm::LiveIntervals::getInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a8d997e12374ab5416fd77c9c0244a5a1">llvm::MipsFunctionInfo::getISRRegFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a11f590fcfb0ddbe8fe971e1b77ee2876">getJumpTableIndexFromReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adfa3ea495f3bf972e75bbad9e4e0d151">llvm::getLanaiRegisterNumbering</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a60dfda975fe4068ff59554303033a9a3">llvm::FunctionLoweringInfo::GetLiveOutRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a923798c288aeebf99a43eb7191492fe2">getLiveRange</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6cf855363122e65fd4e6f2df1d16aba0">llvm::TargetInstrInfo::getLiveRangeSplitOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acaa1b5dff8de1c3bc2e3e9fee3ef7459">llvm::getLiveRegMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a938b09367547ec52608f278241de4ad4">getLoadStoreRegOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyexplicitlocals-cpp/#a0ee5c6f8045187f80dc03efaaf458320">getLocalId</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a2a28f143303b39650c069b1ce0925287">LiveDebugValues::MLocTracker::getLocID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a705be3f7ea0c2050a03f93ea0d51b3fb">getLoopPhiUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp/#a23877408ca0a8e70800e92900708baaf">getMappedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#aa5aad3f9195b1fd331f449ce9a709da2">llvm::TargetRegisterInfo::getMatchingSuperReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#a714ccddaeac7aa56e09e26f2532064ed">getMax32BitSubRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#abc325a2174e8b3649c8867e57f66f3b5">getMaxCalleeSavedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#ac7bca61e537185dff61903b3228d833b">getMClassRegisterMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a12457438c2b018b673e22e0253e466c4">llvm::AMDGPU::getMCReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetregisterinfo-cpp/#a3d384230ab441fc0da0f899122f07b4e">getMinimalPhysRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a669b322839fdc3449a417a7701e04cf3">llvm::getMSARegFromFReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#a960a9047d81cb10b7375cb49364d29bf">getNextOrderedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a4e27e418474f9d51f09a8b940d476faf">getNextRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64instprinter-cpp/#a18ded901f58ccd409dd051ea65458c15">getNextVectorRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#ae1b40d8cfb58f282fa1680fdff5ef001">getNumAllocatableRegsForConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fasttileconfig-cpp/#a10096b4ed26c2b9a8fe283a459e4d81e">getNumDefTiles</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a564aa23c9a5cf95820535f59182aedd4">llvm::MachineRegisterInfo::getOneDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a629d41f7f65cdba7304662a7c7132345">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#a1d482e971c16a2ec43e2f493ca413ddd">llvm::RAGreedy::ExtraRegInfo::getOrAssignNewCascade</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a62c18df693b93ed807e1d6852cc20f3e">llvm::LiveIntervals::getOrCreateEmptyInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#afed2e31224a0344c89a109d51a0ce14b">llvm::RAGreedy::ExtraRegInfo::getOrInitStage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp/#ac2221ad71323cfdfb9d5909e7d1f3775">getPairedGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siprograminfo-cpp/#a10b96dfed259151764cb09bce829818a">getPGMRSrc1Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a165430a83d0399a48d8983764c9e60b3">getPHIDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#a28587903fe646efc2cdcbab03d1dae6f">getPhysicalRegisterVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a28587903fe646efc2cdcbab03d1dae6f">getPhysicalRegisterVT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a228e5f06e0b1125c0b58d52bbe9afa46">llvm::TargetRegisterInfo::getPhysRegBaseClass</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstprinter/#a764e6f89eb04f23437c3d27b55f448f5">llvm::AVRInstPrinter::getPrettyRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ad363f72495aa7bb4c03423556d865ba9">llvm::SIMachineFunctionInfo::getPrologEpilogSGPRSaveRestoreInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ab63a202288b59ede08326547a2126c8a">getPrologueDeath</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#aff74ab74f8d91f36b55b0eba3ba18edc">llvm::rdf::PhysicalRegisterInfo::getRefForUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a29708e79e029f1029d46d65e7631b778">llvm::CCValAssign::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a20b2be9d8ff516d5478757c14dac3b58">llvm::SystemZMC::getRegAsGR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#ab9d9da4af59fe3a9a8b60bf5622abec5">llvm::SystemZMC::getRegAsGR64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a32c6ef22e9f5a480e20df9524c991f09">llvm::SystemZMC::getRegAsGRH32</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ad4f8f1aca0bb01f65be1d7dee43f7f83">llvm::TargetRegisterInfo::getRegAsmName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzmc/#a3e1c35d6865422ed00364cfd47460286">llvm::SystemZMC::getRegAsVR128</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5492997611db35edf27193fe170b4f06">llvm::MachineRegisterInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a718b488ac3350a59380b5070f54061ca">llvm::MachineRegisterInfo::getRegBankOrNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a7907102e3fee77f3105915033fa318a8">getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a34b5ca1a1228655842826f4bad8c44c2">llvm::MachineRegisterInfo::getRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp/#af17921b5ec93b0789e32ab52c9555111">getRegClassFromGRPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aa008940be15669d5b380a1423dae87c8">llvm::MachineRegisterInfo::getRegClassOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a4fd10e1bf2e5ffae96be5b2cef4d17af">llvm::MachineRegisterInfo::getRegClassOrRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a70892602f22700689a10d93ad3c9f28f">llvm::TargetRegisterInfo::getRegClassWeight</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/moduleanalysisinfo/#a042607ec02c65862f1bddded07e23082">llvm::SPIRV::ModuleAnalysisInfo::getRegisterAlias</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#abc10c981c4505185b1d517237acaf9c2">llvm::AVRTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a17b4520610e0151c3ea791c6adf27d07">getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64appleinstprinter/#a9890fcc46cf3c2ddb2eb3db81fe1b627">llvm::AArch64AppleInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ac44cbaab70907308f6fd0e94809d0e23">llvm::AArch64InstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a2d1579b3e66d752d5d8ecae54574c9c8">llvm::AMDGPUInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstprinter/#a49db3704b797fcc070156d9df6ed32cf">llvm::ARCInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#a9b86e6b94fc42a74efec36b6c8d5756b">llvm::ARMInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstprinter/#a584cea3eb41a015ce78e97f3b527f904">llvm::BPFInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a4a20d2694347d568e5722debeabe9678">llvm::CSKYInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstprinter/#aa848b4cc9e43dafb532b0d4c31431c59">llvm::HexagonInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a3fd7cca4c0d57853e9fa3c29be7f83d4">llvm::LanaiInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstprinter/#a22445f105ff77480271dccf3b427b480">llvm::LoongArchInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstprinter/#aed28dfefce76650afcb0b1159a2d93f4">llvm::M68kInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstprinter/#ac137be1c7a6107ca822a00bac2d2ceab">llvm::MipsInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instprinter/#a14168cb26800348c47e8bff835272b2b">llvm::MSP430InstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#aa021e0896ced10e79b81454e4186a7f2">llvm::NVPTXInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstprinter/#a84277ab72a3b3a1e5efaf81dd2b85a18">llvm::PPCInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instprinter/#a0a2167a586b22e7485cd030a06ca1b63">llvm::R600InstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a1cab2789f19376f5fd33eb8bcb6f7cb0">llvm::RISCVInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstprinter/#a7cbbd61733d0b078fc057fbdc85e44bf">llvm::SparcInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstprinter/#a0d38ec90351abf4bdf9f903110573ecd">llvm::SPIRVInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzgnuinstprinter/#af4ada4aaf8d8e055ea1487353f62f49f">llvm::SystemZGNUInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzhlasminstprinter/#a097cfc2f2cf32716decb074e2cd68bed">llvm::SystemZHLASMInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstprinter/#abf34666761e40710160323b789ee5e42">llvm::VEInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstprinter/#ac7e474d59356e83da891137d1f34ad97">llvm::WebAssemblyInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a124a43d72f8680a64fdd7132d29b1775">llvm::X86ATTInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#adf85cc805086cbd68bc73592c3d5d904">llvm::X86IntelInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstprinter/#a4d97c4318c21b0e44273995adfc87638">llvm::XCoreInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstprinter/#a96ae823b2970feb71038752d8e76290d">llvm::XtensaInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ad53f28bfbc4b97b70d443fddefedbde6">getRegisterOrZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/fixupstatepointcallersaved-cpp/#abdbbbd165ab5fb16364c6f6b2a920664">getRegisterSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ade1f2320fe436fd570559a11f1167746">getRegLiveThroughMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp/#a894b4b25e2718aa162dc7675f5208912">getRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#ad12ad3638ef83e9281c5cab4a99f60b0">getRegTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a1815e03e4828869569023dbc394aba10">getRegularRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a6a6d0cc06dd7471df2ee45e20de662c9">llvm::AVRRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a2d536cb0afee47ed6a6fcbef2c85cfe3">getRVVBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ae545337f3c1120747e56e3f5b0aec17a">llvm::SIMachineFunctionInfo::getScratchSGPRCopyDstReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a5a223fa35bcfebf3149a762a7ede4303">llvm::X86::getSegmentOverridePrefixForReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ae51d322caa9d6592ff524f98563eac36">getSetupCost</a>, <a href="#acf8fc7aec1c211309bcfdadf5471efc5">getSingleLiveInSuccBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a6f56cad42a98befcbf18d43739282a38">getSpillArea</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#a02edb52f22f8509b8198c979602c40c7">llvm::RAGreedy::ExtraRegInfo::getStage</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ab2147cc6810c7774110ebed17d4a2242">llvm::TargetRegisterInfo::getSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a376f5aa1990808e8e65cc77dd462c677">getTestBitReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastpretileconfig-cpp/#a24cac6db509961032d22e5ac0362f178">getTileDefNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fasttileconfig-cpp/#adcc912b06f2dd906cea8a599bbfb7686">getTMMIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5dc0a32516ce31f495b440d47287028b">llvm::MachineRegisterInfo::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a49816805ae1abf4f4a01546d06c413a5">getv64i1Argument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp/#a185fac36097d2118ff0b494a0e6bb560">getVectorRegSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a38ebe847e991176c228c75849c200990">getVectorRegSpillRestoreOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a651d110c1dac1aa8d4ba6cf535bfa6a0">getVectorRegSpillSaveOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a513ea914cd36aae44b9f09ebdfafbae6">getVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#afd426d485b9c084cfeb540c87018b219">getVectorSHLImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a4200f6df2fb7c3d67e2b08b0fa0d0ea9">getVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a1d657bbeeb927506546fd529ebb0784b">llvm::MachineRegisterInfo::getVRegAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a43d14ce45443d02b378ac4aab0dec9d4">getVRegDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7c6fd268e11e2eb6e8d13ed32b1820c">llvm::getVRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a0659753c0326c2182ce0d68e1facd56c">llvm::TargetRegisterInfo::getVRegFlagsOfReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aed28a3ee377374468972d5ba4e5cc15f">llvm::MachineRegisterInfo::getVRegName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ad3603fdd430b146d72370dd19afa46d6">llvm::WebAssembly::getWARegStackId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd04b8a497d63d4f11a884ac2ec54f53">llvm::getWRegFromXReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5690bb8ba0b629acff71bb5b4f2e5b4">llvm::getXRegFromWReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#ad025b047378266c13a216920a6ec3346">handleNormalInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a90cb28ef245dd02827b432caed30f710">handleRegMaskClobber</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/#a5da5e370a00cc1e7b56ddc386a739c0e">llvm::BitTracker::has</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuresourceusageanalysis-cpp/#a90ddf54173e251a10dbe49c466971999">hasAnyNonFlatUseOfReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixirreduciblecontrolflow-cpp/#a0b242745d9d1004fe6148b674533afb2">hasArgumentDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a067c1c89704407541cbed8d65ac8dd66">llvm::MachineInstr::hasDebugOperandForReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a5c94b329f3cec9f4fd23db1d208c0bc8">llvm::MachineOperand::hash_value</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#ae5ac9abaa969c4e2801c8c4cdf1dde72">llvm::MCInstrDesc::hasImplicitUseOfPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a11cd70de340f310acc70781d57a00136">llvm::LiveIntervals::hasInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#a801fcd2cb84f0d0292a77e675c7c492c">hasLiveThroughUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a881b49c730ea9d71536df2bf6847f4d0">hasOneNonDBGUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a16fdb3e37daf197199709a37540402d0">hasOnlyLiveInOpers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a22c99596004378b139e9ab48fae048dc">hasOnlyLiveOutUses</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a551bf42450565a2397d0d7033f8d426e">llvm::SIMachineFunctionInfo::hasPrologEpilogSGPRSpillEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/moduleanalysisinfo/#a546a43f3fc0c25ab7fa23070cd633601">llvm::SPIRV::ModuleAnalysisInfo::hasRegisterAlias</a>, <a href="#a5523ffd2d5ced60566f3493c2b48e0e3">hasRegisterDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a0e61a18a8344327fa20ead0274ac9277">llvm::TargetRegisterInfo::hasRegUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#aa781dc3eb971ed5ccc75be17b3c2a9d1">llvm::TargetRegisterInfo::hasReservedSpillSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/splitkit-cpp/#a5cf70104d9aee77d3e009f270354e7ad">hasTiedUseOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#ac798656b15d5b309da9e0cf04880d2d6">hasUseAfterLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#afb944a33b354e4709fb99864f82b9c16">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a217ca2f956651626db2bf0fdf48bd82d">increaseSetPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmux-cpp/#ad13b0b341fa87a688496ceb0cfeca7d1">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp/#a282ab875b746f59b35ee8aa9b0b0b837">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#ad49d5358eb2049a14a99665fc936acf9">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mlregallocevictadvisor-cpp/#a4035cde766164dedab4604c02b29e045">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a04bc45ddbc56deb8b54dacaeea86df8f">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a61e27cf21f938d341d13395bb4e17493">insertCSRSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a1b25635def2844fb5e6c8a79f3af0a6c">InsertFPConstInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a9189604a4845165a94dd42f19b31e7b4">InsertFPImmInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#aa0cefa4c61cc43ff6fd225bc7b4f917e">InsertLDR_STR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#ace10d744a39163b9ab7a166157b018f6">insertNoDuplicates</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a8e7acd0466662074bd2486d1964cd173">insertPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a7f43397146b3eee4bcd4ff73ec27335f">InsertSEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a5c50c1e0000377affb5eec391c213df1">insertSEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#ae88297df93601a3a0929300e6a6b58d7">InsertSPConstInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a830c556c1d7adec01904fdfe8cd50949">InsertSPImmInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a0c212d531fb6d95129ce86a5491bae06">llvm::MachineRegisterInfo::insertVRegByName</a>, <a href="/web-llvm/docs/api/structs/llvm/wineh/instruction/#a100f5b470d7c2a8d19af574b844fa889">llvm::WinEH::Instruction::Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a39bc44baeb40615967a3ce797fb27900">llvm::FunctionLoweringInfo::InvalidatePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a3ccb37bba2965d7b115cbcbbb196b088">llvm::X86II::is32ExtendedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp/#a80a3dc6dc764547a5cd15ad955c3a50f">isACalleeSavedRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae4ac5c3f21740cf8f3f63e50de016209">llvm::TargetInstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#a67245482e0fb8189af448dfed2bc154a">IsAGPROperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#afd160d6c9cc947a3c786d83f07f06e71">IsAGPROperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#a80ae0cf300eb8dbe163a3f14636e6960">IsAliasOfSX</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ae175b31af8d3499f652b5658c385af9c">llvm::CCState::isAllocated</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86tileconfig-cpp/#afa9c81c1e91ee029402444bfac0c07d0">isAMXRegClass</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#a19df3fcdde4ba426474e5557736a4358">llvm::outliner::Candidate::isAnyUnavailableAcrossOrOutOfSeq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#aed3a5dba6b8da462e693c4965ec7c911">llvm::X86II::isApxExtendedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#ab6dbd93dfb585d2714b508b45e7c72ad">isARegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23937faaecd6b00acda39f636f62a986">llvm::isARMLowRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#aed79decf9ab2c9663d2a2170b0ef7a4f">llvm::outliner::Candidate::isAvailableAcrossAndOutOfSeq</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#aca57cfbe9483e432047e4df8f054e98f">llvm::outliner::Candidate::isAvailableInsideSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a0138c08492e75b8b22f8fe0764b95853">llvm::TargetInstrInfo::isBasicBlockPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#ad7ac9a830d8314a42e5b9d6d87168249">isCalleeSavedCR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54c680c694e322fc2ab1b141fa2421be">llvm::isCalleeSavedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecse-cpp/#a04077ca0440dd582f6d2962ab30dd0bd">isCallerPreservedOrConstPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a2bfcb8851d30d4d3ac6b27a82e7f85f7">llvm::X86MachineFunctionInfo::isCandidateForPush2Pop2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#a9d7ece2c75d96915529e44cd7e860f5d">isCompressedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a51d2560cf9a3b689810956a41ce33276">isConstantCostlierToNegate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#adeb4fa20d3ea1515e0a668fccec57f59">IsCopyFromSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#aaa2bd04c34b59b5b2a2c0189c58bc55b">isCopyOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a55d78ed0d26d6a1cde6e30c6f43a5452">isCopyOfBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#ad7e3e96f8628bc40e8f8a662e8ae72c3">isDblRegForSubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#af977af9be6319c90e0918cb38b4f045b">isDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#aa0224ce6f8dd63f7674a2a1f032e23ae">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp/#a9dbfc6f968f0d6cbfd77760b62a9b552">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad6838072f35cd662ae8704973ccfc407">isDefinedOutside</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#af85a5fe23faddaea6601422ca2854b05">isDefLiveOut</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a833aa9ac03a9d223ea251585baaa5642">isEAXLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a661b945147a53ef2ecf91646a481e67c">isEvenReg</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/targetoperandinfo/#a01dc0e0a0357d322249e844d0f9612f0">llvm::rdf::TargetOperandInfo::isFixedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucombinerhelper-cpp/#a3cc2ef5101115495b8700d1e71834d9e">isFPExtFromF16OrConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#ac67ddee154305e17ed2acb0303fe4f80">isFPR64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a0a4718b6006abc33142947dd02f514c8">isGPRShadowAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a3b0f315e261e572d6f0b357e4404ca42">isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a266833fddf153d13701fb723996d3155">llvm::AMDGPU::isHi16Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#ade9944e1adfb7c602c387d072a76d174">llvm::SystemZ::isHighReg</a>, <a href="/web-llvm/docs/api/classes/llvm/allocationorder/#a0015c7575c26c1f5ad7328dee6c669e7">llvm::AllocationOrder::isHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#aa612e3445dd582769ddde75a5c392414">isHReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600optimizevectorregisters-cpp/#a7556f534acec9d9f33e60823f5660717">isImplicitlyDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#aa350b116b644706eb0c341188c2a6a41">isIncrementOrDecrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupleas-cpp/#acd98f840a522e0b918f8589ba4be559d">isInefficientLEAReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa700c119e0f62d742e575aa66f8bd544">llvm::AMDGPU::isInlineValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#aea82178cea5a9eb61dbd5db4f0cf6ae1">isIntRegForSubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#afe78f37f6711d1eba5a7066809cae1b6">isInvariantStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a58e94bcde312518e2a3f65be4c2b9a84">isLaneMaskFromSameBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a4b9e1c74c0536fbade814091fd3c8ee3">llvm::PhiLoweringHelper::isLaneMaskReg</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a87536d29ad236f911a1e72dd210f9305">llvm::LiveVariables::isLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmasking-cpp/#a9f2e59104ff29fd8ad0707fc4a1bac1f">isLiveOut</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a585ff94978b2b41805b1cee265bbbe11">isMatchingOrAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#a34a62ddb3a640d8e527b9c568373b089">IsMovepDestinationReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#aabcaf2ed02932ae6f3ed22f9da8c02cc">IsMovepSrcRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a02146b9f74007031fa7a7436a1d49094">llvm::PPCRegisterInfo::isNonallocatableRegisterCalleeSave</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a77b97edc44b5be77eca22b106db414a3">llvm::TargetRegisterInfo::isNonallocatableRegisterCalleeSave</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aced5d43b6a199d148e877d5536e95739">isNonZeroModBitWidthOrUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kframelowering-cpp/#a56e90a2a52728c533c9a5f497e266f7c">isRegLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp/#a33f3613fb6558bae2f0d2bdd87e18dfa">isRegOtherThanSPAndFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a1c1669c081e93349baa5bcf3ca5aaae4">IsSafeAndProfitableToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a915d3a27fc972595a451b8f2b092bec9">isSafeToMove</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmachinefunctioninfo/#ae496035b161bcec55692209ba683aab5">llvm::LoongArchMachineFunctionInfo::isSExt32Register</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0f8a5563a0ea48d3d74b71e49c179e7e">llvm::AMDGPU::isSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad9b864efe9f37aaee60c010d2e5e6eb0">llvm::SIRegisterInfo::isSGPRPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ad5cc934c55e1ea5f64d3493dcbc3b758">llvm::PPCInstrInfo::isSignExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6c630dc63715497e5e49ab1ca9dc6ccb">IsSimplerBaseSCEVForTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp/#a3739959eaa5952384fc45bcc0d9a92da">isSSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp/#a11329b543886f5ac685e48ab2d45ee6c">isTwoAddrUse</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a4cb1878aadbbe2a380e1535971b3bb25">llvm::TargetRegisterInfo::isUniformReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#aa524a697f0c6f94cef4d7a1f48f856e9">isValidRegDefOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#a0ca5780a94eb690d0ccf6cdda9c16df9">isValidRegUseOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64instprinter-cpp/#a999c6cf9cdcc9f0e69e737ab3e280e25">isValidSysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#af036c502ce8cd3a539589497206c53e2">isVCmpResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorprint-cpp/#a8717fdb397a550ef31154bccf5cfaf0b">isVecReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a6d63c5cc5bfab2094fae30cf9472d436">llvm::SIRegisterInfo::isVectorRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#acc7a469d7d5e4183e2b84d15072786cf">llvm::PPC::isVFRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp/#a9f76c7673322a26dbad00fca14f23e3d">isVRegCompatibleReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a5436d12d95e36064db97636d22f20988">llvm::PPC::isVRRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#aa2a1ec6e61c80b53b1c166df59f9048c">llvm::SIMachineFunctionInfo::isWWMReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#ae63be8b012497f28a863be8cfa255a87">llvm::X86II::isX86_64ExtendedReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a5f97093f1f56f60672b73a8285ce9c96">llvm::X86II::isX86_64NonExtLowByteReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#addd65697e241d821dc9f036f85799be9">isX87Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#aa9fd738474c4c822202e6d73a9509904">llvm::X86II::isXMMReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86vzeroupper-cpp/#af73deea36d6c25eea9242929d3443588">isYmmOrZmmReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#acc7da017f8afea15479e578fcc10a2e2">llvm::X86II::isYMMReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a7640b7b696150d562dad41bf6dfd8d02">llvm::PPCInstrInfo::isZeroExtended</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a301d6276fae739378e945ebbe0c8dd9b">llvm::X86II::isZMMReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a81547ddac1cc7ddad9428925e49ab42b">llvm::MachineInstr::killsRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a77def5524fdc0075b9303cdbb3f01c9e">listContainsReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#a93435c79c80dceea8b29e6b47993a577">llvm::LiveIntervalCalc::LiveIntervalCalc</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/#a7965085ad136e44f328fd9c60c7b1de5">llvm::BitTracker::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64instprinter-cpp/#a4d64bb1fbe56c27449145b46a514bd30">lookupSysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloop/#a7b25b2f840c82a24dfd0fe80b5cfefc9">llvm::MachineLoop::LoopInfoBase&lt; MachineBasicBlock, MachineLoop &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af9f436f6b3196efa8801aadaaf8dd52e">LowerCMP_SWAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a1ae2387cb76daa6d4328c2cc9ab5e850">llvm::rdf::DataFlowGraph::makeRegRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a239d964ac9520cb492a050586bab9d35">mapArgRegToOffsetAIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a5a0637aca1d829036e748915f7c6f306">llvm::SPIRV::mapBuiltinToOpcode</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-efae7fb4ddc27ed2c2f2cd5628dc6fc8/#aa074c0fa3578716addcfca558a7e5e25">llvm::yaml::MappingTraits&lt; VirtualRegisterDefinition &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a0eb9e76a3be6c20a8c72773921580fda">mapRegToGPRIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/checktype/#aafc5456b08c227cb2878941cc8b2b972">llvm::MIPatternMatch::CheckType::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/constantmatch/#ac307ade355a372f980397c901628e7b9">llvm::MIPatternMatch::ConstantMatch&lt; ConstT &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/gcstandregmatch/#a23af950b66bcb325cd214e286a8426ff">llvm::MIPatternMatch::GCstAndRegMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/gfcstandregmatch/#af0058d532d86b7f68d63bfebaf1df2bb">llvm::MIPatternMatch::GFCstAndRegMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/gfcstorsplatgfcstmatch/#a77650521ad045f4cba5ae0677558754f">llvm::MIPatternMatch::GFCstOrSplatGFCstMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/icstorsplatmatch/#afef6a39e06175a80941f6854cbd98ac3">llvm::MIPatternMatch::ICstOrSplatMatch&lt; ConstT &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/implicitdefmatch/#a7d62ea67a54a46c98b4eddb83e1e70f9">llvm::MIPatternMatch::ImplicitDefMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/onenondbguse-match/#af65b6fd4bd6d6677dbe245f491e8a4fe">llvm::MIPatternMatch::OneNonDBGUse_match&lt; SubPatternT &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/oneuse-match/#afa8af140b0f487539c250bd8344d2328">llvm::MIPatternMatch::OneUse_match&lt; SubPatternT &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/operand-type-match/#af49d803372802de65154acae13ffe283">llvm::MIPatternMatch::operand_type_match::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/specificconstantmatch/#ab2748073cc139b7f69b21c9dd015d3b4">llvm::MIPatternMatch::SpecificConstantMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/specificconstantorsplatmatch/#a6feff9f9ace47df12356c35c211c5ac3">llvm::MIPatternMatch::SpecificConstantOrSplatMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/specificconstantsplatmatch/#a759abfe5ebdc95c6414b9c6de77b85a3">llvm::MIPatternMatch::SpecificConstantSplatMatch::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/specificregistermatch/#a1c107068d72f67ff4fbf46caa83411c3">llvm::MIPatternMatch::SpecificRegisterMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#ab6492b3660d23f87b0c20e4abde633a0">llvm::MIPatternMatch::matchConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a6220c46118b22b8394120b87b1790e58">llvm::MIPatternMatch::matchConstantSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a77226965c5aa0b1e9d3b36481566b291">matchLoadAndBytePosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp/#a12e31c0c30a774b7e1a19becc5fa1890">MatchRegisterAltName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#a12e31c0c30a774b7e1a19becc5fa1890">MatchRegisterAltName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp/#a26aae6e65829a0b2261102272eaf0651">matchRegisterNameHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ac2bfcc1d9b7f5effd45c65a5f973df13">matchUniformityAndLLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a92451ecb6973ca4c1190514f75618d40">matchZeroExtendFromS32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblypeephole-cpp/#aa0674cf65bb72bf5302d03cd85c3f14b">maybeRewriteToFallthrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#afb4050a6cd4ceb53360df94a2ff6be39">MaySpeculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad9efbe0569f5011e43f8e847c0fd7e60">llvm::AMDGPU::mc2PseudoReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#a2eadaf6feef51fbb1fe642412ce54ae9">llvm::MCRegAliasIterator::MCRegAliasIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunititerator/#ad3b4547b7252d2399f4c9ff6729f02ce">llvm::MCRegUnitIterator::MCRegUnitIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregunitmaskiterator/#a354da5c3004b55b6143efd8272e6ab86">llvm::MCRegUnitMaskIterator::MCRegUnitMaskIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubregindexiterator/#a067b3c3d9f297a5f7f7da3277bc38f8a">llvm::MCSubRegIndexIterator::MCSubRegIndexIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubregiterator/#af085591de2aed7f37f36dc4f9ec7049d">llvm::MCSubRegIterator::MCSubRegIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsuperregiterator/#a078d1ea992de6b0fcae912cdd33af95d">llvm::MCSuperRegIterator::MCSuperRegIterator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16registerinfo/#a1d5cf121906fd0c39ea512dc759e9392">llvm::Mips16RegisterInfo::Mips16RegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a66e91c5407ade0326e5dbd87e986e648">llvm::MachineInstr::modifiesRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a9317ef8571eae8a49591ed8912c4d102">moveForSingleUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4da36cb65ef881f12fe1d40a47223a61">MoveVPNOTBeforeFirstUser</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/delegate/#a5328bb7196c84610e42bc3c86d37e115">llvm::MachineRegisterInfo::Delegate::MRI_NoteNewVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#a6f94ed74de2043a25224558de11aea10">needToReserveScavengingSpillSlots</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a70fad24fc4701e4e8313b3fea8312c1a">nextReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aa8694a1d461a5b2c58bd83bf50c9f46f">llvm::MachineRegisterInfo::noteNewVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a4b64c9a53aad9413158458205b492e94">llvm::MCTargetAsmParser::omitRegisterFromClobberLists</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp/#a9c40319b4934622623e10864866f6ecf">onlyAllocateTileRegisters</a>, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor/#a02caf38e654ee6b238b90b465fee7a7c">llvm::VirtReg2IndexFunctor::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a0d669c2aaacea16545cd82b179b8d848">llvm::MCRegisterInfo::operator[]</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a714428af145d6964f0312a163f7d3bf0">optimizeToFixedRegisterForm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#ab72dca1e43d1dae61c5f16bd623723fd">parseOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a78a8a248278b3e9ebca51f5ad204c51d">parsePhysicalReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a2b2f8e7ca0c6d68ca6795051d35afb91">llvm::MCTargetAsmParser::parseRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a78ed4247b51cb6ffdaedcc1ff8730246">peekThroughBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/fixupstatepointcallersaved-cpp/#a09e820de0ed1c5d75b6408fb04cda11c">performCopyPropagation</a>, <a href="#a1e64ed92fc7b343fa59c28105e16b794">performSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#af3659f9d7092d775e6bb2451b39aa440">popRegsFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4713251cc0d94764b3bafeff64a26c79">llvm::AMDGPUTargetLowering::PostISelFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a185f9311cecc76ba862f1420c20db158">printAsmMRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#abb1c33c814741adb78a9ff7f10ff3552">llvm::AVRAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a76421690e64ee4e01b59f44c74fa9c20">printAsmVRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a67bc6e371d9dfd804cecd64d83fd073c">printCFIRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64appleinstprinter/#a3cdb3fd30a503fa621fbf42da9b62de9">llvm::AArch64AppleInstPrinter::printCustomAliasOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#a63441d024a58d29fc32ea33c36ca9129">llvm::AArch64InstPrinter::printCustomAliasOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstprinter/#a5f60c1b4a2a5e2619e3b14f97fab4012">llvm::LoongArchInstPrinter::printCustomAliasOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstprinter/#a4c12c5b1ba721c45006904ba3522a7f0">llvm::RISCVInstPrinter::printCustomAliasOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstprintercommon/#a84f6f60161c89280faa55085b4cf5b67">llvm::SystemZInstPrinterCommon::printFormattedRegName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ac297f3bc74269d7fe98eaf7300cba9fa">llvm::MCInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ad2f7d11bf5482fbeda63ae80b1961306">llvm::AArch64InstPrinter::printPredicateAsCounter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a700a88bc424f3577f873f5038ba8ed41">printReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a778c8ea8e87db3255c4590a8a4a09924">printRegClassOrBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#ae07cd49d1962f418e0e2f363b0217219">printRegFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a5861c278d9a814fd24723840f9d91cbf">printRegMIR</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstprinter/#a4e47bdef6a886e01f2cbd46eb1dbb922">llvm::CSKYInstPrinter::printSPAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a61326cd6384971e828511e500b3367c6">processSwitchesConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a6f6181bdacf4ed6dda045f9c832df313">propagateSPIRVType</a>, <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#a6162447a68b07ae0c7ac50e0b2152c57">llvm::Win64EH::Instruction::PushNonVol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#a24366f8644cf1d6492c2abf2999311a1">pushRegsToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2380c209ae5339835b5e6ea6d5c197ad">llvm::MachineInstr::readsRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac823eae276c8bfe6d8c819a3927b7333">llvm::MachineInstr::readsVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a0e05a48717dda8a0ca99449587367660">llvm::MachineRegisterInfo::reg_bundles</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aa7bc06ec30359044cffdc3ccd58bfacf">llvm::MachineRegisterInfo::reg_instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a52760341a18bcab24705161c498aa6f5">llvm::MachineRegisterInfo::reg_nodbg_bundles</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ae916811c548f67c9ed178fa8a38ac7f1">llvm::MachineRegisterInfo::reg_nodbg_instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ac055593361bdcb9d0093f0881ce7f286">llvm::MachineRegisterInfo::reg_nodbg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a26ee456cc6716cfbc16261e544100b12">llvm::MachineRegisterInfo::reg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8e705934ca4178520c75d7ed1218cfc5">llvm::MachineInstr::registerDefIsDead</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#a123209f777591b5401b745f330892d5c">llvm::RegsForValue::RegsForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#ac18edb1d91090c7614b8fcd4dc45d532">regToString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#abf9973b1c9926f0903d0c6bddfc93118">llvm::MCRegisterInfo::regunits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a0dbecb97d916d10bb623cf46c199e0ae">llvm::LiveIntervals::removeAllRegUnitsForPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aa07c0db20cf93bf2f558d00af34a6cb6">llvm::LiveIntervals::removeInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#a7b644203b542cf4091b1ff74bafe78ac">llvm::LivePhysRegs::removeReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#af27497ce6068478bb97765620191e351">llvm::LiveRegUnits::removeReg</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a3ce32310fd2a5d6bf58316fd2a7ad1bf">llvm::LiveVariables::removeVirtualRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a515b9b6464ec4cbf5133d51f63a4e489">llvm::LiveVariables::removeVirtualRegisterKilled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a3107ed4a76b88b6513e9009057b7ad9f">ReplaceCopyFromReg_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcregisterinfo-cpp/#ac30c350ebdcaa96e93852ea6e7ace1c3">replaceFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a049dfdf656884a9d492cb2bc7a664dbf">reservePrivateMemoryRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#afaed20eb9e5f290239aa67ce0e8d7a0c">llvm::SIMachineFunctionInfo::reserveWWMRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#ac582a8ad2c8ee5589ed9251e0d86833a">resetRegMaskBit</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a8b418b49786b4eb1c06b0e407e346c01">llvm::AVRFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzelimcompare-cpp/#a1848f66c0fbc18bb70b33c1e10a9d124">resultTests</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25c7ccd93e74006df24fd1392e07014f">llvm::Ret_CSKY_ABIV2_SOFT_64</a>, <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#acdd5a7e265ee374819dc4039e2fae01e">llvm::Win64EH::Instruction::SaveNonVol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a9b83fea6470c12edb28e6b263d9a35c2">llvm::TargetRegisterInfo::saveScavengerRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#a240406f5d649c95da66daf851f871c01">llvm::Win64EH::Instruction::SaveXMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a9029683bf2a81e8247c168501e85a8b4">scavengeFrameVirtualRegsInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#ab328c242b91fe2bc4d6d0797761fdea1">selectDebugInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4b372ece8559169470a7fcfb471c2302">llvm::BitTracker::RegisterCell::self</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmachinefunctioninfo/#a546049a2a2b675535c1c9457e02c96b9">llvm::SystemZMachineFunctionInfo::setADAVirtualRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseframelowering-cpp/#a8058af7f16d3ab91b5a51f5102843b96">setAliasRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a80d1c640cbdad97a8cd47ffc7deea586">llvm::WebAssemblyFunctionInfo::setBasePointerVreg</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#a13c1c244b79282a279ca23eb3227275e">llvm::RAGreedy::ExtraRegInfo::setCascade</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a306fafb1bafe9d3071420d3795dcfef2">llvm::setDirectAddressInInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a24a896bd0b1be4f6ce1c3458612e5216">llvm::SIMachineFunctionInfo::setFlag</a>, <a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction/#aef7a47bd8f81f98a227fd2b620677aac">llvm::Win64EH::Instruction::SetFPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a02426e8fbe2929e8faa6a6b9b7a1659d">llvm::WebAssemblyFunctionInfo::setFrameBaseVreg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a6313fb5eb4a9b0feeaba3a8f4d4e08f8">llvm::SIMachineFunctionInfo::setFrameOffsetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymachinefunctioninfo/#ac8cf470332785916efa747fc5c240646">llvm::CSKYMachineFunctionInfo::setGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmachinefunctioninfo/#a9d2216566f0d7ecb7fbb57b96e2218bc">llvm::M68kMachineFunctionInfo::setGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmachinefunctioninfo/#af407c963e27d916f9ac8a603f4bb49e1">llvm::SparcMachineFunctionInfo::setGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/vemachinefunctioninfo/#a21142a5c8a8c3d27bea8a6088f2d28a6">llvm::VEMachineFunctionInfo::setGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a98f0a66a5debbefc23eff86baa986acf">llvm::X86MachineFunctionInfo::setGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a8be64a052a049ce84d8d94ebdfb311a6">llvm::SIMachineFunctionInfo::setLongBranchReservedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a6085917e6c5f643ea01c715f90bf80f7">llvm::AArch64FunctionInfo::setPredicateRegForFillSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a84f2897437136a65a41de83cc7a962f6">llvm::SIMachineFunctionInfo::setPrivateSegmentWaveByteOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a7ecdb920d3ec70d949ec71672c9ca521">llvm::AArch64FunctionInfo::setPStateSMReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a604722fe2776c0df4d275cff37a37d95">llvm::MCOperand::setReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eac561775786f17cc1201349328bf5d">llvm::setRegClassIfNull</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5ada07773b69dd6a5e99d47fe368d313">llvm::MachineRegisterInfo::setRegClassOrRegBank</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5559ff3731b4817f96a2e924e1cecf5e">llvm::setRegClassType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d4f8e3bb109dd110769f33e9c00e89f">llvm::setRegClassType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3f9bac9bdd3f5fc36a5f5e13480d4a">llvm::setRegClassType</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/moduleanalysisinfo/#a52e7a8b8ec3fbcb44ed9431abe93e1f4">llvm::SPIRV::ModuleAnalysisInfo::setRegisterAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#abd86d813757b6a6e4b94c03a856002a4">setRegsToType</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af2eb8df40ef12509174f12db70354adb">llvm::SIMachineFunctionInfo::setScratchRSrcReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a04cd8034f1174c19f9eaec2ecdde88a3">llvm::SIMachineFunctionInfo::setSGPRForEXECCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#ad046eec280d118d2c2b650be4425a6e4">llvm::AArch64FunctionInfo::setSMESaveBufferAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#aca78815d0b439cadb992c6436df5d72b">llvm::AArch64FunctionInfo::setSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmachinefunctioninfo/#a44f3e13ad6312d4d2b00bf4f7ae4eeec">llvm::HexagonMachineFunctionInfo::setSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimachinefunctioninfo/#a6fbf5e1b68e422439711404292785a52">llvm::LanaiMachineFunctionInfo::setSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmachinefunctioninfo/#a266734612e4c2db9bb695074eb5f4226">llvm::M68kMachineFunctionInfo::setSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a764d4a7ede91eb8bfdb9b1c6305418d7">llvm::MipsFunctionInfo::setSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430machinefunctioninfo/#aaf660f4e1b5f9a6d7ac2664d3730e94a">llvm::MSP430MachineFunctionInfo::setSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmachinefunctioninfo/#ae23a83eb98f8a37d7a4f7fedd16cb29e">llvm::SparcMachineFunctionInfo::setSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a4993ab3188344f6e93211a1953869821">llvm::X86MachineFunctionInfo::setSRetReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a3929601d0a7e443d08b6a3f97a1b66a9">llvm::SIMachineFunctionInfo::setStackPtrOffsetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#aae007416daf8e59d1f15eeb2dd09a53c">llvm::RAGreedy::ExtraRegInfo::setStage</a>, <a href="/web-llvm/docs/api/classes/llvm/ragreedy/extrareginfo/#a527a72f2e5631463b3f295d42309e031">llvm::RAGreedy::ExtraRegInfo::setStage</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo/#a913c7311eeb6015874ce00c44882a7c6">llvm::WebAssemblyFunctionInfo::setVarargBufferVreg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a791562f6418f0f3b7fd9c6920e2462f5">llvm::MachineFunction::setVariableDbgInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a2b34b6927d7eb879485cd489ee5e8583">sgprPairNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#aee328fb90c6cef95857090cdc67de0d4">llvm::RegAllocBase::shouldAllocateRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#af676cadcef1e3d4d159420f075a083da">llvm::AVRFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcregisterinfo-cpp/#aaa14cbf6168e04cf996c5ab314430bb5">spillRegPairs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#adfdb32bd422a7613ae83c10f2841abf7">spillVGPRtoAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#a6824e94d9b2072a10ce5b95ae157ce50">splitLowAndHighRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#ae40ad0fb496b80530278bd89806de1e6">llvm::AVRRegisterInfo::splitReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#acef65ff78e2f5e7b15e051e0f7296fb0">stripBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#ab2a489a7a85959d15f13f304b509080c">stripCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#ad85f1120e6b067734e6a186f29da3c73">llvm::MCRegisterInfo::sub_and_superregs_inclusive</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a9ded59d8266ccd2647bfd81722046beb">llvm::MCRegisterInfo::subregs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a95656353b813a1dd7ddfa7d8445633a8">llvm::MCRegisterInfo::subregs_inclusive</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a5e72490b2e8a4c4f70e0aab62f0ea176">llvm::MCRegisterInfo::superregs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#ad1f2700e4a533bcbd9d3c4e156a14d67">llvm::MCRegisterInfo::superregs_inclusive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a255fe9c612d68137bc4af488c99f5a6e">toCallerWindow</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a16297e722f8be82ffae1552bde33d061">toggleKills</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a982dd5c343c1b1e191b5cc1d00fefaf6">tryARMPackedUnwind</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a761a52d3bea02d4c73d51dff90e696da">llvm::MCTargetAsmParser::tryParseRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0db542f5acb6d354f4c775a2279e2350">tryScavengeRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a3254ec0c900f8e69d67ae32be83e801b">tryToFindRegisterToRename</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregcoloring-cpp/#a1aa5f22d75826bac2342e9dc078fd815">undefInvalidDbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aa44220d7a83b114a21ca2d23ffed03b2">llvm::TargetInstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a598eeebd324ee0050cc856e6e28f4778">unstackifyVRegsUsedInSplitBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#ab462c5bbf745633740ccfb2920040000">updateLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a77dea00ee37a964ad5edf6072fb35071">UpdateOperandRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1216c0733931de570c17ed44556139bf">updateOperandRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6eb3ac91456a9880aecf25dc8e3cbaa5">updatePhysDepsDownwards</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a79107186b863ddb50f8bfdb721aa41d8">updatePhysDepsUpwards</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a9a5c05172bf1b5e36b42f412c4a176cf">UpdatePredRedefs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afc7dbe81ac85421b062d799777484147">llvm::TargetRegisterInfo::updateRegAllocHint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aef898731887fc99f3a5e62710cb5bade">llvm::MachineRegisterInfo::use_bundles</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ab1c2de27f8d8c4a7de72d6415952473f">llvm::MachineRegisterInfo::use_instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5aa433099910dc844bc8466933779e58">llvm::MachineRegisterInfo::use_nodbg_bundles</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a8c1a48aa3d3155a0e942c785932d9723">llvm::MachineRegisterInfo::use_nodbg_instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a4361906d7698e8b1a912f6affc8e9151">llvm::MachineRegisterInfo::use_nodbg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ade188fadae5a455fcc4bd8d70142851d">llvm::MachineRegisterInfo::use_operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp/#adbcc7553355eafc7694a35f45b614e5b">usedAsAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#afdc3f396ced2d97e9feb5f89e6733457">usesExtendedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a9797c6d6b9fdb29489ea309649a0ef4a">VerifyLowRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregorunit/#a6f53f2e63b428a7e81d1b7c7b2230f4c">llvm::VirtRegOrUnit::VirtRegOrUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a60f1d0c2492ebc3d0e6eba6c6be95424">widenScalarLLTNextPow2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a1d7cfdefe09dc42a8d92cdf8e1ba7237">llvm::jitlink::aarch64::writeMovRegImm64Seq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a6d01c43e1d39cbe97b1c68d7e7c9fd35">llvm::jitlink::aarch32::writeRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#aaf50e0db42fa045e5c4161db69e98909">llvm::jitlink::aarch32::writeRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a1655ccaf8d05c56295292107ab293bfc">llvm::ARMTargetStreamer::~ARMTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsreginforecord/#acf8bb46871a16719557fc231d37f5edd">llvm::MipsRegInfoRecord::~MipsRegInfoRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#a03ab1a42b1533a2c912925f9bd8cadba">llvm::R600SchedStrategy::~R600SchedStrategy</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a19fbb56f62d9686fea21da81ee193de5">llvm::VirtRegAuxInfo::~VirtRegAuxInfo</a>.</p>

</div>
</div>

### sinking {#a3b48f4c83665c4a2ece4938ffc9ffbcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Machine code sinking</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### SinkInstsIntoCycle {#a33ac72ad86d97fe56d3ef6668df30680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SinkInstsIntoCycle("sink-insts-to-avoid-spills", cl::desc("Sink instructions into cycles to avoid " "register spills"), cl::init(false), cl::Hidden)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking/#af56efb8509ab5b039fe9dcf0c4f5eccd">anonymous{MachineSink.cpp}::MachineSinking::runOnMachineFunction</a>.</p>

</div>
</div>

### SinkIntoCycleLimit {#a084ec12a6f4a9e62a9fef7d321250c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; SinkIntoCycleLimit("machine-sink-cycle-limit", cl::desc( "The maximum number of instructions considered for cycle sinking."), cl::init(50), cl::Hidden)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking/#af56efb8509ab5b039fe9dcf0c4f5eccd">anonymous{MachineSink.cpp}::MachineSinking::runOnMachineFunction</a>.</p>

</div>
</div>

### SinkLoadBlocksThreshold {#a341405fd2cb2dfad3d03b4f76b1a577b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; SinkLoadBlocksThreshold("machine-sink-load-blocks-threshold", cl::desc("Do not try to find alias store for a load if the block number in " "the straight line is higher than this threshold."), cl::init(20), cl::Hidden)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### SinkLoadInstsPerBlockThreshold {#a001e53bb2ff322656f27e267f2409a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; SinkLoadInstsPerBlockThreshold("machine-sink-load-instrs-threshold", cl::desc("Do not try to find alias store for a load if there is a in-path " "block whose instruction number is higher than this threshold."), cl::init(2000), cl::Hidden)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### SplitEdgeProbabilityThreshold {#a9e692ddc4d0481e2ca501d7600f8b328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; SplitEdgeProbabilityThreshold("machine-sink-split-probability-threshold", cl::desc( "Percentage threshold for splitting single-instruction critical edge. " "If the branch threshold is higher than this threshold, we allow " "speculative execution of up to 1 instruction to avoid branching to " "splitted critical edge"), cl::init(40), cl::Hidden)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### SplitEdges {#a222c2bec99b5fc7d68f675248e085cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SplitEdges("machine-sink-split", cl::desc("Split critical edges during machine sinking"), cl::init(true), cl::Hidden)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

### TRI {#a0f36ed1bc17fc1aa97fe291c439a0698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned const TargetRegisterInfo* TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
  <a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a> LiveInRegUnits(*TRI)
</div>
</dd>
</dl>

<p>Definition at line 2029 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a8c46e5a35a9df5b131a85976d8d70af0">llvm::AArch64RegisterBankInfo::AArch64RegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a033ed3ccb4d48ca276a60b87127b344d">llvm::AArch64Subtarget::AArch64Subtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ab71e26dc84728f514a94593242e6d931">llvm::DwarfCompileUnit::addAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#aef8395275fb33cea31395023a1df1d54">llvm::DwarfCompileUnit::addComplexAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a8f7e4c04e50a907758b386c72881aeab">llvm::SIMachineFunctionInfo::addDispatchID</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a20d6ce13e4dd56524b3f12e9e0f4e486">llvm::SIMachineFunctionInfo::addDispatchPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a396ce0a5b70320d155c9959a080d543f">llvm::ARMBaseInstrInfo::AddDReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7b24fcad0f9310a088627066269508e2">addExclusiveRegPair</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a2d8c2f895782d369f697943a12afc842">llvm::SIMachineFunctionInfo::addFlatScratchInit</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ad11ce964b5bd5fa132b60b747c6da45b">llvm::SIMachineFunctionInfo::addImplicitBufferPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a8e62f53d9286d3407be6644804a7629b">llvm::SIMachineFunctionInfo::addKernargSegmentPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af9a1ca470b2b9c8e97304f5be5448422">llvm::addLiveIns</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a57484713254f31f8412d08ff85259761">llvm::DwarfExpression::addMachineReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">llvm::DwarfExpression::addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a52716532c3562bbe9c3fc343761c3c8a">llvm::SITargetLowering::AddMemOpInit</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ae282659fb0f4cba63172f01c97d1587b">llvm::SIMachineFunctionInfo::addPreloadedKernArg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#abe9cb2c1e57e662992ae50574e1e0669">llvm::SIMachineFunctionInfo::addPrivateSegmentBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a18a67353fc677817bcbf9ed74b104d8a">llvm::SIMachineFunctionInfo::addPrivateSegmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a3cbc6457d84c432dea9eb6d83ac711fa">llvm::SIMachineFunctionInfo::addQueuePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a6afe81a8562ad740b6edd4c536974067">addRegAndItsAliases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#acd5347e6bb4a068a8ecd7e2b4fd9d4c0">addRegsToSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a6090242d02f8da5fef11db06af3c5783">addRegUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ac65455efc149d81b4d1418acae7596b3">llvm::PPCFrameLowering::addScavengingSpillSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a33b1d3e5b49c049ed08f90d38070a751">AddSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a631f336d06a6088837d505bf1332001e">AdjustBaseAndOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9fb0978a667242babb4778cdf091945c">llvm::SITargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a38ff3df1feb7915dfda6303a34484534">llvm::GCNSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a3986e436467855478f909c9b2226a066">allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4678f677f6c3bd2a4c2d4b64549017d0">llvm::SITargetLowering::allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a3f11f14e589c7b0761e5c61899b6440c">llvm::SITargetLowering::allocateLDSKernelId</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ade385868ff059bef6446f70208541043">llvm::SITargetLowering::allocatePreloadKernArgSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#add01b669c3b94782f5e3a2babaa12f50">llvm::SITargetLowering::allocateSpecialEntryInputVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a3ef0dde77e91309be534394dc420d4a5">llvm::SITargetLowering::allocateSpecialInputSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa387b847af356ba9f53e3bb1384874a2">llvm::SITargetLowering::allocateSpecialInputVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a7e8edb844e6cf1666a202039e9a21d01">llvm::SITargetLowering::allocateSpecialInputVGPRsFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#ad930b47a8263b4fcc37e6209e387b897">llvm::LiveRangeEdit::allUsesAvailableAt</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad304b10479d6791deee8ad1b157fb37f">llvm::X86InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a2256b109946ab87fcd6aa4f82d610e28">analyzeCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab359f8ff91954b23a1e8366666e59cbb">llvm::AArch64InstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34ace715436fcbc42e83e196957b9f16">llvm::AnalyzePhysRegInBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd0dda5918de7ca6c16f4cb3553c261b">llvm::AnalyzeVirtRegLanesInBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a65d34a1acd6c2473aab0fabe963fccfb">AnyAliasLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a9e3defde95d12941aee71bb6f17a7b6e">appendScalableVectorExpression</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/callmutation/#a6cd9122ce8216f80dd0921f844f7b7e1">llvm::HexagonSubtarget::CallMutation::apply</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#ad3ecb1cd79a21ac1f6c064fb0ab8340c">applyBitsNotInRegMaskToRegUnitsMask</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a8b1432c767e3cc50f7cb6900285d003f">llvm::AMDGPUCallLowering::areCalleeOutgoingArgsTailCallable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a19a5a038e1b77984ca9710992b68b938">areCFlagsAccessedBetweenInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#aa67934d23b1e9ff1901ec570930128e4">areCombinableOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a23fc03605ab508eb40a5fb968a78e139">llvm::AArch64InstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a00f254751a3efe88d446fe5fdba2d7c4">llvm::LanaiInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a878d28bcb9d1575d5f5e56c5b1bcf064">llvm::PPCInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#afc0ac4e187f1865c16f5dd0814e7fa5b">llvm::RISCVInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/armregisterbankinfo/#aa2bbc28e24343e76c9a993bed3190ba2">llvm::ARMRegisterBankInfo::ARMRegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#af79b8bdd9826c6c96dd238e32520fc94">llvm::ARCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#aff8b6cd5f8dba25944e8d80ef4eb246b">llvm::ARMFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a1cbda27cd5e5010b2c49b7da0a29afdd">llvm::CSKYFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#adc3de6cf6278fe59671bbdd02e4c1516">llvm::HexagonFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a0c9359d4e969f68a7c7643fc3fcb5c">llvm::RISCVFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#abde66d9f66cba5679c5a1c1c87a6ea8a">llvm::SIFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a4554341b316dd0b06a915ec883f4f74a">llvm::SystemZELFFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#af8195925dae80a73b2c6101290b5962b">llvm::SystemZXPLINKFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a92320a6700ece82446fd508956577ca1">llvm::TargetFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a6a2d9dbee947de1e611cb27ae01419fe">llvm::TargetFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#a6e87024d7fe817808e0288f6b213d40c">assignedRegPartiallyOverlaps</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingvaluehandler/#a0d589439dcf785bc8f36eaf8f4b25a90">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a8c19565cecd65d8f7a60c5867ef5fbce">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::ASRWLoRd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#acd74fc209c40016d7ecf21dd989f8350">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::ASRWRd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a698910f5c9e87f36f1d200f1549f7f00">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::COMWRd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a74138abbe7f3e7c5e99195c2be34a002">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::CPCWRdRr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a987bfbc424c6ff1d326e8c46f70a39f3">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::CPWRdRr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a08ce728728edbc87f05151dac58e34ab">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::INWRdA &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#abbaeceac2b199f97c360e1bbc25602b6">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LDDWRdPtrQ &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a58e9647502521e6042d3e074f3bcaab2">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LDIWRdK &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#aad9372fc2673b406ab1ed5129b93d5bb">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LDSWRdK &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a0609363806d61ae2071fa0b40c90912f">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LDWRdPtr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a53eb253fad7f1c74944a70b80db06824">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LDWRdPtrPd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#afd78d85f5f4d8643f17cdd22e307ef65">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LDWRdPtrPi &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a81ef7826027dbba5db5581d2ed75f047">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LSLWHiRd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a4fa043019fb0e22c9a6ac2b19286a43b">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LSLWRd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#ae9aa0d7802472227814d5f02218dd9d1">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LSRWLoRd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a9c8628678f1049f69fc3a670c044f820">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LSRWRd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a6d42b32068d81aeb185e719d5b284701">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::NEGWRd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a7c6855340129c56b38af99ce00b2c3d2">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::OUTWARr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a46fbc1a4dfa9f1490154f055a0db0255">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::POPWRd &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a5f69c79226dcd5bc86bbf13b8381b87b">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::PUSHWRr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a04a49e2dd641ba9fd9758d4b96293a7b">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::SBCIWRdK &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#ae128dbcd240ab728c6887a4d3a3ece36">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::SEXT &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a2b8467a95de707ff3dbaf7ffbaa6c688">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::SPREAD &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a805f2e0106f53455754a4a20b7ec657e">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::SPWRITE &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a770cd6bae26137069b2ba0c632b7bf22">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::STDWPtrQRr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a6e43addd8d76953c0dd40993d59d67b2">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::STSWKRr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#af1dd8e1562da76bab430d74e77759536">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::STWPtrPdRr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a579a491caf1222ec0754ad35b46894e1">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::STWPtrPiRr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a61c0e5bb4bf171061cf5667ca89fe4bd">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::STWPtrRr &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a11b8117f6986d185fee7687907fdfd3e">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::SUBIWRdK &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a8559eca80e3e9fe988aa76b26f668bfa">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::ZEXT &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#ae3c01405586751c3fce580c0e2321864">llvm::CodeViewDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/bitmaskclassiterator/#a73b411cf3b472263dfda19045d45e93f">llvm::BitMaskClassIterator::BitMaskClassIterator</a>, <a href="#a854df6024334d02ea223f70a543940fc">blockPrologueInterferes</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfregisterbankinfo/#aa344b927ad1bb6e68eabe6f802fc7dbe">llvm::BPFRegisterBankInfo::BPFRegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aec0904aef5bec338f4fea047c49455aa">llvm::ARMBaseInstrInfo::breakPartialRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a525a9aaabc1362deb245b0099ea5538e">llvm::TargetInstrInfo::breakPartialRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad8756402b6bd331b493dc7c0b3efd984">llvm::X86InstrInfo::breakPartialRegDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#af5f0f04b137494bbf8fb56286dea2762">buildAnyextOrCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a980b47a164c04c64274ef41dba790718">buildCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad9c4463170797dc633ce8dfa192f132b">llvm::X86InstrInfo::buildClearRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a122720c6c9f5c3fd65169c6d123d2516">buildEpilogRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a2d1eb7b0207905141f6ddb1f228f3696">buildGitPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a4e6b353116922112b1b470ce15adb2fd">buildPrologSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a544e5e38d5032dd862ab44953c2c173b">buildScratchExecCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a4fa250f99a782d2da223c54ecde4acd0">llvm::GCNDownwardRPTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#ad67d6b7f9f91a2d5852b0f9aebfe542a">llvm::LiveIntervalCalc::calculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#a6c15e4226ea85c6c5ffdb7b907023b85">llvm::LiveRangeEdit::calculateRegClassAndHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a8d3e918d874e8e80cf9a403e8ea59e32">canBeFeederToNewValueJump</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a6a91ff524836d3fca6cabe37c8fb7dc5">canClobberPhysRegDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a7dc60439888b36449abcb98f47d23ec6">canCmpInstrBeRemoved</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a364fb004e57163fc1a3e2adc754af9b1">canCompareBeNewValueJump</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a80ba8826b4f8e7008ae9453968ed35fa">canInstrSubstituteCmpInstr</a>, <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/#a3359f38a412c6b9685e8fd39bd81b6a7">anonymous{DAGCombiner.cpp}::LoadedSlice::canMergeExpensiveCrossRegisterBankCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a435084f5e140c85f72921239385f9edb">canRenameUntilSecondLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af848272aaea9ac1f976aaf56fd31cb8d">canRenameUpToDef</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a2be9d35aaace9716441da5714f048af9">llvm::AArch64FrameLowering::canUseAsPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#aaa1494436b6de4729389856e59276c98">CC_X86_64_VectorCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#af745858766f8ab9fd5ef15335bd011f2">llvm::AArch64TargetLowering::changeStreamingMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#aed8bb289e710a4687f5dbdc1b0b35fd3">checkAndUpdateCCRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a551cf4f2a46a96b347d222acc8df059c">checkAndUpdateCPSRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3c612539445f4446eb1900f515b438ea">checkAndUpdateEFLAGSKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#abbaf6b527fda317964759a8917f436cd">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a37a1b9361cb4ed78aa4af0973696f7fb">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a7d574da13bc65b93810a42059eada04f">CheckForPhysRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a0e8adf21ba4a3e746edcd3b9cf9c5d14">llvm::SITargetLowering::checkForPhysRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ade4fa73063019f286fb23ac86df8839e">llvm::TargetLowering::checkForPhysRegDependency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="#a084d504a7f8b42657e1c910ba098ad94">clearKillFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a80efc9c4efae6c3235e65412a5e359e9">anonymous{MachineCopyPropagation.cpp}::CopyTracker::clobberRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a9e13fad0f5191583a8266f873d87cf6d">anonymous{MachineCopyPropagation.cpp}::CopyTracker::clobberRegUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6b1057a57ff0d013cd3a78bb69f43db2">cloneInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#ab0827bed6547378efa61b05fc7958a13">anonymous{BPFMIPeephole.cpp}::collectBPFFastCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp/#aef8f01c925c0c7beb94976a8f86a9af1">collectRegDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a08414c5d48fed44354cf4c4ea6ca464c">collectVirtualRegUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#abbb1f7665085c8f50fab2ceac4304d91">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::computeCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a88b438423c0bb502e843c7dae099b7f4">computeFPBPAlignmentGap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a14e3343381ea7e432b532ffdc24df933">computeIndirectRegAndOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a5e95e012bf0ddb58e7aa1025f7d093c8">computeIndirectRegIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf741b422c5f449eb83144c3c2fe9730">llvm::computeLiveIns</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a3fb8c57a2275283cbb376004421318da">computeLiveOuts</a>, <a href="/web-llvm/docs/api/classes/llvm/targetschedmodel/#a5a00ff1e3eb19fe4001d742d93f8fade">llvm::TargetSchedModel::computeOutputLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a7ebfe0cc2f78ae5f27e1944412606973">llvm::MachineBasicBlock::computeRegisterLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#af4a07ae5c460ac08439a1a71d15e0166">llvm::LiveInterval::computeSubRangeUndefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#aa238cd5a6fee2e66e4b5bd3fc2040c19">llvm::MachineInstrBuilder::constrainAllUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e6b3672f7d7a310e9b45dc48d464ee8">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a1076b6c332565550ddb86584b25f5df7">consumesDstSelForwardingOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#ae0bc43ffc97603d2acaf34479afbe0c8">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a7bc60d756c70f47b2a9a048c5b4cefa5">convertArgumentInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aa43a432a700f337af56c8f2d1db9fe0b">llvm::MIRPrinter::convertCallSiteObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aa02f64dd0aa867287b5ad17200de097a">llvm::MIRPrinter::convertEntryValueObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#acd4e3782462bd215bc07bd1f9b2b01b5">llvm::AArch64InstrInfo::copyGPRRegTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a01fce66601f12ad1b3bd219ff02c3426">llvm::VirtRegAuxInfo::copyHint</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ade00a4708e793e75a00a3030325cbf84">llvm::AArch64InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abef9f720617461778f1a2e49d17ea159">llvm::ARMBaseInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a5bde594eff371b34c5f5bf6222b690f6">llvm::AVRInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a3e0a4dad177be52a38a07e782fc9207f">llvm::PPCInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5e29efc37d9738b891d35308524d7d5b">llvm::RISCVInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a9cb1dd3dd16025fc64f52adb12c9ce5f">llvm::SparcInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad8b8d94aaf80cefc49bc3263f05cd741">llvm::VEInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a79b6327f4d0680e2eb8f28cbe3a2abb9">llvm::X86InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af01e300c1d03a13eb9edabea4ed9aef5">llvm::AArch64InstrInfo::copyPhysRegTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a436965f98f9e4301e33096c32ed6dbd2">llvm::RISCVInstrInfo::copyPhysRegVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#a669f90d5fe703ecfe25fb738553f6ea5">copyPhysSubRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/allocationorder/#a1d17986988f0819f29d78d1be8555c9e">llvm::AllocationOrder::create</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#ab710efd47f1e822b43de2f8726105f96">llvm::M68kTargetLowering::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a145f77473f4a050a8e1bf0dd7e2a34fa">llvm::createBURRListDAGScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd95c4fd57b9c1804bc70a37ac24574">llvm::createCFAOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae82d653cf862c571ba16050a19426458">llvm::createCopyConstrainDAGMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1170c3796a8947456c2d7841642b96eb">llvm::createDefCFA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad301df8bf0c11d0c17113d3c221025d8">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af7b1b04b85a4e865d887cbf6f5889a10">createDefCFAOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#abc6950c9642cee4a3149ee5e1afbf5fe">llvm::MipsFunctionInfo::createEhDataRegsFI</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#a3ed9b1830a33b388d26b73a324b8503f">llvm::XCoreFunctionInfo::createEHSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#aaf7ccbc0c4ee11882e3e2835d84b90d2">llvm::XCoreFunctionInfo::createFPSpillSlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24fb0e850aa86095101c2cd7110aa32b">llvm::createHybridListDAGScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2c88a3ebea5ca10491d30d01274c96d">llvm::createILPListDAGScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#ae45b4d95be1f419bfa32ece88b82ed6f">llvm::MipsFunctionInfo::createISRRegFI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab36ef7fb029dbd7ed2314db341b9f854">llvm::createLoadClusterDAGMutation</a>, <a href="/web-llvm/docs/api/classes/llvm/xcorefunctioninfo/#a75dfee78519833f2ad7e210c5e471f5d">llvm::XCoreFunctionInfo::createLRSpillSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81895310467818e56fd11bbcbb64ee59">llvm::ARMBaseInstrInfo::createMIROperandComment</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#abe6772bd0f8b4b1bc3186473a7205dfe">llvm::RISCVInstrInfo::createMIROperandComment</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aea7fb8b18a37883f51af73238e47dea4">llvm::TargetInstrInfo::createMIROperandComment</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a7bec9e5fa4cafeca001d506741b38f0f">createPostIncLoadStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ff60d96d753c683224740c17f57a2f2">llvm::createRISCVVectorMaskDAGMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa743cb95ae4e26544366fb66fa23f4dc">llvm::createSourceListDAGScheduler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bc2ad470d8a41e9423748814b0e3596">llvm::createStoreClusterDAGMutation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#afb7df659747f14484e642788c2fe6788">createTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a01ee44fd979fc25e2afe3d23a2079494">llvm::RISCVTargetLowering::decomposeSubvectorInsertExtractToSubRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9024bfb74506b66f45d153234a802000">llvm::MachineInstr::definesRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#ac9fa612919367a702574336b92a242d2">llvm::MipsInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0275d59e3ed329286ba88b96120d280e">describeMOVrrLoadedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a562f6e6e1f13537b17f177e13161a1b6">describeORRLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a27b8c40891bfea8db2ad3b9fa25cba0f">llvm::MipsSEFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a7865e2cad3030c3c48b64c9cf1243d46">llvm::SIFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9eb6f3247260b906218068229b8d5b67">llvm::SystemZELFFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a2f26766f4dcfa6457ba405584a34d5c3">llvm::TargetFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ac5bebf636fd9c3f6c9b7484f3244fb67">llvm::SIFrameLowering::determineCalleeSavesSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a0ad5cb616fdce8d90db0927dbdf0533c">llvm::SIFrameLowering::determinePrologEpilogSGPRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aa3dfee03e12575026fa0a0461348a756">llvm::MachineRegisterInfo::disableCalleeSavedRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae513c203a406e1186d2342cbdbf95765">llvm::AMDGPUCallLowering::doCallerAndCalleePassArgsTheSameWay</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#aa38ce9de80252e6af533d4544dde77b7">doesModifyCalleeSavedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#a86962b61c920a437e06eda5dafd929d5">llvm::PressureDiff::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#a9908e6684d648ead83a4bab5f1bf7c51">llvm::RegisterBank::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/registerpressure/#aed5b5c7fd078ad82cea332031dd5099d">llvm::RegisterPressure::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#ace1019e8cefb80490348369f12fe0a44">llvm::SDep::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#acee1b8853250afb7856e26623c828491">dump_registers</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#aa982f20e5259bc8094e8bcfd3c787e5e">llvm::TargetRegisterInfo::dumpReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb6fca77863850136760be488d6ea345">llvm::dumpRegSetPressure</a>, <a href="/web-llvm/docs/api/structs/llvm/veregisterinfo/#a6ab5420775a7cd360178e78c09f5774e">llvm::VERegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a2d8b50ff5c8dad758eb8d36c4d98bcaf">emitAlignedDPRCS2Restores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a3046f0367b644d6feafcc16f8da39967">emitAlignedDPRCS2Spills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ad04238a3223242e0565e4f98df0461a6">llvm::SIFrameLowering::emitCSRSpillRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a84c4c1518f3593f9c1d0b10f8364ebb8">llvm::SIFrameLowering::emitCSRSpillStores</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aa441f906c99d29f50a64369799d8f737">llvm::DwarfDebug::emitDebugLocValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a38c76eebc11caaa9225a4bfe146585a6">anonymous{LiveDebugVariables.cpp}::UserValue::emitDebugValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1886741049357a9b7cea7f8e8784a818">emitDefineCFAWithFP</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ace1de8acc8ac15962f04832273df87b1">llvm::SIFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acfee0aff6a62996ec1dbee56ef35ad88">llvm::AArch64TargetLowering::EmitGetSMESaveSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ab69231adafff5e2e89dfae5a21ba246b">emitIndirectDst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a071d8b84e530f1a6e725aea09fdc6407">emitIndirectSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a44ddc08d3e0ee02a2a8fb36fb4c8ac18">llvm::MachineRegisterInfo::EmitLiveInCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a476adf24d3374520fb31b2785f331d58">emitLoadScalarOpsFromVGPRLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a143e4c2358a1f5d46268f20f0fc52ba7">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitPtrauthTailCallHardening</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab0a615cb68b545ea3a9c88243a0ab4d9">emitVFROUND_NOEXCEPT_MASK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a1a011d7a55ad214720e5e6765df6cf9d">estimateRSStackSizeLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#a7c45383cd53ee8ccfeceafc1daed18d3">llvm::MipsFrameLowering::estimateStackSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d6c4616e2c2cc90d58377868eda6102">llvm::examineCFlagsUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd734184546746d0ab64985a91368a14">llvm::execMayBeModifiedBeforeAnyUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a20c762703f9faa4263464684aae1ad">llvm::execMayBeModifiedBeforeUse</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a0ea5ffee956540dce97bf5d067051c6b">llvm::M68kInstrInfo::ExpandMOVSZX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a6388048852214c02aa209e16f10b588a">llvm::M68kInstrInfo::ExpandMOVX_RR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#acf2585460bbea1e2bac210c9588d4bc4">expandNOVLXLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a44f31fb5ea31b5062b22b05cb8fddee4">expandNOVLXStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abe2c3303ec55393902e579d316051289">llvm::ARMBaseInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a404db50d68f1ca8d28396b5e2deb061d">llvm::VEInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a9dec32763bff61fb024d352592596f99">expandSMEPPRToZPRSpillPseudos</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ab8ebdf9a381ab517c0225f7f0719cf45">expandSpillPPRToZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ab69e2cd15cb4ac3f0262a15fdd65befa">expandXorFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a274a99ee4eac8fbc5e112f80cd84c71e">llvm::PPCInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa5ee374b5dd8bd37ca7876c4bfb24bbf">llvm::SITargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0f0065098f13d0b2ef0e39f9d2e1ecdd">FindAllMemoryUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a498962c0029b14cf3cc8fb08c5e20ab2">FindAllMemoryUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a57a867565747e5ed15e3f6e417857a1b">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findAvailBackwardCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#afa3ae93d47c5dcf2858522c9868301ca">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findAvailCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a079add9cf3b7069c79b91a3d8c7c28a3">llvm::findCMPToFoldIntoCBZ</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a261597f929a2b892211cfb9f9128ff2c">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findCopyDefViaUnit</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a07296c78a384480d58288c9779ce0bb4">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findCopyForUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kframelowering-cpp/#ae82cb5b8bd04147ce1ebe063f447c718">findDeadCallerSavedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#ae9089253a8c971c8429d201735c81ed6">findHoistingInsertPosAndDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a8552801cb962041dbea8cc767b82e850">findIncDecAfter</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#adc8ca4d1d7106281e788558813399a48">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findLastSeenDefInCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a3ebccb491a3d10cc3ca2acce4ca97784">anonymous{MachineCopyPropagation.cpp}::CopyTracker::findLastSeenUseInCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a8b1a8fc118e74550d4d11d8740ae10eb">findNextInsertLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a13ac240bf32d04a19ef44ba47f40407c">findRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afc1df0cb1a8c3103a4266def94c3a670">llvm::MachineInstr::findRegisterDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aedaafad0e3bea3243199613910e2a7ce">llvm::MachineInstr::findRegisterDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab692b90c6e0e9b450f407896cbbe4b02">llvm::MachineInstr::findRegisterUseOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a934c36cbb52619d7d75dfc0766e2b946">llvm::MachineInstr::findRegisterUseOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6f42d93281a5cbf5360f836c09166c06">llvm::MachineInstr::findRegisterUseOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a4a8c56807dfa1a49f37218084fb6c044">findRenameRegForSameLdStRegPair</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8b4bcdae4a907d7a62317ed35092d5bb">llvm::ARMTargetLowering::findRepresentativeClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ac1cbaebc2a18476b73105d6916a56664">llvm::TargetLoweringBase::findRepresentativeClass</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a08569892769aa5e49c2bf954082e9be5">llvm::X86TargetLowering::findRepresentativeClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a8705d5d3c895b6ddc6502220cbe3a965">findScratchNonCalleeSaveRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a989e26280ba069ba20dd83144c3bd31a">findSurvivorBackwards</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ac9883c9ec5baeee39d4215b9af8e0a70">findUseBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ab457e04adca93e5cb81989a2414b1a49">findUseBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvevptblockpass-cpp/#ab65fd688ebdc8951019a8d796ebcdae5">findVCMPToFoldIntoVPST</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetregisterinfo-cpp/#a9328574a2c0f8c6e1b16e0212a7d082c">firstCommonClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#aae1f40fb1287aaa0c9bab009ba9802b3">forAllMIsUntilDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#aab2ae433d483c154d92c727cf7282996">foreachUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a4d52ee98b63ac121fc09f1a5b04358ed">llvm::AArch64InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a7ea0602dc926bed4a92bc63ae99e7cc9">llvm::TargetInstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a864dfd605ab4c40b895d035a165a873b">llvm::MachineBasicBlock::getBeginClobberMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#af6bfa18127f16dd84301143202b34ee1">getBundledDefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a2a0d637eafda3140c5ba8f8c17ba25d9">getBundledUseMI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a647fbf2c5d5bb2fe4f4b5b9af7e0ab00">llvm::TargetFrameLowering::getCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetregisterinfo-cpp/#ac2edf0373e31245fe6691d49c4274f2e">getCommonMinimalPhysRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a01bc1ea0c681b4b2c171cc164805cf5a">getCopyRegClasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a596b52704a2d5f9e2dfff04400eef99f">getCorrespondingDRegAndLane</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a75eb4d99ebf26777f16034567505166b">GetCostForDef</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aff2173f1b09ff7e5b1458b9441bcf10d">llvm::PPCInstrInfo::getDefMIPostRA</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#aa25d0e2dbd3fc56009ef5f753a131a71">anonymous{X86DomainReassignment.cpp}::getDomain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a6d17b1c87fb8acd3da00cdb7f2c86117">GetDSubRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp/#a5c1040e7ce3199cf1f9adfa1e7d7ad25">getDwarfRegNum</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#af80cc22ae7f226a8c819be6bf9e731d4">llvm::MachineBasicBlock::getEndClobberMask</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0df98b068b652d32c3529381db723b9c">llvm::PPCInstrInfo::getFMAPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a019faf4f933d37d46d1fb3e7a37dccd5">getImplicitSPRUseForDPRUse</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a3f4bf9736903f31820c978bdb1b6810f">llvm::AArch64RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#a513e6961f1f77e1fb018daaad0b43157">llvm::X86RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#af196b990f6f506c44a4512bad4a36cef">getInstReadLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo/#a9a34245bb11e89a64a45063a8fc9e201">llvm::RISCVRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#ab84d39303f3dab27a9cf03cd488b23c6">llvm::X86RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a161f481971cacf2cf192725cf68390f6">llvm::AVRRegisterInfo::getLargestLegalSuperClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a8c086c133d633e899103bcc88ec14442">getLivePhysRegsUpTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupreloadkernargprolog-cpp/#a5ca3057bcaa1346422ec67d4608b22eb">getLoadParameters</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-m68kinstrinfo-cpp-/#ae31e97d01deb72b48da63760444278f8">anonymous{M68kInstrInfo.cpp}::getLoadRegOpcode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-m68kinstrinfo-cpp-/#adcc3a3676a78defc36c549712aaf2540">anonymous{M68kInstrInfo.cpp}::getLoadStoreRegOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a79d70fa60cedff640ded089e56149d24">getMaskForArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#a714ccddaeac7aa56e09e26f2532064ed">getMax32BitSubRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonframelowering-cpp/#abc325a2174e8b3649c8867e57f66f3b5">getMaxCalleeSavedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a512855a97cf9032c007ca232000a81ba">llvm::AArch64InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a515e8a223dcc58a4e478f70ec88d9520">llvm::HexagonInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ad7b408f8f589425b7ba7eb3e3be6e818">llvm::LanaiInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8d30b811118077ff2c35bb08613af26f">llvm::PPCInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa04c64c287d0b42c8a1714011a943e3d">llvm::RISCVInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ad562f15f35ef21a4965d1b9f522a360c">llvm::TargetInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a4870646ffc5b5a7d4425edd55d6f93de">llvm::X86InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#afbbc2492f83b9a1b2b2b850283240272">llvm::TargetInstrInfo::getMemOperandWithOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetregisterinfo-cpp/#a3d384230ab441fc0da0f899122f07b4e">getMinimalPhysRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5f1318c87bc0007368e815c55c31d06b">llvm::RegisterBankInfo::getMinimalPhysRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#a4354515685ca31a2583e246f54977aee">llvm::MipsFunctionInfo::getMoveF64ViaSpillFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#ae1b40d8cfb58f282fa1680fdff5ef001">getNumAllocatableRegsForConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcndppcombine-cpp/#a86f854f13c9073d83338c10bfc5122c3">getOperandSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a93bebb4498805f11e17d91d7cde35511">llvm::MipsTargetLowering::getOpndList</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a99791c9647b053fc872d35a3f0faafd7">llvm::ARMBaseInstrInfo::getOutliningCandidateInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abffddc65a79eca0830b7dd232ff74dc5">llvm::ARMBaseInstrInfo::getOutliningTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a80ada2af2a2f2c3f640c0ad4192f53cb">llvm::RISCVInstrInfo::getOutliningTypeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a51539193cc8ad7ae2884993bbb57ddea">llvm::ARMBaseInstrInfo::getPartialRegUpdateClearance</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a14308e147ea57526f7fd1198ab551a9a">llvm::TargetInstrInfo::getPartialRegUpdateClearance</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#af94193776566ea8e90fc662cb038b0a1">llvm::X86InstrInfo::getPartialRegUpdateClearance</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#aba7fb21a2d5ab45963fa25629ad883aa">anonymous{MachineCopyPropagation.cpp}::CopyTracker::getPreservedRegUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa42c3828ac3f788f2ef3ff6fa46e4926">llvm::MachineFrameInfo::getPristineRegs</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a93a0a8ab06630d5406ef007e182bc05f">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a96b1c6181f78fcdb7aba634c687d20a7">llvm::RegisterBankInfo::getRegBankFromConstraints</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac18c5827c119a73ea6f07b4ef4649654">llvm::SIInstrInfo::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af81ceec76ff4ca95f29b037c28a54ba7">llvm::TargetInstrInfo::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a1829580bbe3650b4649ba6094604e0fb">llvm::X86InstrInfo::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af551bfe7ee8756cbe50de3bb97478723">llvm::MachineInstr::getRegClassConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a88f8cb24fba67649c1f32531d0f6ab90">llvm::MachineInstr::getRegClassConstraintEffect</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3b3fa67a3a5da00dd6bc096cfbacd3a4">llvm::MachineInstr::getRegClassConstraintEffectForVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a1cb20ca947002d194a0220677583167f">getRegClassesForCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a503e72a2d289df6f71b2ccdc58a18907">llvm::SITargetLowering::getRegClassFor</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ae36dfcf0bacb4009b75fb2323aba6869">llvm::ARMTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a27c6ef6dacc842737370d22c1f7ed946">llvm::AVRTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#aeb5e73aa86ef5c3747a4fa348274ad20">llvm::BPFTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ad1de76d884688c0714045295511132af">llvm::HexagonTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#afd1e3e4aa43dd55aaf713d32f108a3de">llvm::M68kTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a17109faa1b23afe706771effb725d9fb">llvm::MSP430TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ab18a78c277667a151b0cb707c7e80a02">llvm::NVPTXTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#add923d3128dce4cad95ce5ad642f6946">llvm::PPCTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7ade77bdee8e8fe0f6694d0ef8fda0ad">llvm::RISCVTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a299e5debf3d108b71fc6642ecd31e5e7">llvm::SparcTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ae9f8d60c452f2f26ca84f0bde2b530ad">llvm::SPIRVTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a8b056a961f0931f4e64f0bddf07ba784">llvm::SystemZTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#af09507c47dcb4cdb2a13064aaa6d5243">llvm::TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a04b839fdbef86703e2716838602c37aa">llvm::VETargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7a7237cd5cb35f9159b32a96f4b14541">llvm::X86TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ae09e10149c0fdd82a96ee9252d48354f">llvm::XtensaTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#a690f39ef8620b9d57557d0cc194b3098">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::getRegInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af4f13984fe50ba9df4f0345922c76639">llvm::SparcTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a17b4520610e0151c3ea791c6adf27d07">getRegisterName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a43762e6a22fd0e7b98b8115946fc87b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa2b5a0a0f6bf1b5480337a01257df8b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/fixupstatepointcallersaved-cpp/#abdbbbd165ab5fb16364c6f6b2a920664">getRegisterSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a7fcb99675ac619b90ab5d7c2eec0a482">getRegOpRC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#ad12ad3638ef83e9281c5cab4a99f60b0">getRegTy</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a9b134d4df9353786cf749d861b77b792">llvm::WebAssemblyAsmPrinter::getRegType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a2d536cb0afee47ed6a6fcbef2c85cfe3">getRVVBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a3b564776c915bd764fdcaa5e36525953">llvm::SIMachineFunctionInfo::getScavengeFI</a>, <a href="#a760cd0801dd2ecf5d8951c3c1db40ca8">getSingleLiveInSuccBB</a>, <a href="#acf8fc7aec1c211309bcfdadf5471efc5">getSingleLiveInSuccBB</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a5f8650d325125270b7698fdb6e3e7039">anonymous{MachineCopyPropagation.cpp}::CopyTracker::getSrcUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a5cf58df95b00905950bdfee515cd5e9d">llvm::TargetInstrInfo::getStackSlotRange</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-m68kinstrinfo-cpp-/#a3da13d3718b50df8b877973da43cb75a">anonymous{M68kInstrInfo.cpp}::getStoreRegOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a902b09cfe1ad72267169b4f08909f680">getSubRegForClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a8094520fe3fe9f3967fe72b7266a2f68">getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a4159fd0062dd97fe920f738c776a7356">llvm::TargetInstrInfo::getUndefRegClearance</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad526a98b9842792511d37f5499693349">llvm::X86InstrInfo::getUndefRegClearance</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a38ebe847e991176c228c75849c200990">getVectorRegSpillRestoreOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a651d110c1dac1aa8d4ba6cf535bfa6a0">getVectorRegSpillSaveOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a233876a8dfa07f6566cbaa28f64d6e6f">getVGPRSpillLaneOrTempRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/pertargetmiparsingstate/#a0352dc3d26218453c96382ceb3eeaa5f">llvm::PerTargetMIParsingState::getVRegFlagValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a54a74ca0c82840e37a9a92890385eee6">llvm::GIMatchTableExecutor::GIMatchTableExecutor</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af5822132e0c77a924c92cd4bbedf9c97">llvm::LoongArchFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#a454a61d9ff61d6d4402ce57c16f40fc3">llvm::MipsFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a38fe3f67034841400e749f75768348a2">llvm::RISCVFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a4762e4f2c447b020abc88c3bd501c407">llvm::VEFrameLowering::hasBP</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#acc03bc4b3fe668894a31738a4f03269b">llvm::MipsFrameLowering::hasFPImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmichecking-cpp-/#ad2a3ca606c834775be562cd5019370c1">anonymous{BPFMIChecking.cpp}::hasLiveDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armhazardrecognizer-cpp/#af4b92b87cdc1663f71632274fefb42c3">hasRAWHazard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#aa2eaa868ed1dfcc89946d7b7fc4d2149">hasWriteToReadDep</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressure/#a8a4c16c737c90f7de638e1ee724d4785">llvm::GCNRegPressure::inc</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregset/#a550d4a10f48068094cb9e4dc85a7ac5a">llvm::LiveRegSet::init</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64redundantcopyelimination-cpp/#af884214031cdb18344d85b5d4c422fef">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandpostrapseudos-cpp/#a406c74892c483b9ba9532bc070ceda6f">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsplitconst32andconst64-cpp/#a79661f41f9eef555922452344ae54280">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsplitdouble-cpp/#ab9a3a1f23e02f40120823d7ad6ee8531">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp/#a4fb27fac71c41b0d9873024cbbd12bc6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp/#a282ab875b746f59b35ee8aa9b0b0b837">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#ae4785d013b2a0f60334309544abc43fe">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#ad49d5358eb2049a14a99665fc936acf9">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp/#afdf0d4c2af63e1b86738790e457a3b49">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a948a039c4649894649702b931539b368">initLiveUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a8b7067629b6a083fe938e1e73d0b505b">llvm::VEInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a23393317cdaeed97903d191dcc6c84f8">llvm::AArch64TargetLowering::insertCopiesSplitCSR</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1dfc6019f3ac9b3b50bfc020a60baf7c">llvm::SITargetLowering::insertCopiesSplitCSR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a04bc45ddbc56deb8b54dacaeea86df8f">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a61e27cf21f938d341d13395bb4e17493">insertCSRSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#ac9ed3ecc7dfa1e9f4c9c2fef92aaccb2">insertCSRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a29c37970b1c079bbbc4515cb00e112fe">llvm::X86InstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/copypropagation/#ab12951430f2984b5f0b26e265ccb8ac7">llvm::rdf::CopyPropagation::interpretAsCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a88d50bb943ed6d9b7bf0a34367d018af">interpretValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#abbf02514d481b5292b34f111865e4605">anonymous{MachineCopyPropagation.cpp}::CopyTracker::invalidateRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa558d4d2ff55bd212df17400c6715343">invalidateRegisterPairing</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a6e70c6eb89daed9d5ad60fcd4e0944be">invalidateWindowsRegisterPairing</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp/#a80a3dc6dc764547a5cd15ad955c3a50f">isACalleeSavedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a58db20676cb0ff354eca34b86f0c3ab1">isAGPRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a4a6fb3ac38359791e56965c6b5329e69">isAnyArgRegReserved</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#a19df3fcdde4ba426474e5557736a4358">llvm::outliner::Candidate::isAnyUnavailableAcrossOrOutOfSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a71ca38441063cb10ea3fb9d1ed7c8d25">llvm::X86RegisterInfo::isArgumentRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#aed79decf9ab2c9663d2a2170b0ef7a4f">llvm::outliner::Candidate::isAvailableAcrossAndOutOfSeq</a>, <a href="/web-llvm/docs/api/structs/llvm/outliner/candidate/#aca57cfbe9483e432047e4df8f054e98f">llvm::outliner::Candidate::isAvailableInsideSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecse-cpp/#a04077ca0440dd582f6d2962ab30dd0bd">isCallerPreservedOrConstPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af28ada2e1e13faab18ee3746c01e684c">llvm::AArch64InstrInfo::isCandidateToMergeOrPair</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#abe36a37a2974f73af12228bccbaef0b4">llvm::MachineRegisterInfo::isConstantPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#acec254d4fbb18621ee4d54f867af85f9">isConvertibleToVMV_V_V</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#acfdb7e9be44e0d08b3b97b9177b8239e">isCopyFeedingInvariantStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#adeb4fa20d3ea1515e0a668fccec57f59">IsCopyFromSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp/#adecd11022a5f472b5ad0682bd79f479a">isCrossCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a186cd7587b668062d1cbf36fd03c24da">llvm::isCycleInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#aa0224ce6f8dd63f7674a2a1f032e23ae">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a93f8e5dacbcd949d688c3af5f491468d">isEFLAGSLive</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a1c1ba0852c28df8598b5a0d2f0abb3aa">llvm::AMDGPUCallLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9330a86a613cf892ee5c7f515713f200">llvm::SITargetLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#aef241765e05d84992ebe4133862b899d">isFIPlusImmOrVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ae7dd37fd8fba5e8dd416dd428e6f550c">llvm::X86RegisterInfo::isFixedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#a63e534b2d2892aadaa791d48b0397c74">isFPBPAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a2c49fb1fb9fd56187b3a506c56c726f2">llvm::DwarfExpression::isFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7f2dc64214551418f486026ffc95fa4">llvm::MachineOperand::isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a3e874f5073fd59211348a2ea23e9d0ce">llvm::GCNTTIImpl::isInlineAsmSourceOfDivergence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#afe78f37f6711d1eba5a7066809cae1b6">isInvariantStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#aa5a8087086656299167f931f805778bb">isLdStSafeToCluster</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a59078941da3e0dedf257050df111a8d1">llvm::TargetLoweringBase::isLegalRC</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloop/#ac3ba70811fe6842e3354120afc36c8d5">llvm::MachineLoop::isLoopInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#a8edbf608fa301aa44ce994dd5ea0a874">isLRAvailable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#aeb69b6cf24b76aca006ad1237ff9565c">anonymous{X86DomainReassignment.cpp}::isMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#adc7c182e30e29f733866253f399e5839">isMIModifiesReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ab0c063f61ab51976b76b1b7faa696d31">isMIReadsReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#abed37e9eeb67324751569d54ac13c0ef">isNonFoldablePartialRegisterLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp/#aa3f54ba0f4f9c1bff1b6e218a98256d3">isNopCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb26c86c4abcccbe5376b3f7e5e8af69">llvm::isNZCVTouchedInInstructionRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad1125e2fe4751891ae3e54013588b5bf">llvm::isOfRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a86026627b644e50527898aad0747b3e5">IsOperandAMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af2a209ffefa8ca1df76b99fe3c2e2cc4">llvm::MachineRegisterInfo::isPhysRegModified</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#afd23983bb9fb4af65e27b56cc506edbc">llvm::MachineRegisterInfo::isPhysRegUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a3790c110e8f9d3ffde8dfde05bd53edb">llvm::ARMBaseInstrInfo::isProfitableToIfCvt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp/#a33f3613fb6558bae2f0d2bdd87e18dfa">isRegOtherThanSPAndFP</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ada7de8e2cf4949a58445f955d4d98caa">llvm::MachineRegisterInfo::isReservedRegUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a1c1669c081e93349baa5bcf3ca5aaae4">IsSafeAndProfitableToMove</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ad071e937f4986e51fd3fd54b10888894">llvm::TargetInstrInfo::isSchedulingBoundary</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9226f8a6386f03bffa9a98d07b2ed582">llvm::SITargetLowering::isSDNodeSourceOfDivergence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0f8a5563a0ea48d3d74b71e49c179e7e">llvm::AMDGPU::isSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a8e3874f05140c734fbc0e9f0ac91d85d">isSGPRToVGPRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#adbb4dcc227f28ef32563170ce820d498">isSubRegOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#a6dd59c68c09f54df98dfea454a222fe1">isSVERegOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a686006fb295775c77b3d569f6d028fde">isUnsafeToMoveAcross</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a53372200df2c3350a7b61c797e578be7">llvm::HexagonInstrInfo::isValidOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#aa524a697f0c6f94cef4d7a1f48f856e9">isValidRegDefOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#a0ca5780a94eb690d0ccf6cdda9c16df9">isValidRegUseOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a445e6b5f778e8bc22f6c7bdfcb73ac31">isVCmpXWritesExec</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac53294939ccc54481097815c813545b5">anonymous{RISCVInsertVSETVLI.cpp}::isVectorCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a7c3e37fe69c334ec977a67eabc0da4ca">isVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp/#a9f76c7673322a26dbad00fca14f23e3d">isVRegCompatibleReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a81547ddac1cc7ddad9428925e49ab42b">llvm::MachineInstr::killsRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a696bdea6147585aeab4c74925c3587c3">loadM0FromVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#aa31003f66af0241b32a8572e8b33d7c4">llvm::Mips16InstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a47e0860c4ff5c58e015e8485de105496">llvm::MipsInstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#abf65c6f3a770509d24a75efbbe785a67">llvm::MipsSEInstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ad96e959009cbe91d2814bcdfe4fcd51c">llvm::ARCInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#aa3221ba2a1b01836c1f02c48d2bd2c4e">llvm::AVRInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#a3ab811022aee0c0ea9656dd6ccefdd99">llvm::BPFInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a2c4630e6b74de7b52933845fe4f48f01">llvm::CSKYInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad3b3220844622daec97aeb14080a66e4">llvm::HexagonInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#afa83048a6e09247f7f6310ffc0681909">llvm::LoongArchInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a239b76db482ddf927605d2df0345f32c">llvm::M68kInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#adcb9baaf8dfd9c146ccbe47368bc9864">llvm::MipsInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a3a04d16772e68de8d911d305070f0e0b">llvm::MSP430InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0da975f6f39f57c7baf3ec1fefadc566">llvm::PPCInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abe4a49e8ceb6213fe44eb0ebc9869eb1">llvm::SIInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a38be8eeeb68d45e0a914cd8f3237ce83">llvm::SparcInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a28d09c19ed8aae1da569fd4d52e2ae30">llvm::SystemZInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a9b1710394413e85110e485ec260c6a91">llvm::TargetInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a6d4af3948133ad97770947f7d1242561">llvm::VEInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a00e20eba7b1f0d10d7094c146a00a705">llvm::X86InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a541a292af69ae4be75a66b7994e89abb">llvm::XCoreInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a4803afec16045eda40159c13dca06afa">llvm::XtensaInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a4f5aa6feffe52b80166f0d252cf354cb">llvm::PPCInstrInfo::loadRegFromStackSlotNoUpd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab1601d92ffdfcf6fe48b40b6a7cf8d59">loadRegPairFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#a24fbb3a26fc0fcefed74db2072222bb5">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::lookThroughCRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/localstackslotallocation-cpp/#a1cab3409c3d6f4b4b77dfbb3bd3ac80e">lookupCandidateBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a68b7b9c491045c788173e83be1ba5d2b">llvm::TargetInstrInfo::lowerCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a38572a53736b568d95a5adc23bcd67f0">llvm::PPCRegisterInfo::lowerCRBitSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#acf79ac9988d00b2ded8a68907a1569e4">llvm::AMDGPUCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a4119a7f5d262af0d89332b5c2d30abbc">llvm::AMDGPUCallLowering::lowerFormalArgumentsKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4ce28f633cfe7a89369965cd9792e8fb">llvm::SITargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a293e39e43b6f68064cdfd37061c84128">llvm::RISCVRegisterInfo::lowerVRELOAD</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a7238a4dd92fc1bb51c004c49c2b22263">llvm::RISCVRegisterInfo::lowerVSPILL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a7809852647bc7e8ceed1f287b2d03125">lowerWaveReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterbankinfo/#a18f5a1209aa4d2a3cfa5892ad5cf4c3d">llvm::M68kRegisterBankInfo::M68kRegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/genericuniformityanalysisimpl/#a7357d4d98f9741b2ede9180f437f7623">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDefsDivergent</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a6a330b866759100cb33d2cb9e98a1a54">anonymous{MachineCopyPropagation.cpp}::CopyTracker::markRegsUnavailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsreginforecord/#acfc18bd37af88f32dd6f57630a30604c">llvm::MipsRegInfoRecord::MipsRegInfoRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a273294b63d70a86b69742c1f4256e098">llvm::MipsRegisterBankInfo::MipsRegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a66e91c5407ade0326e5dbd87e986e648">llvm::MachineInstr::modifiesRegister</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvtargetmachine-cpp-/#a19d9dd0cfe6b9d17e4cb92911dff0e1d">anonymous{RISCVTargetMachine.cpp}::onlyAllocateRVVReg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a6d828a500b726dc52f7addecd99e841b">anonymous{AMDGPUTargetMachine.cpp}::onlyAllocateSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp/#a9c40319b4934622623e10864866f6ecf">onlyAllocateTileRegisters</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#a85c037340dcf7250f2fa6d36846b9ee3">anonymous{AMDGPUTargetMachine.cpp}::onlyAllocateVGPRs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgputargetmachine-cpp-/#af4f4e68d5e8a0046458775daea99506e">anonymous{AMDGPUTargetMachine.cpp}::onlyAllocateWWMRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/structs/anonymous-smepeepholeopt-cpp-/smepeepholeopt/#a5c603866e25916faea1af9c83ee89286">anonymous{SMEPeepholeOpt.cpp}::SMEPeepholeOpt::optimizeStartStopPairs</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7954356a1d4fe56e90cf50b2820cd502">anonymous{MIParser.cpp}::MIParser::parseCFIRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a1c5e8b6aef41aead06d61ff0530ed9c2">llvm::TargetLowering::ParseConstraints</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a6e4e4f98e1264c57604c033122d6fceb">anonymous{MIParser.cpp}::MIParser::parseRegisterClassOrBank</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a5ec1b0ffb0fbbbc5d74381b0b1d38ae1">patchMatchingInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/fixupstatepointcallersaved-cpp/#a09e820de0ed1c5d75b6408fb04cda11c">performCopyPropagation</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#a85b64ed3b63991007729db74f0721fe0">llvm::PPCRegisterBankInfo::PPCRegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a45aa2763f52ee7bb3f41393d1d4ba079">llvm::TargetInstrInfo::preservesZeroValueInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#af4af3417d2f18e72f3b26416f7c4997c">llvm::X86InstrInfo::preservesZeroValueInReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/machineconstpropagator/cellmap/#aa246bf2643299671d37edd6d77277f70">anonymous{HexagonConstPropagation.cpp}::MachineConstPropagator::CellMap::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstpropagation-cpp-/registersubreg/#abd4439229542e32709e4d80db8449df8">anonymous{HexagonConstPropagation.cpp}::RegisterSubReg::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonhardwareloops-cpp-/countvalue/#a8e2ee3bf4839fcec449ee3ef01bc914d">anonymous{HexagonHardwareLoops.cpp}::CountValue::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/userlabel/#afa3befc37137ca1a55bd8a2e88ff00e0">anonymous{LiveDebugVariables.cpp}::UserLabel::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a7cc6bb18e07abb863469007d3e3be069">anonymous{LiveDebugVariables.cpp}::UserValue::print</a>, <a href="/web-llvm/docs/api/structs/llvm/argdescriptor/#a96a608070d394c15c847e9a52e250c1c">llvm::ArgDescriptor::print</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/#ac71126c0da12305fa8cf78f7e1d4d1a2">llvm::LiveIntervalUnion::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5a4302f4590a281bb84e08b30c80591c">llvm::MachineBasicBlock::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad9c9c8915579c517eff56e638c1a643c">llvm::MachineFunction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aedeaf186a99c875b4196318a4083ff77">llvm::MachineOperand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3f9d3159041bfbc33655256282b6afda">llvm::MachineOperand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>, <a href="/web-llvm/docs/api/classes/llvm/miprinter/#a3217d1ff332f5c57cf87c02208afb5cc">llvm::MIPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/miprinter/#ac9a4f7f4a86744121b96bfb651c60567">llvm::MIPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/miprinter/#a0dec8c3931e753255d1e88ab0216e629">llvm::MIPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/physicalregisterusageinfo/#aaa2c354cf7353f24dac62741d54bc98b">llvm::PhysicalRegisterUsageInfo::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af33634fb6c71e0e2e25241c94baf8c26">llvm::print</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#a2f200a149ac3e8669bb616c3b1049ecf">llvm::RegisterBank::print</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a35dd3699ac135501fca0bf3c7087f311">llvm::RegisterBankInfo::OperandsMapper::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a1a6d908f749f40987c9bd895ef5c7849">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6cff8e6e40904c8170d57f5307f73c20">llvm::ARMAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#abb1c33c814741adb78a9ff7f10ff3552">llvm::AVRAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a81e38a8f99bc74ae4acb4d135d1b7278">llvm::HexagonAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a67bc6e371d9dfd804cecd64d83fd073c">printCFIRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a98b3f72dd143c6cf275022dcef2dc161">printCustomRegMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocpbqp-cpp/#a1166be335294ec092a70278682db3950">PrintNodeInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84f1f18b0f13167b8e9c455b9524b58d">llvm::printRegClassOrBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a778c8ea8e87db3255c4590a8a4a09924">printRegClassOrBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#ae07cd49d1962f418e0e2f363b0217219">printRegFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a5861c278d9a814fd24723840f9d91cbf">printRegMIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a34302b557354b8a09796c30b9f7408ab">llvm::printRegUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a2f9c9ef300cdd17a112e9760aaf73e82">llvm::MipsAsmPrinter::printSavedRegsBitmask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2c59687e1086bf24ffa307eaee13c3d3">llvm::MachineOperand::printSubRegIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a788c5905de970028eb0efa2266bd10bf">llvm::printVRegOrUnit</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a24b80d6d36821f80675874283190f291">llvm::SIFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#ad1c7f63bd41f376ebc594e3f8440d1ad">llvm::XCoreFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ae9f1f8c1e84b90f052a26ffea62a381f">llvm::SIFrameLowering::processFunctionBeforeFrameIndicesReplaced</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a62a1e2af50ab6132cd2d8d168835ef57">llvm::PPCInstrInfo::promoteInstr32To64ForElimEXTSW</a>, <a href="/web-llvm/docs/api/classes/llvm/psetiterator/#a592bf3df803ffac98c7328a523769bac">llvm::PSetIterator::PSetIterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#a6e634ebc0d21fdf961ec8451940caf20">readsLaneSubset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2380c209ae5339835b5e6ea6d5c197ad">llvm::MachineInstr::readsRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa323e6c0586d706279d7e764fc18d1ba">llvm::recomputeLivenessFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a2786870c4807261593ac11e734db2f76">llvm::MachineRegisterInfo::recomputeRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeredundantdebugvalues-cpp/#a0cb9f41d03e7efefe10150f7941cdd16">reduceDbgValsForwardScan</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a967540f5e5799b56c6fbcee378d110eb">llvm::LiveInterval::refineSubRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e2a565237b7880c7a6834517a5287b0">llvm::registerDefinedBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8e705934ca4178520c75d7ed1218cfc5">llvm::MachineInstr::registerDefIsDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#a0d7ae72cbefa48b3c446bbe0a0347010">regMaskFromTemplate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#ac18edb1d91090c7614b8fcd4dc45d532">regToString</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aadcfe8906a95ad57f3f7a7d433f47204">llvm::TargetInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a220e5ab986bbeae53290cfb49f913fed">llvm::X86InstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a3bbf276657ebe5de723f93bc95498b6f">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::removeRedundantLIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcregisterinfo-cpp/#ac30c350ebdcaa96e93852ea6e7ace1c3">replaceFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ad6408dc62ff8fa8de6c9c6daa57b897f">llvm::PPCInstrInfo::replaceInstrOperandWithImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af16c39ee36e4633f821b6820f8bd52ef">llvm::MachineRegisterInfo::replaceRegWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2b74085541381aa878e3cbad0cb7b71">llvm::reportMismatch</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#aa21fe05557eb564cf547a20ccf43d9f5">llvm::R600InstrInfo::reserveIndirectRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a049dfdf656884a9d492cb2bc7a664dbf">reservePrivateMemoryRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ab490792bb2387856aeb83267a1bd55d2">llvm::MachineRegisterInfo::reserveReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a5c22366d9b2f68fba8285148c794a74d">llvm::AArch64FrameLowering::resetCFIToInitialState</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#ac582a8ad2c8ee5589ed9251e0d86833a">resetRegMaskBit</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a058c2c2f387b28b806bb94abc34aaab7">llvm::ARCFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a03aa2120f2d9d154313c31faec3d97d2">llvm::ARMFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a8b418b49786b4eb1c06b0e407e346c01">llvm::AVRFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a7c89ea904b5a33a2c24357c301e4ea21">llvm::CSKYFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#afe209d6441f38c76735d589d88f5145d">llvm::HexagonFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#ad42e9514f06b847f7c06af29d7b42184">llvm::Mips16FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aae5bad356a0c0583ebad92fbe899230c">llvm::PPCFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a15d74c0d6159ac707f99c91219d0c6a5">llvm::SystemZELFFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a3d043cad28262fefa366ecc64c9591f1">llvm::SystemZXPLINKFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#af4e91c7e613771679b2f0e71f03b172d">llvm::TargetFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#adca65a5406a289a41bd58993e28bb3aa">llvm::Thumb1FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a88fe1478dc92f6e9310051316749f031">llvm::XCoreFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aa3921084f5ef700564dcb83801124551">anonymous{LiveDebugVariables.cpp}::UserValue::rewriteLocations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a190dd3c890042807e4008b5bdd04927a">llvm::RISCVTargetLowering::RISCVTargetLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#a20589df6cd2c2e12e77a1741a0e4223e">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixvgprcopies-cpp-/sifixvgprcopies/#a09c2c01c550356b7377cdd8a2cd619a4">anonymous{SIFixVGPRCopies.cpp}::SIFixVGPRCopies::run</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/copypropagation/#ab5cc393f3a921f0a6fe0505561a80e23">llvm::rdf::CopyPropagation::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfixcortexa57aes1742098pass-cpp-/armfixcortexa57aes1742098/#a43d2faff17080847be1128de33a8fe54">anonymous{ARMFixCortexA57AES1742098Pass.cpp}::ARMFixCortexA57AES1742098::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreralongbranchreg-cpp-/gcnpreralongbranchreg/#a8b5ef68b98f901c64096eb633984c661">anonymous{GCNPreRALongBranchReg.cpp}::GCNPreRALongBranchReg::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonloadwidening/#a9e42da81e4f2dc0432ee7d615420d07f">anonymous{HexagonLoadStoreWidening.cpp}::HexagonLoadWidening::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloadstorewidening-cpp-/hexagonstorewidening/#a70e2faddefd0484ebf9d2dfa47007678">anonymous{HexagonLoadStoreWidening.cpp}::HexagonStoreWidening::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/postramachinesinking/#a1f860254ea2183299eecbd087f61d405">anonymous{MachineSink.cpp}::PostRAMachineSinking::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxprologepilogpass-cpp-/nvptxprologepilogpass/#a58c45f00a8ce8f9282ad2bbcfbd08cde">anonymous{NVPTXPrologEpilogPass.cpp}::NVPTXPrologEpilogPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-prologepiloginserter-cpp-/pei/#a8677f120f60c9ac2cdc36759298a94b2">anonymous{PrologEpilogInserter.cpp}::PEI::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600expandspecialinstrs-cpp-/r600expandspecialinstrspass/#a38dc359e925f1a8fd75ba272f45b4736">anonymous{R600ExpandSpecialInstrs.cpp}::R600ExpandSpecialInstrsPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-shrinkwrap-cpp-/shrinkwrap/#a0b77b3bd867840460e8de5e83245240e">anonymous{ShrinkWrap.cpp}::ShrinkWrap::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#a014ee381e519aa7b2b38d66744faa5bb">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionrethardening-cpp-/x86loadvalueinjectionrethardeningpass/#a555db007ae6df71fb9fa02662e2c8643">anonymous{X86LoadValueInjectionRetHardening.cpp}::X86LoadValueInjectionRetHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#a207cce78de7e84e6885684960f5c4f50">RemoveLoadsIntoFakeUses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fa258f0e297563fcec4bb619d2a759">llvm::MachineFunction::salvageCopySSAImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a9029683bf2a81e8247c168501e85a8b4">scavengeFrameVirtualRegsInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a176bfede6f24b05b428c0f42f9d95390">scavengeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppcinstructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a2d3135a3679a9bf0460e25b9d03f9298">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a6182598aaa3c33b0c1e4eb1f7b1ce870">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a0d70a38e8f0622515630e7e8672df270">selectMergeValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a838cd050490773e0349589c0d78618fc">selectUnmergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a971f804e98558726a547fa8fefe28a11">llvm::FunctionLoweringInfo::set</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseframelowering-cpp/#a8058af7f16d3ab91b5a51f5102843b96">setAliasRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5b3180edf81915b106633986034d7a01">llvm::ARMBaseInstrInfo::setExecutionDomain</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2afcfcff9187a2201549d75d4e16149">llvm::MachineInstr::setPhysRegsDeadExcept</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0909a505055aae0cb9dee8e5730b3724">llvm::MIRParserImpl::setupRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a2b34b6927d7eb879485cd489ee5e8583">sgprPairNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetregisterinfo-cpp/#afe1159c2a87a23c05d974b8c14d28a1e">shareSameRegisterFile</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1101a933da1fae1b166dc36e2a384ce1">llvm::SIMachineFunctionInfo::shiftWwmVGPRsToLowestRange</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#acba682e84de176f762ddc4d774819cae">llvm::PPCInstrInfo::shouldReduceRegisterPressure</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpumacrofusion-cpp-/#af5da450a1411e5b2e09527cb36568ff1">anonymous{AMDGPUMacroFusion.cpp}::shouldScheduleAdjacent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a1c53e709679ac5205c22134f73456327">shouldUseFrameHelper</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a801175ec17220ad7c2f309838f0a50d9">llvm::yaml::SIMachineFunctionInfo::SIMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a80f6630b845109786f0840f4b15737f9">llvm::yaml::SIMachineFunctionInfo::SIMachineFunctionInfo</a>, <a href="#a316803c463af8ba2c38182332fb3c8a4">SinkingPreventsImplicitNullCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#acaca0c9ffff0d1cba0462a1daccf5f12">llvm::SITargetLowering::SITargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#ae76f197bf80407fa11be07ed0a2c682d">llvm::ARCFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a77dc4905d180a52615d00a760b111f9a">llvm::ARMFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#af676cadcef1e3d4d159420f075a083da">llvm::AVRFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#af57354b85b1bb51bd0d56651205786a9">llvm::CSKYFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#ad1df4d29452b039094c0205f4a24f5a7">llvm::HexagonFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a6d7492a7a948b4a2d3bb8fd69395503d">llvm::LoongArchFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#a2eb8fb675dfceaccbf3a2dbdfee2e9a3">llvm::Mips16FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a8eced7de6aa2268fa96f3580b9ef01bf">llvm::MipsSEFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a42ba26b731da85ec85d9f4ebb7d27e02">llvm::PPCFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a9db07f97c8d52e506e689b789b231f0c">llvm::SystemZXPLINKFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a4e3f90e73775a2603db1bc5f1cf8c1f0">llvm::TargetFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#af07ce77a4beea41a98862690cee5ec2d">llvm::Thumb1FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#acc16e0a256c156ca27db8e17d37cceab">llvm::XCoreFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#adfdb32bd422a7613ae83c10f2841abf7">spillVGPRtoAGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#afb4c3921369b6b1fef886bfa979b6d2a">storeRegPairToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a59a4a03c8f10059fe2fed96077fc311c">llvm::Mips16InstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a5d803336d21f657d44a993cb9924dae4">llvm::MipsInstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#ac808bf28cfa407acff2b367a0bb383ba">llvm::MipsSEInstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aeba4e73d60d1b4cedc120d06114c0620">llvm::AArch64InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a687fecaf502080080ba5069e6b211a65">llvm::ARCInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8a7868df2562a3b48d08d24c9db87b98">llvm::ARMBaseInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a90829bf41a9e8e4c4e4ad59eab490719">llvm::AVRInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#a41c0bd4e75d4643a8387fe6d56eca337">llvm::BPFInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a647cde93263cdcab73a72f5e459041c6">llvm::CSKYInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a9644f3506784b55b500d2f73f94d79e0">llvm::HexagonInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aed611129b85082f7e6459907b50a8cd5">llvm::LoongArchInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acc65122fa06b8871a427abbbd700b22a">llvm::M68kInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a818f9f02652c7da65c35e92677bb142a">llvm::MipsInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#ae215353a37be6d2f533a4858bd96be74">llvm::MSP430InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a1088aa0c7b8ba7ea56bd7f5c443bb6dd">llvm::PPCInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ec207a1c12adfc61c6566436e5a2cd7">llvm::SIInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#abc124725b4afa4a9d9449c6e2cfb3d73">llvm::SparcInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a5980d318f12f61018df1b80a17ce394a">llvm::SystemZInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6d3df2a0837fb3b75b9a0ac8f0923843">llvm::TargetInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a2132749e515b00c60255bdb4acfba223">llvm::VEInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aa424b646f1bed0832f4eb126081e6fe5">llvm::X86InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a915259afe54d2619524ed03c9c273c57">llvm::XCoreInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#aef5d7d851ae3869d7094741795181ae5">llvm::XtensaInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a97de15cd29255b90b2ce510e967340bf">llvm::PPCInstrInfo::storeRegToStackSlotNoUpd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9842e6805ce84262b6bbe7da2b26772c">llvm::MachineOperand::substPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a13a5b2fd837189405f1b07a6c9249d4f">llvm::MachineOperand::substVirtReg</a>, <a href="/web-llvm/docs/api/classes/llvm/superregclassiterator/#a75cd8d7ef877408dace338c8c57b67da">llvm::SuperRegClassIterator::SuperRegClassIterator</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a900f1a90fad33256f71fe326507afa43">anonymous{MachineCopyPropagation.cpp}::CopyTracker::trackCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2itblockpass-cpp/#adc8d1d32a1860d5e21f283b913ac0880">TrackDefUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#a6fc3c1b63330a00fb5f865c0b76ca058">anonymous{MachineCopyPropagation.cpp}::CopyTracker::trackSrcUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a0992d70176e7dfe68ee15af73be3f948">transferImplicitOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a7c8714527422f164b52d6daaa65850e8">tryChangeVGPRtoSGPRinCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62cf34ac18c5612524978166788b5c80">llvm::tryPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a3254ec0c900f8e69d67ae32be83e801b">tryToFindRegisterToRename</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#ab48e3dab3c79330a34264424247f0276">tryToGetTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#ac27abdb8883d8ef8d984acaea1846fd2">tryToGetTargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a768c85ec7c5044117192b9fc18395231">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#ac3419b7821dce4fc2e3a6f4a96b7dbaa">unsupportedBinOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntbrackets/#aed39bc406ed2e03670a0ed9abd45145c">anonymous{SIInsertWaitcnts.cpp}::WaitcntBrackets::updateByEvent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af5fcd8a3114504b21e5f08a08e4fa512">updateDefinedRegisters</a>, <a href="#a6c1da13a967ff01e9076c55b0b6d158c">updateLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a77dea00ee37a964ad5edf6072fb35071">UpdateOperandRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1216c0733931de570c17ed44556139bf">updateOperandRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6eb3ac91456a9880aecf25dc8e3cbaa5">updatePhysDepsDownwards</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a79107186b863ddb50f8bfdb721aa41d8">updatePhysDepsUpwards</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a9a5c05172bf1b5e36b42f412c4a176cf">UpdatePredRedefs</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#a29b158112720b57e5aa9898944c69330">llvm::RegisterBank::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#aca0f86b578b560c1ea67d71987c1df57">llvm::RegisterBankInfo::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#a09e6becd5a0cf0c041d79f2b42ccb12a">llvm::X86RegisterBankInfo::X86RegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ae81349a3eaea48847f574c5c7293d084">llvm::SIFrameLowering::~SIFrameLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a19fbb56f62d9686fea21da81ee193de5">llvm::VirtRegAuxInfo::~VirtRegAuxInfo</a>.</p>

</div>
</div>

### UseBlockFreqInfo {#ae8a57b53e1029a66423f1c8beeee72b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseBlockFreqInfo("machine-sink-bfi", cl::desc("Use block frequency info to find successors to sink"), cl::init(true), cl::Hidden)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking/#aa7678b365028630e8b51cb7b43988523">anonymous{MachineSink.cpp}::MachineSinking::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinesink-cpp-/machinesinking/#af56efb8509ab5b039fe9dcf0c4f5eccd">anonymous{MachineSink.cpp}::MachineSinking::runOnMachineFunction</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"machine-sink"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp">MachineSink.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
