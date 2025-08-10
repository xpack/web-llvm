---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mipscalllowering-cpp-/mipsincomingvaluehandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MipsIncomingValueHandler` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{MipsCallLowering.cpp}::MipsIncomingValueHandler { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler">IncomingValueHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for ValueHandlers used for arguments coming into the current function, or for return values received from a call. <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mipscalllowering-cpp-/callreturnhandler">CallReturnHandler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ddce66dc2761f591fde1bbbcbcd2eb6">MipsIncomingValueHandler</a> (MachineIRBuilder &amp;MIRBuilder, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ec4325e51971db2ac0a25a3ada521e">assignValueToReg</a> (Register ValVReg, Register PhysReg, const CCValAssign &amp;VA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides a default implementation for argument handling. <a href="#af9ec4325e51971db2ac0a25a3ada521e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00fb5d3ab9ae791d5ce59a5160419df5">getStackAddress</a> (uint64_t Size, int64_t Offset, MachinePointerInfo &amp;MPO, ISD::ArgFlagsTy Flags) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize a VReg containing the address of the specified stack-based object. <a href="#a00fb5d3ab9ae791d5ce59a5160419df5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5a6bd7f6f5ed239c5e2e220909a23a0">assignValueToAddress</a> (Register ValVReg, Register Addr, LLT MemTy, const MachinePointerInfo &amp;MPO, const CCValAssign &amp;VA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified value has been assigned to a stack location. <a href="#ac5a6bd7f6f5ed239c5e2e220909a23a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d6c2caf8e37548bebbe758c101612e">assignCustomValue</a> (CallLowering::ArgInfo &amp;Arg, ArrayRef&lt; CCValAssign &gt; VAs, std::function&lt; void()&gt; *Thunk=nullptr) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle cases when f64 is split into 2 32-bit GPRs. <a href="#ab2d6c2caf8e37548bebbe758c101612e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f9cf093fb75961ced8f240ce47efbfb">markPhysRegUsed</a> (unsigned PhysReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ef85cf2d43aa715a6c4c61021b0983">STI</a></td>
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


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsIncomingValueHandler() {#a5ddce66dc2761f591fde1bbbcbcd2eb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MipsCallLowering.cpp}::MipsIncomingValueHandler::MipsIncomingValueHandler (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#af7ca7bf1f0eb34e567785c99196e6329">llvm::CallLowering::IncomingValueHandler::IncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a3968b5fbbfcb762c497c4312c369dad6">llvm::CallLowering::ValueHandler::MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mipscalllowering-cpp-/callreturnhandler/#aa8ffa53566af906102119e02500ddb2c">anonymous{MipsCallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### assignCustomValue() {#ab2d6c2caf8e37548bebbe758c101612e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsIncomingValueHandler::assignCustomValue (<a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">CallLowering::ArgInfo</a> &amp; Arg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &gt; VAs, std::function&lt; void()&gt; * Thunk=nullptr)</td>
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

<p>Handle cases when f64 is split into 2 32-bit GPRs.</p>


<p>This is a custom assignment because generic code assumes getNumRegistersForCallingConv is accurate. In this case it is not because the type/number are context dependent on other arguments.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>

</div>
</div>

### assignValueToAddress() {#ac5a6bd7f6f5ed239c5e2e220909a23a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsIncomingValueHandler::assignValueToAddress (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValVReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MemTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
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

<p>The specified value has been assigned to a stack location.</p>


<p>Load or store it there, with appropriate extension if necessary.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>

</div>
</div>

### assignValueToReg() {#af9ec4325e51971db2ac0a25a3ada521e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsIncomingValueHandler::assignValueToReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValVReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
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

<p>Provides a default implementation for argument handling.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>

</div>
</div>

### getStackAddress() {#a00fb5d3ab9ae791d5ce59a5160419df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MipsIncomingValueHandler::getStackAddress (uint64_t MemSize, int64_t Offset, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags)</td>
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

<p>Materialize a VReg containing the address of the specified stack-based object.</p>


<p>This is either based on a FrameIndex or direct SP manipulation, depending on the context. <span class="doxyComputerOutput">MPO</span> should be initialized to an appropriate description of the address created.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>

</div>
</div>

### markPhysRegUsed() {#a1f9cf093fb75961ced8f240ce47efbfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{MipsCallLowering.cpp}::MipsIncomingValueHandler::markPhysRegUsed (unsigned PhysReg)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### STI {#a57ef85cf2d43aa715a6c4c61021b0983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MipsSubtarget&amp; anonymous{MipsCallLowering.cpp}::MipsIncomingValueHandler::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipscalllowering-cpp">MipsCallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
