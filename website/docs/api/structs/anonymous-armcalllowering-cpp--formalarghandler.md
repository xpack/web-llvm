---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-armcalllowering-cpp-/formalarghandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FormalArgHandler` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{ARMCallLowering.cpp}::FormalArgHandler { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler">ARMIncomingValueHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class for values coming in through an ABI boundary (used for handling formal arguments and call return values). <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5b37a7c0224961068f483dbd75fdf63">FormalArgHandler</a> (MachineIRBuilder &amp;MIRBuilder, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef67a91bac56498bb34ffb93a78bbd8">markPhysRegUsed</a> (unsigned PhysReg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marking a physical register as used is different between formal parameters, where it's a basic block live-in, and call returns, where it's an implicit-def of the call instruction. <a href="#a0ef67a91bac56498bb34ffb93a78bbd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-cpp">ARMCallLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FormalArgHandler() {#ab5b37a7c0224961068f483dbd75fdf63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMCallLowering.cpp}::FormalArgHandler::FormalArgHandler (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-cpp">ARMCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a48c5d90707badc56101aef2ec9d36505">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::ARMIncomingValueHandler</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a> and <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a3968b5fbbfcb762c497c4312c369dad6">llvm::CallLowering::ValueHandler::MRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### markPhysRegUsed() {#a0ef67a91bac56498bb34ffb93a78bbd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ARMCallLowering.cpp}::FormalArgHandler::markPhysRegUsed (unsigned PhysReg)</td>
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

<p>Marking a physical register as used is different between formal parameters, where it's a basic block live-in, and call returns, where it's an implicit-def of the call instruction.</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-cpp">ARMCallLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcalllowering-cpp">ARMCallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
