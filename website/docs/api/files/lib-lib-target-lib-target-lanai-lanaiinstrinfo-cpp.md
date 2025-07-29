---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LanaiInstrInfo.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-h">LanaiInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaialucode-h">LanaiAluCode.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaicondcode-h">LanaiCondCode.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaibaseinfo-h">MCTargetDesc/LanaiBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "LanaiGenInstrInfo.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63">LPCC::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a7d4787487ef4575b07dabfed4702e9">getOppositeCondition</a> (LPCC::CondCode CC)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2ee57aa544018b7e0092782fe00170">isRedundantFlagInstr</a> (MachineInstr *CmpI, unsigned SrcReg, unsigned SrcReg2, int64_t ImmValue, MachineInstr *OI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a31513e6baee779d5e43def3403e8f">flagSettingOpcodeVariant</a> (unsigned OldOpcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7772892599289e46b96fc0f775fa0a24">canFoldIntoSelect</a> (Register Reg, const MachineRegisterInfo &amp;MRI)</td>
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

## Functions

### canFoldIntoSelect() {#a7772892599289e46b96fc0f775fa0a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * canFoldIntoSelect (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp">LanaiInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>.</p>

</div>
</div>

### flagSettingOpcodeVariant() {#a75a31513e6baee779d5e43def3403e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned flagSettingOpcodeVariant (unsigned OldOpcode)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp">LanaiInstrInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### getOppositeCondition() {#a6a7d4787487ef4575b07dabfed4702e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LPCC::CondCode getOppositeCondition (<a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63">LPCC::CondCode</a> CC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp">LanaiInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a6b459fb381cd6527b9d3ef42cd9dff94">llvm::LPCC::ICC_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a735741ae657bc89272f0ae7450083955">llvm::LPCC::ICC_CS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63ad36d0e67aa10b86b18c882bdcaf8b1e6">llvm::LPCC::ICC_EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63ae0a7df38f0c12918214e854e6deee51d">llvm::LPCC::ICC_F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a12652b0d33f1f971dbf5a4fd38bc5aff">llvm::LPCC::ICC_GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a593c3982b94c15ee37c1eedae8ad32af">llvm::LPCC::ICC_GT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63ac145e413a917503f7a67eb6bc48d04ef">llvm::LPCC::ICC_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a70d686d83ff0b4e0e35b9fb7f58baec2">llvm::LPCC::ICC_LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63addd15e46a2dd7b17ad5f9e1361894c7b">llvm::LPCC::ICC_LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63ad9d53591ae8b91e43083845563944a70">llvm::LPCC::ICC_LT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a815c7346bf7c8148f67f65c435a5b5dc">llvm::LPCC::ICC_MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a5f1cb00bb0ede601421beb828a5d4b76">llvm::LPCC::ICC_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a65ea2278be672ad82bbdd398e55a1385">llvm::LPCC::ICC_PL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a8deb801305591326bd46652c46a63af9">llvm::LPCC::ICC_T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63ab4b351de10d06667563764f4bde545ba">llvm::LPCC::ICC_VC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63ace781999f382382719a06a2980682289">llvm::LPCC::ICC_VS</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#af5365132fb67e1e49ed76284c6e0905e">llvm::LanaiInstrInfo::reverseBranchCondition</a>.</p>

</div>
</div>

### isRedundantFlagInstr() {#adf2ee57aa544018b7e0092782fe00170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRedundantFlagInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CmpI, unsigned SrcReg, unsigned SrcReg2, int64_t ImmValue, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OI)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp">LanaiInstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp">LanaiInstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
