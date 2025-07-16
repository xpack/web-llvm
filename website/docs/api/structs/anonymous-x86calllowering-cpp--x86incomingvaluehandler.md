---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-x86calllowering-cpp-/x86incomingvaluehandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `X86IncomingValueHandler` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{X86CallLowering.cpp}::X86IncomingValueHandler { ... }
</div>

## Base struct

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

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/callreturnhandler">CallReturnHandler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/formalarghandler">FormalArgHandler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ed74ee588be1658d093e6fab656062">X86IncomingValueHandler</a> (MachineIRBuilder &amp;MIRBuilder, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ebcdacc79bcbbbb515e69090df3ea18">getStackAddress</a> (uint64_t Size, int64_t Offset, MachinePointerInfo &amp;MPO, ISD::ArgFlagsTy Flags) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Materialize a VReg containing the address of the specified stack-based object. <a href="#a1ebcdacc79bcbbbb515e69090df3ea18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf3ef28ca2e33efc6438aa1a53d546ad">assignValueToAddress</a> (Register ValVReg, Register Addr, LLT MemTy, const MachinePointerInfo &amp;MPO, const CCValAssign &amp;VA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specified value has been assigned to a stack location. <a href="#adf3ef28ca2e33efc6438aa1a53d546ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f213b5ff147a3149479a99b3f55e6a">assignValueToReg</a> (Register ValVReg, Register PhysReg, const CCValAssign &amp;VA) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides a default implementation for argument handling. <a href="#ab0f213b5ff147a3149479a99b3f55e6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeae536ce102406b16626a08046eea70">markPhysRegUsed</a> (unsigned PhysReg)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How the physical register gets marked varies between formal parameters (it's a basic-block live-in), and a call instruction (it's an implicit-def of the BL). <a href="#aaeae536ce102406b16626a08046eea70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198f03d07fc732c440cd8e307d88cd5c">DL</a></td>
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


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86calllowering-cpp">X86CallLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86IncomingValueHandler() {#a48ed74ee588be1658d093e6fab656062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::X86IncomingValueHandler (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86calllowering-cpp">X86CallLowering.cpp</a>.</p>


<p>References <a href="#a198f03d07fc732c440cd8e307d88cd5c">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/incomingvaluehandler/#af7ca7bf1f0eb34e567785c99196e6329">llvm::CallLowering::IncomingValueHandler::IncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a3968b5fbbfcb762c497c4312c369dad6">llvm::CallLowering::ValueHandler::MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/callreturnhandler/#aba60b4cc93f20b792e87744999e562a5">anonymous{X86CallLowering.cpp}::CallReturnHandler::CallReturnHandler</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/formalarghandler/#a92f38dce810eac1af52fa24588e8963a">anonymous{X86CallLowering.cpp}::FormalArgHandler::FormalArgHandler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignValueToAddress() {#adf3ef28ca2e33efc6438aa1a53d546ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::assignValueToAddress (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValVReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Addr, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MemTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
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


<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86calllowering-cpp">X86CallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff719a7221f395b1b3849c9675ca32dd">llvm::inferAlignFromPtrInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac63dd9c4fe69bfeaac7a363fda846ac6">llvm::MachineMemOperand::MOInvariant</a> and <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>.</p>

</div>
</div>

### assignValueToReg() {#ab0f213b5ff147a3149479a99b3f55e6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::assignValueToReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ValVReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &amp; VA)</td>
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

<p>Provides a default implementation for argument handling.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86calllowering-cpp">X86CallLowering.cpp</a>.</p>


<p>Reference <a href="#aaeae536ce102406b16626a08046eea70">markPhysRegUsed</a>.</p>

</div>
</div>

### getStackAddress() {#a1ebcdacc79bcbbbb515e69090df3ea18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::getStackAddress (uint64_t MemSize, int64_t Offset, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo">MachinePointerInfo</a> &amp; MPO, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags)</td>
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


<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86calllowering-cpp">X86CallLowering.cpp</a>.</p>


<p>References <a href="#a198f03d07fc732c440cd8e307d88cd5c">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### markPhysRegUsed() {#aaeae536ce102406b16626a08046eea70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::markPhysRegUsed (unsigned PhysReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How the physical register gets marked varies between formal parameters (it's a basic-block live-in), and a call instruction (it's an implicit-def of the BL).</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86calllowering-cpp">X86CallLowering.cpp</a>.</p>


<p>Referenced by <a href="#ab0f213b5ff147a3149479a99b3f55e6a">assignValueToReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### DL {#a198f03d07fc732c440cd8e307d88cd5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{X86CallLowering.cpp}::X86IncomingValueHandler::DL</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86calllowering-cpp">X86CallLowering.cpp</a>.</p>


<p>Referenced by <a href="#a1ebcdacc79bcbbbb515e69090df3ea18">getStackAddress</a> and <a href="#a48ed74ee588be1658d093e6fab656062">X86IncomingValueHandler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86calllowering-cpp">X86CallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
