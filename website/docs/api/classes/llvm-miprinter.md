---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/miprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MIPrinter` Class

<p>This class prints out the machine instructions using the MIR serialization format. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MIPrinter { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36fd46274375ba57de306d9d68ade853">MIPrinter</a> (raw_ostream &amp;OS, ModuleSlotTracker &amp;MST, const DenseMap&lt; const uint32_t *, unsigned &gt; &amp;RegisterMaskIds, const DenseMap&lt; int, FrameIndexOperand &gt; &amp;StackObjectOperandMapping)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3217d1ff332f5c57cf87c02208afb5cc">print</a> (const MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a4f7f4a86744121b96bfb651c60567">print</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7c297367c0cce1855e484d15703b759">printStackObjectReference</a> (int FrameIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dec8c3931e753255d1e88ab0216e629">print</a> (const MachineInstr &amp;MI, unsigned OpIdx, const TargetRegisterInfo *TRI, const TargetInstrInfo *TII, bool ShouldPrintRegisterTies, LLT TypeToPrint, bool PrintDef=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0c87d9c3eb266f47d31e114de1e835">canPredictBranchProbabilities</a> (const MachineBasicBlock &amp;MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795229c1729285a509bb13a2cccbbb36">canPredictSuccessors</a> (const MachineBasicBlock &amp;MBB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a9c747153bd0591b670408072645a89">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8099b8784dfd0892187d705c268db6d3">MST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *, unsigned &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9ee537e268db23ffa792f15070b59a">RegisterMaskIds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, FrameIndexOperand &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4be1daa9fb5911d748e206dd0a52bf6">StackObjectOperandMapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882072d70081c9756062322de78b91c1">SSNs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Synchronization scope names registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#a882072d70081c9756062322de78b91c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class prints out the machine instructions using the MIR serialization format.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MIPrinter() {#a36fd46274375ba57de306d9d68ade853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIPrinter::MIPrinter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *, unsigned &gt; &amp; RegisterMaskIds, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, FrameIndexOperand &gt; &amp; StackObjectOperandMapping)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### print() {#a3217d1ff332f5c57cf87c02208afb5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIPrinter::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">llvm::MachineInstr::BundledSucc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a3217d1ff332f5c57cf87c02208afb5cc">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e30e18d6f7ebd943eaf8ebc3a2b2930">llvm::PrintLaneMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a55df99d8362d83a10b9fb35fd5b8cf7caf29bf9642eaca6e0619977346c03efd8">llvm::MachineBasicBlock::PrintNameAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a55df99d8362d83a10b9fb35fd5b8cf7cac13a649d6c2087dca8873a8edd4d3c8d">llvm::MachineBasicBlock::PrintNameIr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#ac7ff44093d66da87e6bc5b91d257af04">SimplifyMIR</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a3217d1ff332f5c57cf87c02208afb5cc">print</a>, <a href="#ac9a4f7f4a86744121b96bfb651c60567">print</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### print() {#ac9a4f7f4a86744121b96bfb651c60567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIPrinter::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518ab9f2d292718c407a75b2f2c829c1c874">llvm::MachineInstr::Disjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4802af6d0cf3b900adb6296bccedf2a0">llvm::MachineInstr::FmAfn</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a43892bfec2e4bb79639d4b4f1cf28ae8">llvm::MachineInstr::FmArcp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a9a1da4c7c2a2a2ed0d083327dd28277c">llvm::MachineInstr::FmContract</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a45ffd15293a16979f698cec4e2c60ad0">llvm::MachineInstr::FmNoInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518aba11aa58176a446ba70d4f0ad0e04418">llvm::MachineInstr::FmNoNans</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518adc42a7d40f8bd9c7f1a9c2beb0135fdc">llvm::MachineInstr::FmNsz</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a7e452f6e23b696b4701cb18790b32992">llvm::MachineInstr::FmReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">llvm::MachineInstr::FrameDestroy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1a2592a2154d9272614c7d626f3dd991">llvm::MachineInstr::IsExact</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a09808ae32b91764194984d6892e40a2e">llvm::MachineInstr::NoConvergent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1cf224b3316c689f4735877ef0bbd893">llvm::MachineInstr::NoFPExcept</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4a1592bf2f68ec050798e3aeb6a7b095">llvm::MachineInstr::NoMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a3453657a772c3023f6ef942525db0d5d">llvm::MachineInstr::NonNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518aefc960a99fa4cefc28a0ea76de0a0535">llvm::MachineInstr::NoSWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1eb5c75dbc40abd0d7998aeefd1c758b">llvm::MachineInstr::NoUSWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a16996c70759af20709e11bec0f30a14b">llvm::MachineInstr::NoUWrap</a>, <a href="#a3217d1ff332f5c57cf87c02208afb5cc">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a5df32a1d74f9239efcf9964d4217d818">PrintLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af04079051720988fb6801f962d034e03">llvm::MachineOperand::printSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518ae6a23fd6cabf87a0e53689d9b18620ad">llvm::MachineInstr::SameSign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a87ff88efff0f69c3e3f902410756ddef">llvm::MachineInstr::Unpredictable</a>.</p>

</div>
</div>

### print() {#a0dec8c3931e753255d1e88ab0216e629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIPrinter::print (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, bool ShouldPrintRegisterTies, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> TypeToPrint, bool PrintDef=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a522bea49be1b962630444a1c924d7ec5">formatOperandComment</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#abb1344e353958db14e66ec7ab574001a">llvm::StringRef::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">llvm::MachineOperand::MO_BlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba0270d8f468e7b92dafb486293ecf137d">llvm::MachineOperand::MO_CFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba5cc9e17457a92caa963ed784d83f6233">llvm::MachineOperand::MO_CImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">llvm::MachineOperand::MO_ConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba87cf4128c65c3799c2189ceb3fb62bd3">llvm::MachineOperand::MO_DbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">llvm::MachineOperand::MO_ExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639bac4edc21072344f5aafa2a8f307c78b81">llvm::MachineOperand::MO_FPImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba97561985119c4a774e3ec6439240fa80">llvm::MachineOperand::MO_FrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba9f104d16987b5384042276466fc2e003">llvm::MachineOperand::MO_IntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">llvm::MachineOperand::MO_JumpTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">llvm::MachineOperand::MO_MachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba17c8e891dacb2adc4a2d0ee5b10d6e9f">llvm::MachineOperand::MO_MCSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639babf35c1c1ff9daae15b2dff8efa224623">llvm::MachineOperand::MO_Metadata</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3ab395cc24292a5e8e499e48f1553d94">llvm::MachineOperand::MO_Predicate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639bac72cbca4074e0bc4a26afc03db602da5">llvm::MachineOperand::MO_RegisterLiveOut</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba48257b48932e88a230caff68469fd9f6">llvm::MachineOperand::MO_RegisterMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba512cc7de4a9ee26228ed614f8447d760">llvm::MachineOperand::MO_ShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639babb48fd8c9fa828e23f5d33f46cb0cbbb">llvm::MachineOperand::MO_TargetIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp/#a98b3f72dd143c6cf275022dcef2dc161">printCustomRegMask</a>, <a href="#aa7c297367c0cce1855e484d15703b759">printStackObjectReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2c59687e1086bf24ffa307eaee13c3d3">llvm::MachineOperand::printSubRegIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bdc6bcbf7eec4329ba1b6c91ff776d8">llvm::MachineOperand::printTargetFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### printStackObjectReference() {#aa7c297367c0cce1855e484d15703b759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MIPrinter::printStackObjectReference (int FrameIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2c42d0e762a9efb66e50b7f349ee4207">llvm::MachineOperand::printStackObjectReference</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a> and <a href="#a0dec8c3931e753255d1e88ab0216e629">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canPredictBranchProbabilities() {#a2d0c87d9c3eb266f47d31e114de1e835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIPrinter::canPredictBranchProbabilities (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

### canPredictSuccessors() {#a795229c1729285a509bb13a2cccbbb36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MIPrinter::canPredictSuccessors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MST {#a8099b8784dfd0892187d705c268db6d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSlotTracker&amp; llvm::MIPrinter::MST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

### OS {#a3a9c747153bd0591b670408072645a89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::MIPrinter::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

### RegisterMaskIds {#adf9ee537e268db23ffa792f15070b59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt;const uint32_t *, unsigned&gt;&amp; llvm::MIPrinter::RegisterMaskIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

### SSNs {#a882072d70081c9756062322de78b91c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;StringRef, 8&gt; llvm::MIPrinter::SSNs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Synchronization scope names registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

### StackObjectOperandMapping {#ab4be1daa9fb5911d748e206dd0a52bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseMap&lt;int, FrameIndexOperand&gt;&amp; llvm::MIPrinter::StackObjectOperandMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/mirprinter-cpp">MIRPrinter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
