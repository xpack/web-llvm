---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `HexagonMCInstLower.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-h">HexagonAsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcexpr-h">MCTargetDesc/HexagonMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">MCTargetDesc/HexagonMCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">MCTargetDesc/HexagonMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
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

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a> (const MachineOperand &amp;MO, const MCSymbol *Symbol, HexagonAsmPrinter &amp;Printer, bool MustExtend)</td>
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

### GetSymbolRef() {#a5d48c2fbd54413cd08a7ada69f05e7f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand GetSymbolRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter">HexagonAsmPrinter</a> &amp; Printer, bool MustExtend)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp">HexagonMCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/hexagonmcexpr/#a81566bd7394be9eb4df918513ea11b9b">llvm::HexagonMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015af8e9710c7d5ec4bbaf58b6cda231cbfc">llvm::HexagonII::HMOTF_ConstExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8eb9bf17230a1c4329e26935f44d72eb">llvm::MachineOperand::isJTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015ac47ffaa169a1f69f25379a5255772ede">llvm::HexagonII::MO_GDGOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015a385d0c15ee4b6599b17220ae9c4e1721">llvm::HexagonII::MO_GDPLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015ad3aec67f5ecec6269701ba7bc6eb62bc">llvm::HexagonII::MO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015af900f84c52797ab78621c177e9f4c11c">llvm::HexagonII::MO_GPREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015a3a8e839d376fa2e3dae562779b074436">llvm::HexagonII::MO_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015a99716b904314fdf0bc051a08783ae2ee">llvm::HexagonII::MO_IE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015aaf2427120b8c9e98eacca4725e18fa05">llvm::HexagonII::MO_IEGOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015a1ec50691c238a910cc07b23749270c88">llvm::HexagonII::MO_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015a9ae5c2988c1808a45aa1c19c43e7413a">llvm::HexagonII::MO_PCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#ae6671c2e6222df7b72d9ff1399eea015a8a187914ba23d68f03c027904ca058cc">llvm::HexagonII::MO_TPREL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aedeada7604ef9521d3aec4ec5441811c">llvm::HexagonMCInstrInfo::setMustExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a7de84847ab4ad2a218fefb78e952e6ab">llvm::MCSymbolRefExpr::VK_Hexagon_GD_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a935589a2c56d70c003eaec114c908fae">llvm::MCSymbolRefExpr::VK_Hexagon_GD_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a5bb196f8bf15a224cdb60b96cbec0d2e">llvm::MCSymbolRefExpr::VK_Hexagon_GPREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0b9581b7a8c98210fca1a88eb050c7e7">llvm::MCSymbolRefExpr::VK_Hexagon_HI16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a76148043f2fa1509f2b55b6472eeac7f">llvm::MCSymbolRefExpr::VK_Hexagon_IE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab09b72e3f9139ae88ba205eabfb79c4a">llvm::MCSymbolRefExpr::VK_Hexagon_IE_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4e7973f3204bb0bc6c0d6d37341af6e5">llvm::MCSymbolRefExpr::VK_Hexagon_LO16</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a97666c9a886a80de41f6ef1b61a528c7">llvm::MCSymbolRefExpr::VK_PCREL</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa12b324430d5f16b6a4e1f965048c38a">llvm::MCSymbolRefExpr::VK_TPREL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
