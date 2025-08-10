---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/amdgpumcinstlower-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AMDGPUMCInstLower.cpp` File

<p>Code to lower <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> MachineInstrs to their corresponding <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcinstlower-h">AMDGPUMCInstLower.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-h">AMDGPUAsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumachinefunction-h">AMDGPUMachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpuinstprinter-h">MCTargetDesc/AMDGPUInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-h">MCTargetDesc/AMDGPUMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeemitter-h">llvm/MC/MCCodeEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectstreamer-h">llvm/MC/MCObjectStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include &lt;algorithm&gt;
#include "AMDGPUGenMCPseudoLowering.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985">MCSymbolRefExpr::VariantKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5682cbf85a288bc1a96218dfe20772e1">getVariantKind</a> (unsigned MOFlags)</td>
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

<p>Code to lower <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a> MachineInstrs to their corresponding <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>

<div class="doxySectionDef">

## Functions

### getVariantKind() {#a5682cbf85a288bc1a96218dfe20772e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolRefExpr::VariantKind getVariantKind (unsigned MOFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumcinstlower-cpp">AMDGPUMCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ade90146180a53b9d9edc077b933e70bba3e9ced1912f545db50d64c7932e9ae72">llvm::SIInstrInfo::MO_ABS32_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ade90146180a53b9d9edc077b933e70bbafe82a0bc03151bffd10d66929b1ed545">llvm::SIInstrInfo::MO_ABS32_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ade90146180a53b9d9edc077b933e70bbae1cf0b40cb6ab32eca2bb094dbf01c87">llvm::SIInstrInfo::MO_GOTPCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ade90146180a53b9d9edc077b933e70bbad2a7a2d26258b290db9b195d021623a2">llvm::SIInstrInfo::MO_GOTPCREL32_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ade90146180a53b9d9edc077b933e70bba2a19cea491a8770e242de4561299ee96">llvm::SIInstrInfo::MO_GOTPCREL32_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ade90146180a53b9d9edc077b933e70bba5330b2c3f2242c9c700f91ae1372500e">llvm::SIInstrInfo::MO_REL32_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ade90146180a53b9d9edc077b933e70bba878d31fbae9344bcf4e0b9a8928f4107">llvm::SIInstrInfo::MO_REL32_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a7aeae3effe59f76e31c990f8e19ddb59">llvm::MCSymbolRefExpr::VK_AMDGPU_ABS32_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a50b2f7c7d226c8cee497e63de5f88024">llvm::MCSymbolRefExpr::VK_AMDGPU_ABS32_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa2865b7a92bfdde40bd5232a89f95d07">llvm::MCSymbolRefExpr::VK_AMDGPU_GOTPCREL32_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8b3d7769ea4864cafc0c4b473c51e8e4">llvm::MCSymbolRefExpr::VK_AMDGPU_GOTPCREL32_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a5b4e0a90b28c09da92dfc8b971253a0c">llvm::MCSymbolRefExpr::VK_AMDGPU_REL32_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0fa9b2f75ff263e67c141233b7e6ac23">llvm::MCSymbolRefExpr::VK_AMDGPU_REL32_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">llvm::MCSymbolRefExpr::VK_GOTPCREL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#a34e3dd28fecb20679563d191667e9e9c">llvm::SystemZMCInstLower::lowerOperand</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
