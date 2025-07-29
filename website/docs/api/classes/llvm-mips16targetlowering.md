---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mips16targetlowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Mips16TargetLowering` Class



## Declaration

<div class="doxyDeclaration">
class llvm::Mips16TargetLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Target/Mips/Mips16ISelLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering">MipsTargetLowering</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97b896b6b94b563138613746e46e053e">Mips16TargetLowering</a> (const MipsTargetMachine &amp;TM, const MipsSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb82fc3359067f1e7d2e20479337c305">allowsMisalignedMemoryAccesses</a> (EVT VT, unsigned AddrSpace, Align Alignment, MachineMemOperand::Flags Flags, unsigned *Fast) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the target supports unaligned memory accesses. <a href="#adb82fc3359067f1e7d2e20479337c305">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3de3b06df114ac07ac0f5e9c14fe77da">EmitInstrWithCustomInserter</a> (MachineInstr &amp;MI, MachineBasicBlock *MBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag. <a href="#a3de3b06df114ac07ac0f5e9c14fe77da">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19a73b4358e9ffc374fd59061117548">isEligibleForTailCallOptimization</a> (const CCState &amp;CCInfo, unsigned NextStackOffset, const MipsFunctionInfo &amp;FI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization. <a href="#af19a73b4358e9ffc374fd59061117548">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0fb545c5989fae432fdc93a5eb483fa">setMips16HardFloatLibCalls</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667e2e18708e94183a2eac193f77ac17">getMips16HelperFunctionStubNumber</a> (ArgListTy &amp;Args) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d7a222e34f18933f86d857e430c3b11">getMips16HelperFunction</a> (Type *RetTy, ArgListTy &amp;Args, bool &amp;needHelper) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d624512d41988f2c4acbc7bd210fbf8">getOpndList</a> (SmallVectorImpl&lt; SDValue &gt; &amp;Ops, std::deque&lt; std::pair&lt; unsigned, SDValue &gt; &gt; &amp;RegsToPass, bool IsPICCall, bool GlobalOrExternal, bool InternalLinkage, bool IsCallReloc, CallLoweringInfo &amp;CLI, SDValue Callee, SDValue Chain) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function fills Ops, which is the list of operands that will later be used when a function call node is created. <a href="#a3d624512d41988f2c4acbc7bd210fbf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f2c233a0179819c40565a82a719db6">emitSel16</a> (unsigned Opc, MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab416faef2c5c3df2bd5be8b49d7f6684">emitSeliT16</a> (unsigned Opc1, unsigned Opc2, MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0354a54f6e374196470f911aff4f32cf">emitSelT16</a> (unsigned Opc1, unsigned Opc2, MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8584f6a497b2a5ead7468d1ada71b7">emitFEXT_T8I816_ins</a> (unsigned BtOpc, unsigned CmpOpc, MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf4400ac3d41c47a50d6a3f0f32ac02">emitFEXT_T8I8I16_ins</a> (unsigned BtOpc, unsigned CmpiOpc, unsigned CmpiXOpc, bool ImmSigned, MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7717562dd83551f0959b87675779167">emitFEXT_CCRX16_ins</a> (unsigned SltOpc, MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e35741a3e38dc7ef3b2af50dbf029d">emitFEXT_CCRXI16_ins</a> (unsigned SltiOpc, unsigned SltiXOpc, MachineInstr &amp;MI, MachineBasicBlock *BB) const</td>
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


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Mips16TargetLowering() {#a97b896b6b94b563138613746e46e053e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Mips16TargetLowering::Mips16TargetLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine">MipsTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> &amp; STI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a7c45a718f16057459d95d09d42ec6902">llvm::TargetLoweringBase::addRegisterClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9c91befeca2a25c8050d4c3dff8b6d67">llvm::ISD::ATOMIC_CMP_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a385d7f9c63f921a2b28e8426e4101de8">llvm::ISD::ATOMIC_FENCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf5f612de1a25451c9a0c33d77bf3e74">llvm::ISD::ATOMIC_LOAD_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a905925a49cdc6b4a6017d215820dad30">llvm::ISD::ATOMIC_LOAD_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1cf8547d612d954d34aab1d4f78e7fa1">llvm::ISD::ATOMIC_LOAD_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7049708cb0e0703a467b95a506293aec">llvm::ISD::ATOMIC_LOAD_MIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a13a3e6402abf972278c6a7d5ee509f9d">llvm::ISD::ATOMIC_LOAD_NAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4112a866197a97a70bdc78ef92c79b4c">llvm::ISD::ATOMIC_LOAD_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3d12dbff6e50803982d0e92768a1479">llvm::ISD::ATOMIC_LOAD_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9ca44a643714809ef384e7494604db14">llvm::ISD::ATOMIC_LOAD_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1ff6f20a9255f7a333f4c9d25393674c">llvm::ISD::ATOMIC_LOAD_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a428ec1341b34eafa63518914e7f5ddf0">llvm::ISD::ATOMIC_LOAD_XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad728a4b56d49f39375881511d8d3118d">llvm::ISD::ATOMIC_SWAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6df03220bbe2ea3cfb905f36fb26822c">llvm::TargetLoweringBase::computeRegisterProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aa4b85349547c5b6126817e10152007931">llvm::TargetLoweringBase::Expand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#a856ec36e844545656044c24f78dbcbbd">llvm::MipsSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a12b8712b6c436a8152a5fa996cd8956aafb9a152dd1ee4089f5fc96a33c5c90d2">llvm::TargetLoweringBase::LibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a4baae7363a2379cc1714f47c6f0404aa">llvm::MipsTargetLowering::MipsTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19cd524269b035941434cce28b585715">llvm::ISD::ROTR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a07c0c67913bb543fc45ce9ef65ef260a">llvm::TargetLoweringBase::setOperationAction</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#abd5bf0c117bc4ead7f73f5e51a39a160">llvm::MipsTargetLowering::Subtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allowsMisalignedMemoryAccesses() {#adb82fc3359067f1e7d2e20479337c305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Mips16TargetLowering::allowsMisalignedMemoryAccesses (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a>, unsigned AddrSpace, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dd">MachineMemOperand::Flags</a> Flags, unsigned *)</td>
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

<p>Determine if the target supports unaligned memory accesses.</p>


<p>This function returns true if the target allows unaligned memory accesses of the specified type in the given address space. If true, it also returns a relative speed of the unaligned memory access in the last argument by reference. The higher the speed number the faster the operation comparing to a number returned by another such call. This is used, for example, in situations where an array copy/move/set is converted to a sequence of store operations. Its use helps to ensure that such replacements don't generate code that causes an alignment error (trap) on the target machine.</p>


<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>.</p>

</div>
</div>

### EmitInstrWithCustomInserter() {#a3de3b06df114ac07ac0f5e9c14fe77da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * Mips16TargetLowering::EmitInstrWithCustomInserter (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>This method should be implemented by targets that mark instructions with the 'usesCustomInserter' flag.</p>


<p>These instructions are special in various ways, which require special support to insert. The specified <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> is created but not inserted into any basic blocks, and this method is called to expand it into a sequence of instructions, potentially also creating new basic blocks and control flow. As long as the returned basic block is different (i.e., we created a new one), the custom inserter is free to modify the rest of <span class="doxyComputerOutput">MBB</span>.</p>


<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a74ceed526d62127854c54efe9e7f6f06">llvm::MipsTargetLowering::EmitInstrWithCustomInserter</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitFEXT\_CCRX16\_ins() {#aa7717562dd83551f0959b87675779167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * Mips16TargetLowering::emitFEXT_CCRX16_ins (unsigned SltOpc, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### emitFEXT\_CCRXI16\_ins() {#a57e35741a3e38dc7ef3b2af50dbf029d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * Mips16TargetLowering::emitFEXT_CCRXI16_ins (unsigned SltiOpc, unsigned SltiXOpc, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### emitFEXT\_T8I816\_ins() {#ade8584f6a497b2a5ead7468d1ada71b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * Mips16TargetLowering::emitFEXT_T8I816_ins (unsigned BtOpc, unsigned CmpOpc, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### emitFEXT\_T8I8I16\_ins() {#a3bf4400ac3d41c47a50d6a3f0f32ac02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * Mips16TargetLowering::emitFEXT_T8I8I16_ins (unsigned BtOpc, unsigned CmpiOpc, unsigned CmpiXOpc, bool ImmSigned, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### emitSel16() {#a25f2c233a0179819c40565a82a719db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * Mips16TargetLowering::emitSel16 (unsigned Opc, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### emitSeliT16() {#ab416faef2c5c3df2bd5be8b49d7f6684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * Mips16TargetLowering::emitSeliT16 (unsigned Opc1, unsigned Opc2, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### emitSelT16() {#a0354a54f6e374196470f911aff4f32cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * Mips16TargetLowering::emitSelT16 (unsigned Opc1, unsigned Opc2, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### getMips16HelperFunction() {#a6d7a222e34f18933f86d857e430c3b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * Mips16TargetLowering::getMips16HelperFunction (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">ArgListTy</a> &amp; Args, bool &amp; needHelper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### getMips16HelperFunctionStubNumber() {#a667e2e18708e94183a2eac193f77ac17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int Mips16TargetLowering::getMips16HelperFunctionStubNumber (<a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ae4ac6bc14db22dbd7b94a3b1bd276796">ArgListTy</a> &amp; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### getOpndList() {#a3d624512d41988f2c4acbc7bd210fbf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Mips16TargetLowering::getOpndList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Ops, std::deque&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &gt; &amp; RegsToPass, bool IsPICCall, bool GlobalOrExternal, bool InternalLinkage, bool IsCallReloc, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo">CallLoweringInfo</a> &amp; CLI, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Callee, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain)</td>
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

<p>This function fills Ops, which is the list of operands that will later be used when a function call node is created.</p>


<p>It also generates copyToReg nodes to set up argument registers.</p>


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### isEligibleForTailCallOptimization() {#af19a73b4358e9ffc374fd59061117548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Mips16TargetLowering::isEligibleForTailCallOptimization (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; CCInfo, unsigned NextStackOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo">MipsFunctionInfo</a> &amp; FI)</td>
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

<p>isEligibleForTailCallOptimization - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the call is eligible for tail call optimization.</p>

<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

### setMips16HardFloatLibCalls() {#ab0fb545c5989fae432fdc93a5eb483fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Mips16TargetLowering::setMips16HardFloatLibCalls ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp">Mips16ISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-h">Mips16ISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
