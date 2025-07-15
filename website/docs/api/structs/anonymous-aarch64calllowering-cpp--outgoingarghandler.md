---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OutgoingArgHandler` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvaluehandler">OutgoingValueHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for ValueHandlers used for arguments passed to a function call, or for return values. <a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvaluehandler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6dc2f76f75665ad05c2e84455992ce">OutgoingArgHandler</a> (MachineIRBuilder &amp;MIRBuilder, MachineRegisterInfo &amp;MRI, MachineInstrBuilder MIB, bool IsTailCall=false, int FPDiff=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11c07e0125e7cd5df9cd7747977f9638">getStackAddress</a> (uint64_t Size, int64_t Offset, MachinePointerInfo &amp;MPO, ISD::ArgFlagsTy Flags) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize a VReg containing the address of the specified stack-based object. <a href="#a11c07e0125e7cd5df9cd7747977f9638">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac99436d5d4df441878ecb554975338">getStackValueStoreType</a> (const DataLayout &amp;DL, const CCValAssign &amp;VA, ISD::ArgFlagsTy Flags) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We need to fixup the reported store size for certain value types because we invert the interpretation of ValVT and LocVT in certain cases. <a href="#a2ac99436d5d4df441878ecb554975338">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f01fb9e3b2a3122bef7bdb701394934">assignValueToReg</a> (Register ValVReg, Register PhysReg, const CCValAssign &amp;VA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified value has been assigned to a physical register, handle the appropriate COPY (either to or from) and mark any relevant uses/defines as needed. <a href="#a6f01fb9e3b2a3122bef7bdb701394934">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa068dacf95ae419eb2e19382e1889443">assignValueToAddress</a> (Register ValVReg, Register Addr, LLT MemTy, const MachinePointerInfo &amp;MPO, const CCValAssign &amp;VA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified value has been assigned to a stack location. <a href="#aa068dacf95ae419eb2e19382e1889443">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475797835e85ab2eee4c3364cfc79a2f">assignValueToAddress</a> (const CallLowering::ArgInfo &amp;Arg, unsigned RegIndex, Register Addr, LLT MemTy, const MachinePointerInfo &amp;MPO, const CCValAssign &amp;VA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An overload which takes an ArgInfo if additional information about the arg is needed. <a href="#a475797835e85ab2eee4c3364cfc79a2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd3d260a1329632c6e387e407baa20a">MIB</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae482ec643b8d916f88577d0ed0fd19c1">IsTailCall</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434907b21c437ea55bf2e32a4bc2ffc1">FPDiff</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For tail calls, the byte offset of the call's argument area from the callee's. <a href="#a434907b21c437ea55bf2e32a4bc2ffc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2eb8a693090e70190f7505b0b41eeab">SPReg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a910c738bf1dc8b1b62aea90988904cf2">Subtarget</a></td>
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


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OutgoingArgHandler() {#abe6dc2f76f75665ad05c2e84455992ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::OutgoingArgHandler (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> MIB, bool IsTailCall=false, int FPDiff=0)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="#a434907b21c437ea55bf2e32a4bc2ffc1">FPDiff</a>, <a href="#ae482ec643b8d916f88577d0ed0fd19c1">IsTailCall</a>, <a href="#a3bd3d260a1329632c6e387e407baa20a">MIB</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a3968b5fbbfcb762c497c4312c369dad6">llvm::CallLowering::ValueHandler::MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvaluehandler/#a819f3473cb5e18e9a50a73055fef4769">llvm::CallLowering::OutgoingValueHandler::OutgoingValueHandler</a> and <a href="#a910c738bf1dc8b1b62aea90988904cf2">Subtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignValueToAddress() {#aa068dacf95ae419eb2e19382e1889443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToAddress (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValVReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MemTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
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

<p>The specified value has been assigned to a stack location.</p>


<p>Load or store it there, with appropriate extension if necessary.</p>


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff719a7221f395b1b3849c9675ca32dd">llvm::inferAlignFromPtrInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>.</p>


<p>Referenced by <a href="#a475797835e85ab2eee4c3364cfc79a2f">assignValueToAddress</a>.</p>

</div>
</div>

### assignValueToAddress() {#a475797835e85ab2eee4c3364cfc79a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">CallLowering::ArgInfo</a> &amp; Arg, unsigned ValRegIndex, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MemTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
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

<p>An overload which takes an ArgInfo if additional information about the arg is needed.</p>


<p><span class="doxyComputerOutput">ValRegIndex</span> is the index in <span class="doxyComputerOutput">Arg.Regs</span> for the value to store.</p>


<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="#aa068dacf95ae419eb2e19382e1889443">assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a9b9867c23ea2c20125ffe635160cb9bb">llvm::CallLowering::ValueHandler::extendRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45ac52f457c429c17250b13662a5ddd0c4a">llvm::CCValAssign::FPExt</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2897ab064cc53e41f2b6ae3d69902abc">llvm::CCValAssign::getLocInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae456a811703836ee5d9e32c3e51a15b6">llvm::LLT::getSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5972ab02a98f9b5ce46e7f55fd711982">llvm::CCValAssign::getValVT</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/basearginfo/#adbd64ada64994ff4e291f50a0b742dff">llvm::CallLowering::BaseArgInfo::IsFixed</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#a15bd554291a003ec01a0f9e3cbfab8e5">llvm::CallLowering::ArgInfo::Regs</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### assignValueToReg() {#a6f01fb9e3b2a3122bef7bdb701394934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValVReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
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

<p>The specified value has been assigned to a physical register, handle the appropriate COPY (either to or from) and mark any relevant uses/defines as needed.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a9b9867c23ea2c20125ffe635160cb9bb">llvm::CallLowering::ValueHandler::extendRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="#a3bd3d260a1329632c6e387e407baa20a">MIB</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a>.</p>

</div>
</div>

### getStackAddress() {#a11c07e0125e7cd5df9cd7747977f9638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackAddress (uint64_t MemSize, int64_t Offset, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags)</td>
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

<p>Materialize a VReg containing the address of the specified stack-based object.</p>


<p>This is either based on a FrameIndex or direct SP manipulation, depending on the context. <span class="doxyComputerOutput">MPO</span> should be initialized to an appropriate description of the address created.</p>


<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a03cf34252938b54f7e86c736f9fd7dc1">llvm::MachineFrameInfo::CreateFixedObject</a>, <a href="#a434907b21c437ea55bf2e32a4bc2ffc1">FPDiff</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a2f877286c09d06ac6b9c5534736433d9">llvm::MachinePointerInfo::getStack</a>, <a href="#ae482ec643b8d916f88577d0ed0fd19c1">IsTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#aa2eb8a693090e70190f7505b0b41eeab">SPReg</a>.</p>

</div>
</div>

### getStackValueStoreType() {#a2ac99436d5d4df441878ecb554975338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackValueStoreType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags)</td>
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

<p>We need to fixup the reported store size for certain value types because we invert the interpretation of ValVT and LocVT in certain cases.</p>


<p>This is for compatability with the DAG call lowering implementation, which we're currently building on top of.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a5176666164b27a32c0b6093b921cde29">llvm::CallLowering::ValueHandler::getStackValueStoreType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a77c170f4c52ebc0ecaeaae4a2b660916">getStackValueStoreTypeHack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FPDiff {#a434907b21c437ea55bf2e32a4bc2ffc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::FPDiff</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For tail calls, the byte offset of the call's argument area from the callee's.</p>


<p>Unused elsewhere.</p>


<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a11c07e0125e7cd5df9cd7747977f9638">getStackAddress</a> and <a href="#abe6dc2f76f75665ad05c2e84455992ce">OutgoingArgHandler</a>.</p>

</div>
</div>

### IsTailCall {#ae482ec643b8d916f88577d0ed0fd19c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::IsTailCall</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a11c07e0125e7cd5df9cd7747977f9638">getStackAddress</a> and <a href="#abe6dc2f76f75665ad05c2e84455992ce">OutgoingArgHandler</a>.</p>

</div>
</div>

### MIB {#a3bd3d260a1329632c6e387e407baa20a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::MIB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a6f01fb9e3b2a3122bef7bdb701394934">assignValueToReg</a> and <a href="#abe6dc2f76f75665ad05c2e84455992ce">OutgoingArgHandler</a>.</p>

</div>
</div>

### SPReg {#aa2eb8a693090e70190f7505b0b41eeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::SPReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a11c07e0125e7cd5df9cd7747977f9638">getStackAddress</a>.</p>

</div>
</div>

### Subtarget {#a910c738bf1dc8b1b62aea90988904cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64Subtarget&amp; anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a>.</p>


<p>Referenced by <a href="#abe6dc2f76f75665ad05c2e84455992ce">OutgoingArgHandler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp">AArch64CallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
