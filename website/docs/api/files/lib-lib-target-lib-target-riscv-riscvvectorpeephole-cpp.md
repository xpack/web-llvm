---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RISCVVectorPeephole.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscv-h">RISCV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-riscvvectorpeephole-cpp-">anonymous{RISCVVectorPeephole.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-riscvvectorpeephole-cpp-/riscvvectorpeephole">RISCVVectorPeephole</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4707f2d4fe8e86f046089a400af7e72">INITIALIZE_PASS</a> (RISCVVectorPeephole, DEBUG_TYPE, "RISC-V Fold Masks", false, false) bool RISCVVectorPeephole</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></span> that has an input operand with EEW=SEW, which uses the dest operand of <span class="doxyComputerOutput">Src</span> with an unknown EEW, return true if their EEWs match. <a href="#af4707f2d4fe8e86f046089a400af7e72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1ace11555e6a74661cd750915d2c2f4">isSafeToMove</a> (const MachineInstr &amp;From, const MachineInstr &amp;To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if it's safe to move From down to To, checking that no physical registers are clobbered. <a href="#ad1ace11555e6a74661cd750915d2c2f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17ca2fbe73a5adbf622847e4b8e0b76">dominates</a> (MachineBasicBlock::const_iterator A, MachineBasicBlock::const_iterator B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given A and B are in the same MBB, returns true if A comes before B. <a href="#af17ca2fbe73a5adbf622847e4b8e0b76">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"riscv-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a>-peephole"</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08515c9d05ad97421f02d4db4ebdb037">CASE_WHOLE_REGISTER_LMUL_SEW</a>(lmul, sew)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87981629280c5af5b9190ac3baf64323">CASE_WHOLE_REGISTER_LMUL</a>(lmul)&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa677f1313d16c415226d5b409f7fa55b">CASE_VMERGE_TO_VMV</a>(lmul)&nbsp;&nbsp;&nbsp;...</td>
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

### dominates() {#af17ca2fbe73a5adbf622847e4b8e0b76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool dominates (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> A, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> B)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given A and B are in the same MBB, returns true if A comes before B.</p>

<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp">RISCVVectorPeephole.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#af4707f2d4fe8e86f046089a400af7e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (RISCVVectorPeephole, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "RISC-V Fold Masks", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></span> that has an input operand with EEW=SEW, which uses the dest operand of <span class="doxyComputerOutput">Src</span> with an unknown EEW, return true if their EEWs match.</p>


<p>Convert unit strided unmasked loads and stores to whole-register equivalents to avoid the dependency on $vl and $vtype.</p>


<p>x = PseudoVLE8_V_M1 passthru, ptr, vlmax, policy PseudoVSE8_V_M1 v, ptr, vlmax</p>


<p>-&gt;</p>


<p>x = VL1RE8_V ptr VS1R_V v, ptr</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp">RISCVVectorPeephole.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a9414834a0b1e18b5734e7d4a18eccf01">llvm::RISCV::getDestLog2EEW</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a90a55d922eac310187ebfcf9008525e5">llvm::RISCV::getRVVMCOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#af9dfac3d961f5f889f2c6d38ce89685f">llvm::RISCVII::getSEWOpNum</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### isSafeToMove() {#ad1ace11555e6a74661cd750915d2c2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSafeToMove (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; To)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if it's safe to move From down to To, checking that no physical registers are clobbered.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp">RISCVVectorPeephole.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3daf8e155bf0aa3e65b5260bfe3698c5">llvm::MachineInstr::all_uses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5879bc3bd2b8f21ba2d83a1f97a020d9">llvm::MachineInstr::hasImplicitDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3c3bece1d6d099a7b6bc4c22ea768e8e">llvm::MachineInstr::isSafeToMove</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CASE\_VMERGE\_TO\_VMV {#aa677f1313d16c415226d5b409f7fa55b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_VMERGE_TO_VMV(lmul)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::PseudoVMERGE_VVM_##lmul:                                         \
    return RISCV::PseudoVMV_V_V_##lmul;
</div>
</dd>
</dl>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp">RISCVVectorPeephole.cpp</a>.</p>

</div>
</div>

### CASE\_WHOLE\_REGISTER\_LMUL {#a87981629280c5af5b9190ac3baf64323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_WHOLE_REGISTER_LMUL(lmul)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a08515c9d05ad97421f02d4db4ebdb037">CASE_WHOLE_REGISTER_LMUL_SEW</a>(lmul, 8)                                        \
  <a href="#a08515c9d05ad97421f02d4db4ebdb037">CASE_WHOLE_REGISTER_LMUL_SEW</a>(lmul, 16)                                       \
  <a href="#a08515c9d05ad97421f02d4db4ebdb037">CASE_WHOLE_REGISTER_LMUL_SEW</a>(lmul, 32)                                       \
  <a href="#a08515c9d05ad97421f02d4db4ebdb037">CASE_WHOLE_REGISTER_LMUL_SEW</a>(lmul, 64)
</div>
</dd>
</dl>

<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp">RISCVVectorPeephole.cpp</a>.</p>

</div>
</div>

### CASE\_WHOLE\_REGISTER\_LMUL\_SEW {#a08515c9d05ad97421f02d4db4ebdb037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_WHOLE_REGISTER_LMUL_SEW(lmul, sew)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case RISCV::PseudoVLE##sew##_V_M##lmul:                                      \
    NewOpc = RISCV::VL##lmul##RE##sew##_V;                                     \
    break;                                                                     \
  case RISCV::PseudoVSE##sew##_V_M##lmul:                                      \
    NewOpc = RISCV::VS##lmul##R_V;                                             \
    break;
</div>
</dd>
</dl>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp">RISCVVectorPeephole.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"riscv-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a>-peephole"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp">RISCVVectorPeephole.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
