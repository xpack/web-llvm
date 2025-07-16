---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AArch64CollectLOH.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64-h">AArch64.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64collectloh-cpp-">anonymous{AArch64CollectLOH.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh">AArch64CollectLOH</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/lohinfo">LOHInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State tracked per register. <a href="/web-llvm/docs/api/structs/lohinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16fdc3d75073a2089c545c82ecc31425">STATISTIC</a> (NumADRPSimpleCandidate, "Number of simplifiable ADRP dominate by another")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeacc3685f494c8ceaf4f26610d71b324">STATISTIC</a> (NumADDToSTR, "Number of simplifiable STR reachable by ADD")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4000367668b691b8c0e25e9f45161b95">STATISTIC</a> (NumLDRToSTR, "Number of simplifiable STR reachable by LDR")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308807550c461f87ac12ca303bf72a27">STATISTIC</a> (NumADDToLDR, "Number of simplifiable LDR reachable by ADD")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b16b527003ed237dbd752b389a4762f">STATISTIC</a> (NumLDRToLDR, "Number of simplifiable LDR reachable by LDR")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e352868bdc1d4de5adc71e675aa3acd">STATISTIC</a> (NumADRPToLDR, "Number of simplifiable LDR reachable by ADRP")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b41f1c9cdddc6ef8ad6042e2c7126a">STATISTIC</a> (NumADRSimpleCandidate, "Number of simplifiable ADRP + ADD")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3841d5fcdb3b56a8d1f5a9df25fc2b1e">INITIALIZE_PASS</a> (AArch64CollectLOH, "aarch64-collect-loh", AARCH64_COLLECT_LOH_NAME, false, false) static bool canAddBePartOfLOH(const MachineInstr &amp;MI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21b13dde011cf416652032cc1df8e53">canDefBePartOfLOH</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Answer the following question: Can Def be one of the definition involved in a part of a LOH? <a href="#ab21b13dde011cf416652032cc1df8e53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dfd6a2f7a029b96610f42e270317cdb">isCandidateStore</a> (const MachineInstr &amp;MI, const MachineOperand &amp;MO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction can the end of a LOH chain involving a store. <a href="#a3dfd6a2f7a029b96610f42e270317cdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee008aadbf7b28b65a0dfec67297a32c">isCandidateLoad</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction can be the end of a LOH chain involving a load. <a href="#aee008aadbf7b28b65a0dfec67297a32c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8888c83857dc3ea76e2322251b65fbb2">supportLoadFromLiteral</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction can load a litteral. <a href="#a8888c83857dc3ea76e2322251b65fbb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb9e76a3be6c20a8c72773921580fda">mapRegToGPRIndex</a> (MCRegister Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map register number to index from 0-30. <a href="#a0eb9e76a3be6c20a8c72773921580fda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae251b02643ece61176adb4ce4e93784d">handleUse</a> (const MachineInstr &amp;MI, const MachineOperand &amp;MO, LOHInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update state <span class="doxyComputerOutput">Info</span> given <span class="doxyComputerOutput">MI</span> uses the tracked register. <a href="#ae251b02643ece61176adb4ce4e93784d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29bedb450469f2260b81f5500326305">handleClobber</a> (LOHInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update state <span class="doxyComputerOutput">Info</span> given the tracked register is clobbered. <a href="#aa29bedb450469f2260b81f5500326305">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125ac2ddb35b7776daf1ed49fc6a5ad6">handleMiddleInst</a> (const MachineInstr &amp;MI, LOHInfo &amp;DefInfo, LOHInfo &amp;OpInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update state <span class="doxyComputerOutput">Info</span> given that <span class="doxyComputerOutput">MI</span> is possibly the middle instruction of an LOH involving 3 instructions. <a href="#a125ac2ddb35b7776daf1ed49fc6a5ad6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a> (const MachineInstr &amp;MI, AArch64FunctionInfo &amp;AFI, LOHInfo &amp;Info, LOHInfo *LOHInfos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update state when seeing and ADRP instruction. <a href="#a897e4640c14c6556e0b1bc06eca81134">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90cb28ef245dd02827b432caed30f710">handleRegMaskClobber</a> (const uint32_t *RegMask, MCPhysReg Reg, LOHInfo *LOHInfos)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad025b047378266c13a216920a6ec3346">handleNormalInst</a> (const MachineInstr &amp;MI, LOHInfo *LOHInfos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a1357b363f9acdd3a1d9a352e2db0e3">N_GPR_REGS</a> = 31</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of GPR registers traked by <a href="#a0eb9e76a3be6c20a8c72773921580fda">mapRegToGPRIndex()</a> <a href="#a3a1357b363f9acdd3a1d9a352e2db0e3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"aarch64-collect-loh"</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd9150891e8d102b4e00f5aa5a9a51a">AARCH64_COLLECT_LOH_NAME</a>&nbsp;&nbsp;&nbsp;"AArch64 Collect <a href="/web-llvm/docs/api/classes/llvm/linker">Linker</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmipeephole-cpp/#a2fe1d201770f2584dbb2a26cd39bb556">Optimization</a> Hint (LOH)"</td>
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

### canDefBePartOfLOH() {#ab21b13dde011cf416652032cc1df8e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canDefBePartOfLOH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Answer the following question: Can Def be one of the definition involved in a part of a LOH?</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a">llvm::AArch64II::MO_GOT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a4bee2d3457dd2d22962d67c658644125">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::runOnMachineFunction</a>.</p>

</div>
</div>

### handleADRP() {#a897e4640c14c6556e0b1bc06eca81134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleADRP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo">AArch64FunctionInfo</a> &amp; AFI, <a href="/web-llvm/docs/api/structs/lohinfo">LOHInfo</a> &amp; Info, <a href="/web-llvm/docs/api/structs/lohinfo">LOHInfo</a> * LOHInfos)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update state when seeing and ADRP instruction.</p>

<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a03324cd61d637f496c9f19984b59df94">llvm::AArch64FunctionInfo::addLOHDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#aa29bedb450469f2260b81f5500326305">handleClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a0eb9e76a3be6c20a8c72773921580fda">mapRegToGPRIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5aa629adeda58539821890f262b3a2176f">llvm::MCLOH_AdrpAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a07354bc38393a198849180ca416660dc">llvm::MCLOH_AdrpAddLdr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5abf6b5edd247e3ceb86c2f3651f82a581">llvm::MCLOH_AdrpAddStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5ae753dab61d4e2c2b32ea1fe8c9a6995d">llvm::MCLOH_AdrpAdrp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a992613461a441c18807122dac5801a84">llvm::MCLOH_AdrpLdr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a89b1c697318a08b94e8f2f6794346a51">llvm::MCLOH_AdrpLdrGot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a3c1858ef073b310b6be3e6c9bd4c2919">llvm::MCLOH_AdrpLdrGotLdr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a17609e5a8270fc80d4983921de4b8f52">llvm::MCLOH_AdrpLdrGotStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/lohinfo/#a453908066162ea515d123e1a555f84be">LOHInfo::MultiUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0270bdca4aeb43f39bf91c900a398057">llvm::next_nodbg</a>, <a href="/web-llvm/docs/api/structs/lohinfo/#a3b6fb6984a6a36ff23c2f654d7432781">LOHInfo::OneUser</a> and <a href="#a8888c83857dc3ea76e2322251b65fbb2">supportLoadFromLiteral</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a4bee2d3457dd2d22962d67c658644125">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::runOnMachineFunction</a>.</p>

</div>
</div>

### handleClobber() {#aa29bedb450469f2260b81f5500326305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleClobber (<a href="/web-llvm/docs/api/structs/lohinfo">LOHInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update state <span class="doxyComputerOutput">Info</span> given the tracked register is clobbered.</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>


<p>Referenced by <a href="#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>, <a href="#a125ac2ddb35b7776daf1ed49fc6a5ad6">handleMiddleInst</a>, <a href="#ad025b047378266c13a216920a6ec3346">handleNormalInst</a> and <a href="#a90cb28ef245dd02827b432caed30f710">handleRegMaskClobber</a>.</p>

</div>
</div>

### handleMiddleInst() {#a125ac2ddb35b7776daf1ed49fc6a5ad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool handleMiddleInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/lohinfo">LOHInfo</a> &amp; DefInfo, <a href="/web-llvm/docs/api/structs/lohinfo">LOHInfo</a> &amp; OpInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update state <span class="doxyComputerOutput">Info</span> given that <span class="doxyComputerOutput">MI</span> is possibly the middle instruction of an LOH involving 3 instructions.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa29bedb450469f2260b81f5500326305">handleClobber</a>, <a href="/web-llvm/docs/api/structs/lohinfo/#a7411c64a5c36e7dbe3536f81a5036878">LOHInfo::IsCandidate</a>, <a href="/web-llvm/docs/api/structs/lohinfo/#a65017a46ee187d10ea5a8499e64a8766">LOHInfo::LastADRP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a07354bc38393a198849180ca416660dc">llvm::MCLOH_AdrpAddLdr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5abf6b5edd247e3ceb86c2f3651f82a581">llvm::MCLOH_AdrpAddStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a992613461a441c18807122dac5801a84">llvm::MCLOH_AdrpLdr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a3c1858ef073b310b6be3e6c9bd4c2919">llvm::MCLOH_AdrpLdrGotLdr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a17609e5a8270fc80d4983921de4b8f52">llvm::MCLOH_AdrpLdrGotStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/lohinfo/#a8622219f1ae97a2925ad94e3d358c679">LOHInfo::MI1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a">llvm::AArch64II::MO_GOT</a>, <a href="/web-llvm/docs/api/structs/lohinfo/#a3b6fb6984a6a36ff23c2f654d7432781">LOHInfo::OneUser</a> and <a href="/web-llvm/docs/api/structs/lohinfo/#a0965ae588ba0cc9e5771339308611f9c">LOHInfo::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a4bee2d3457dd2d22962d67c658644125">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::runOnMachineFunction</a>.</p>

</div>
</div>

### handleNormalInst() {#ad025b047378266c13a216920a6ec3346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleNormalInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/structs/lohinfo">LOHInfo</a> * LOHInfos)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="#aa29bedb450469f2260b81f5500326305">handleClobber</a>, <a href="#a90cb28ef245dd02827b432caed30f710">handleRegMaskClobber</a>, <a href="#ae251b02643ece61176adb4ce4e93784d">handleUse</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="#a0eb9e76a3be6c20a8c72773921580fda">mapRegToGPRIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a4bee2d3457dd2d22962d67c658644125">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::runOnMachineFunction</a>.</p>

</div>
</div>

### handleRegMaskClobber() {#a90cb28ef245dd02827b432caed30f710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleRegMaskClobber (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * RegMask, <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> Reg, <a href="/web-llvm/docs/api/structs/lohinfo">LOHInfo</a> * LOHInfos)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a>, <a href="#aa29bedb450469f2260b81f5500326305">handleClobber</a>, <a href="#a0eb9e76a3be6c20a8c72773921580fda">mapRegToGPRIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#ad025b047378266c13a216920a6ec3346">handleNormalInst</a>.</p>

</div>
</div>

### handleUse() {#ae251b02643ece61176adb4ce4e93784d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/structs/lohinfo">LOHInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update state <span class="doxyComputerOutput">Info</span> given <span class="doxyComputerOutput">MI</span> uses the tracked register.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="#aee008aadbf7b28b65a0dfec67297a32c">isCandidateLoad</a>, <a href="#a3dfd6a2f7a029b96610f42e270317cdb">isCandidateStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5aa629adeda58539821890f262b3a2176f">llvm::MCLOH_AdrpAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5abf6b5edd247e3ceb86c2f3651f82a581">llvm::MCLOH_AdrpAddStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a992613461a441c18807122dac5801a84">llvm::MCLOH_AdrpLdr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5a89b1c697318a08b94e8f2f6794346a51">llvm::MCLOH_AdrpLdrGot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a">llvm::AArch64II::MO_GOT</a>.</p>


<p>Referenced by <a href="#ad025b047378266c13a216920a6ec3346">handleNormalInst</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a3841d5fcdb3b56a8d1f5a9df25fc2b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (AArch64CollectLOH, "aarch64-collect-loh", <a href="#a0fd9150891e8d102b4e00f5aa5a9a51a">AARCH64_COLLECT_LOH_NAME</a>, false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="#a0fd9150891e8d102b4e00f5aa5a9a51a">AARCH64_COLLECT_LOH_NAME</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isCandidateLoad() {#aee008aadbf7b28b65a0dfec67297a32c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCandidateLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction can be the end of a LOH chain involving a load.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71a4144c2ee93286fba09bd8f14fb11f27a">llvm::AArch64II::MO_GOT</a>.</p>


<p>Referenced by <a href="#ae251b02643ece61176adb4ce4e93784d">handleUse</a>.</p>

</div>
</div>

### isCandidateStore() {#a3dfd6a2f7a029b96610f42e270317cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCandidateStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction can the end of a LOH chain involving a store.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0c893675dfd5d1b1e4aea1e8211217c7">llvm::MachineOperand::getOperandNo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#ae251b02643ece61176adb4ce4e93784d">handleUse</a>.</p>

</div>
</div>

### mapRegToGPRIndex() {#a0eb9e76a3be6c20a8c72773921580fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int mapRegToGPRIndex (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map register number to index from 0-30.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>References <a href="#a3a1357b363f9acdd3a1d9a352e2db0e3">N_GPR_REGS</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>, <a href="#ad025b047378266c13a216920a6ec3346">handleNormalInst</a>, <a href="#a90cb28ef245dd02827b432caed30f710">handleRegMaskClobber</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a4bee2d3457dd2d22962d67c658644125">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::runOnMachineFunction</a>.</p>

</div>
</div>

### STATISTIC() {#a16fdc3d75073a2089c545c82ecc31425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumADRPSimpleCandidate, "Number of simplifiable ADRP dominate by another")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aeacc3685f494c8ceaf4f26610d71b324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumADDToSTR, "Number of simplifiable STR reachable by ADD")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a4000367668b691b8c0e25e9f45161b95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumLDRToSTR, "Number of simplifiable STR reachable by LDR")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a308807550c461f87ac12ca303bf72a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumADDToLDR, "Number of simplifiable LDR reachable by ADD")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a7b16b527003ed237dbd752b389a4762f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumLDRToLDR, "Number of simplifiable LDR reachable by LDR")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a8e352868bdc1d4de5adc71e675aa3acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumADRPToLDR, "Number of simplifiable LDR reachable by ADRP")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a00b41f1c9cdddc6ef8ad6042e2c7126a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumADRSimpleCandidate, "Number of simplifiable ADRP + ADD")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>

</div>
</div>

### supportLoadFromLiteral() {#a8888c83857dc3ea76e2322251b65fbb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool supportLoadFromLiteral (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given instruction can load a litteral.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### N\_GPR\_REGS {#a3a1357b363f9acdd3a1d9a352e2db0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned N_GPR_REGS = 31</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of GPR registers traked by <a href="#a0eb9e76a3be6c20a8c72773921580fda">mapRegToGPRIndex()</a></p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Referenced by <a href="#a0eb9e76a3be6c20a8c72773921580fda">mapRegToGPRIndex</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a4bee2d3457dd2d22962d67c658644125">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### AARCH64\_COLLECT\_LOH\_NAME {#a0fd9150891e8d102b4e00f5aa5a9a51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AARCH64_COLLECT_LOH_NAME&nbsp;&nbsp;&nbsp;"AArch64 Collect <a href="/web-llvm/docs/api/classes/llvm/linker">Linker</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmipeephole-cpp/#a2fe1d201770f2584dbb2a26cd39bb556">Optimization</a> Hint (LOH)"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a8ea04a740ed547155325db2b415f9380">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::getPassName</a> and <a href="#a3841d5fcdb3b56a8d1f5a9df25fc2b1e">INITIALIZE_PASS</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"aarch64-collect-loh"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp">AArch64CollectLOH.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
