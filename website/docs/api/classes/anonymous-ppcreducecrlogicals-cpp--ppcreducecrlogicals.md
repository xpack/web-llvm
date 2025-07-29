---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PPCReduceCRLogicals` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6d156736ee3429f4f50adb9be8aff6">PPCReduceCRLogicals</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24fbb3a26fc0fcefed74db2072222bb5">lookThroughCRCopy</a> (unsigned Reg, unsigned &amp;Subreg, MachineInstr *&amp;CpDef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks through a COPY instruction to the actual definition of the CR-bit register and returns the instruction that defines it. <a href="#a24fbb3a26fc0fcefed74db2072222bb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bec670bfb8a6c8cc0cc29c248ed8a54">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a6bec670bfb8a6c8cc0cc29c248ed8a54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/crlogicalopinfo">CRLogicalOpInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e50a6a8cb928fb34cd4fde19384381">createCRLogicalOpInfo</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab30c2f24f66704c3debfd08a32e6710e">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#ab30c2f24f66704c3debfd08a32e6710e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88518f0927d642780e0fc96aac6a3679">initialize</a> (MachineFunction &amp;MFParm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76fd444f438f868d51ddd4983a1d6847">collectCRLogicals</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a4f820e50ea74a8951fd87f043029c1">handleCROp</a> (unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Contains all the implemented transformations on CR logical operations. <a href="#a6a4f820e50ea74a8951fd87f043029c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3339bc4d4b77ab994c2af1150ad6e1">splitBlockOnBinaryCROp</a> (CRLogicalOpInfo &amp;CRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splits a block that contains a CR-logical operation that feeds a branch and whose operands are produced within the block. <a href="#adb3339bc4d4b77ab994c2af1150ad6e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b8ba3e0fbdfcf8d94f245d392b8309">simplifyCode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo">PPCInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a1bb9365624e56cfc140509d58a315">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9305f49cccb3a0bc6b3fe0378bd2d423">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dc56bdd9de6870d824f6996e943b2c1">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf776c4fa8375d2e83765bb6d478d2d0">MBPI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/crlogicalopinfo">CRLogicalOpInfo</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f6a2e35b538ca028c3d5f015f1f267">AllCRLogicalOps</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd9f1179926c62e4eac34a2ba3a3a8a">isCRLogical</a> (MachineInstr &amp;MI)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0b1914a6c3fb8b017a3ec88a3346d8a">ID</a> = 0</td>
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


<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCReduceCRLogicals() {#acc6d156736ee3429f4f50adb9be8aff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::PPCReduceCRLogicals ()</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#ae0b1914a6c3fb8b017a3ec88a3346d8a">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bea571707f3bcc8dee4687debe0a697">llvm::initializePPCReduceCRLogicalsPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a912b44382cebbd70757e95dbfd9501e9">llvm::createPPCReduceCRLogicalsPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createCRLogicalOpInfo() {#ae5e50a6a8cb928fb34cd4fde19384381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCReduceCRLogicals::CRLogicalOpInfo anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::createCRLogicalOpInfo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a2f97198e249f3b493a0abed59c1de605">isBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a5eed64d1d0c1599110644d62fcdca99d">isNullary</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a24fbb3a26fc0fcefed74db2072222bb5">lookThroughCRCopy</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>

</div>
</div>

### getAnalysisUsage() {#ab30c2f24f66704c3debfd08a32e6710e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### lookThroughCRCopy() {#a24fbb3a26fc0fcefed74db2072222bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::lookThroughCRCopy (unsigned Reg, unsigned &amp; Subreg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; CpDef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks through a COPY instruction to the actual definition of the CR-bit register and returns the instruction that defines it.</p>


<p>FIXME: This currently handles what is by-far the most common case: an instruction that defines a CR field followed by a single copy of a bit from that field into a virtual register. If chains of copies need to be handled, this should have a loop until a non-copy instruction is found.</p>


<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ac6bf744f357352cde7578931007c0b6f">llvm::Register::isVirtualRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#ae5e50a6a8cb928fb34cd4fde19384381">createCRLogicalOpInfo</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a6bec670bfb8a6c8cc0cc29c248ed8a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#a19d27915595e7f0a0ef271448bcdac6f">initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectCRLogicals() {#a76fd444f438f868d51ddd4983a1d6847}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::collectCRLogicals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

### handleCROp() {#a6a4f820e50ea74a8951fd87f043029c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::handleCROp (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Contains all the implemented transformations on CR logical operations.</p>


<p>For example, a binary CR logical can be used to split a block on its inputs, a unary CR logical might be used to change the condition code on a comparison feeding it. A nullary CR logical might simply be removable if the user of the bit it [un]sets can be transformed.</p>


<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

### initialize() {#a88518f0927d642780e0fc96aac6a3679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::initialize (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MFParm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

### simplifyCode() {#a17b8ba3e0fbdfcf8d94f245d392b8309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::simplifyCode ()</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

### splitBlockOnBinaryCROp() {#adb3339bc4d4b77ab994c2af1150ad6e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::splitBlockOnBinaryCROp (<a href="/web-llvm/docs/api/structs/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/crlogicalopinfo">CRLogicalOpInfo</a> &amp; CRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Splits a block that contains a CR-logical operation that feeds a branch and whose operands are produced within the block.</p>


<p>Example: vr5&lt;def&gt; = CMPDI vr2, 0; CRRC:vr5 G8RC:vr2 vr6&lt;def&gt; = COPY vr5:sub_eq; CRBITRC:vr6 CRRC:vr5 vr7&lt;def&gt; = CMPDI vr3, 0; CRRC:vr7 G8RC:vr3 vr8&lt;def&gt; = COPY vr7:sub_eq; CRBITRC:vr8 CRRC:vr7 vr9&lt;def&gt; = CROR vr6&lt;kill&gt;, vr8&lt;kill&gt;; CRBITRC:vr9,vr6,vr8 BC vr9&lt;kill&gt;, &lt;BB#2&gt;; CRBITRC:vr9 Becomes: vr5&lt;def&gt; = CMPDI vr2, 0; CRRC:vr5 G8RC:vr2 vr6&lt;def&gt; = COPY vr5:sub_eq; CRBITRC:vr6 CRRC:vr5 BC vr6&lt;kill&gt;, &lt;BB#2&gt;; CRBITRC:vr6</p>


<p>vr7&lt;def&gt; = CMPDI vr3, 0; CRRC:vr7 G8RC:vr3 vr8&lt;def&gt; = COPY vr7:sub_eq; CRBITRC:vr8 CRRC:vr7 BC vr9&lt;kill&gt;, &lt;BB#2&gt;; CRBITRC:vr9</p>


<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllCRLogicalOps {#a39f6a2e35b538ca028c3d5f015f1f267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CRLogicalOpInfo, 16&gt; anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::AllCRLogicalOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

### MBPI {#acf776c4fa8375d2e83765bb6d478d2d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBranchProbabilityInfo* anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::MBPI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

### MF {#a9305f49cccb3a0bc6b3fe0378bd2d423}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

### MRI {#a1dc56bdd9de6870d824f6996e943b2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

### TII {#a11a1bb9365624e56cfc140509d58a315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCInstrInfo* anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isCRLogical() {#a3fd9f1179926c62e4eac34a2ba3a3a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::isCRLogical (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ae0b1914a6c3fb8b017a3ec88a3346d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PowerPC Reduce CR logical false char PPCReduceCRLogicals::ID = 0</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a>.</p>


<p>Referenced by <a href="#acc6d156736ee3429f4f50adb9be8aff6">PPCReduceCRLogicals</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp">PPCReduceCRLogicals.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
