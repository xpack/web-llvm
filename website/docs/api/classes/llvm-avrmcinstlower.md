---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrmcinstlower
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AVRMCInstLower` Class

<p>Lowers <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></span> objects into <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a></span> objects. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRMCInstLower { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-h">Target/AVR/AVRMCInstLower.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a0a1955f1d357611385f57dbedb5a6">AVRMCInstLower</a> (MCContext &amp;Ctx, AsmPrinter &amp;Printer)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a984878b12749e1f06574b379915f8524">lowerInstruction</a> (const MachineInstr &amp;MI, MCInst &amp;OutMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lowers a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></span> into a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a></span>. <a href="#a984878b12749e1f06574b379915f8524">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb4de1517ebc1f8095f87eef68f290f7">lowerSymbolOperand</a> (const MachineOperand &amp;MO, MCSymbol *Sym, const AVRSubtarget &amp;Subtarget) const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1eef62f9ed6f6866aa64e92eea145b">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e38b3a124831e1525b15490f4d32058">Printer</a></td>
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

<p>Lowers <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></span> objects into <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a></span> objects.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-h">AVRMCInstLower.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AVRMCInstLower() {#a72a0a1955f1d357611385f57dbedb5a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRMCInstLower::AVRMCInstLower (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp; Printer)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-h">AVRMCInstLower.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lowerInstruction() {#a984878b12749e1f06574b379915f8524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMCInstLower::lowerInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; OutMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lowers a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></span> into a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a></span>.</p>

<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-h">AVRMCInstLower.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-cpp">AVRMCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#acb4de1517ebc1f8095f87eef68f290f7">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">llvm::MachineOperand::MO_BlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">llvm::MachineOperand::MO_ConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">llvm::MachineOperand::MO_ExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">llvm::MachineOperand::MO_JumpTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">llvm::MachineOperand::MO_MachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba48257b48932e88a230caff68469fd9f6">llvm::MachineOperand::MO_RegisterMask</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a0a552fd6ad20ba6d7cfe37409868c99d">llvm::AVRAsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### lowerSymbolOperand() {#acb4de1517ebc1f8095f87eef68f290f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand llvm::AVRMCInstLower::lowerSymbolOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrsubtarget">AVRSubtarget</a> &amp; Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-h">AVRMCInstLower.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-cpp">AVRMCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a06dda60009ec68b948826892b8cb5f75">llvm::AVRMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8eb9bf17230a1c4329e26935f44d72eb">llvm::MachineOperand::isJTI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avrii/#af0b01fa3c73b359837f3a7713274269aa57a5b7b4f208829b5bd00cc3ad16ded5">llvm::AVRII::MO_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avrii/#af0b01fa3c73b359837f3a7713274269aac78eef6657cad8b6d62131d926614fe8">llvm::AVRII::MO_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avrii/#af0b01fa3c73b359837f3a7713274269aab0512370caac05423652bb0aea02a9a6">llvm::AVRII::MO_NEG</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ead983bf089910d03f38c6ecfd9895f40b">llvm::AVRMCExpr::VK_AVR_HI8</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea842018630575f76fa01b12213e92e8a7">llvm::AVRMCExpr::VK_AVR_HI8_GS</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea17d68c3365d37bba98c265778c257de8">llvm::AVRMCExpr::VK_AVR_LO8</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7eabe72413cf67aa8fcadcf8f6944696211">llvm::AVRMCExpr::VK_AVR_LO8_GS</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea20904697ab7c0bfa532f2a5285321a82">llvm::AVRMCExpr::VK_AVR_PM_HI8</a> and <a href="/web-llvm/docs/api/classes/llvm/avrmcexpr/#a963c676dc0bbdb455b7d84f71f35ca7ea09e73cf360d6f7dded6a699c9d29a66f">llvm::AVRMCExpr::VK_AVR_PM_LO8</a>.</p>


<p>Referenced by <a href="#a984878b12749e1f06574b379915f8524">lowerInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctx {#a7e1eef62f9ed6f6866aa64e92eea145b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; llvm::AVRMCInstLower::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-h">AVRMCInstLower.h</a>.</p>

</div>
</div>

### Printer {#a1e38b3a124831e1525b15490f4d32058}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter&amp; llvm::AVRMCInstLower::Printer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-h">AVRMCInstLower.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-cpp">AVRMCInstLower.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrmcinstlower-h">AVRMCInstLower.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
