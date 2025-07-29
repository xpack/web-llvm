---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LanaiAsmPrinter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is intended to be used as a driving class for all asm writers. <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebbf718fe08a4d635492c64593ac8abc">LanaiAsmPrinter</a> (TargetMachine &amp;TM, std::unique_ptr&lt; MCStreamer &gt; Streamer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7156c5c53a46b0c4c535a2c6e1ec7e4f">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a7156c5c53a46b0c4c535a2c6e1ec7e4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb05d49b5f0228bba4b29a4a0806756">printOperand</a> (const MachineInstr *MI, int OpNum, raw_ostream &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad9f20f96b8ee1142e75c4e7a5a9c9d">PrintAsmOperand</a> (const MachineInstr *MI, unsigned OpNo, const char *ExtraCode, raw_ostream &amp;O) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant. <a href="#a2ad9f20f96b8ee1142e75c4e7a5a9c9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addac8abf0eaf8f3b19bd75fafaa19931">emitInstruction</a> (const MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets should implement this to emit instructions. <a href="#addac8abf0eaf8f3b19bd75fafaa19931">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0aa6192df6f64fe70ce2d8f15fb4b1b">isBlockOnlyReachableByFallthrough</a> (const MachineBasicBlock *MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the basic block has exactly one predecessor and the control transfer mechanism between the predecessor and this block is a fall-through. <a href="#ad0aa6192df6f64fe70ce2d8f15fb4b1b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4953060f1a1da8c385c46c50813bb067">customEmitInstruction</a> (const MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff0c291f506887224a3a8d7e9119c1d3">emitCallInstruction</a> (const MachineInstr *MI)</td>
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


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LanaiAsmPrinter() {#aebbf718fe08a4d635492c64593ac8abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::LanaiAsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; Streamer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#afcfe4636c15aaef711e33ecc8638f9b4">llvm::AsmPrinter::AsmPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitInstruction() {#addac8abf0eaf8f3b19bd75fafaa19931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LanaiAsmPrinter::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Targets should implement this to emit instructions.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aebe7e48735a59049062e384e810c108a">llvm::AsmPrinter::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getPassName() {#a7156c5c53a46b0c4c535a2c6e1ec7e4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::getPassName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a>.</p>

</div>
</div>

### isBlockOnlyReachableByFallthrough() {#ad0aa6192df6f64fe70ce2d8f15fb4b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LanaiAsmPrinter::isBlockOnlyReachableByFallthrough (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the basic block has exactly one predecessor and the control transfer mechanism between the predecessor and this block is a fall-through.</p>


<p>isBlockOnlyReachableByFallthough - Return true if the basic block has exactly one predecessor and the control transfer mechanism between the predecessor and this block is a fall-through.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5e81f1acc479086310c4e522a0fca54c">llvm::AsmPrinter::isBlockOnlyReachableByFallthrough</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### PrintAsmOperand() {#a2ad9f20f96b8ee1142e75c4e7a5a9c9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LanaiAsmPrinter::PrintAsmOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ExtraCode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant.</p>


<p>PrintAsmOperand - Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant.</p>


<p>Targets should override this to format as appropriate. This method can return true if the operand is erroneous.</p>


<p>Targets should override this to format as appropriate for machine specific ExtraCodes or when the arch-independent handling would be too complex otherwise.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a3fd7cca4c0d57853e9fa3c29be7f83d4">llvm::LanaiInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af865b91965a6c4e1082d1510228db5b5">llvm::AsmPrinter::PrintAsmOperand</a> and <a href="#accb05d49b5f0228bba4b29a4a0806756">printOperand</a>.</p>

</div>
</div>

### printOperand() {#accb05d49b5f0228bba4b29a4a0806756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LanaiAsmPrinter::printOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, int OpNum, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a94f5b10f666acf5a0cddd5ac8302d0b8">llvm::MachineOperand::getBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ae285dffa957552fa3fe1d34e1bcb7963">llvm::AsmPrinter::GetBlockAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaac6d709ea6a14a69a632a3685936c92">llvm::AsmPrinter::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a848e97da70c9a3e915855fc0cdaf19a8">llvm::AsmPrinter::getFunctionNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstprinter/#a3fd7cca4c0d57853e9fa3c29be7f83d4">llvm::LanaiInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1cc134bd22a318835dc929323da70ea4">llvm::MachineBasicBlock::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab59b255f78cd503133d032152a41d105">llvm::MachineOperand::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab313591ae4ea1e3a4ab59121a7dc2a2b">llvm::MachineOperand::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a47692fd7344d1adc2916ad4cc31d26c8">llvm::AsmPrinter::MAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">llvm::MachineOperand::MO_BlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">llvm::MachineOperand::MO_ConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">llvm::MachineOperand::MO_ExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">llvm::MachineOperand::MO_JumpTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">llvm::MachineOperand::MO_MachineBasicBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>.</p>


<p>Referenced by <a href="#a2ad9f20f96b8ee1142e75c4e7a5a9c9d">PrintAsmOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### customEmitInstruction() {#a4953060f1a1da8c385c46c50813bb067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LanaiAsmPrinter::customEmitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a>.</p>

</div>
</div>

### emitCallInstruction() {#aff0c291f506887224a3a8d7e9119c1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LanaiAsmPrinter::emitCallInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp">LanaiAsmPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
