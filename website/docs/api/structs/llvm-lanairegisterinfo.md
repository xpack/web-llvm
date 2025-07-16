---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/lanairegisterinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LanaiRegisterInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::LanaiRegisterInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">Target/Lanai/LanaiRegisterInfo.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/lanaigenregisterinfo">LanaiGenRegisterInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102b1648f22faafbeb80a2a30afc7475">LanaiRegisterInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1525e5c75f830c4af2cdd1529f5aba2">getCallPreservedMask</a> (const MachineFunction &amp;MF, CallingConv::ID) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9953218d4775d6245cae83c5486eed43">getCalleeSavedRegs</a> (const MachineFunction *MF=nullptr) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65c8fddd5a839080a9e431da8a8ab61">getReservedRegs</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920c0dfaadd85c6a6bdc05549f4111b8">requiresRegisterScavenging</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd4d1d9eb28b9bca2ca401487bdf529e">eliminateFrameIndex</a> (MachineBasicBlock::iterator II, int SPAdj, unsigned FIOperandNum, RegScavenger *RS=nullptr) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b591a2e1e146b942b6eb5317c7452d9">getRARegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5374e905beb04c541bf428b2a0b68ee">getFrameRegister</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23fbd1ead47cd5da713ff699b551b791">getBaseRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e518a82dbb0c60127edda3a20c5e0e">hasBasePointer</a> (const MachineFunction &amp;MF) const</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LanaiRegisterInfo() {#a102b1648f22faafbeb80a2a30afc7475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LanaiRegisterInfo::LanaiRegisterInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### eliminateFrameIndex() {#acd4d1d9eb28b9bca2ca401487bdf529e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LanaiRegisterInfo::eliminateFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> II, int SPAdj, unsigned FIOperandNum, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lpac/#ab2e8fd263c886a713ccba7505c1b2ee0a25d8ba0c31384de6b8eaf87262199804">llvm::LPAC::ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a28849ec4920f5ee3f97d344633e695f4">llvm::RegScavenger::FindUnusedReg</a>, <a href="#a23fbd1ead47cd5da713ff699b551b791">getBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ac83b44e69c9f9f4f9d60be2d72f4a5df">llvm::TargetSubtargetInfo::getFrameLowering</a>, <a href="#ad5374e905beb04c541bf428b2a0b68ee">getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp/#ac70fe1e73bed9af455f151b43b10d1c1">getOppositeALULoOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp/#a32731a2172f546f3396775d0794504fe">getRRMOpcodeVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a14c39a24bf6ebbe339ae8a453c7fdd11">llvm::MachineFrameInfo::getStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a40e518a82dbb0c60127edda3a20c5e0e">hasBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a0c361440fb8d1e36932e65c8cc8497e7">llvm::TargetFrameLowering::hasFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a402439560272232a2e241a32dcb19f63a8deb801305591326bd46652c46a63af9">llvm::LPCC::ICC_T</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp/#a85c54b357503bde272ca075ff9a6babd">isALUArithLoOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2befc1248058bd700348223a8b71ad6f">llvm::isRMOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab19591c7c3d8dc58cbe780634371f9e8">llvm::isSPLSOpcode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a62d08c8303092539ecb1fde389108e7a">llvm::RegScavenger::scavengeRegisterBackwards</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpac/#ab2e8fd263c886a713ccba7505c1b2ee0aeac5360fd57cf828f2c5a7dda5978787">llvm::LPAC::SUB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getBaseRegister() {#a23fbd1ead47cd5da713ff699b551b791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LanaiRegisterInfo::getBaseRegister ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#af9008c34cdebe84ae9252952470f0599">llvm::LanaiFrameLowering::determineCalleeSaves</a>, <a href="#acd4d1d9eb28b9bca2ca401487bdf529e">eliminateFrameIndex</a> and <a href="#ad65c8fddd5a839080a9e431da8a8ab61">getReservedRegs</a>.</p>

</div>
</div>

### getCalleeSavedRegs() {#a9953218d4775d6245cae83c5486eed43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t * LanaiRegisterInfo::getCalleeSavedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>

</div>
</div>

### getCallPreservedMask() {#aa1525e5c75f830c4af2cdd1529f5aba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * LanaiRegisterInfo::getCallPreservedMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>

</div>
</div>

### getFrameRegister() {#ad5374e905beb04c541bf428b2a0b68ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LanaiRegisterInfo::getFrameRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>


<p>Referenced by <a href="#acd4d1d9eb28b9bca2ca401487bdf529e">eliminateFrameIndex</a>.</p>

</div>
</div>

### getRARegister() {#a3b591a2e1e146b942b6eb5317c7452d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LanaiRegisterInfo::getRARegister ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>

</div>
</div>

### getReservedRegs() {#ad65c8fddd5a839080a9e431da8a8ab61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector LanaiRegisterInfo::getReservedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>


<p>References <a href="#a23fbd1ead47cd5da713ff699b551b791">getBaseRegister</a>, <a href="#a40e518a82dbb0c60127edda3a20c5e0e">hasBasePointer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15a942d4e37dd5607ab68e54755540d4a47">llvm::Reserved</a>.</p>

</div>
</div>

### hasBasePointer() {#a40e518a82dbb0c60127edda3a20c5e0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LanaiRegisterInfo::hasBasePointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#af9008c34cdebe84ae9252952470f0599">llvm::LanaiFrameLowering::determineCalleeSaves</a>, <a href="#acd4d1d9eb28b9bca2ca401487bdf529e">eliminateFrameIndex</a> and <a href="#ad65c8fddd5a839080a9e431da8a8ab61">getReservedRegs</a>.</p>

</div>
</div>

### requiresRegisterScavenging() {#a920c0dfaadd85c6a6bdc05549f4111b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LanaiRegisterInfo::requiresRegisterScavenging (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-cpp">LanaiRegisterInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanairegisterinfo-h">LanaiRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
