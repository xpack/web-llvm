---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-riscvcalllowering-cpp-/riscvformalarghandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RISCVFormalArgHandler` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{RISCVCallLowering.cpp}::RISCVFormalArgHandler { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler">RISCVIncomingValueHandler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff2d4e09e78bd02a8e81daba36e0f4d6">RISCVFormalArgHandler</a> (MachineIRBuilder &amp;B, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ff47d17cd3b6cda5f35bc08babe6c95">markPhysRegUsed</a> (MCRegister PhysReg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How the physical register gets marked varies between formal parameters (it's a basic-block live-in), and a call instruction (it's an implicit-def of the BL). <a href="#a5ff47d17cd3b6cda5f35bc08babe6c95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVFormalArgHandler() {#aff2d4e09e78bd02a8e81daba36e0f4d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVCallLowering.cpp}::RISCVFormalArgHandler::RISCVFormalArgHandler (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a3968b5fbbfcb762c497c4312c369dad6">llvm::CallLowering::ValueHandler::MRI</a> and <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#ab0bd7f08eabd70317e7b6372fb357e63">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::RISCVIncomingValueHandler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### markPhysRegUsed() {#a5ff47d17cd3b6cda5f35bc08babe6c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVCallLowering.cpp}::RISCVFormalArgHandler::markPhysRegUsed (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
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

<p>How the physical register gets marked varies between formal parameters (it's a basic-block live-in), and a call instruction (it's an implicit-def of the BL).</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/calllowering/valuehandler/#a00344e2d8f7ad399989bf320adf73aa8">llvm::CallLowering::ValueHandler::MIRBuilder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvcalllowering-cpp">RISCVCallLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
