---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RISCVAsmPrinter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">MCTargetDesc/RISCVBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvinstprinter-h">MCTargetDesc/RISCVInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmcexpr-h">MCTargetDesc/RISCVMCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmatint-h">MCTargetDesc/RISCVMatInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvtargetstreamer-h">MCTargetDesc/RISCVTargetStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscv-h">RISCV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvconstantpoolvalue-h">RISCVConstantPoolValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmachinefunctioninfo-h">RISCVMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvregisterinfo-h">RISCVRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/targetinfo/riscvtargetinfo-h">TargetInfo/RISCVTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/asmprinter-h">llvm/CodeGen/AsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">llvm/CodeGen/MachineConstantPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">llvm/MC/MCInstBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcobjectfileinfo-h">llvm/MC/MCObjectFileInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionelf-h">llvm/MC/MCSectionELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/riscvisainfo-h">llvm/TargetParser/RISCVISAInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/hwaddresssanitizer-h">llvm/Transforms/Instrumentation/HWAddressSanitizer.h</a>"
#include "RISCVGenMCPseudoLowering.inc"
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-riscvasmprinter-cpp-">anonymous{RISCVAsmPrinter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter">RISCVAsmPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad52947e811c73a4bad69d9134cd37ac5">STATISTIC</a> (RISCVNumInstrsCompressed, "Number of RISC-V Compressed instructions emitted")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27824c12da09de79ef94151cccf77eda">LLVMInitializeRISCVAsmPrinter</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a> (const MachineOperand &amp;MO, MCSymbol *Sym, const AsmPrinter &amp;AP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a> (const MachineInstr *MI, MCInst &amp;OutMI)</td>
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

</table>


<div class="doxySectionDef">

## Functions

### LLVMInitializeRISCVAsmPrinter() {#a27824c12da09de79ef94151cccf77eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeRISCVAsmPrinter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp">RISCVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3568b368ff108cf4afed7b8ae32ded70">llvm::getTheRISCV32Target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab86cdf9a38a9729ea849bcb012fc075d">llvm::getTheRISCV64Target</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### lowerRISCVVMachineInstrToMCInst() {#af3b87eccd7dfd84ba438253014223161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool lowerRISCVVMachineInstrToMCInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; OutMI)</td>
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



<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp">RISCVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#ad1484b3b6dbf33deb1c526d456f1d256">llvm::RISCVSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0ca904e64ee29c8812ed34e632d3c947">llvm::MCInstrDesc::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a7695bd2e20788ffc4b645533c018f26e">llvm::MCInstrDesc::getOperandConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#ac548025beac55d0f686dab8fa015e968">llvm::RISCVSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab313591ae4ea1e3a4ab59121a7dc2a2b">llvm::MachineOperand::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a2c1654a9deec21b9a081a20a01833948">llvm::RISCVII::hasRoundModeOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#afc858f8e35813be95df97504afd771ef">llvm::RISCVII::hasSEWOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ad330ee2b7583cf1bf0a79f69c23ce6fe">llvm::RISCVII::hasVecPolicyOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a81c11c8178c6df7f55ef0557daa54765">llvm::RISCVII::hasVLOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ab168f2f439a9450cdc1525d381d4d6ea">llvm::RISCV::isFaultFirstLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a894030fbf6d0f6c70991f05fff650930">llvm::MachineOperand::isTied</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a49f5aa4a0ff198123f76f55f0670139a">llvm::RISCVII::isTiedPseudo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca2ce62e1cd502db9d1a7a8295164f6584">llvm::RVV</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### lowerSymbolOperand() {#a931cec5e0b9faa60b9b6943de522e49b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand lowerSymbolOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> &amp; AP)</td>
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



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp">RISCVAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a113007d7338e79e7c4ebfec41a5b733a">llvm::RISCVMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8eb9bf17230a1c4329e26935f44d72eb">llvm::MachineOperand::isJTI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afe1784e242ce66da6029b3a681896bd2">llvm::MachineOperand::isMBB</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62a5c3971e24b86ff0172b94caf1cdae609">llvm::RISCVII::MO_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62aa2a1abfb3c0e021a6bb289ab34cda0eb">llvm::RISCVII::MO_GOT_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62ae4723860788b05182a95427d44b40beb">llvm::RISCVII::MO_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62af86137b2ce51cd877b329efd691375e4">llvm::RISCVII::MO_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62a46cb12a82b20834632896cf7d39a74ee">llvm::RISCVII::MO_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62a48e6dd53f1fe18894e54b247172b1080">llvm::RISCVII::MO_PCREL_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62a4df61c725b8277557e89407b7276197f">llvm::RISCVII::MO_PCREL_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62ae945f0e9c4a00103c349b8b98740ce6b">llvm::RISCVII::MO_TLS_GD_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62aa252bd6ac43fc20cf53c51d0c5930713">llvm::RISCVII::MO_TLS_GOT_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62a6685b50e2d349f607fe793d7619bad8a">llvm::RISCVII::MO_TLSDESC_ADD_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62a4e78b4d445c3a6f9c3f5157d06f2dba5">llvm::RISCVII::MO_TLSDESC_CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62afb77e9de3cd98e07ec412d3fcc28dbea">llvm::RISCVII::MO_TLSDESC_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62ab8818c2fa820cc51b6557b55e3927731">llvm::RISCVII::MO_TLSDESC_LOAD_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62afe1523507536407f4e68e020cb1a8a4e">llvm::RISCVII::MO_TPREL_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62a578b9893069058852e212bc06bdbb6f0">llvm::RISCVII::MO_TPREL_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a45d4f176e9191f946715cf4673af6e62ada8456db599116079f21a0c7cd4803a3">llvm::RISCVII::MO_TPREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a7f0a2ade0160be4082351dd594bfab25">llvm::RISCVMCExpr::VK_RISCV_CALL_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6af53e7457e88370f76455f7cf9c525a8f">llvm::RISCVMCExpr::VK_RISCV_GOT_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6ab5c3ca301e449ab85f42444601bba378">llvm::RISCVMCExpr::VK_RISCV_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a3c930f90b860b3ff02df7bd420c1f89e">llvm::RISCVMCExpr::VK_RISCV_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a380387ebfe7e093c92941ec73b8a2557">llvm::RISCVMCExpr::VK_RISCV_PCREL_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a4b697ccb4bf41db17dc4422189098f55">llvm::RISCVMCExpr::VK_RISCV_PCREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a739b9795700df7ae19816f89508f1b49">llvm::RISCVMCExpr::VK_RISCV_TLS_GD_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a17c514839d8a0aca51f132e5dae74967">llvm::RISCVMCExpr::VK_RISCV_TLS_GOT_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a563b259281b6f3e45a89bb1784036aec">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_ADD_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6ae5770558120b3a15fc80a83e0532dc22">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6aada38a4713e0b102bd6c05f34926f896">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a5e718279c4aba4b5032b0e4ae1435db7">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_LOAD_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a9396ec898399370b727b35de80497248">llvm::RISCVMCExpr::VK_RISCV_TPREL_ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a28a380cf34cda5c68bbe50aa22378bb1">llvm::RISCVMCExpr::VK_RISCV_TPREL_HI</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a1cfe2bb904199433c2ef567b6227db8c">llvm::RISCVMCExpr::VK_RISCV_TPREL_LO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>.</p>

</div>
</div>

### STATISTIC() {#ad52947e811c73a4bad69d9134cd37ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (RISCVNumInstrsCompressed, "Number of RISC-V Compressed <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> emitted")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp">RISCVAsmPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae51d584e6bd7deb9a5ae3cca19625641">llvm::RISCVFeatureKV</a>.</p>

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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp">RISCVAsmPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
