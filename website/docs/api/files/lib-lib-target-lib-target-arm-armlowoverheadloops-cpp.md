---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ARMLowOverheadLoops.cpp` File

<p>Finalize v8.1-m low-overhead loops by converting the associated pseudo instructions into machine operations. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arm-h">ARM.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbasicblockinfo-h">ARMBasicBlockInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetailpredutils-h">MVETailPredUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2instrinfo-h">Thumb2InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">llvm/CodeGen/LivePhysRegs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinelooputils-h">llvm/CodeGen/MachineLoopUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/reachingdefanalysis-h">llvm/CodeGen/ReachingDefAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armlowoverheadloops-cpp-">anonymous{ARMLowOverheadLoops.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/postorderlooptraversal">PostOrderLoopTraversal</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptblock">VPTBlock</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate">VPTState</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop">LowOverheadLoop</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/armlowoverheadloops">ARMLowOverheadLoops</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eba246efd54ade21f193d2362acdead">isVectorPredicated</a> (MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8535dd8e5a6bb6d0f053ba22246a1593">isVectorPredicate</a> (MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57802d669faf5aa67bf5eea374072858">hasVPRUse</a> (MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00f72b50a86f27bb8b126906a164f8ba">isDomainMVE</a> (MachineInstr *MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad84c5ccc73435217f046a6fe26d547f9">getVecSize</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df1ebcc0b9226f9cfda9d5f73a21526">shouldInspect</a> (MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33871fd2a06a8af436f0cb548798ec5d">isHorizontalReduction</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6390597185c559f28ec61cc95a8ab606">INITIALIZE_PASS</a> (ARMLowOverheadLoops, DEBUG_TYPE, ARM_LOW_OVERHEAD_LOOPS_NAME, false, false) static bool TryRemove(MachineInstr *MI</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3003e70b3cb1d2dc2659796b546ca2">if</a> (!RDA.isSafeToRemove(MI, Uses, Ignore)) return false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d72f43eb0c681f84fc9a00c9621941">if</a> (WontCorruptITs(Uses, RDA))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5898b6ed934ad744eefecc5d5297a3a8">isRegInClass</a> (const MachineOperand &amp;MO, const TargetRegisterClass *Class)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8af4c9dee593e1e883a0d3509c25d1d0">retainsPreviousHalfElement</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ef4c167cadd485c1e39881969bc2d5">producesDoubleWidthResult</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2765f2d6b072f973ae4e6aba772836c7">canGenerateNonZeros</a> (const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f25f6a5125ee4d8f6e01e85ebf836e">producesFalseLanesZero</a> (MachineInstr &amp;MI, const TargetRegisterClass *QPRs, const ReachingDefAnalysis &amp;RDA, InstSet &amp;FalseLanesZero)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d85b8fd4787153b0ade229c616b7562">ValidateMVEStore</a> (MachineInstr *MI, MachineLoop *ML)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab781884eec3c9f1366adf3bb5f4ece69">DisableTailPredication</a>("arm-loloops-disable-tailpred", cl::Hidden, cl::desc("Disable tail-predication in the ARM LowOverheadLoop pass"), cl::init(false))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee936d04057d93ca2a8691dbca781770">DisableOmitDLS</a>("arm-disable-omit-dls", cl::Hidden, cl::desc("Disable omitting 'dls lr, lr' instructions"), cl::init(false))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis">ReachingDefAnalysis</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b4c3cf053b165d7b914e2ebf4bb02c6">RDA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis">ReachingDefAnalysis</a> InstSet &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf42baf773b375802538951c88d8e12">ToRemove</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis">ReachingDefAnalysis</a> InstSet InstSet &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee9acb24ef4f057644a7cf7217922eaa">Ignore</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0971d62011c35b29ff4a2325d45e93">Uses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">return</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5df37b7f02e5cdc7d9412b7f872b8e01">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"arm-low-overhead-loops"</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeddbd656a8e178ba416c845cd0171060">ARM_LOW_OVERHEAD_LOOPS_NAME</a>&nbsp;&nbsp;&nbsp;"ARM Low Overhead <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a> pass"</td>
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

## Description {#details}

<p>Finalize v8.1-m low-overhead loops by converting the associated pseudo instructions into machine operations.</p>


<p>The expectation is that the loop contains three pseudo instructions:</p>


<ul class="doxyList ">
<li>t2*LoopStart - placed in the preheader or pre-preheader. The do-loop form should be in the preheader, whereas the while form should be in the preheaders only predecessor.</li>
<li>t2LoopDec - placed within in the loop body.</li>
<li>t2LoopEnd - the loop latch terminator.</li>
</ul>

<p>In addition to this, we also look for the presence of the VCTP instruction, which determines whether we can generated the tail-predicated low-overhead loop form.</p>


<p>Assumptions and Dependencies: Low-overhead loops are constructed and executed using a setup instruction: DLS, WLS, DLSTP or WLSTP and an instruction that loops back: LE or LETP. WLS(TP) and LE(TP) are branching instructions with a (large) limited range but fixed polarity: WLS can only branch forwards and LE can only branch backwards. These restrictions mean that this pass is dependent upon block layout and block sizes, which is why it's the last pass to run. The same is true for ConstantIslands, but this pass does not increase the size of the basic blocks, nor does it change the CFG. Instructions are mainly removed during the transform and pseudo instructions are replaced by real ones. In some cases, when we have to revert to a 'normal' loop, we have to introduce multiple instructions for a single pseudo (see RevertWhile and RevertLoopEnd). To handle this situation, t2WhileLoopStartLR and t2LoopEnd are defined to be as large as this maximum sequence of replacement instructions.</p>


<p>A note on VPR.P0 (the lane mask): VPT, VCMP, VPNOT and VCTP won't overwrite VPR.P0 when they update it in a "VPT Active" context (which includes low-overhead loops and vpt blocks). They will simply "and" the result of their calculation with the current value of VPR.P0. You can think of it like this:</p>



<pre><code>/// if VPT active:    ; Between a DLSTP/LETP, or for predicated instrs
 *    VPR.P0 &amp;= Value
 *  else
 *    VPR.P0 = Value
 *
</code></pre>


<p>When we're inside the low-overhead loop (between DLSTP and LETP), we always fall in the "VPT active" case, so we can consider that all VPR writes by one of those instruction is actually a "and".</p>


<div class="doxySectionDef">

## Functions

### canGenerateNonZeros() {#a2765f2d6b072f973ae4e6aba772836c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canGenerateNonZeros (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a46ef4c167cadd485c1e39881969bc2d5">producesDoubleWidthResult</a>.</p>


<p>Referenced by <a href="#ad6f25f6a5125ee4d8f6e01e85ebf836e">producesFalseLanesZero</a>.</p>

</div>
</div>

### getVecSize() {#ad84c5ccc73435217f046a6fe26d547f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getVecSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a479711d0ab662307550fc709665589ea">llvm::ARMII::VecSize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a07023b4966d755e56b328349ef01a237">llvm::ARMII::VecSizeShift</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a22414e0619deaa2a695fd6d31002bb9d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateTailPredicate</a>.</p>

</div>
</div>

### hasVPRUse() {#a57802d669faf5aa67bf5eea374072858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasVPRUse (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9df1ebcc0b9226f9cfda9d5f73a21526">shouldInspect</a>.</p>

</div>
</div>

### if() {#aef3003e70b3cb1d2dc2659796b546ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (!RDA. isSafeToRemove=MI, Uses, Ignore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#aee9acb24ef4f057644a7cf7217922eaa">Ignore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a1b4c3cf053b165d7b914e2ebf4bb02c6">RDA</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>

</div>
</div>

### if() {#a14d72f43eb0c681f84fc9a00c9621941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (WontCorruptITs(<a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>, <a href="#a1b4c3cf053b165d7b914e2ebf4bb02c6">RDA</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a7004354fbee1c8cd74ed9001915e1db5">llvm::SmallPtrSetImpl&lt; PtrType &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a1b4c3cf053b165d7b914e2ebf4bb02c6">RDA</a>, <a href="#a3bf42baf773b375802538951c88d8e12">ToRemove</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a6390597185c559f28ec61cc95a8ab606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (ARMLowOverheadLoops, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="#aeddbd656a8e178ba416c845cd0171060">ARM_LOW_OVERHEAD_LOOPS_NAME</a>, false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#aeddbd656a8e178ba416c845cd0171060">ARM_LOW_OVERHEAD_LOOPS_NAME</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>.</p>

</div>
</div>

### isDomainMVE() {#a00f72b50a86f27bb8b126906a164f8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isDomainMVE (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a96db53f04326f6421725b16e4ee7a596">llvm::ARMII::DomainMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4ab5112bfba90c616984021580dd1131b8">llvm::ARMII::DomainMVE</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9df1ebcc0b9226f9cfda9d5f73a21526">shouldInspect</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#afdb11d0b5d726b02916f412453587951">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateMVEInst</a>.</p>

</div>
</div>

### isHorizontalReduction() {#a33871fd2a06a8af436f0cb548798ec5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isHorizontalReduction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a9e2a02c8e15c43cfe03fee48f85f76cf">llvm::ARMII::HorizontalReduction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad6f25f6a5125ee4d8f6e01e85ebf836e">producesFalseLanesZero</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>.</p>

</div>
</div>

### isRegInClass() {#a5898b6ed934ad744eefecc5d5297a3a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRegInClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * Class)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>.</p>


<p>Referenced by <a href="#ad6f25f6a5125ee4d8f6e01e85ebf836e">producesFalseLanesZero</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>.</p>

</div>
</div>

### isVectorPredicate() {#a8535dd8e5a6bb6d0f053ba22246a1593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isVectorPredicate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptblock/#a08c481890facf85f7465eb3359becd5b">anonymous{ARMLowOverheadLoops.cpp}::VPTBlock::getDivergent</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a3471d30b320c2d011979c2956eb33ab1">anonymous{ARMLowOverheadLoops.cpp}::VPTState::isValid</a>, <a href="#a9df1ebcc0b9226f9cfda9d5f73a21526">shouldInspect</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#afdb11d0b5d726b02916f412453587951">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateMVEInst</a>.</p>

</div>
</div>

### isVectorPredicated() {#a0eba246efd54ade21f193d2362acdead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isVectorPredicated (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0833f10a51730f325a49f05d5bc1d327">llvm::findFirstVPTPredOperandIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ad6f25f6a5125ee4d8f6e01e85ebf836e">producesFalseLanesZero</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#afdb11d0b5d726b02916f412453587951">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateMVEInst</a>.</p>

</div>
</div>

### producesDoubleWidthResult() {#a46ef4c167cadd485c1e39881969bc2d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool producesDoubleWidthResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a1d1ee0a18b878ed2571430f0b9ba7441">llvm::ARMII::DoubleWidthResult</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2765f2d6b072f973ae4e6aba772836c7">canGenerateNonZeros</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#afdb11d0b5d726b02916f412453587951">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateMVEInst</a>.</p>

</div>
</div>

### producesFalseLanesZero() {#ad6f25f6a5125ee4d8f6e01e85ebf836e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool producesFalseLanesZero (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * QPRs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis">ReachingDefAnalysis</a> &amp; RDA, InstSet &amp; FalseLanesZero)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#a2765f2d6b072f973ae4e6aba772836c7">canGenerateNonZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0833f10a51730f325a49f05d5bc1d327">llvm::findFirstVPTPredOperandIdx</a>, <a href="#a33871fd2a06a8af436f0cb548798ec5d">isHorizontalReduction</a>, <a href="#a5898b6ed934ad744eefecc5d5297a3a8">isRegInClass</a>, <a href="#a0eba246efd54ade21f193d2362acdead">isVectorPredicated</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a1b4c3cf053b165d7b914e2ebf4bb02c6">RDA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>.</p>

</div>
</div>

### retainsPreviousHalfElement() {#a8af4c9dee593e1e883a0d3509c25d1d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool retainsPreviousHalfElement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4aa25c5be216c7a89861b0ef6822601465">llvm::ARMII::RetainsPreviousHalfElement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>.</p>

</div>
</div>

### shouldInspect() {#a9df1ebcc0b9226f9cfda9d5f73a21526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldInspect (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="#a57802d669faf5aa67bf5eea374072858">hasVPRUse</a>, <a href="#a00f72b50a86f27bb8b126906a164f8ba">isDomainMVE</a>, <a href="#a8535dd8e5a6bb6d0f053ba22246a1593">isVectorPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#afdb11d0b5d726b02916f412453587951">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateMVEInst</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a22414e0619deaa2a695fd6d31002bb9d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateTailPredicate</a>.</p>

</div>
</div>

### ValidateMVEStore() {#a5d85b8fd4787153b0ade229c616b7562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ValidateMVEStore (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * ML)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259eaf38d1857511c3f0404c95f65664b36ab">llvm::PseudoSourceValue::FixedStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#ab1969256cc373d72874932779a45b46c">llvm::PseudoSourceValue::kind</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3ad01fd9b01e9dde8bd3dc247afbfb7218">ML</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad88ff1529541fb4e243cc8ed90b11131">llvm::MachineBasicBlock::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#afdb11d0b5d726b02916f412453587951">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateMVEInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableOmitDLS {#aee936d04057d93ca2a8691dbca781770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableOmitDLS("arm-disable-omit-dls", cl::Hidden, cl::desc("Disable omitting 'dls lr, lr' instructions"), cl::init(false))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>

</div>
</div>

### DisableTailPredication {#ab781884eec3c9f1366adf3bb5f4ece69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableTailPredication("arm-loloops-disable-tailpred", cl::Hidden, cl::desc("Disable tail-predication in the ARM LowOverheadLoop pass"), cl::init(false))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a22414e0619deaa2a695fd6d31002bb9d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateTailPredicate</a>.</p>

</div>
</div>

### false {#a5df37b7f02e5cdc7d9412b7f872b8e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">return false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>

</div>
</div>

### Ignore {#aee9acb24ef4f057644a7cf7217922eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReachingDefAnalysis InstSet InstSet&amp; Ignore</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="#aef3003e70b3cb1d2dc2659796b546ca2">if</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#abd1c3cbea21aa15aed845a4c163fe62c">llvm::ReachingDefAnalysis::isSafeToDefRegAt</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#ac153a9af74f3b0bb72e5f95a7654574e">llvm::ReachingDefAnalysis::isSafeToDefRegAt</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a2f90013f33dac170acc9c62907d99e44">llvm::ReachingDefAnalysis::isSafeToRemove</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a90cebb38d9bd176e0efbc97c9bf33c2d">llvm::ReachingDefAnalysis::isSafeToRemove</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a263bac5d85adb87956f47116b8fd5b2a">llvm::sys::unicode::startsWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a22414e0619deaa2a695fd6d31002bb9d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateTailPredicate</a>.</p>

</div>
</div>

### RDA {#a1b4c3cf053b165d7b914e2ebf4bb02c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReachingDefAnalysis&amp; RDA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a334e7c41df90efd700b045c03de6777d">anonymous{ARMLowOverheadLoops.cpp}::VPTState::hasImplicitlyValidVPT</a>, <a href="#aef3003e70b3cb1d2dc2659796b546ca2">if</a>, <a href="#a14d72f43eb0c681f84fc9a00c9621941">if</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a3471d30b320c2d011979c2956eb33ab1">anonymous{ARMLowOverheadLoops.cpp}::VPTState::isValid</a>, <a href="#ad6f25f6a5125ee4d8f6e01e85ebf836e">producesFalseLanesZero</a> and <a href="/web-llvm/docs/api/classes/anonymous-armfixcortexa57aes1742098pass-cpp-/armfixcortexa57aes1742098/#a43d2faff17080847be1128de33a8fe54">anonymous{ARMFixCortexA57AES1742098Pass.cpp}::ARMFixCortexA57AES1742098::runOnMachineFunction</a>.</p>

</div>
</div>

### ToRemove {#a3bf42baf773b375802538951c88d8e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReachingDefAnalysis InstSet&amp; ToRemove</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/aa/pointerinfo/state/#a0ec6e46ec669f364d2396241b5b7b2ae">llvm::AA::PointerInfo::State::addAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a57d54880afa1fb74833cc7c43ad33377">analyzeAndPruneOutputBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ae4662629d6acdb1e1ce903027853151b">checkAndReplaceCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#add6cb3c2274e68181ab8a1b4be472b90">checkAndReplaceCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a761596303fee8f03f896c70d36a18303">checkAndReplaceMinMax</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a38e9b77a3c8508ea8ff0ba1f5bf81eba">anonymous{DXILOpLowering.cpp}::OpLowerer::cleanupHandleCasts</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfomanager/#ad97a5f903c4da15770aedf502ea501d6">llvm::LoopAccessInfoManager::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed498f056a09006219c59ee9fab0450f">llvm::EliminateDuplicatePHINodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ddf07853114e72808bc2713805814f3">llvm::EliminateDuplicatePHINodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa5133cfd6ce1419c7162cd0d7ba39ea9">EliminateDuplicatePHINodesNaiveImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a272de407838df85f0919b0640aa79f9d">erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjcopy-cpp-/removenotedetail/#a8f3aa0867bb68ba0c5f04860633f6ca9">anonymous{ELFObjcopy.cpp}::RemoveNoteDetail::findNotesToRemove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ae25b1e577bcd72ebc8b84b83aca02662">for</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#adbe3fa02a27f967fb4552e3e608be5ce">for</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/coff/#aaa859579ac4adb9cbcebf0ddc98a085b">llvm::objcopy::coff::handleArgs</a>, <a href="#a14d72f43eb0c681f84fc9a00c9621941">if</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a2f90013f33dac170acc9c62907d99e44">llvm::ReachingDefAnalysis::isSafeToRemove</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a90cebb38d9bd176e0efbc97c9bf33c2d">llvm::ReachingDefAnalysis::isSafeToRemove</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/requirementhandler/#a86258ccd5f0c68dfcb67d590b27fe802">llvm::SPIRV::RequirementHandler::removeCapabilityIf</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#ac88025eb8866478014f41b34cd29b593">anonymous{AMDGPUExportClustering.cpp}::removeExportDependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a29234a4bcb1dca0dabae964f8eacb264">llvm::objcopy::macho::Object::removeLoadCommands</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#a06d536441c3553e3bc7639fdfb0fb45c">removeNotes</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/dynamicrelocationsection/#ae340c5fc4a8b0ced18faab32479843d0">llvm::objcopy::elf::DynamicRelocationSection::removeSectionReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/groupsection/#a99b0c256b36c261eb440d1d44ea68dad">llvm::objcopy::elf::GroupSection::removeSectionReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocationsection/#afd3bb785ee41f817bf6b4f4bfeeae2e5">llvm::objcopy::elf::RelocationSection::removeSectionReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/section/#a16db01500a4e6c2dfb50f812a092f643">llvm::objcopy::elf::Section::removeSectionReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#a1e3899ce7de382a1a68774418093a83b">llvm::objcopy::elf::SymbolTableSection::removeSectionReferences</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#a95463c813d6c4a15390dfe8a0a03bfda">llvm::objcopy::coff::Object::removeSections</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a7ffd3f6642f3190ce71003bbe6500203">llvm::objcopy::elf::Object::removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/object/#a47fbc494119ba51bed1e722d310bba1e">llvm::objcopy::macho::Object::removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/object/#af9ff1730158f82c9b5c99b3947740404">llvm::objcopy::wasm::Object::removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/coff/object/#adb4129c7b7fb10fedccaaa668094cb31">llvm::objcopy::coff::Object::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/groupsection/#accb463905d354a442ac7beb6d85b12a9">llvm::objcopy::elf::GroupSection::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/object/#a6f5260724ddb92daec8287a2365ba36f">llvm::objcopy::elf::Object::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/relocationsection/#ad393bb7849b7f179f5f1d649318d6204">llvm::objcopy::elf::RelocationSection::removeSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/symboltablesection/#aa2f765a7f0d42094f04d32ac60ddaad5">llvm::objcopy::elf::SymbolTableSection::removeSymbols</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/macho/symboltable/#a93dd1b9a6cbe03781efa0a11ea3bd236">llvm::objcopy::macho::SymbolTable::removeSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/lowerallowcheckpass-cpp/#aeab949c1d2a96004a9076b8b2176ca74">removeUbsanTraps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#a7a7872729b8078d24a66aab43990ddfe">removeUnreachableFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ac26a57370fde8e7b017b6094a9216b77">replaceSubOverflowUses</a>, <a href="/web-llvm/docs/api/classes/spirvstripconvergentintrinsics/#a4d2b7f7dd9786ee2f5eba35539cbd397">SPIRVStripConvergentIntrinsics::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armoptimizebarrierspass-cpp-/armoptimizebarrierspass/#ab1979687a625b3edd1dde60803a899e4">anonymous{ARMOptimizeBarriersPass.cpp}::ARMOptimizeBarriersPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#a19a6a168a50b639280b51eada31cae76">llvm::DbgValueHistoryMap::trimLocationRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#acb9adec0a838b8a5664673e0c7265c4b">tryToSimplifyOverflowMath</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjcopy-cpp-/removenotedetail/#aed2b24c385053ea197788dfc04744582">anonymous{ELFObjcopy.cpp}::RemoveNoteDetail::updateData</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/sectionbase/#a9218f60ea4308953dde7306a54292fa1">llvm::objcopy::elf::SectionBase::~SectionBase</a>.</p>

</div>
</div>

### Uses {#a0a0971d62011c35b29ff4a2325d45e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr *, 2&gt; Uses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ARM\_LOW\_OVERHEAD\_LOOPS\_NAME {#aeddbd656a8e178ba416c845cd0171060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ARM_LOW_OVERHEAD_LOOPS_NAME&nbsp;&nbsp;&nbsp;"ARM Low Overhead <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a> pass"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/armlowoverheadloops/#ad097dcfb8ec7528bfad1148948e7546a">anonymous{ARMLowOverheadLoops.cpp}::ARMLowOverheadLoops::getPassName</a> and <a href="#a6390597185c559f28ec61cc95a8ab606">INITIALIZE_PASS</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"arm-low-overhead-loops"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp">ARMLowOverheadLoops.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
