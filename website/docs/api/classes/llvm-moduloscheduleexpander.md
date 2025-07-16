---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/moduloscheduleexpander
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ModuloScheduleExpander` Class Reference

<p>The <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpander">ModuloScheduleExpander</a> takes a <a href="/web-llvm/docs/api/classes/llvm/moduloschedule">ModuloSchedule</a> and expands it in-place, rewriting the old loop and inserting prologs and epilogs as required. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ModuloScheduleExpander { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">llvm/CodeGen/ModuloSchedule.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90b1a1bcd24ae454b2967189a7ff3890">InstrChangesTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, std::pair&lt; unsigned, int64_t &gt; &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f593aad4cf673083f60961404c87aa">ValueMapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484ed8cbc211bcec174931715cae59b6">MBBVectorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a635b471096e984c171b72294993a58d6">InstrMapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56e57beaf67091c69da7c12a6fe7d58">ModuloScheduleExpander</a> (MachineFunction &amp;MF, ModuloSchedule &amp;S, LiveIntervals &amp;LIS, InstrChangesTy InstrChanges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpander">ModuloScheduleExpander</a>. <a href="#ae56e57beaf67091c69da7c12a6fe7d58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772c336d26015c2e6fb5efc62cf166be">expand</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Performs the actual expansion. <a href="#a772c336d26015c2e6fb5efc62cf166be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6babf78504a9699ed219fab9ce3460">cleanup</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Performs final cleanup after expansion. <a href="#a1e6babf78504a9699ed219fab9ce3460">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0515409dae206f2863109e9b6a4cc625">getRewrittenKernel</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the newly rewritten kernel block, or nullptr if this was optimized away. <a href="#a0515409dae206f2863109e9b6a4cc625">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0574af0cf5d443c0cced6f0da0eb89d5">generatePipelinedLoop</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6407368592f847dbf14e17b6edbf554">generateProlog</a> (unsigned LastStage, MachineBasicBlock *KernelBB, ValueMapTy *VRMap, MBBVectorTy &amp;PrologBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the pipeline prolog code. <a href="#ac6407368592f847dbf14e17b6edbf554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8276a809c01ef0eeea2f6535981e497">generateEpilog</a> (unsigned LastStage, MachineBasicBlock *KernelBB, MachineBasicBlock *OrigBB, ValueMapTy *VRMap, ValueMapTy *VRMapPhi, MBBVectorTy &amp;EpilogBBs, MBBVectorTy &amp;PrologBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the pipeline epilog code. <a href="#ab8276a809c01ef0eeea2f6535981e497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980818f28d6c3f160426c5aa7e18d0b0">generateExistingPhis</a> (MachineBasicBlock *NewBB, MachineBasicBlock *BB1, MachineBasicBlock *BB2, MachineBasicBlock *KernelBB, ValueMapTy *VRMap, InstrMapTy &amp;InstrMap, unsigned LastStageNum, unsigned CurStageNum, bool IsLast)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate Phis for the specific block in the generated pipelined code. <a href="#a980818f28d6c3f160426c5aa7e18d0b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d51380889bff0fc6cc830e2de21765">generatePhis</a> (MachineBasicBlock *NewBB, MachineBasicBlock *BB1, MachineBasicBlock *BB2, MachineBasicBlock *KernelBB, ValueMapTy *VRMap, ValueMapTy *VRMapPhi, InstrMapTy &amp;InstrMap, unsigned LastStageNum, unsigned CurStageNum, bool IsLast)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate Phis for the specified block in the generated pipelined code. <a href="#a54d51380889bff0fc6cc830e2de21765">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ecfcd376614c6406b242e7b1e8b4c9">removeDeadInstructions</a> (MachineBasicBlock *KernelBB, MBBVectorTy &amp;EpilogBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove instructions that generate values with no uses. <a href="#ad9ecfcd376614c6406b242e7b1e8b4c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747ab797dc667e9b47d19da0d4578d63">splitLifetimes</a> (MachineBasicBlock *KernelBB, MBBVectorTy &amp;EpilogBBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For loop carried definitions, we split the lifetime of a virtual register that has uses past the definition in the next iteration. <a href="#a747ab797dc667e9b47d19da0d4578d63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea4dd869786e83fc292525aa36d6b9b">addBranches</a> (MachineBasicBlock &amp;PreheaderBB, MBBVectorTy &amp;PrologBBs, MachineBasicBlock *KernelBB, MBBVectorTy &amp;EpilogBBs, ValueMapTy *VRMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create branches from each prolog basic block to the appropriate epilog block. <a href="#a4ea4dd869786e83fc292525aa36d6b9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d401757f1b81890b243e1f35291d349">computeDelta</a> (MachineInstr &amp;MI, unsigned &amp;Delta)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can compute the amount the instruction changes during each iteration. <a href="#a2d401757f1b81890b243e1f35291d349">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1673917299251cbfa8d6e10a1ce3906">updateMemOperands</a> (MachineInstr &amp;NewMI, MachineInstr &amp;OldMI, unsigned Num)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the memory operand with a new offset when the pipeliner generates a new copy of the instruction that refers to a different memory location. <a href="#ae1673917299251cbfa8d6e10a1ce3906">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc6dd082ab126afbca1e214d431e2db">cloneInstr</a> (MachineInstr *OldMI, unsigned CurStageNum, unsigned InstStageNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the instruction for the new pipelined loop and update the memory operands, if needed. <a href="#a1fc6dd082ab126afbca1e214d431e2db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cceeefb2469be799a3877cfa27de356">cloneAndChangeInstr</a> (MachineInstr *OldMI, unsigned CurStageNum, unsigned InstStageNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the instruction for the new pipelined loop. <a href="#a3cceeefb2469be799a3877cfa27de356">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65ea5c04493f37f83a0aa80ed896b31">updateInstruction</a> (MachineInstr *NewMI, bool LastDef, unsigned CurStageNum, unsigned InstrStageNum, ValueMapTy *VRMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the machine instruction with new virtual registers. <a href="#ad65ea5c04493f37f83a0aa80ed896b31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5cd1c58bfea3aedaca6259a4a48a378">findDefInLoop</a> (unsigned Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the instruction in the loop that defines the register. <a href="#aa5cd1c58bfea3aedaca6259a4a48a378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c6b4e4e9108ffe51bda9df0a643e4df">getPrevMapVal</a> (unsigned StageNum, unsigned PhiStage, unsigned LoopVal, unsigned LoopStage, ValueMapTy *VRMap, MachineBasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the new name for the value from the previous stage. <a href="#a3c6b4e4e9108ffe51bda9df0a643e4df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b32ad6fc983c4d9ab9691169cfcab4">rewritePhiValues</a> (MachineBasicBlock *NewBB, unsigned StageNum, ValueMapTy *VRMap, InstrMapTy &amp;InstrMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite the Phi values in the specified block to use the mappings from the initial operand. <a href="#a84b32ad6fc983c4d9ab9691169cfcab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a576fedcc2dc6c4506cb025e0db5634f1">rewriteScheduledInstr</a> (MachineBasicBlock *BB, InstrMapTy &amp;InstrMap, unsigned CurStageNum, unsigned PhiNum, MachineInstr *Phi, unsigned OldReg, unsigned NewReg, unsigned PrevReg=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite a previously scheduled instruction to use the register value from the new instruction. <a href="#a576fedcc2dc6c4506cb025e0db5634f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0184a84b2c92af9a25bf70d76ab417">isLoopCarried</a> (MachineInstr &amp;Phi)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3c2e75da5e7d0056423d15af9af374d">getStagesForReg</a> (int Reg, unsigned CurStage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the max. <a href="#af3c2e75da5e7d0056423d15af9af374d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac749843d2d0351fe6a6308e8b478b46c">getStagesForPhi</a> (int Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of stages for a Phi is a little different than other instructions. <a href="#ac749843d2d0351fe6a6308e8b478b46c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/moduloschedule">ModuloSchedule</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdeed50fa186e519b3a7922eac5a8a0d">Schedule</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6224d7cb8bae893a16b342cd783c562e">MF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adee462113c2b285b33a3336e1f451c8c">ST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6522070fe1a24d9432cf7b09731adba1">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9fbe7175104136435a57d53bc39e48">TII</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed311b9032f0a744dc1a240d8be1e52">LIS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2773222a6a5c34dedc9fa1d96ae6a671">BB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34cdbe5b0c00ab11ce49f46aa9e23c24">Preheader</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f4f8d9e452f7307033db31e422e899">NewKernel</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/pipelinerloopinfo">TargetInstrInfo::PipelinerLoopInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0549ef5f532664882a747629fcd05aca">LoopInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, std::pair&lt; unsigned, bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af60426f5ba6fae0c39aa37bde5994acc">RegToStageDiff</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map for each register and the max difference between its uses and def. <a href="#af60426f5ba6fae0c39aa37bde5994acc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a90b1a1bcd24ae454b2967189a7ff3890">InstrChangesTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc438001532490636ce2594a790a2e6">InstrChanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructions to change when emitting the final schedule. <a href="#a5fc438001532490636ce2594a790a2e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpander">ModuloScheduleExpander</a> takes a <a href="/web-llvm/docs/api/classes/llvm/moduloschedule">ModuloSchedule</a> and expands it in-place, rewriting the old loop and inserting prologs and epilogs as required.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### InstrChangesTy {#a90b1a1bcd24ae454b2967189a7ff3890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ModuloScheduleExpander::InstrChangesTy =  DenseMap&lt;MachineInstr *, std::pair&lt;unsigned, int64_t&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### InstrMapTy {#a635b471096e984c171b72294993a58d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ModuloScheduleExpander::InstrMapTy =  DenseMap&lt;MachineInstr *, MachineInstr *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### MBBVectorTy {#a484ed8cbc211bcec174931715cae59b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ModuloScheduleExpander::MBBVectorTy =  SmallVectorImpl&lt;MachineBasicBlock *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### ValueMapTy {#a21f593aad4cf673083f60961404c87aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ModuloScheduleExpander::ValueMapTy =  DenseMap&lt;unsigned, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ModuloScheduleExpander() {#ae56e57beaf67091c69da7c12a6fe7d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ModuloScheduleExpander::ModuloScheduleExpander (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/moduloschedule">ModuloSchedule</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="#a90b1a1bcd24ae454b2967189a7ff3890">InstrChangesTy</a> InstrChanges)</td>
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

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpander">ModuloScheduleExpander</a>.</p>


<ul class="doxyList ">
<li>InstrChanges Modifications to make to instructions with memory operands. FIXME: InstrChanges is opaque and is an implementation detail of an optimization in <a href="/web-llvm/docs/api/classes/llvm/machinepipeliner">MachinePipeliner</a> that crosses abstraction boundaries.</li>
</ul>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cleanup() {#a1e6babf78504a9699ed219fab9ce3460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::cleanup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Performs final cleanup after expansion.</p>

<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/windowscheduler/#a8b546fe78d24f8c9f7d440957a37a801">llvm::WindowScheduler::expand</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/moduloscheduletest/#aff71500f971dc1f796d293a1450dc6b0">anonymous{ModuloSchedule.cpp}::ModuloScheduleTest::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae67a99405a40814d2261e31f11fe7a38">llvm::PeelingModuloScheduleExpander::validateAgainstModuloScheduleExpander</a>.</p>

</div>
</div>

### expand() {#a772c336d26015c2e6fb5efc62cf166be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::expand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Performs the actual expansion.</p>

<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/windowscheduler/#a8b546fe78d24f8c9f7d440957a37a801">llvm::WindowScheduler::expand</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/moduloscheduletest/#aff71500f971dc1f796d293a1450dc6b0">anonymous{ModuloSchedule.cpp}::ModuloScheduleTest::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a87416d44c85818861fe0152759e9acb1">llvm::SwingSchedulerDAG::schedule</a> and <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae67a99405a40814d2261e31f11fe7a38">llvm::PeelingModuloScheduleExpander::validateAgainstModuloScheduleExpander</a>.</p>

</div>
</div>

### getRewrittenKernel() {#a0515409dae206f2863109e9b6a4cc625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::ModuloScheduleExpander::getRewrittenKernel ()</td>
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

<p>Returns the newly rewritten kernel block, or nullptr if this was optimized away.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae67a99405a40814d2261e31f11fe7a38">llvm::PeelingModuloScheduleExpander::validateAgainstModuloScheduleExpander</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addBranches() {#a4ea4dd869786e83fc292525aa36d6b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::addBranches (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; PreheaderBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">MBBVectorTy</a> &amp; PrologBBs, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * KernelBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">MBBVectorTy</a> &amp; EpilogBBs, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create branches from each prolog basic block to the appropriate epilog block.</p>


<p>These edges are needed if the loop ends before reaching the kernel.</p>


<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 876 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### cloneAndChangeInstr() {#a3cceeefb2469be799a3877cfa27de356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ModuloScheduleExpander::cloneAndChangeInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OldMI, unsigned CurStageNum, unsigned InstStageNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone the instruction for the new pipelined loop.</p>


<p>If needed, this function updates the instruction using the values saved in the InstrChanges structure.</p>


<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### cloneInstr() {#a1fc6dd082ab126afbca1e214d431e2db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ModuloScheduleExpander::cloneInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OldMI, unsigned CurStageNum, unsigned InstStageNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone the instruction for the new pipelined loop and update the memory operands, if needed.</p>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### computeDelta() {#a2d401757f1b81890b243e1f35291d349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuloScheduleExpander::computeDelta (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned &amp; Delta)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if we can compute the amount the instruction changes during each iteration.</p>


<p>Set Delta to the amount of the change.</p>


<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### findDefInLoop() {#aa5cd1c58bfea3aedaca6259a4a48a378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ModuloScheduleExpander::findDefInLoop (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the instruction in the loop that defines the register.</p>


<p>If the definition is a Phi, then follow the Phi operand to the instruction in the loop.</p>


<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### generateEpilog() {#ab8276a809c01ef0eeea2f6535981e497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::generateEpilog (unsigned LastStage, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * KernelBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * OrigBB, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMap, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMapPhi, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">MBBVectorTy</a> &amp; EpilogBBs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">MBBVectorTy</a> &amp; PrologBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the pipeline epilog code.</p>


<p>The epilog code finishes the iterations that were started in either the prolog or the kernel. We create a basic block for each stage that needs to complete.</p>


<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### generateExistingPhis() {#a980818f28d6c3f160426c5aa7e18d0b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::generateExistingPhis (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB1, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB2, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * KernelBB, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMap, <a href="/web-llvm/docs/api/classes/llvm/densemap">InstrMapTy</a> &amp; InstrMap, unsigned LastStageNum, unsigned CurStageNum, bool IsLast)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate Phis for the specific block in the generated pipelined code.</p>


<p>This function looks at the Phis from the original code to guide the creation of new Phis.</p>


<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### generatePhis() {#a54d51380889bff0fc6cc830e2de21765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::generatePhis (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB1, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB2, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * KernelBB, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMap, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMapPhi, <a href="/web-llvm/docs/api/classes/llvm/densemap">InstrMapTy</a> &amp; InstrMap, unsigned LastStageNum, unsigned CurStageNum, bool IsLast)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate Phis for the specified block in the generated pipelined code.</p>


<p>These are new Phis needed because the definition is scheduled after the use in the pipelined sequence.</p>


<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### generatePipelinedLoop() {#a0574af0cf5d443c0cced6f0da0eb89d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::generatePipelinedLoop ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### generateProlog() {#ac6407368592f847dbf14e17b6edbf554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::generateProlog (unsigned LastStage, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * KernelBB, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMap, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">MBBVectorTy</a> &amp; PrologBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the pipeline prolog code.</p>

<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### getPrevMapVal() {#a3c6b4e4e9108ffe51bda9df0a643e4df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ModuloScheduleExpander::getPrevMapVal (unsigned StageNum, unsigned PhiStage, unsigned LoopVal, unsigned LoopStage, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMap, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the new name for the value from the previous stage.</p>

<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### getStagesForPhi() {#ac749843d2d0351fe6a6308e8b478b46c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ModuloScheduleExpander::getStagesForPhi (int Reg)</td>
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

<p>The number of stages for a Phi is a little different than other instructions.</p>


<p>The minimum value computed in RegToStageDiff is 1 because we assume the Phi is needed for at least 1 iteration. This is not the case if the loop value is scheduled prior to the Phi in the same stage. This function returns the number of stages or iterations needed between the Phi definition and any uses.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### getStagesForReg() {#af3c2e75da5e7d0056423d15af9af374d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ModuloScheduleExpander::getStagesForReg (int Reg, unsigned CurStage)</td>
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

<p>Return the max.</p>


<p>number of stages/iterations that can occur between a register definition and its uses.</p>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### isLoopCarried() {#a0a0184a84b2c92af9a25bf70d76ab417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuloScheduleExpander::isLoopCarried (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Phi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 1221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### removeDeadInstructions() {#ad9ecfcd376614c6406b242e7b1e8b4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::removeDeadInstructions (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * KernelBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">MBBVectorTy</a> &amp; EpilogBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove instructions that generate values with no uses.</p>


<p>Typically, these are induction variable operations that generate values used in the loop itself. A dead instruction has a definition with no uses, or uses that occur in the original loop only.</p>


<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### rewritePhiValues() {#a84b32ad6fc983c4d9ab9691169cfcab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::rewritePhiValues (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewBB, unsigned StageNum, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMap, <a href="/web-llvm/docs/api/classes/llvm/densemap">InstrMapTy</a> &amp; InstrMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite the Phi values in the specified block to use the mappings from the initial operand.</p>


<p>Once the Phi is scheduled, we switch to using the loop value instead of the Phi value, so those names do not need to be rewritten.</p>


<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### rewriteScheduledInstr() {#a576fedcc2dc6c4506cb025e0db5634f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::rewriteScheduledInstr (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/densemap">InstrMapTy</a> &amp; InstrMap, unsigned CurStageNum, unsigned PhiNum, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Phi, unsigned OldReg, unsigned NewReg, unsigned PrevReg=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite a previously scheduled instruction to use the register value from the new instruction.</p>


<p>Make sure the instruction occurs in the basic block, and we don't change the uses in the new instruction.</p>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 1160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### splitLifetimes() {#a747ab797dc667e9b47d19da0d4578d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::splitLifetimes (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * KernelBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">MBBVectorTy</a> &amp; EpilogBBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For loop carried definitions, we split the lifetime of a virtual register that has uses past the definition in the next iteration.</p>


<p>A copy with a new virtual register is inserted before the definition, which helps with generating a better register assignment.</p>


<p>v1 = phi(a, v2) v1 = phi(a, v2) v2 = phi(b, v3) v2 = phi(b, v3) v3 = .. v4 = copy v1 .. = V1 v3 = .. .. = v4</p>


<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### updateInstruction() {#ad65ea5c04493f37f83a0aa80ed896b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::updateInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * NewMI, bool LastDef, unsigned CurStageNum, unsigned InstrStageNum, <a href="/web-llvm/docs/api/classes/llvm/densemap">ValueMapTy</a> * VRMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the machine instruction with new virtual registers.</p>


<p>This function may change the definitions and/or uses.</p>


<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

### updateMemOperands() {#ae1673917299251cbfa8d6e10a1ce3906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuloScheduleExpander::updateMemOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; NewMI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; OldMI, unsigned Num)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the memory operand with a new offset when the pipeliner generates a new copy of the instruction that refers to a different memory location.</p>

<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>, definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BB {#a2773222a6a5c34dedc9fa1d96ae6a671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::ModuloScheduleExpander::BB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### InstrChanges {#a5fc438001532490636ce2594a790a2e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrChangesTy llvm::ModuloScheduleExpander::InstrChanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instructions to change when emitting the final schedule.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### LIS {#abed311b9032f0a744dc1a240d8be1e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals&amp; llvm::ModuloScheduleExpander::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### LoopInfo {#a0549ef5f532664882a747629fcd05aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TargetInstrInfo::PipelinerLoopInfo&gt; llvm::ModuloScheduleExpander::LoopInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### MF {#a6224d7cb8bae893a16b342cd783c562e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::ModuloScheduleExpander::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### MRI {#a6522070fe1a24d9432cf7b09731adba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::ModuloScheduleExpander::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### NewKernel {#a47f4f8d9e452f7307033db31e422e899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::ModuloScheduleExpander::NewKernel = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### Preheader {#a34cdbe5b0c00ab11ce49f46aa9e23c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::ModuloScheduleExpander::Preheader = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### RegToStageDiff {#af60426f5ba6fae0c39aa37bde5994acc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, std::pair&lt;unsigned, bool&gt; &gt; llvm::ModuloScheduleExpander::RegToStageDiff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map for each register and the max difference between its uses and def.</p>


<p>The first element in the pair is the max difference in stages. The second is true if the register defines a Phi value and loop value is scheduled before the Phi.</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### Schedule {#afdeed50fa186e519b3a7922eac5a8a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuloSchedule&amp; llvm::ModuloScheduleExpander::Schedule</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### ST {#adee462113c2b285b33a3336e1f451c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSubtargetInfo&amp; llvm::ModuloScheduleExpander::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

### TII {#add9fbe7175104136435a57d53bc39e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::ModuloScheduleExpander::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/moduloschedule-h">ModuloSchedule.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp">ModuloSchedule.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
