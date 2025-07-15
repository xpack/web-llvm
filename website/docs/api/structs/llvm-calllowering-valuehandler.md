---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/calllowering/valuehandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ValueHandler` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::CallLowering::ValueHandler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">llvm/CodeGen/GlobalISel/CallLowering.h</a>"
</div>

## Derived Structs

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57eb691d08960d04de928d7bd856fef">ValueHandler</a> (bool IsIncoming, MachineIRBuilder &amp;MIRBuilder, MachineRegisterInfo &amp;MRI)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6a572494d4dbb02c575cb7d8540eaa">~ValueHandler</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e3835a69edc9dcb7eed477ae19a72cb">isIncomingArgumentHandler</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the handler is dealing with incoming arguments, i.e. <a href="#a7e3835a69edc9dcb7eed477ae19a72cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c59b9c547e0a0eaab82ed083154ee22">getStackAddress</a> (uint64_t MemSize, int64_t Offset, MachinePointerInfo &amp;MPO, ISD::ArgFlagsTy Flags)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize a VReg containing the address of the specified stack-based object. <a href="#a3c59b9c547e0a0eaab82ed083154ee22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5176666164b27a32c0b6093b921cde29">getStackValueStoreType</a> (const DataLayout &amp;DL, const CCValAssign &amp;VA, ISD::ArgFlagsTy Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the in-memory size to write for the argument at <span class="doxyComputerOutput">VA</span>. <a href="#a5176666164b27a32c0b6093b921cde29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae29b02231f034b1c8c9f9d5de549d706">assignValueToReg</a> (Register ValVReg, Register PhysReg, const CCValAssign &amp;VA)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified value has been assigned to a physical register, handle the appropriate COPY (either to or from) and mark any relevant uses/defines as needed. <a href="#ae29b02231f034b1c8c9f9d5de549d706">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d06ef014ba7f9e056d6765150614386">assignValueToAddress</a> (Register ValVReg, Register Addr, LLT MemTy, const MachinePointerInfo &amp;MPO, const CCValAssign &amp;VA)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified value has been assigned to a stack location. <a href="#a8d06ef014ba7f9e056d6765150614386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca87ef18ce284cfcf8e69d180b08979">assignValueToAddress</a> (const ArgInfo &amp;Arg, unsigned ValRegIndex, Register Addr, LLT MemTy, const MachinePointerInfo &amp;MPO, const CCValAssign &amp;VA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An overload which takes an <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> if additional information about the arg is needed. <a href="#a4ca87ef18ce284cfcf8e69d180b08979">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcdfa9adfee0c237b61d8708183f1006">assignCustomValue</a> (ArgInfo &amp;Arg, ArrayRef&lt; CCValAssign &gt; VAs, std::function&lt; void()&gt; *Thunk=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle custom values, which may be passed into one or more of <span class="doxyComputerOutput">VAs</span>. <a href="#abcdfa9adfee0c237b61d8708183f1006">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a681b9303b51d21a9392975a6cd422c">copyArgumentMemory</a> (const ArgInfo &amp;Arg, Register DstPtr, Register SrcPtr, const MachinePointerInfo &amp;DstPtrInfo, Align DstAlign, const MachinePointerInfo &amp;SrcPtrInfo, Align SrcAlign, uint64_t MemSize, CCValAssign &amp;VA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do a memory copy of <span class="doxyComputerOutput">MemSize</span> bytes from <span class="doxyComputerOutput">SrcPtr</span> to <span class="doxyComputerOutput">DstPtr</span>. <a href="#a2a681b9303b51d21a9392975a6cd422c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b9867c23ea2c20125ffe635160cb9bb">extendRegister</a> (Register ValReg, const CCValAssign &amp;VA, unsigned MaxSizeBits=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extend a register to the location type given in VA, capped at extending to at most MaxSize bits. <a href="#a9b9867c23ea2c20125ffe635160cb9bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00344e2d8f7ad399989bf320adf73aa8">MIRBuilder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3968b5fbbfcb762c497c4312c369dad6">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a6b8e9d83180d85446a3f663b1700cf">IsIncomingArgumentHandler</a></td>
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


<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ValueHandler() {#af57eb691d08960d04de928d7bd856fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallLowering::ValueHandler::ValueHandler (bool IsIncoming, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>References <a href="#a3a6b8e9d83180d85446a3f663b1700cf">IsIncomingArgumentHandler</a>, <a href="#a00344e2d8f7ad399989bf320adf73aa8">MIRBuilder</a> and <a href="#a3968b5fbbfcb762c497c4312c369dad6">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#af7ca7bf1f0eb34e567785c99196e6329">llvm::CallLowering::IncomingValueHandler::IncomingValueHandler</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvaluehandler/#a819f3473cb5e18e9a50a73055fef4769">llvm::CallLowering::OutgoingValueHandler::OutgoingValueHandler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ValueHandler() {#a2b6a572494d4dbb02c575cb7d8540eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::CallLowering::ValueHandler::~ValueHandler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignCustomValue() {#abcdfa9adfee0c237b61d8708183f1006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::CallLowering::ValueHandler::assignCustomValue (<a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> &amp; Arg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &gt; VAs, std::function&lt; void()&gt; * Thunk=nullptr)</td>
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

<p>Handle custom values, which may be passed into one or more of <span class="doxyComputerOutput">VAs</span>.</p>


<p><span class="doxyComputerOutput">If</span> the handler wants the assignments to be delayed until after mem loc assignments, then it sets <span class="doxyComputerOutput">Thunk</span> to the thunk to do the assignment.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of <span class="doxyComputerOutput">VAs</span> that have been assigned including the first one, and which should therefore be skipped from further processing.</p></dd>
</dl>


<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### assignValueToAddress() {#a8d06ef014ba7f9e056d6765150614386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::CallLowering::ValueHandler::assignValueToAddress (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValVReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MemTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The specified value has been assigned to a stack location.</p>


<p>Load or store it there, with appropriate extension if necessary.</p>


<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="#a4ca87ef18ce284cfcf8e69d180b08979">assignValueToAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### assignValueToAddress() {#a4ca87ef18ce284cfcf8e69d180b08979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::CallLowering::ValueHandler::assignValueToAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> &amp; Arg, unsigned ValRegIndex, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MemTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
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

<p>An overload which takes an <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> if additional information about the arg is needed.</p>


<p><span class="doxyComputerOutput">ValRegIndex</span> is the index in <span class="doxyComputerOutput">Arg.Regs</span> for the value to store.</p>


<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>References <a href="#a8d06ef014ba7f9e056d6765150614386">assignValueToAddress</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#a15bd554291a003ec01a0f9e3cbfab8e5">llvm::CallLowering::ArgInfo::Regs</a>.</p>

</div>
</div>

### assignValueToReg() {#ae29b02231f034b1c8c9f9d5de549d706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::CallLowering::ValueHandler::assignValueToReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValVReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The specified value has been assigned to a physical register, handle the appropriate COPY (either to or from) and mark any relevant uses/defines as needed.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### copyArgumentMemory() {#a2a681b9303b51d21a9392975a6cd422c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallLowering::ValueHandler::copyArgumentMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a> &amp; Arg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstPtr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcPtr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; DstPtrInfo, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> DstAlign, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; SrcPtrInfo, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> SrcAlign, uint64_t MemSize, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do a memory copy of <span class="doxyComputerOutput">MemSize</span> bytes from <span class="doxyComputerOutput">SrcPtr</span> to <span class="doxyComputerOutput">DstPtr</span>.</p>


<p>This is necessary for outgoing stack-passed byval arguments.</p>


<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>, definition at line 1268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a00344e2d8f7ad399989bf320adf73aa8">MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7b999a936bc7a4d45dfadbe356e77b3f">llvm::MachineMemOperand::MODereferenceable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="#a3968b5fbbfcb762c497c4312c369dad6">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### extendRegister() {#a9b9867c23ea2c20125ffe635160cb9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register CallLowering::ValueHandler::extendRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA, unsigned MaxSizeBits=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extend a register to the location type given in VA, capped at extending to at most MaxSize bits.</p>


<p>If MaxSizeBits is 0 then no maximum is set.</p>


<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>, definition at line 1291 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45acc07b91f72979f3e9b12c2e0c355db46">llvm::CCValAssign::AExt</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a0f94adbbe71c94edaa533a25973bbffc">llvm::CCValAssign::BCvt</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a8b73d77b9e54663c2e80a48d0917dce1">llvm::CCValAssign::Full</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2897ab064cc53e41f2b6ae3d69902abc">llvm::CCValAssign::getLocInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#ab7c2e47e51795ce2f60500846109d5a7">llvm::CCValAssign::getLocVT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5972ab02a98f9b5ce46e7f55fd711982">llvm::CCValAssign::getValVT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a9d825f5954d7bd527aea490668c624c6">llvm::LLT::isPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a00344e2d8f7ad399989bf320adf73aa8">MIRBuilder</a>, <a href="#a3968b5fbbfcb762c497c4312c369dad6">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a7fd25972cdb14499949c7726499e0cb6">llvm::CCValAssign::SExt</a> and <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45a807a4e133d7f743724d809a3f3875aa2">llvm::CCValAssign::ZExt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a475797835e85ab2eee4c3364cfc79a2f">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#aa0e53803ef9c1e4cee4e195ced9c0841">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a7bb32d82d6f5b07876cebd105601f5cc">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#af1779518d5baec53b2ce17673169282f">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#a51477dade1ea8ff142a3c4d2bbfbfc3e">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#a93f62c76d3a18dfdb05e79ce365d424f">M68kOutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a6f01fb9e3b2a3122bef7bdb701394934">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a8037cdaaf593bc895700f71a95ee9bcc">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppccalllowering-cpp-/outgoingarghandler/#acc95bad51875324c4736816a511edb50">anonymous{PPCCallLowering.cpp}::OutgoingArgHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#ae0cbdaa8c809b18f554f6665e38d51b9">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#a5e4b5b2c4846435ed01ae207b6ebc436">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#ad73336dfe5539da4a516f31cbfda08c4">M68kOutgoingArgHandler::assignValueToReg</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucalllowering-cpp-/#af49a6097a8071a69f37f57febd91c05c">anonymous{AMDGPUCallLowering.cpp}::extendRegisterMin32</a>.</p>

</div>
</div>

### getStackAddress() {#a3c59b9c547e0a0eaab82ed083154ee22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Register llvm::CallLowering::ValueHandler::getStackAddress (uint64_t MemSize, int64_t Offset, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Materialize a VReg containing the address of the specified stack-based object.</p>


<p>This is either based on a FrameIndex or direct SP manipulation, depending on the context. <span class="doxyComputerOutput">MPO</span> should be initialized to an appropriate description of the address created.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### getStackValueStoreType() {#a5176666164b27a32c0b6093b921cde29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT CallLowering::ValueHandler::getStackValueStoreType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags)</td>
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

<p>Return the in-memory size to write for the argument at <span class="doxyComputerOutput">VA</span>.</p>


<p>This may be smaller than the allocated stack slot size.</p>


<p>This is overridable primarily for targets to maintain compatibility with hacks around the existing DAG call lowering infrastructure.</p>


<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>, definition at line 1245 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a5972ab02a98f9b5ce46e7f55fd711982">llvm::CCValAssign::getValVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#ad743c42316a13699646a3ed402aab910">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::getStackValueStoreType</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a2ac99436d5d4df441878ecb554975338">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackValueStoreType</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

### isIncomingArgumentHandler() {#a7e3835a69edc9dcb7eed477ae19a72cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallLowering::ValueHandler::isIncomingArgumentHandler ()</td>
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

<p>Returns true if the handler is dealing with incoming arguments, i.e.</p>


<p>those that move values from some physical location to vregs.</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Reference <a href="#a3a6b8e9d83180d85446a3f663b1700cf">IsIncomingArgumentHandler</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsIncomingArgumentHandler {#a3a6b8e9d83180d85446a3f663b1700cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::CallLowering::ValueHandler::IsIncomingArgumentHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="#a7e3835a69edc9dcb7eed477ae19a72cb">isIncomingArgumentHandler</a> and <a href="#af57eb691d08960d04de928d7bd856fef">ValueHandler</a>.</p>

</div>
</div>

### MIRBuilder {#a00344e2d8f7ad399989bf320adf73aa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilder&amp; llvm::CallLowering::ValueHandler::MIRBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a3f3f7e9576f13da710c95f08fdab7b3b">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::AMDGPUOutgoingArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a48c5d90707badc56101aef2ec9d36505">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::ARMIncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#abe7fe8fa26a06be69eeaab70c5068395">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::ARMOutgoingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a2d9bff6057c95e354dbc28e4604517c0">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#ac2990fcd086ddeb552b46fe5d49c77de">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a1cdf9ea1d249387f26e37569d6cdb088">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#aa068dacf95ae419eb2e19382e1889443">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuincomingarghandler/#aacea4b8961ff61ec169565ec617bfd94">anonymous{AMDGPUCallLowering.cpp}::AMDGPUIncomingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a4017f4bbfa6740ad4927245ad4dba2c4">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a84f5d960aa6e996db2572c7d5c7b163e">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a7bb32d82d6f5b07876cebd105601f5cc">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#ac44ad4f487564d8b9ae3418b9b3c55d4">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#af1779518d5baec53b2ce17673169282f">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86incomingvaluehandler/#adf3ef28ca2e33efc6438aa1a53d546ad">anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#a51477dade1ea8ff142a3c4d2bbfbfc3e">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#a93f62c76d3a18dfdb05e79ce365d424f">M68kOutgoingArgHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a6f01fb9e3b2a3122bef7bdb701394934">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuincomingarghandler/#a3769dc3bae28271b452cf69cf3494761">anonymous{AMDGPUCallLowering.cpp}::AMDGPUIncomingArgHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingvaluehandler/#a0d589439dcf785bc8f36eaf8f4b25a90">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#aa35ca40243a91b75afd51c04ee241788">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a8037cdaaf593bc895700f71a95ee9bcc">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppccalllowering-cpp-/outgoingarghandler/#acc95bad51875324c4736816a511edb50">anonymous{PPCCallLowering.cpp}::OutgoingArgHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#ae0cbdaa8c809b18f554f6665e38d51b9">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#a5e4b5b2c4846435ed01ae207b6ebc436">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#a2d2d74818c4f4ba5fb41e8a4f2c9d152">llvm::CallLowering::IncomingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#ad73336dfe5539da4a516f31cbfda08c4">M68kOutgoingArgHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#a64309ae031097cf3cde8199ea5e0249a">llvm::CallLowering::IncomingValueHandler::buildExtensionHint</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a1623bba2a28207a4ded0016ebfb5e841">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::buildLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/callreturnhandler/#a9f8fbd9537ea49488a90f02d2faedfd5">anonymous{AArch64CallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/callreturnhandler/#a1c08b46bb0f0ce8109d5231dea0d5ccb">anonymous{AMDGPUCallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/callreturnhandler/#a5ce3c284a61b868289f984e9fa8883db">anonymous{ARMCallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-m68kcalllowering-cpp-/callreturnhandler/#aa723d0e3d2386c7fd147b2a541dbc45c">anonymous{M68kCallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipscalllowering-cpp-/callreturnhandler/#aa8ffa53566af906102119e02500ddb2c">anonymous{MipsCallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/callreturnhandler/#aba60b4cc93f20b792e87744999e562a5">anonymous{X86CallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="#a2a681b9303b51d21a9392975a6cd422c">copyArgumentMemory</a>, <a href="#a9b9867c23ea2c20125ffe635160cb9bb">extendRegister</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucalllowering-cpp-/#af49a6097a8071a69f37f57febd91c05c">anonymous{AMDGPUCallLowering.cpp}::extendRegisterMin32</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/formalarghandler/#acb2df6cb79d00fe36a21009742e3c791">anonymous{AArch64CallLowering.cpp}::FormalArgHandler::FormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/formalarghandler/#ab5b37a7c0224961068f483dbd75fdf63">anonymous{ARMCallLowering.cpp}::FormalArgHandler::FormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/formalarghandler/#a92f38dce810eac1af52fa24588e8963a">anonymous{X86CallLowering.cpp}::FormalArgHandler::FormalArgHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/formalarghandler/#a319e507ba00910ab903cdfa735edd975">llvm::FormalArgHandler::FormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a18bab7a0c4783a00f51d05cae58ee7da">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a11c07e0125e7cd5df9cd7747977f9638">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuincomingarghandler/#a84d626ad52140616b26b997d67d2c7b1">anonymous{AMDGPUCallLowering.cpp}::AMDGPUIncomingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a6901759e2aab843e39497ccb23a0c3cd">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#ab81aa7a77f61bbabb3f265712cd8ad53">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a1de30cc152058819888b9d02619f16ac">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a2cc4d384d22ddae8f252b9cbb9313949">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a0256194175f52db6cc06eb379bd412dc">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86incomingvaluehandler/#a1ebcdacc79bcbbbb515e69090df3ea18">anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#a059b61bb0bab07b3cf7da0e06f5893dd">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#a202a7e2a16e7921c97c6767cb68bdae9">M68kOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a63875c269012585d1f3acd8ff022c31e">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::IncomingArgHandler</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#af7ca7bf1f0eb34e567785c99196e6329">llvm::CallLowering::IncomingValueHandler::IncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-m68kcalllowering-cpp-/m68kformalarghandler/#a7999e1fa7147d5c6ef25882a7bf4ea24">anonymous{M68kCallLowering.cpp}::M68kFormalArgHandler::M68kFormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/llvm/m68kincomingvaluehandler/#af18481c75471789521e880b9cc6b9604">llvm::M68kIncomingValueHandler::M68kIncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#a3a32c81eafeede36c05051316c93b56a">M68kOutgoingArgHandler::M68kOutgoingArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/formalarghandler/#a7cb2c06b2a37235c3f9342f881f17f86">anonymous{AMDGPUCallLowering.cpp}::FormalArgHandler::markPhysRegUsed</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/formalarghandler/#a0ef67a91bac56498bb34ffb93a78bbd8">anonymous{ARMCallLowering.cpp}::FormalArgHandler::markPhysRegUsed</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvformalarghandler/#a5ff47d17cd3b6cda5f35bc08babe6c95">anonymous{RISCVCallLowering.cpp}::RISCVFormalArgHandler::markPhysRegUsed</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/formalarghandler/#a430d436fcee1557b8f68930131a8146e">anonymous{X86CallLowering.cpp}::FormalArgHandler::markPhysRegUsed</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/formalarghandler/#adcfd19dc2b787e76fa42f4177b568570">anonymous{AArch64CallLowering.cpp}::FormalArgHandler::markRegUsed</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipscalllowering-cpp-/mipsincomingvaluehandler/#a5ddce66dc2761f591fde1bbbcbcd2eb6">anonymous{MipsCallLowering.cpp}::MipsIncomingValueHandler::MipsIncomingValueHandler</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipscalllowering-cpp-/mipsoutgoingvaluehandler/#a2de6aec8b7c13cda20302d6e51136ca1">anonymous{MipsCallLowering.cpp}::MipsOutgoingValueHandler::MipsOutgoingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#abe6dc2f76f75665ad05c2e84455992ce">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::OutgoingArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppccalllowering-cpp-/outgoingarghandler/#acce176a1457f4f55616067d0a24674e8">anonymous{PPCCallLowering.cpp}::OutgoingArgHandler::OutgoingArgHandler</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvaluehandler/#a819f3473cb5e18e9a50a73055fef4769">llvm::CallLowering::OutgoingValueHandler::OutgoingValueHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcincomingvaluehandler/#a2a7d0ff4191a23301f1f407bbfd61864">llvm::PPCIncomingValueHandler::PPCIncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/returnedargcallreturnhandler/#a75646b0937f62780e8c68ad234685bd8">anonymous{AArch64CallLowering.cpp}::ReturnedArgCallReturnHandler::ReturnedArgCallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#ab0bd7f08eabd70317e7b6372fb357e63">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::RISCVIncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a7dd5f130336672f544c9e240117a3a97">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::RISCVOutgoingValueHandler</a>, <a href="#af57eb691d08960d04de928d7bd856fef">ValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86incomingvaluehandler/#a48ed74ee588be1658d093e6fab656062">anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::X86IncomingValueHandler</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#aebc5846279c41e08d1c6bc01cd0150bc">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::X86OutgoingValueHandler</a>.</p>

</div>
</div>

### MRI {#a3968b5fbbfcb762c497c4312c369dad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::CallLowering::ValueHandler::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuincomingarghandler/#a183dd103180aa68731288be9ea5d4be8">anonymous{AMDGPUCallLowering.cpp}::AMDGPUIncomingArgHandler::AMDGPUIncomingArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a3f3f7e9576f13da710c95f08fdab7b3b">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::AMDGPUOutgoingArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingvaluehandler/#a9529c4bfec7e851518c268c837d866f3">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingValueHandler::AMDGPUOutgoingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a48c5d90707badc56101aef2ec9d36505">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::ARMIncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#abe7fe8fa26a06be69eeaab70c5068395">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::ARMOutgoingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a2d9bff6057c95e354dbc28e4604517c0">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#ac2990fcd086ddeb552b46fe5d49c77de">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a84f5d960aa6e996db2572c7d5c7b163e">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignValueToAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingvaluehandler/#a0d589439dcf785bc8f36eaf8f4b25a90">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#a2d2d74818c4f4ba5fb41e8a4f2c9d152">llvm::CallLowering::IncomingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#a64309ae031097cf3cde8199ea5e0249a">llvm::CallLowering::IncomingValueHandler::buildExtensionHint</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/callreturnhandler/#a9f8fbd9537ea49488a90f02d2faedfd5">anonymous{AArch64CallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/callreturnhandler/#a1c08b46bb0f0ce8109d5231dea0d5ccb">anonymous{AMDGPUCallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/callreturnhandler/#a5ce3c284a61b868289f984e9fa8883db">anonymous{ARMCallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-m68kcalllowering-cpp-/callreturnhandler/#aa723d0e3d2386c7fd147b2a541dbc45c">anonymous{M68kCallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipscalllowering-cpp-/callreturnhandler/#aa8ffa53566af906102119e02500ddb2c">anonymous{MipsCallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/callreturnhandler/#aba60b4cc93f20b792e87744999e562a5">anonymous{X86CallLowering.cpp}::CallReturnHandler::CallReturnHandler</a>, <a href="#a2a681b9303b51d21a9392975a6cd422c">copyArgumentMemory</a>, <a href="#a9b9867c23ea2c20125ffe635160cb9bb">extendRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/formalarghandler/#acb2df6cb79d00fe36a21009742e3c791">anonymous{AArch64CallLowering.cpp}::FormalArgHandler::FormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/formalarghandler/#aa7d027d485b67ef429e4dea9101aa331">anonymous{AMDGPUCallLowering.cpp}::FormalArgHandler::FormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/formalarghandler/#ab5b37a7c0224961068f483dbd75fdf63">anonymous{ARMCallLowering.cpp}::FormalArgHandler::FormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/formalarghandler/#a92f38dce810eac1af52fa24588e8963a">anonymous{X86CallLowering.cpp}::FormalArgHandler::FormalArgHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/formalarghandler/#a319e507ba00910ab903cdfa735edd975">llvm::FormalArgHandler::FormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/incomingarghandler/#a63875c269012585d1f3acd8ff022c31e">anonymous{AArch64CallLowering.cpp}::IncomingArgHandler::IncomingArgHandler</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#af7ca7bf1f0eb34e567785c99196e6329">llvm::CallLowering::IncomingValueHandler::IncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-m68kcalllowering-cpp-/m68kformalarghandler/#a7999e1fa7147d5c6ef25882a7bf4ea24">anonymous{M68kCallLowering.cpp}::M68kFormalArgHandler::M68kFormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/llvm/m68kincomingvaluehandler/#af18481c75471789521e880b9cc6b9604">llvm::M68kIncomingValueHandler::M68kIncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#a3a32c81eafeede36c05051316c93b56a">M68kOutgoingArgHandler::M68kOutgoingArgHandler</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipscalllowering-cpp-/mipsincomingvaluehandler/#a5ddce66dc2761f591fde1bbbcbcd2eb6">anonymous{MipsCallLowering.cpp}::MipsIncomingValueHandler::MipsIncomingValueHandler</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipscalllowering-cpp-/mipsoutgoingvaluehandler/#a2de6aec8b7c13cda20302d6e51136ca1">anonymous{MipsCallLowering.cpp}::MipsOutgoingValueHandler::MipsOutgoingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#abe6dc2f76f75665ad05c2e84455992ce">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::OutgoingArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppccalllowering-cpp-/outgoingarghandler/#acce176a1457f4f55616067d0a24674e8">anonymous{PPCCallLowering.cpp}::OutgoingArgHandler::OutgoingArgHandler</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/outgoingvaluehandler/#a819f3473cb5e18e9a50a73055fef4769">llvm::CallLowering::OutgoingValueHandler::OutgoingValueHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcincomingvaluehandler/#a2a7d0ff4191a23301f1f407bbfd61864">llvm::PPCIncomingValueHandler::PPCIncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/returnedargcallreturnhandler/#a75646b0937f62780e8c68ad234685bd8">anonymous{AArch64CallLowering.cpp}::ReturnedArgCallReturnHandler::ReturnedArgCallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvcallreturnhandler/#aa3bde19f13090c9036907641d370b39a">anonymous{RISCVCallLowering.cpp}::RISCVCallReturnHandler::RISCVCallReturnHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvformalarghandler/#aff2d4e09e78bd02a8e81daba36e0f4d6">anonymous{RISCVCallLowering.cpp}::RISCVFormalArgHandler::RISCVFormalArgHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#ab0bd7f08eabd70317e7b6372fb357e63">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::RISCVIncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a7dd5f130336672f544c9e240117a3a97">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::RISCVOutgoingValueHandler</a>, <a href="#af57eb691d08960d04de928d7bd856fef">ValueHandler</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86incomingvaluehandler/#a48ed74ee588be1658d093e6fab656062">anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::X86IncomingValueHandler</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#aebc5846279c41e08d1c6bc01cd0150bc">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::X86OutgoingValueHandler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp">CallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
