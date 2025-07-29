---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MipsInstPrinter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-h">MipsInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips-h">Mips.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "MipsGenAsmWriter.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned R&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a> (const MCInst &amp;MI, unsigned OpNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"asm-printer"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab949b6eb4a1dc9d5105b99bc1553088">PRINT_ALIAS_INSTR</a></td>
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

### isReg() {#a85e8dc708ae90b1129b892cb8ae1500f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned R&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp">MipsInstPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aaaf972edd3d60e198b996c65e05c4a5a">llvm::MachineInstr::changeDebugValuesDefReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#ac39168a48563b3979effd5915975ebbf">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getAddrMode2OffsetOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#abb21f77ed3dc15eb330b93b3efaa94ba">llvm::AMDGPURegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#acdf9051278b18a64c83cc047a3080de3">anonymous{LiveDebugVariables.cpp}::UserValue::getLocationNo</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonhardwareloops-cpp-/countvalue/#acea0927f100037bc2e0129fa4ff13bc8">anonymous{HexagonHardwareLoops.cpp}::CountValue::getReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a8df742095eda8b544c2c418d92821368">anonymous{LanaiAsmParser.cpp}::LanaiOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af551bfe7ee8756cbe50de3bb97478723">llvm::MachineInstr::getRegClassConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#aab2e617786f0429ea73422f70fdb0606">llvm::HexagonInstrInfo::getSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonhardwareloops-cpp-/countvalue/#a900da533fe6fedf7f9568a0a6766871d">anonymous{HexagonHardwareLoops.cpp}::CountValue::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a76f8dfae3796fd187aebe3f8f60643ec">llvm::HexagonInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a8b7067629b6a083fe938e1e73d0b505b">llvm::VEInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a53b8159ab6d09402d643d63f9927c5e8">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isADDR32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a5bf7edb8a5901ab5ffa0cb5b6622785b">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isADDR64</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a08ea1066c3f3f6b30e2ab53b39054ec3">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isAnyReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a1f47a9c9abe9710c69244ce3c2db9970">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isAR32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#aa8c51e33dab5decdddbb04b370e741ad">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isCR64</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a02e7391249985b593e5dea93679b1aed">anonymous{ARMAsmParser.cpp}::ARMOperand::isDReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a8d17f013f564103ab8efe285dd61dfb2">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isFP128</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#acd8dff833867e3509565dcc7d6b4cb3b">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isFP32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a34e94d15fd6f7842290b2a7a16b0fb18">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isFP64</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a031110e5d94f00fa5d6239e8f6fb8dae">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isGR128</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a2b878cd98af868fcdadc94c9aa220d61">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isGR32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a98681787bb59be7a983b65ae6c44fb38">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isGR64</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a370502caa01b985a9bb645268b2ba9a5">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isGRH32</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aaf41abae6cf61b825cd21826ee457b51">anonymous{ARMAsmParser.cpp}::ARMOperand::isQReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ad2eb5ae7782040f081faca112c8751a4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::isRegOrImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#ae935ea2e6ff4e91984388d460174e14f">anonymous{HexagonAsmParser.cpp}::HexagonOperand::issgp10Const</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a4a8512e3642408d1cde75268a05ffa1f">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isVR128</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#ab7f7eab11791fc5b122ea2526b2f4e2e">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isVR32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#af4d3eb61d9ad447ddbde6297b2f4b789">anonymous{SystemZAsmParser.cpp}::SystemZOperand::isVR64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a80ca145710cb63f6d1484dacf37a8620">isWaitInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afe1802220ee7c164e882ade3d80f1845">llvm::MachineInstr::mayFoldInlineAsmRegOp</a>, <a href="/web-llvm/docs/api/classes/llvm/patchpointopers/#a2c909da0edfdf49c75cc43819f44bf7b">llvm::PatchPointOpers::PatchPointOpers</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonhardwareloops-cpp-/countvalue/#a8e2ee3bf4839fcec449ee3ef01bc914d">anonymous{HexagonHardwareLoops.cpp}::CountValue::print</a>, <a href="/web-llvm/docs/api/classes/llvm/miprinter/#ac9a4f7f4a86744121b96bfb651c60567">llvm::MIPrinter::print</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac3b161ec90385105cb46a08b52139e60">llvm::MachineInstr::removeOperand</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"asm-printer"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp">MipsInstPrinter.cpp</a>.</p>

</div>
</div>

### PRINT\_ALIAS\_INSTR {#aab949b6eb4a1dc9d5105b99bc1553088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PRINT_ALIAS_INSTR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp">MipsInstPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
