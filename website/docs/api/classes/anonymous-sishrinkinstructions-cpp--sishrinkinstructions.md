---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SIShrinkInstructions` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa8a440f1be0897845fe2dffe8ee860">SIShrinkInstructions</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4969e8e07a8085b166f5b83efc5a8c">run</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0bff35148a3c442923af440c113c345">foldImmediates</a> (MachineInstr &amp;MI, bool TryToCommute=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function checks <span class="doxyComputerOutput">MI</span> for operands defined by a move immediate instruction and then folds the literal constant into the instruction if it can. <a href="#ad0bff35148a3c442923af440c113c345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a573cfa375ebf3ec9a9cf49830200d361">shouldShrinkTrue16</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do not shrink the instruction if its registers are not expressible in the shrunk encoding. <a href="#a573cfa375ebf3ec9a9cf49830200d361">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1bc55ebf72405c2472cf9e1e109b742">isKImmOperand</a> (const MachineOperand &amp;Src) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba8d004f1580c59a926d067823d09ca">isKUImmOperand</a> (const MachineOperand &amp;Src) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc80a6214b3b93dacbcfa77e27fd70cd">isKImmOrKUImmOperand</a> (const MachineOperand &amp;Src, bool &amp;IsUnsigned) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d9c525399e53f9d2ab6e6ffbbdee36">copyExtraImplicitOps</a> (MachineInstr &amp;NewMI, MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy implicit register operands from specified instruction to this instruction that are not part of the instruction definition. <a href="#a30d9c525399e53f9d2ab6e6ffbbdee36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf13a5965d697e6016c2e828192ff1b">shrinkScalarCompare</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598f4f5c82abed881dce2f86ebb66988">shrinkMIMG</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb3678b9585fc423e2f34584972de2b">shrinkMadFma</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f1944c0f1fec9c842ba7c07b84a96f2">shrinkScalarLogicOp</a> (MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to shrink AND/OR/XOR operations requiring non-inlineable literals. <a href="#a8f1944c0f1fec9c842ba7c07b84a96f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b74a07d97bb722f91b69e9f7385f0b">tryReplaceDeadSDST</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f7c685972475f9875ea8228a68a635c">instAccessReg</a> (iterator_range&lt; MachineInstr::const_mop_iterator &gt; &amp;&amp;R, Register Reg, unsigned SubReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd72dee28bba5e02345684807e187a13">instReadsReg</a> (const MachineInstr *MI, unsigned Reg, unsigned SubReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10eed6c3a3c49fdc748920361fa350da">instModifiesReg</a> (const MachineInstr *MI, unsigned Reg, unsigned SubReg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetinstrinfo/regsubregpair">TargetInstrInfo::RegSubRegPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99e1e6d5daecdd53eb23efb5b34bb23">getSubRegForIndex</a> (Register Reg, unsigned Sub, unsigned I) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a972f27eddd806efa001a7b832e64dc47">dropInstructionKeepingImpDefs</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c051d76ecba77f3bbe2e25bace05fd3">matchSwap</a> (MachineInstr &amp;MovT) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a115371590017893502e2efb4c106349d">MF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11080790cf6a7c6fc3eb942453cf442">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a325a1e98d30788d9ce20fb4a96f7e85b">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de394925b9cde09032e3e49bdd3f1ea">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe767b5b35697a0adcae7caa8e41b327">TRI</a></td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIShrinkInstructions() {#a7fa8a440f1be0897845fe2dffe8ee860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::SIShrinkInstructions ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>


<p>Reference <a href="#a2d4969e8e07a8085b166f5b83efc5a8c">run</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructionslegacy/#a28cf8ebeb9ff3ad8561898a165662ef6">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructionsLegacy::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a2d4969e8e07a8085b166f5b83efc5a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::run (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp/#aee60884f5ed993caf8f347c1497062f5">canModifyToInlineImmOp32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afc1df0cb1a8c3103a4266def94c3a670">llvm::MachineInstr::findRegisterDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a32384420526a080b93cc98ab5a023001">llvm::GCNSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#addd7333a1ddd4f2210a9870f8e2b20b0">llvm::SIInstrInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a17fda9e2f2cb60c24bfdec02d7793b86">llvm::AMDGPU::getVOPe32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a0a29519a2da61e1cf78d898e26fef446">llvm::AMDGPUSubtarget::GFX10</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a75b79141e48ddded5600396eeb38eb1c">llvm::AMDGPU::isTrue16Inst</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a7fa8a440f1be0897845fe2dffe8ee860">SIShrinkInstructions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### copyExtraImplicitOps() {#a30d9c525399e53f9d2ab6e6ffbbdee36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIShrinkInstructions::copyExtraImplicitOps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; NewMI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy implicit register operands from specified instruction to this instruction that are not part of the instruction definition.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### dropInstructionKeepingImpDefs() {#a972f27eddd806efa001a7b832e64dc47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIShrinkInstructions::dropInstructionKeepingImpDefs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### foldImmediates() {#ad0bff35148a3c442923af440c113c345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::foldImmediates (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool TryToCommute=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function checks <span class="doxyComputerOutput">MI</span> for operands defined by a move immediate instruction and then folds the literal constant into the instruction if it can.</p>


<p>This function assumes that <span class="doxyComputerOutput">MI</span> is a VOP1, VOP2, or VOPC instructions.</p>


<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### getSubRegForIndex() {#aa99e1e6d5daecdd53eb23efb5b34bb23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetInstrInfo::RegSubRegPair SIShrinkInstructions::getSubRegForIndex (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned Sub, unsigned I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### instAccessReg() {#a3f7c685972475f9875ea8228a68a635c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::instAccessReg (<a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a476971826fa13b07e28ad971ec5a3234">MachineInstr::const_mop_iterator</a> &gt; &amp;&amp; R, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned SubReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### instModifiesReg() {#a10eed6c3a3c49fdc748920361fa350da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::instModifiesReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Reg, unsigned SubReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### instReadsReg() {#acd72dee28bba5e02345684807e187a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::instReadsReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Reg, unsigned SubReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### isKImmOperand() {#aa1bc55ebf72405c2472cf9e1e109b742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::isKImmOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### isKImmOrKUImmOperand() {#afc80a6214b3b93dacbcfa77e27fd70cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::isKImmOrKUImmOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Src, bool &amp; IsUnsigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### isKUImmOperand() {#a1ba8d004f1580c59a926d067823d09ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::isKUImmOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### matchSwap() {#a4c051d76ecba77f3bbe2e25bace05fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * SIShrinkInstructions::matchSwap (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MovT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### shouldShrinkTrue16() {#a573cfa375ebf3ec9a9cf49830200d361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::shouldShrinkTrue16 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do not shrink the instruction if its registers are not expressible in the shrunk encoding.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### shrinkMadFma() {#a3bb3678b9585fc423e2f34584972de2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIShrinkInstructions::shrinkMadFma (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### shrinkMIMG() {#a598f4f5c82abed881dce2f86ebb66988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIShrinkInstructions::shrinkMIMG (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### shrinkScalarCompare() {#a7cf13a5965d697e6016c2e828192ff1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIShrinkInstructions::shrinkScalarCompare (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### shrinkScalarLogicOp() {#a8f1944c0f1fec9c842ba7c07b84a96f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::shrinkScalarLogicOp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to shrink AND/OR/XOR operations requiring non-inlineable literals.</p>


<p>For AND or OR, try using S_BITSET{0,1} to clear or set bits. If the inverse of the immediate is legal, use ANDN2, ORN2 or XNOR (as a ^ b == ~(a ^ ~b)).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the caller should continue the machine function iterator</p></dd>
</dl>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### tryReplaceDeadSDST() {#a51b74a07d97bb722f91b69e9f7385f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIShrinkInstructions::tryReplaceDeadSDST (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MF {#a115371590017893502e2efb4c106349d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### MRI {#af11080790cf6a7c6fc3eb942453cf442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### ST {#a325a1e98d30788d9ce20fb4a96f7e85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget* anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### TII {#a6de394925b9cde09032e3e49bdd3f1ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

### TRI {#afe767b5b35697a0adcae7caa8e41b327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo* anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sishrinkinstructions-cpp">SIShrinkInstructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
