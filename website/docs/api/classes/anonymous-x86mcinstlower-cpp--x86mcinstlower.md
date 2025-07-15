---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86MCInstLower` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower">X86MCInstLower</a> - This class is used to lower an <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> into an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{X86MCInstLower.cpp}::X86MCInstLower { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3ca344e2aa4e849a503d098dd482e7">X86MCInstLower</a> (const MachineFunction &amp;MF, X86AsmPrinter &amp;asmprinter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7687092765d6f25890cefb856f35b881">LowerMachineOperand</a> (const MachineInstr *MI, const MachineOperand &amp;MO) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74bd673118d2cbb40d776bb1726d4c95">Lower</a> (const MachineInstr *MI, MCInst &amp;OutMI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74245f7fce2e423d6a6b11e6ec37847">GetSymbolFromOperand</a> (const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetSymbolFromOperand - Lower an MO_GlobalAddress or MO_ExternalSymbol operand to an <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a>. <a href="#af74245f7fce2e423d6a6b11e6ec37847">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55859f4a9f64b42f225c2f6c63212be5">LowerSymbolOperand</a> (const MachineOperand &amp;MO, MCSymbol *Sym) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfomacho">MachineModuleInfoMachO</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c98f9d3aa7e1d2846420c0df7a56a2c">getMachOMMI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ca97487a869fc5336c63981f7964638">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e0cf2a8d88d0c115752aa6ffd7a4bd5">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ab9a4dd8ca7d024b3af078b5233a99">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add4ffc48dc0144143a1dd405557b6b1e">MAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86asmprinter">X86AsmPrinter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ff615c8582de2b83f86ed7acd6da1f7">AsmPrinter</a></td>
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

<p><a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower">X86MCInstLower</a> - This class is used to lower an <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> into an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86MCInstLower() {#a9e3ca344e2aa4e849a503d098dd482e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86MCInstLower::X86MCInstLower (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter">X86AsmPrinter</a> &amp; asmprinter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### GetSymbolFromOperand() {#af74245f7fce2e423d6a6b11e6ec37847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * X86MCInstLower::GetSymbolFromOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetSymbolFromOperand - Lower an MO_GlobalAddress or MO_ExternalSymbol operand to an <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a>.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfocoff/#a1719f8bc4109ab58a8443bebf34442e6">llvm::MachineModuleInfoCOFF::getGVStubEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/pointerintpair/#ac8b55437ca130fe0c826e94e669e5d99">llvm::PointerIntPair&lt; PointerTy, IntBits, IntType, PtrTraits, Info &gt;::getPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1cc134bd22a318835dc929323da70ea4">llvm::MachineBasicBlock::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab59b255f78cd503133d032152a41d105">llvm::MachineOperand::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a7bc292fc6d075e3ed6e68b0866ec3524">llvm::GlobalValue::hasInternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afe1784e242ce66da6029b3a681896bd2">llvm::MachineOperand::isMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7c5f0ef161b5b4dedad2e9aac9fcfee7">llvm::MachineOperand::isSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a59da9a9089b55f8b8353fda32a609457">llvm::X86II::MO_COFFSTUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a67e336d92dced7f5d76b7c82c0df184b">llvm::X86II::MO_DARWIN_NONLAZY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a4ce2d9504cacb290d7ff8ac3bfdab373">llvm::X86II::MO_DARWIN_NONLAZY_PIC_BASE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ac7366ddd1a9010fa97b002cad95c3044">llvm::X86II::MO_DLLIMPORT</a>.</p>


<p>Referenced by <a href="#a7687092765d6f25890cefb856f35b881">LowerMachineOperand</a>.</p>

</div>
</div>

### Lower() {#a74bd673118d2cbb40d776bb1726d4c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86MCInstLower::Lower (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; OutMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84ac4169d78e1c6de9b189f31b90f1c2691">llvm::X86::AddrNumOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84a8fed367c46e025e4269e9725a94391b6">llvm::X86::AddrSegmentReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad7df02a018c3a01d74738d5ba3a09e93">llvm::MCInst::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a4f3f0f12dd242748fc4c62997ae5b6b0">convertTailJumpOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a3c5c7109f398fdca515509e2284cd8c0">llvm::MCInst::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a16c971705a49e1964c2ce26c6a537650">getRetOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a780fe7b1259c076cd5abef9ce9dda01d">llvm::MCInst::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a67cfccc16f5e2e2e69d3f20804774ff9">llvm::X86::IP_HAS_AD_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a6afdb4f34129d1756d5983acde2125ea">llvm::X86::IP_HAS_REPEAT</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a7687092765d6f25890cefb856f35b881">LowerMachineOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ae0e27cbc3acd22d76564e1f3ac9b8311">llvm::X86::optimizeINCDEC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#aade8574cba756ffdc426344718ada414">llvm::X86::optimizeInstFromVEX3ToVEX2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a3e5a30d596e5e8933a926e2d14d5227f">llvm::X86::optimizeMOV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a690516c8cb802c97acc69f6363735984">llvm::X86::optimizeMOVSX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a88575ba0f198af79c61ba3a8c27a69d8">llvm::X86::optimizeShiftRotateWithImmediateOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a0256d671ff2830d0ada28b07b9c7ab25">llvm::X86::optimizeToFixedRegisterOrShortImmediateForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a76d5022aceb3599fdcaf0ef25ee3ce73">llvm::X86::optimizeVPCMPWithImmediateOneOrSix</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a80636f9f710d053d06c8de4f755255a3">llvm::MCInst::setFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>

</div>
</div>

### LowerMachineOperand() {#a7687092765d6f25890cefb856f35b881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand X86MCInstLower::LowerMachineOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a94f5b10f666acf5a0cddd5ac8302d0b8">llvm::MachineOperand::getBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af155da145e58791956c5e922e900fcb3">llvm::MachineOperand::getMCSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#af74245f7fce2e423d6a6b11e6ec37847">GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab313591ae4ea1e3a4ab59121a7dc2a2b">llvm::MachineOperand::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a55859f4a9f64b42f225c2f6c63212be5">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">llvm::MachineOperand::MO_BlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">llvm::MachineOperand::MO_ConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">llvm::MachineOperand::MO_ExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">llvm::MachineOperand::MO_JumpTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">llvm::MachineOperand::MO_MachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba17c8e891dacb2adc4a2d0ee5b10d6e9f">llvm::MachineOperand::MO_MCSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba48257b48932e88a230caff68469fd9f6">llvm::MachineOperand::MO_RegisterMask</a>.</p>


<p>Referenced by <a href="#a74bd673118d2cbb40d776bb1726d4c95">Lower</a>.</p>

</div>
</div>

### LowerSymbolOperand() {#a55859f4a9f64b42f225c2f6c63212be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCOperand X86MCInstLower::LowerSymbolOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8eb9bf17230a1c4329e26935f44d72eb">llvm::MachineOperand::isJTI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afe1784e242ce66da6029b3a681896bd2">llvm::MachineOperand::isMBB</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84aa0e6d252881afe8f7e653d8a1e0f3c4e">llvm::X86II::MO_ABS8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a59da9a9089b55f8b8353fda32a609457">llvm::X86II::MO_COFFSTUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a67e336d92dced7f5d76b7c82c0df184b">llvm::X86II::MO_DARWIN_NONLAZY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a4ce2d9504cacb290d7ff8ac3bfdab373">llvm::X86II::MO_DARWIN_NONLAZY_PIC_BASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ac7366ddd1a9010fa97b002cad95c3044">llvm::X86II::MO_DLLIMPORT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84acd532d5e95fa6d3eccc0a1175abb5efa">llvm::X86II::MO_DTPOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a9763861fde2dabda42072fbf46424e4c">llvm::X86II::MO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a739692efcf48167fdfc70d040b21670a">llvm::X86II::MO_GOTNTPOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a23bf757b117faacb20d4521a6ab42e51">llvm::X86II::MO_GOTOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ae39565b585476b7142228e439e80372e">llvm::X86II::MO_GOTPCREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a115ba6fe8930383c25e51d587e6a333b">llvm::X86II::MO_GOTPCREL_NORELAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ac7ab3243c491b3b6ff673eaf87335fe5">llvm::X86II::MO_GOTTPOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a727b000cf3292eb1594ef5ede74025e1">llvm::X86II::MO_INDNTPOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ab9508856c635578f8aaed9dd83c3f347">llvm::X86II::MO_NO_FLAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a5c1651fb93fe6b8e7f7c1207c3eba33d">llvm::X86II::MO_NTPOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84adca1e9b1551356bed7c8ef8cb0f1c471">llvm::X86II::MO_PIC_BASE_OFFSET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ab2b21d9c332e616e0a11c3ff76ce0bdf">llvm::X86II::MO_PLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ac899fad9731b612ab9c84ac157210edc">llvm::X86II::MO_SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ab79eb4639f668e99fa6389282bbc8983">llvm::X86II::MO_TLSGD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a0bfa33e5861d2bf5088c682b1ee1da85">llvm::X86II::MO_TLSLD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84ae0fcbd11eb4098cdb801f889349993c3">llvm::X86II::MO_TLSLDM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84abc06b946fa50ffaa09a13fdd648b4dbb">llvm::X86II::MO_TLVP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a75edcbd216129f693a5e2765b457f4c5">llvm::X86II::MO_TLVP_PIC_BASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a45cdfdabb3963ec52b198ce5d3aabc84a74affd0fa65b28e7359abbd4a0d08dca">llvm::X86II::MO_TPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a005feb527dcbfd0ff9cb36d5926259b5">llvm::MCSymbolRefExpr::VK_DTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a39bde642c4c205e820490b44c7c99eaf">llvm::MCSymbolRefExpr::VK_GOTNTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a4396d69feb19b053f335f9baa4fb9b62">llvm::MCSymbolRefExpr::VK_GOTOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2a25c9a7112bb84b5d93e6ab5d0d8185">llvm::MCSymbolRefExpr::VK_GOTPCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2f5bfabdc7c07641d263e7f3921de0f5">llvm::MCSymbolRefExpr::VK_GOTPCREL_NORELAX</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a8ab1ea9815c9a2bbe67f215b5ee2f680">llvm::MCSymbolRefExpr::VK_GOTTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a542605f9315d7c837ffdf0db3d36ab00">llvm::MCSymbolRefExpr::VK_INDNTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ad51962e40d9ba19993f108197dd65f57">llvm::MCSymbolRefExpr::VK_NTPOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab5951d4b3308f406e60e2bf743b14ca4">llvm::MCSymbolRefExpr::VK_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0cca43f5b196466926fb823727bd8902">llvm::MCSymbolRefExpr::VK_SECREL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985ab2e079373e7edad956ec4feb0587658e">llvm::MCSymbolRefExpr::VK_TLSGD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a2bd18a4543b4686a238d7c84cf299257">llvm::MCSymbolRefExpr::VK_TLSLD</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a3edde5344c6385f99e6b4f7606b79048">llvm::MCSymbolRefExpr::VK_TLSLDM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a5d7dc0ab54306dc5d9af486598f7d26d">llvm::MCSymbolRefExpr::VK_TLVP</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aab276e610bb8711df7b2a9565411b2f3">llvm::MCSymbolRefExpr::VK_TPOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a02786fddb19ccf9f05859236b8d4d23f">llvm::MCSymbolRefExpr::VK_X86_ABS8</a>.</p>


<p>Referenced by <a href="#a7687092765d6f25890cefb856f35b881">LowerMachineOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getMachOMMI() {#a6c98f9d3aa7e1d2846420c0df7a56a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfoMachO &amp; X86MCInstLower::getMachOMMI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AsmPrinter {#a4ff615c8582de2b83f86ed7acd6da1f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86AsmPrinter&amp; anonymous{X86MCInstLower.cpp}::X86MCInstLower::AsmPrinter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

### Ctx {#a1ca97487a869fc5336c63981f7964638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; anonymous{X86MCInstLower.cpp}::X86MCInstLower::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

### MAI {#add4ffc48dc0144143a1dd405557b6b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo&amp; anonymous{X86MCInstLower.cpp}::X86MCInstLower::MAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

### MF {#a2e0cf2a8d88d0c115752aa6ffd7a4bd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction&amp; anonymous{X86MCInstLower.cpp}::X86MCInstLower::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

### TM {#a65ab9a4dd8ca7d024b3af078b5233a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine&amp; anonymous{X86MCInstLower.cpp}::X86MCInstLower::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
