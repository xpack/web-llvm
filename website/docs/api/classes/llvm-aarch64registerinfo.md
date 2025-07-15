---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64registerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AArch64RegisterInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AArch64RegisterInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">Target/AArch64/AArch64RegisterInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/aarch64genregisterinfo">AArch64GenRegisterInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55bc507d25285327689bff4f5e75240">AArch64RegisterInfo</a> (const Triple &amp;TT, unsigned HwMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f843070807cb293478a6ba335fd896a">getSEHRegNum</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a291580cc01efa41a004f8b30e358969f">isReservedReg</a> (const MachineFunction &amp;MF, MCRegister Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999b53e29b4f65e8b69cc35300b4e1b3">isStrictlyReservedReg</a> (const MachineFunction &amp;MF, MCRegister Reg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f56fea99a4fd71730825c599b71f255">isAnyArgRegReserved</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92f6c66cdcfda320596faa724a82937c">emitReservedArgRegCallError</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776852734c11ae705971ee8d39e589c6">UpdateCustomCalleeSavedRegs</a> (MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d8a95e0be5b8b7c9e31abc8ead009d">UpdateCustomCallPreservedMask</a> (MachineFunction &amp;MF, const uint32_t **Mask) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26dae5c257bfaab5aa15cab7255f107">getCalleeSavedRegs</a> (const MachineFunction *MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Code Generation virtual methods... <a href="#ac26dae5c257bfaab5aa15cab7255f107">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab57b42c1306819f384fbc8917e728b">getDarwinCalleeSavedRegs</a> (const MachineFunction *MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35e0d4e10fc033d23cb665a9f6ef4bc6">getCalleeSavedRegsViaCopy</a> (const MachineFunction *MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a4f0d74a9e54517b5009c2ac31503b5">getCallPreservedMask</a> (const MachineFunction &amp;MF, CallingConv::ID) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace1d2fbafd80bd71d27a949593da97f7">getDarwinCallPreservedMask</a> (const MachineFunction &amp;MF, CallingConv::ID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3412da4a5b8c1999d660e6e780bcefaa">getCSRFirstUseCost</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d539c1d62e32c02ef7148119cd8fce">getSubClassWithSubReg</a> (const TargetRegisterClass *RC, unsigned Idx) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26bfc77e6ce2219491ef73aa43041af">getTLSCallPreservedMask</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07637fa0d73f595bd80eba10f74114d">getSMStartStopCallPreservedMask</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79c1292e71ad692227eb056a527903f">SMEABISupportRoutinesCallPreservedMaskFromX0</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2cf15f3429b07ac38ce86c0deecdf2d">getNoPreservedMask</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46af6be29759c071896093e8a5ec220">getCustomEHPadPreservedMask</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e901d70774581088feef3ee1d967ff1">getThisReturnPreservedMask</a> (const MachineFunction &amp;MF, CallingConv::ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getThisReturnPreservedMask - Returns a call preserved mask specific to the case that 'returned' is on an i64 first argument if the calling convention is one that can (partially) model this attribute with a preserved mask (i.e. <a href="#a1e901d70774581088feef3ee1d967ff1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85e8a1b86fd5ae947211163016cf7b80">getWindowsStackProbePreservedMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stack probing calls preserve different CSRs to the normal CC. <a href="#a85e8a1b86fd5ae947211163016cf7b80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135ff03665f8746c89e91d3b802a1017">getStrictlyReservedRegs</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a366a7f426707271b798b4355c12ce57d">getReservedRegs</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af05862d6eaf49d6ca3a5ddac9231fd0d">explainReservedReg</a> (const MachineFunction &amp;MF, MCRegister PhysReg) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaed10441dd729ce9fdc91120f2a77f0">isAsmClobberable</a> (const MachineFunction &amp;MF, MCRegister PhysReg) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774a5b2a1b863baedbae7c5c9f62f360">getPointerRegClass</a> (const MachineFunction &amp;MF, unsigned Kind=0) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192c197358f88606b27a80ceb34f2954">getCrossCopyRegClass</a> (const TargetRegisterClass *RC) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7926f85d35e77a4f1c4d9c041a0f7612">requiresRegisterScavenging</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6176251034fbacf30f8e906db5f347">useFPForScavengingIndex</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81e5df3a149fe59116ca57fd66f92fa">requiresFrameIndexScavenging</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83f94d5dd8793554e6f3be24bc75eea5">needsFrameBaseReg</a> (MachineInstr *MI, int64_t Offset) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>needsFrameBaseReg - Returns true if the instruction's frame index reference would be better served by a base register other than FP or SP. <a href="#a83f94d5dd8793554e6f3be24bc75eea5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0d5c1915330faa3a19839c10ccfd2f">isFrameOffsetLegal</a> (const MachineInstr *MI, Register BaseReg, int64_t Offset) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7321f8d9c50eb416611a0309a3fd9742">materializeFrameBaseRegister</a> (MachineBasicBlock *MBB, int FrameIdx, int64_t Offset) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert defining instruction(s) for BaseReg to be a pointer to FrameIdx at the beginning of the basic block. <a href="#a7321f8d9c50eb416611a0309a3fd9742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825b9cf5093b700f2b37cf4b7555af66">resolveFrameIndex</a> (MachineInstr &amp;MI, Register BaseReg, int64_t Offset) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24149b04083669797095c1473b14f3a">eliminateFrameIndex</a> (MachineBasicBlock::iterator II, int SPAdj, unsigned FIOperandNum, RegScavenger *RS=nullptr) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf86b81af5da74aea6a11c36eadf41be">cannotEliminateFrame</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51acc1b21295aa0d3e06392e26601e12">requiresVirtualBaseRegisters</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acafe750c425c834b596416c311715d8c">hasBasePointer</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af855b9574123510dd91bee730edba54b">getBaseRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01246dc7ecdd8a082730860cd3166a1">isArgumentRegister</a> (const MachineFunction &amp;MF, MCRegister Reg) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa403598e50fb4724e2c5927e2ad8864e">getFrameRegister</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a686453b777e5e7540ba688dc84fd4733">getRegPressureLimit</a> (const TargetRegisterClass *RC, MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a2253decaa6ee31ae96ec6e0b3de13">getRegAllocationHints</a> (Register VirtReg, ArrayRef&lt; MCPhysReg &gt; Order, SmallVectorImpl&lt; MCPhysReg &gt; &amp;Hints, const MachineFunction &amp;MF, const VirtRegMap *VRM, const LiveRegMatrix *Matrix) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca088b3aa514b9ef361f5d4d244c97b7">getLocalAddressRegister</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96feb3493457dc69868b789630e4506b">regNeedsCFI</a> (unsigned Reg, unsigned &amp;RegToUseForCFI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether the register needs a CFI entry. <a href="#a96feb3493457dc69868b789630e4506b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472cefd8107362b99710b1e58174b7a0">shouldCoalesce</a> (MachineInstr *MI, const TargetRegisterClass *SrcRC, unsigned SubReg, const TargetRegisterClass *DstRC, unsigned DstSubReg, const TargetRegisterClass *NewRC, LiveIntervals &amp;LIS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SrcRC and DstRC will be morphed into NewRC if this returns true. <a href="#a472cefd8107362b99710b1e58174b7a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa93abb15d7ccdae4c8dc69cef75a202a">getOffsetOpcodes</a> (const StackOffset &amp;Offset, SmallVectorImpl&lt; uint64_t &gt; &amp;Ops) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6694e321bed1af36a3bdba1689dc1b9">shouldAnalyzePhysregInMachineLoopInfo</a> (MCRegister R) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e203e68fd0111fc59f2b9b168bb5923">TT</a></td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64RegisterInfo() {#ab55bc507d25285327689bff4f5e75240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AArch64RegisterInfo::AArch64RegisterInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, unsigned HwMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-mc/#a7cbac6ccc31cf1c6b0a5aca90d273c3b">llvm::AArch64_MC::initLLVMToCVRegMapping</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cannotEliminateFrame() {#adf86b81af5da74aea6a11c36eadf41be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::cannotEliminateFrame (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a19e260b3bbf8fad8480d151e11919836">llvm::MachineFrameInfo::adjustsStack</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aad0fc1de8197ddf2c49346c5d92a2bec">llvm::TargetOptions::DisableFramePointerElim</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a32125253541ab2e7ec5bbe550ecc2d0c">llvm::MachineFrameInfo::isFrameAddressTaken</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>.</p>

</div>
</div>

### eliminateFrameIndex() {#aa24149b04083669797095c1473b14f3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::eliminateFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> II, int SPAdj, unsigned FIOperandNum, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 944 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3d42df7595bb7da318e52023ffe95226a8dc2c9caf2dbb5337725c3f2dc11f72f">llvm::AArch64FrameOffsetCanUpdate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d42df7595bb7da318e52023ffe95226a11e259103be968c42cfd9c607f12904a">llvm::AArch64FrameOffsetIsLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a7b39ecfd6793534206dbb095b0d464c7">llvm::MachineOperand::ChangeToImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp/#a671a8a3ae77dbb608929dca09e7e395f">createScratchRegisterForInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c6206e8d8fd98ecca8ac2c785ee9491">llvm::emitFrameOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#a0775e5fb52ac148f4d06e7eedb34e94e">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a492547015f6f9aaf93099d70b32e8d9a">llvm::AArch64FrameLowering::getNonLocalFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a73f8cb59d120af794be129a54a0343fb">llvm::AArch64FunctionInfo::getTaggedBasePointerOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18dec717578f39bfcff50e325c2d27c5">llvm::isAArch64FrameOffsetLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a82a0ed0e83e8058a1594c9bb6e9678cc">llvm::RegScavenger::isScavengingFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64ii/#ae22a65863fdb02ce99abf9ee08bcbb71aefb2c1834e49df9715967d4a2c9c99e8">llvm::AArch64II::MO_TAGGED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ae748adf8316f78f9fc4f6a32e938da0a">llvm::AArch64FrameLowering::resolveFrameIndexReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acbe69ef233b07b4362366dcfc380abca">llvm::rewriteAArch64FrameIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### emitReservedArgRegCallError() {#a92f6c66cdcfda320596faa724a82937c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64RegisterInfo::emitReservedArgRegCallError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>.</p>

</div>
</div>

### explainReservedReg() {#af05862d6eaf49d6ca3a5ddac9231fd0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; AArch64RegisterInfo::explainReservedReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aarch64instprinter/#ac44cbaab70907308f6fd0e94809d0e23">llvm::AArch64InstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#acafe750c425c834b596416c311715d8c">hasBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#ab11ed6ee239ab7c9328927b7327fc8f1">llvm::AArch64Subtarget::isWindowsArm64EC</a> and <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a0bd1b194b601377bdb0f3a4a6e1f7e0d">llvm::MCRegisterInfo::regsOverlap</a>.</p>

</div>
</div>

### getBaseRegister() {#af855b9574123510dd91bee730edba54b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64RegisterInfo::getBaseRegister ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#aca088b3aa514b9ef361f5d4d244c97b7">getLocalAddressRegister</a>.</p>

</div>
</div>

### getCalleeSavedRegs() {#ac26dae5c257bfaab5aa15cab7255f107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * AArch64RegisterInfo::getCalleeSavedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Code Generation virtual methods...</p>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca7c23dce1e95fc36e9d2c168f9e036cc7">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca963e14ac38d6e3b63f8e37085702951c">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca72069ecfe852db0ea1f10c1549989424">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca300efd85d130657d0d06f0469980bd0f">llvm::CallingConv::AArch64_SVE_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca0e62ecb2c693281fafd77f39b2ddd284">llvm::CallingConv::AArch64_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f42667edde6e9cb80cfae6361e5e76a">llvm::CallingConv::AnyReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf80cc3a71c40926e6c35a60ccdc6428e">llvm::CallingConv::ARM64EC_Thunk_X64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="#aaab57b42c1306819f384fbc8917e728b">getDarwinCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a66b26e824dd1b4bb346cd20278651032">llvm::AArch64Subtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a093615ad7a3c3eac2dc8c8655d0ac00b">llvm::AArch64FunctionInfo::isSVECC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4d2e6b50d2d120966b45253b1ad825b4">llvm::AArch64Subtarget::isTargetDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a05fb81a3747dd4f76894a66c574cf99e">llvm::AArch64Subtarget::isTargetWindows</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9f6ac05d37c2fbf197de42295c23fd6e">llvm::CallingConv::PreserveAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4eeb29fe27dc20afa4f443765f45f9a5">llvm::CallingConv::PreserveMost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad5385f408f537fc279d485c77d2463ce">llvm::CallingConv::PreserveNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aeed6ff19584b28f6a534e1aa8ed60037">llvm::AArch64TargetLowering::supportSwiftError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae41511c1ad4197da36cef403f34bac72">llvm::CallingConv::Win64</a>.</p>


<p>Referenced by <a href="#a776852734c11ae705971ee8d39e589c6">UpdateCustomCalleeSavedRegs</a>.</p>

</div>
</div>

### getCalleeSavedRegsViaCopy() {#a35e0d4e10fc033d23cb665a9f6ef4bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * AArch64RegisterInfo::getCalleeSavedRegsViaCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a89194de9866090f36bd192e81aeb1e1a">llvm::AArch64FunctionInfo::isSplitCSR</a>.</p>

</div>
</div>

### getCallPreservedMask() {#a2a4f0d74a9e54517b5009c2ac31503b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * AArch64RegisterInfo::getCallPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca7c23dce1e95fc36e9d2c168f9e036cc7">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca963e14ac38d6e3b63f8e37085702951c">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca72069ecfe852db0ea1f10c1549989424">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca300efd85d130657d0d06f0469980bd0f">llvm::CallingConv::AArch64_SVE_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca0e62ecb2c693281fafd77f39b2ddd284">llvm::CallingConv::AArch64_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f42667edde6e9cb80cfae6361e5e76a">llvm::CallingConv::AnyReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="#ace1d2fbafd80bd71d27a949593da97f7">getDarwinCallPreservedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a66b26e824dd1b4bb346cd20278651032">llvm::AArch64Subtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4d2e6b50d2d120966b45253b1ad825b4">llvm::AArch64Subtarget::isTargetDarwin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9f6ac05d37c2fbf197de42295c23fd6e">llvm::CallingConv::PreserveAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4eeb29fe27dc20afa4f443765f45f9a5">llvm::CallingConv::PreserveMost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad5385f408f537fc279d485c77d2463ce">llvm::CallingConv::PreserveNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aeed6ff19584b28f6a534e1aa8ed60037">llvm::AArch64TargetLowering::supportSwiftError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a>.</p>

</div>
</div>

### getCrossCopyRegClass() {#a192c197358f88606b27a80ceb34f2954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * AArch64RegisterInfo::getCrossCopyRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### getCSRFirstUseCost() {#a3412da4a5b8c1999d660e6e780bcefaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AArch64RegisterInfo::getCSRFirstUseCost ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>.</p>

</div>
</div>

### getCustomEHPadPreservedMask() {#ac46af6be29759c071896093e8a5ec220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * AArch64RegisterInfo::getCustomEHPadPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#ae958bc5e804978a9be305c1b6f3cd63b">llvm::AArch64Subtarget::isTargetLinux</a>.</p>

</div>
</div>

### getDarwinCalleeSavedRegs() {#aaab57b42c1306819f384fbc8917e728b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * AArch64RegisterInfo::getDarwinCalleeSavedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca7c23dce1e95fc36e9d2c168f9e036cc7">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca963e14ac38d6e3b63f8e37085702951c">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca72069ecfe852db0ea1f10c1549989424">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca300efd85d130657d0d06f0469980bd0f">llvm::CallingConv::AArch64_SVE_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca0e62ecb2c693281fafd77f39b2ddd284">llvm::CallingConv::AArch64_VectorCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a66b26e824dd1b4bb346cd20278651032">llvm::AArch64Subtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a093615ad7a3c3eac2dc8c8655d0ac00b">llvm::AArch64FunctionInfo::isSVECC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4d2e6b50d2d120966b45253b1ad825b4">llvm::AArch64Subtarget::isTargetDarwin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9f6ac05d37c2fbf197de42295c23fd6e">llvm::CallingConv::PreserveAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4eeb29fe27dc20afa4f443765f45f9a5">llvm::CallingConv::PreserveMost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aeed6ff19584b28f6a534e1aa8ed60037">llvm::AArch64TargetLowering::supportSwiftError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae41511c1ad4197da36cef403f34bac72">llvm::CallingConv::Win64</a>.</p>


<p>Referenced by <a href="#ac26dae5c257bfaab5aa15cab7255f107">getCalleeSavedRegs</a>.</p>

</div>
</div>

### getDarwinCallPreservedMask() {#ace1d2fbafd80bd71d27a949593da97f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * AArch64RegisterInfo::getDarwinCallPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca7c23dce1e95fc36e9d2c168f9e036cc7">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca963e14ac38d6e3b63f8e37085702951c">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca72069ecfe852db0ea1f10c1549989424">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca300efd85d130657d0d06f0469980bd0f">llvm::CallingConv::AArch64_SVE_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca0e62ecb2c693281fafd77f39b2ddd284">llvm::CallingConv::AArch64_VectorCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a66b26e824dd1b4bb346cd20278651032">llvm::AArch64Subtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4d2e6b50d2d120966b45253b1ad825b4">llvm::AArch64Subtarget::isTargetDarwin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9f6ac05d37c2fbf197de42295c23fd6e">llvm::CallingConv::PreserveAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4eeb29fe27dc20afa4f443765f45f9a5">llvm::CallingConv::PreserveMost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aeed6ff19584b28f6a534e1aa8ed60037">llvm::AArch64TargetLowering::supportSwiftError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a>.</p>


<p>Referenced by <a href="#a2a4f0d74a9e54517b5009c2ac31503b5">getCallPreservedMask</a>.</p>

</div>
</div>

### getFrameRegister() {#aa403598e50fb4724e2c5927e2ad8864e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register AArch64RegisterInfo::getFrameRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>.</p>


<p>Referenced by <a href="#aca088b3aa514b9ef361f5d4d244c97b7">getLocalAddressRegister</a>.</p>

</div>
</div>

### getLocalAddressRegister() {#aca088b3aa514b9ef361f5d4d244c97b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64RegisterInfo::getLocalAddressRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 1166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="#af855b9574123510dd91bee730edba54b">getBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#aa403598e50fb4724e2c5927e2ad8864e">getFrameRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a>.</p>

</div>
</div>

### getNoPreservedMask() {#aa2cf15f3429b07ac38ce86c0deecdf2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * AArch64RegisterInfo::getNoPreservedMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### getOffsetOpcodes() {#aa93abb15d7ccdae4c8dc69cef75a202a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64RegisterInfo::getOffsetOpcodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a272fe723d8c234f2137d34621a5cef78">llvm::DIExpression::appendOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackmaps-cpp/#a5c1040e7ce3199cf1f9adfa1e7d7ad25">getDwarfRegNum</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getPointerRegClass() {#a774a5b2a1b863baedbae7c5c9f62f360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * AArch64RegisterInfo::getPointerRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned Kind=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### getRegAllocationHints() {#a69a2253decaa6ee31ae96ec6e0b3de13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::getRegAllocationHints (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt; &amp; Hints, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * VRM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix">LiveRegMatrix</a> * Matrix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a785a4e2daf4e5bf3f0836adbc4fb7e65">llvm::VirtRegMap::getPhys</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afc99d2835eb4b8cde9e81db9abca597c">llvm::TargetRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#ab28bf4ffd3e2223dab0527c9d7e18288">llvm::VirtRegMap::hasPhys</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregmatrix-cpp/#a8989acb71bd355e02bcf3a930b5e54ea">Matrix</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### getRegPressureLimit() {#a686453b777e5e7540ba688dc84fd4733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AArch64RegisterInfo::getRegPressureLimit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#acafe750c425c834b596416c311715d8c">hasBasePointer</a> and <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>.</p>

</div>
</div>

### getReservedRegs() {#a366a7f426707271b798b4355c12ce57d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector AArch64RegisterInfo::getReservedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="#a135ff03665f8746c89e91d3b802a1017">getStrictlyReservedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aacef05f16d3e71703f08bb4677e1d7a2">llvm::MachineFunctionProperties::hasProperty</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a18bccbc1eec80c28e26095f1adfc62e8">llvm::AArch64Subtarget::isLRReservedForRA</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a60b99c1daa52f651e107fb381e3433f9">llvm::AArch64Subtarget::isXRegisterReservedForRA</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15a942d4e37dd5607ab68e54755540d4a47">llvm::Reserved</a>.</p>


<p>Referenced by <a href="#a291580cc01efa41a004f8b30e358969f">isReservedReg</a>.</p>

</div>
</div>

### getSEHRegNum() {#a1f843070807cb293478a6ba335fd896a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AArch64RegisterInfo::getSEHRegNum (unsigned i)</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>.</p>

</div>
</div>

### getSMStartStopCallPreservedMask() {#ad07637fa0d73f595bd80eba10f74114d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * AArch64RegisterInfo::getSMStartStopCallPreservedMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### getStrictlyReservedRegs() {#a135ff03665f8746c89e91d3b802a1017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector AArch64RegisterInfo::getStrictlyReservedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae9c6786f93f1d156d2b40ecc6be438bb">llvm::CallingConv::GRAAL</a>, <a href="#acafe750c425c834b596416c311715d8c">hasBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#ab11ed6ee239ab7c9328927b7327fc8f1">llvm::AArch64Subtarget::isWindowsArm64EC</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#abebf776aea4ae4a420fd4a2c5f02cbbd">llvm::AArch64Subtarget::isXRegisterReserved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15a942d4e37dd5607ab68e54755540d4a47">llvm::Reserved</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="#a366a7f426707271b798b4355c12ce57d">getReservedRegs</a> and <a href="#a999b53e29b4f65e8b69cc35300b4e1b3">isStrictlyReservedReg</a>.</p>

</div>
</div>

### getSubClassWithSubReg() {#a63d539c1d62e32c02ef7148119cd8fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * AArch64RegisterInfo::getSubClassWithSubReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC, unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### getThisReturnPreservedMask() {#a1e901d70774581088feef3ee1d967ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * AArch64RegisterInfo::getThisReturnPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getThisReturnPreservedMask - Returns a call preserved mask specific to the case that 'returned' is on an i64 first argument if the calling convention is one that can (partially) model this attribute with a preserved mask (i.e.</p>


<p>it is a calling convention that uses the same register for the first i64 argument and an i64 return value)</p>


<p>Should return NULL in the case that the calling convention does not have this property</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4d2e6b50d2d120966b45253b1ad825b4">llvm::AArch64Subtarget::isTargetDarwin</a>.</p>

</div>
</div>

### getTLSCallPreservedMask() {#aa26bfc77e6ce2219491ef73aa43041af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * AArch64RegisterInfo::getTLSCallPreservedMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getWindowsStackProbePreservedMask() {#a85e8a1b86fd5ae947211163016cf7b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * AArch64RegisterInfo::getWindowsStackProbePreservedMask ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stack probing calls preserve different CSRs to the normal CC.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### hasBasePointer() {#acafe750c425c834b596416c311715d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::hasBasePointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 602 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa306e1d00f65a9bb1030e66e9d195a69">llvm::MachineFrameInfo::getLocalFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a7b316ba6e060bc850312c3d294130878">llvm::AArch64FunctionInfo::getStackSizeSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#ad7bb9da1cdb51abc81f080b265948015">llvm::AArch64FunctionInfo::hasCalculatedStackSizeSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad40522ac860df72189255e38782acc3f">llvm::MachineFunction::hasEHFunclets</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>.</p>


<p>Referenced by <a href="#af05862d6eaf49d6ca3a5ddac9231fd0d">explainReservedReg</a>, <a href="#a686453b777e5e7540ba688dc84fd4733">getRegPressureLimit</a> and <a href="#a135ff03665f8746c89e91d3b802a1017">getStrictlyReservedRegs</a>.</p>

</div>
</div>

### isAnyArgRegReserved() {#a8f56fea99a4fd71730825c599b71f255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::isAnyArgRegReserved (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="#a999b53e29b4f65e8b69cc35300b4e1b3">isStrictlyReservedReg</a>.</p>

</div>
</div>

### isArgumentRegister() {#ae01246dc7ecdd8a082730860cd3166a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::isArgumentRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca7c23dce1e95fc36e9d2c168f9e036cc7">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca963e14ac38d6e3b63f8e37085702951c">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca72069ecfe852db0ea1f10c1549989424">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca300efd85d130657d0d06f0469980bd0f">llvm::CallingConv::AArch64_SVE_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca0e62ecb2c693281fafd77f39b2ddd284">llvm::CallingConv::AArch64_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#ae5185becf2e4a0ecfb059a5ce69da205">llvm::AArch64Subtarget::isCallingConvWin64</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4d2e6b50d2d120966b45253b1ad825b4">llvm::AArch64Subtarget::isTargetDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a59137b132e07516767761d5decf7e252">llvm::AArch64Subtarget::isTargetILP32</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a05fb81a3747dd4f76894a66c574cf99e">llvm::AArch64Subtarget::isTargetWindows</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#af457a58a84b500d44feb7b699aa43ec1">llvm::Function::isVarArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9f6ac05d37c2fbf197de42295c23fd6e">llvm::CallingConv::PreserveAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4eeb29fe27dc20afa4f443765f45f9a5">llvm::CallingConv::PreserveMost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad5385f408f537fc279d485c77d2463ce">llvm::CallingConv::PreserveNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2740493172a4ce246941c8cff95e0f83">llvm::CallingConv::Swift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae41511c1ad4197da36cef403f34bac72">llvm::CallingConv::Win64</a>.</p>

</div>
</div>

### isAsmClobberable() {#aaaed10441dd729ce9fdc91120f2a77f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::isAsmClobberable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="#a291580cc01efa41a004f8b30e358969f">isReservedReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a0bd1b194b601377bdb0f3a4a6e1f7e0d">llvm::MCRegisterInfo::regsOverlap</a>.</p>

</div>
</div>

### isFrameOffsetLegal() {#a7b0d5c1915330faa3a19839c10ccfd2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::isFrameOffsetLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> BaseReg, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3d42df7595bb7da318e52023ffe95226a11e259103be968c42cfd9c607f12904a">llvm::AArch64FrameOffsetIsLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#a0775e5fb52ac148f4d06e7eedb34e94e">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18dec717578f39bfcff50e325c2d27c5">llvm::isAArch64FrameOffsetLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a83f94d5dd8793554e6f3be24bc75eea5">needsFrameBaseReg</a>.</p>

</div>
</div>

### isReservedReg() {#a291580cc01efa41a004f8b30e358969f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::isReservedReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>Reference <a href="#a366a7f426707271b798b4355c12ce57d">getReservedRegs</a>.</p>


<p>Referenced by <a href="#aaaed10441dd729ce9fdc91120f2a77f0">isAsmClobberable</a>.</p>

</div>
</div>

### isStrictlyReservedReg() {#a999b53e29b4f65e8b69cc35300b4e1b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::isStrictlyReservedReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>Reference <a href="#a135ff03665f8746c89e91d3b802a1017">getStrictlyReservedRegs</a>.</p>


<p>Referenced by <a href="#a8f56fea99a4fd71730825c599b71f255">isAnyArgRegReserved</a>.</p>

</div>
</div>

### materializeFrameBaseRegister() {#a7321f8d9c50eb416611a0309a3fd9742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register AArch64RegisterInfo::materializeFrameBaseRegister (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, int FrameIdx, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert defining instruction(s) for BaseReg to be a pointer to FrameIdx at the beginning of the basic block.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#aeae88f12b667477f90db9b726556b337">llvm::AArch64_AM::getShifterImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a7e75394a33f6a5897d7a14c0ba5d44f1a1d97e13eb9923037fe733eda83b7f938">llvm::AArch64_AM::LSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### needsFrameBaseReg() {#a83f94d5dd8793554e6f3be24bc75eea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::needsFrameBaseReg (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>needsFrameBaseReg - Returns true if the instruction's frame index reference would be better served by a base register other than FP or SP.</p>


<p>Used by LocalStackFrameAllocation to determine which frame index references it should create new base registers for.</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aa306e1d00f65a9bb1030e66e9d195a69">llvm::MachineFrameInfo::getLocalFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="#a7b0d5c1915330faa3a19839c10ccfd2f">isFrameOffsetLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### regNeedsCFI() {#a96feb3493457dc69868b789630e4506b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::regNeedsCFI (unsigned Reg, unsigned &amp; RegToUseForCFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether the register needs a CFI entry.</p>


<p>Not all unwinders may know about SVE registers, so we assume the lowest common denominator, i.e. the callee-saves required by the base ABI. For the SVE registers z8-z15 only the lower 64-bits (d8-d15) need to be saved. The lower 64-bits subreg is returned in <span class="doxyComputerOutput">RegToUseForCFI</span>.</p>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### requiresFrameIndexScavenging() {#af81e5df3a149fe59116ca57fd66f92fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::requiresFrameIndexScavenging (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### requiresRegisterScavenging() {#a7926f85d35e77a4f1c4d9c041a0f7612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::requiresRegisterScavenging (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### requiresVirtualBaseRegisters() {#a51acc1b21295aa0d3e06392e26601e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::requiresVirtualBaseRegisters (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### resolveFrameIndex() {#a825b9cf5093b700f2b37cf4b7555af66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64RegisterInfo::resolveFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> BaseReg, int64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/classes/llvm/stackoffset/#a0775e5fb52ac148f4d06e7eedb34e94e">llvm::StackOffset::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acbe69ef233b07b4362366dcfc380abca">llvm::rewriteAArch64FrameIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### shouldAnalyzePhysregInMachineLoopInfo() {#aa6694e321bed1af36a3bdba1689dc1b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::shouldAnalyzePhysregInMachineLoopInfo (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 1227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### shouldCoalesce() {#a472cefd8107362b99710b1e58174b7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::shouldCoalesce (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * SrcRC, unsigned SubReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * DstRC, unsigned DstSubReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * NewRC, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SrcRC and DstRC will be morphed into NewRC if this returns true.</p>

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### SMEABISupportRoutinesCallPreservedMaskFromX0() {#ab79c1292e71ad692227eb056a527903f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * AArch64RegisterInfo::SMEABISupportRoutinesCallPreservedMaskFromX0 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>

</div>
</div>

### UpdateCustomCalleeSavedRegs() {#a776852734c11ae705971ee8d39e589c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64RegisterInfo::UpdateCustomCalleeSavedRegs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="#ac26dae5c257bfaab5aa15cab7255f107">getCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a8e92c78c91c9a864b7902df1502fb029">llvm::AArch64Subtarget::isXRegCustomCalleeSaved</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aaefaeb20cd3228ca22ecaff2fa385f9c">llvm::MachineRegisterInfo::setCalleeSavedRegs</a>.</p>

</div>
</div>

### UpdateCustomCallPreservedMask() {#ae0d8a95e0be5b8b7c9e31abc8ead009d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64RegisterInfo::UpdateCustomCallPreservedMask (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t ** Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6cba8c24b1495a6caff37e5e6df77aa2">llvm::MachineFunction::allocateRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9fd1f4d5c1460886c4aa983a2027d944">llvm::MachineOperand::getRegMaskSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a8e92c78c91c9a864b7902df1502fb029">llvm::AArch64Subtarget::isXRegCustomCalleeSaved</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>

</div>
</div>

### useFPForScavengingIndex() {#add6176251034fbacf30f8e906db5f347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64RegisterInfo::useFPForScavengingIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>, definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a7b316ba6e060bc850312c3d294130878">llvm::AArch64FunctionInfo::getStackSizeSVE</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#ad7bb9da1cdb51abc81f080b265948015">llvm::AArch64FunctionInfo::hasCalculatedStackSizeSVE</a> and <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TT {#a4e203e68fd0111fc59f2b9b168bb5923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple&amp; llvm::AArch64RegisterInfo::TT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-cpp">AArch64RegisterInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64registerinfo-h">AArch64RegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
