---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/spirvtargetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SPIRVTargetLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SPIRVTargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">Target/SPIRV/SPIRVISelLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class defines information used to lower LLVM code to legal <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operators that the target instruction selector can accept natively. <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1351821179467af346577d6a3b481d1">SPIRVTargetLowering</a> (const TargetMachine &amp;TM, const SPIRVSubtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af06ed7aa196e53b5e14db2eeb3e553e3">isFMAFasterThanFMulAndFAdd</a> (const MachineFunction &amp;MF, EVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if an FMA operation is faster than a pair of fmul and fadd instructions. <a href="#af06ed7aa196e53b5e14db2eeb3e553e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bbd28445a7dbf98194070cd179da430">areJTsAllowed</a> (const Function *) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if lowering to a jump table is allowed. <a href="#a5bbd28445a7dbf98194070cd179da430">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a921b5e32e1c838394acefbdc1d7be3fe">getVectorIdxTy</a> (const DataLayout &amp;DL) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type to be used for the index operand of: <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">ISD::INSERT_SUBVECTOR</a>, and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">ISD::EXTRACT_SUBVECTOR</a>. <a href="#a921b5e32e1c838394acefbdc1d7be3fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9869cb9330f243cad6d20c176de62d19">getNumRegistersForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Certain targets require unusual breakdowns of certain types. <a href="#a9869cb9330f243cad6d20c176de62d19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3b5623e42a15bdd63bfea603699d01d">getRegisterTypeForCallingConv</a> (LLVMContext &amp;Context, CallingConv::ID CC, EVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Certain combinations of ABIs, Targets and features require that types are legal for some operations and not for other operations. <a href="#aa3b5623e42a15bdd63bfea603699d01d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa61639a28e9d9e650a2e6eaa7ec59c16">getTgtMemIntrinsic</a> (IntrinsicInfo &amp;Info, const CallInst &amp;I, MachineFunction &amp;MF, unsigned Intrinsic) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an intrinsic, checks if on the target the intrinsic will need to map to a MemIntrinsicNode (touches memory). <a href="#aa61639a28e9d9e650a2e6eaa7ec59c16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f8d60c452f2f26ca84f0bde2b530ad">getRegForInlineAsmConstraint</a> (const TargetRegisterInfo *TRI, StringRef Constraint, MVT VT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a physical register constraint (e.g. <a href="#ae9f8d60c452f2f26ca84f0bde2b530ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a812a3facaedadecc7f0215f4283dca3e">getNumRegisters</a> (LLVMContext &amp;Context, EVT VT, std::optional&lt; MVT &gt; RegisterVT=std::nullopt) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of registers that this <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> will eventually require. <a href="#a812a3facaedadecc7f0215f4283dca3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b7a641c5208a3cd348ac5ea98e59b6">finalizeLowering</a> (MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Execute target specific actions to finalize target lowering. <a href="#ab0b7a641c5208a3cd348ac5ea98e59b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2667ec9f866e346e4bd6b85380bf67">getPreferredSwitchConditionType</a> (LLVMContext &amp;Context, EVT ConditionVT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns preferred type for switch condition. <a href="#a1d2667ec9f866e346e4bd6b85380bf67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvsubtarget">SPIRVSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792eda8e5ee1f24f785662ac8b7a15c9">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684f40e01ac3e7895db968c2614c82d3">ProcessedMF</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SPIRVTargetLowering() {#af1351821179467af346577d6a3b481d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SPIRVTargetLowering::SPIRVTargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/spirvsubtarget">SPIRVSubtarget</a> &amp; ST)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa96f111a59a7a2e7f9c689b344543df">llvm::TargetLowering::TargetLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### areJTsAllowed() {#a5bbd28445a7dbf98194070cd179da430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SPIRVTargetLowering::areJTsAllowed (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Fn)</td>
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

<p>Return true if lowering to a jump table is allowed.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>.</p>

</div>
</div>

### finalizeLowering() {#ab0b7a641c5208a3cd348ac5ea98e59b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SPIRVTargetLowering::finalizeLowering (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Execute target specific actions to finalize target lowering.</p>


<p>This is used to set extra flags in MachineFrameInformation and freezing the set of reserved registers. The default implementation just freezes the set of reserved registers.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp">SPIRVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a088dabce389b169b6428434b3fee2153">llvm::SPIRVGlobalRegistry::addForwardCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9d017af749f76484cb9aec9ff6e4330c">llvm::MachineFunction::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07e9067b95ae52ee880a08c7d132fd56">llvm::TargetLoweringBase::finalizeLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acdec96f14d81b2043e31f3452e440a4b">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVIntegerType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acd545bc376f8f5880178094a2d165476">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a05b34a70cde1fcbdcb0767cf218c1752">llvm::SPIRVGlobalRegistry::getSPIRVTypeForVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ab91827a04a8d97aa04d5fd0d86ec790e">llvm::SPIRVGlobalRegistry::isScalarOrVectorOfType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab644fcf07a4c2708333cf66276282357">llvm::MachineBasicBlock::pred_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a877507fda31c207ec36a018784369708">llvm::MachineBasicBlock::pred_empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1590a6d5d0f6d95dda90f2cf8954f3fb">llvm::MachineBasicBlock::remove_instr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abe2132b08f73f4e1715fbefbddfacb55">llvm::SPIRVGlobalRegistry::setCurrentFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad6611e7ee084ecf0ef7b23ca25b50db0">validateAccessChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#adb82a49ed4e56654b9200b97535f637e">validateForwardCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#adc3ecee5ecd3f86b45e6779653ca10da">validateFunCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#abbe8c4ff227aafd9e016eeb143490bcc">validateGroupWaitEventsPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#af60628c2329ed3a894bf3d9fc1c5ec51">validatePtrTypes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ac6789e73101dcf0d746feb6343f4aae6">validatePtrUnwrapStructField</a>.</p>

</div>
</div>

### getNumRegisters() {#a812a3facaedadecc7f0215f4283dca3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SPIRVTargetLowering::getNumRegisters (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &gt; RegisterVT=std::nullopt)</td>
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

<p>Return the number of registers that this <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> will eventually require.</p>


<p>This is one for any types promoted to live in larger registers, but may be more than one for types (like i64) that are split into pieces. For types like i140, which are first promoted then expanded, it is the number of registers needed to hold all the bits of the original type. For an i140 on a 32 bit machine this means 5 registers.</p>


<p>RegisterVT may be passed as a way to override the default settings, for instance with i128 inline assembly operands on <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a>.</p>


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>.</p>


<p>Referenced by <a href="#a9869cb9330f243cad6d20c176de62d19">getNumRegistersForCallingConv</a>.</p>

</div>
</div>

### getNumRegistersForCallingConv() {#a9869cb9330f243cad6d20c176de62d19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SPIRVTargetLowering::getNumRegistersForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Certain targets require unusual breakdowns of certain types.</p>


<p>For MIPS, this occurs when a vector type is used, as vector are passed through the integer register set.</p>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp">SPIRVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a812a3facaedadecc7f0215f4283dca3e">getNumRegisters</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#af975bf04c49cc895cfe38e7dc126a2f1">llvm::EVT::isInteger</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### getPreferredSwitchConditionType() {#a1d2667ec9f866e346e4bd6b85380bf67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::SPIRVTargetLowering::getPreferredSwitchConditionType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ConditionVT)</td>
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

<p>Returns preferred type for switch condition.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>.</p>

</div>
</div>

### getRegForInlineAsmConstraint() {#ae9f8d60c452f2f26ca84f0bde2b530ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, const TargetRegisterClass * &gt; SPIRVTargetLowering::getRegForInlineAsmConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Constraint, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT)</td>
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

<p>Given a physical register constraint (e.g.</p>


<p>{edx}), return the register number and the register class for the register.</p>


<p>Given a register class constraint, like 'r', if this corresponds directly to an LLVM register class, return a register of 0 and the register class pointer.</p>


<p>This should only be used for C_Register constraints. On error, this returns a register number of 0 and a null register class pointer.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp">SPIRVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mvt/#adc90e34882c97d5a86dd883d3d23b4ca">llvm::MVT::isFloatingPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a437cf7bc875369cbe0ea62f949626f0b">llvm::MVT::isInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getRegisterTypeForCallingConv() {#aa3b5623e42a15bdd63bfea603699d01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT SPIRVTargetLowering::getRegisterTypeForCallingConv (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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

<p>Certain combinations of ABIs, Targets and features require that types are legal for some operations and not for other operations.</p>


<p>For MIPS all vector types must be passed through the integer register set.</p>


<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp">SPIRVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af344c6bd2d070c999525df85be7688cf">llvm::TargetLoweringBase::getRegisterType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abc4c6365ade17ad4443ad0e381e7479d">llvm::EVT::getVectorElementType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a> and <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>.</p>

</div>
</div>

### getTgtMemIntrinsic() {#aa61639a28e9d9e650a2e6eaa7ec59c16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SPIRVTargetLowering::getTgtMemIntrinsic (<a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/intrinsicinfo">IntrinsicInfo</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;, unsigned)</td>
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

<p>Given an intrinsic, checks if on the target the intrinsic will need to map to a MemIntrinsicNode (touches memory).</p>


<p>If this is the case, it returns true and store the intrinsic information into the <a href="/web-llvm/docs/api/structs/llvm/targetloweringbase/intrinsicinfo">IntrinsicInfo</a> that was passed to the function.</p>


<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp">SPIRVISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getVectorIdxTy() {#a921b5e32e1c838394acefbdc1d7be3fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::SPIRVTargetLowering::getVectorIdxTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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

<p>Returns the type to be used for the index operand of: <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad3bc7c2d379fbfdc2f8eaca038690ec9">ISD::INSERT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">ISD::INSERT_SUBVECTOR</a>, and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">ISD::EXTRACT_SUBVECTOR</a>.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>.</p>

</div>
</div>

### isFMAFasterThanFMulAndFAdd() {#af06ed7aa196e53b5e14db2eeb3e553e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SPIRVTargetLowering::isFMAFasterThanFMulAndFAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>)</td>
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

<p>Return true if an FMA operation is faster than a pair of fmul and fadd instructions.</p>


<p>fmuladd intrinsics will be expanded to FMAs when this method returns true, otherwise fmuladd is expanded to fmul + fadd.</p>


<p>NOTE: This may be called before legalization on types for which FMAs are not legal, but should return true if those types will eventually legalize to types that support FMAs. After legalization, it will only be called on types that support FMAs (via Legal or Custom actions)</p>


<p>Targets that care about soft float support should return false when soft float code is being generated (i.e. use-soft-float).</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ProcessedMF {#a684f40e01ac3e7895db968c2614c82d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;const MachineFunction *&gt; llvm::SPIRVTargetLowering::ProcessedMF</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>.</p>

</div>
</div>

### STI {#a792eda8e5ee1f24f785662ac8b7a15c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SPIRVSubtarget&amp; llvm::SPIRVTargetLowering::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp">SPIRVISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-h">SPIRVISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
