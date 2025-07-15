---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/m68kcalllowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `M68kCallLowering` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::M68kCallLowering { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-h">Target/M68k/GISel/M68kCallLowering.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/calllowering">CallLowering</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4360732f2642cb8099b9e72baca2368">M68kCallLowering</a> (const M68kTargetLowering &amp;TLI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdadd18c92c595797ca5409d708f2ef">lowerReturn</a> (MachineIRBuilder &amp;MIRBuilder, const Value *Val, ArrayRef&lt; Register &gt; VRegs, FunctionLoweringInfo &amp;FLI, Register SwiftErrorVReg) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower outgoing return values, described by <span class="doxyComputerOutput">Val</span>, into the specified virtual registers <span class="doxyComputerOutput">VRegs</span>. <a href="#abfdadd18c92c595797ca5409d708f2ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c78051669d5513b0b9616495bfc7a5">lowerFormalArguments</a> (MachineIRBuilder &amp;MIRBuilder, const Function &amp;F, ArrayRef&lt; ArrayRef&lt; Register &gt; &gt; VRegs, FunctionLoweringInfo &amp;FLI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the incoming (formal) arguments, described by <span class="doxyComputerOutput">VRegs</span>, for GlobalISel. <a href="#a74c78051669d5513b0b9616495bfc7a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c714d045da3eaad01dfd893048e9a0c">lowerCall</a> (MachineIRBuilder &amp;MIRBuilder, CallLoweringInfo &amp;Info) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook must be implemented to lower the given call instruction, including argument and return value marshalling. <a href="#a2c714d045da3eaad01dfd893048e9a0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75fb1dc2cb89450ab60af4140d9ccea">enableBigEndian</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For targets which want to use big-endian can enable it with <a href="#ac75fb1dc2cb89450ab60af4140d9ccea">enableBigEndian()</a> hook. <a href="#ac75fb1dc2cb89450ab60af4140d9ccea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-h">M68kCallLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### M68kCallLowering() {#aa4360732f2642cb8099b9e72baca2368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">M68kCallLowering::M68kCallLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering">M68kTargetLowering</a> &amp; TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-h">M68kCallLowering.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-cpp">M68kCallLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/calllowering/#aceb7a26daf1242d77d983191579009db">llvm::CallLowering::CallLowering</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableBigEndian() {#ac75fb1dc2cb89450ab60af4140d9ccea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kCallLowering::enableBigEndian ()</td>
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

<p>For targets which want to use big-endian can enable it with <a href="#ac75fb1dc2cb89450ab60af4140d9ccea">enableBigEndian()</a> hook.</p>

<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-h">M68kCallLowering.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-cpp">M68kCallLowering.cpp</a>.</p>

</div>
</div>

### lowerCall() {#a2c714d045da3eaad01dfd893048e9a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kCallLowering::lowerCall (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/structs/llvm/calllowering/callloweringinfo">CallLoweringInfo</a> &amp; Info)</td>
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

<p>This hook must be implemented to lower the given call instruction, including argument and return value marshalling.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the lowering succeeded, false otherwise.</p></dd>
</dl>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-h">M68kCallLowering.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-cpp">M68kCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a8880ccaea51a4ee9b48c3c8d7fbfebf4">llvm::MachineInstrBuilder::addRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae04499daa8807ddb4d00e7ed18b1698f">llvm::MachineIRBuilder::buildInstrNoInsert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a837dc9f535c4db3c1d4bc3cea1358651">llvm::CallLowering::determineAndHandleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget/#aa6202d7bf1d02aafd7cd6576dc7c4b03">llvm::M68kSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget/#a6ace610ea65a3d398e730c3248e08101">llvm::M68kSubtarget::getRegBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget/#ad37055600593cd4b591df42904012061">llvm::M68kSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ae960af8a6cb8d7ec718c34dcd569d2ec">llvm::CallLowering::getTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a06dc2f24e1f4dea357bf6c646f5b2607">llvm::MachineIRBuilder::insertInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner/#ad737172e1e2f85c9f819c2e4e8b364b7">llvm::CallLowering::ValueAssigner::StackSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### lowerFormalArguments() {#a74c78051669d5513b0b9616495bfc7a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kCallLowering::lowerFormalArguments (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &gt; VRegs, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FLI)</td>
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

<p>This hook must be implemented to lower the incoming (formal) arguments, described by <span class="doxyComputerOutput">VRegs</span>, for GlobalISel.</p>


<p>Each argument must end up in the related virtual registers described by <span class="doxyComputerOutput">VRegs</span>. In other words, the first argument should end up in <span class="doxyComputerOutput">VRegs</span>[0], the second in <span class="doxyComputerOutput">VRegs</span>[1], and so on. For each argument, there will be one register for each non-aggregate type, as returned by <span class="doxyComputerOutput">computeValueLLTs</span>. <span class="doxyComputerOutput">MIRBuilder</span> is set to the proper insertion for the argument lowering. <span class="doxyComputerOutput">FLI</span> is required for sret demotion.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the lowering succeeded, false otherwise.</p></dd>
</dl>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-h">M68kCallLowering.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-cpp">M68kCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a837dc9f535c4db3c1d4bc3cea1358651">llvm::CallLowering::determineAndHandleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ae960af8a6cb8d7ec718c34dcd569d2ec">llvm::CallLowering::getTLI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af835582e4e7766298680c7d01947036e">llvm::CallLowering::setArgFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>.</p>

</div>
</div>

### lowerReturn() {#abfdadd18c92c595797ca5409d708f2ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kCallLowering::lowerReturn (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; VRegs, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; FLI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SwiftErrorVReg)</td>
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

<p>This hook must be implemented to lower outgoing return values, described by <span class="doxyComputerOutput">Val</span>, into the specified virtual registers <span class="doxyComputerOutput">VRegs</span>.</p>


<p>This hook is used by GlobalISel.</p>


<p><span class="doxyComputerOutput">FLI</span> is required for sret demotion.</p>


<p><span class="doxyComputerOutput">SwiftErrorVReg</span> is non-zero if the function has a swifterror parameter that needs to be implicitly returned.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the lowering succeeds, false otherwise.</p></dd>
</dl>


<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-h">M68kCallLowering.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-cpp">M68kCallLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae04499daa8807ddb4d00e7ed18b1698f">llvm::MachineIRBuilder::buildInstrNoInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a837dc9f535c4db3c1d4bc3cea1358651">llvm::CallLowering::determineAndHandleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ae960af8a6cb8d7ec718c34dcd569d2ec">llvm::CallLowering::getTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a06dc2f24e1f4dea357bf6c646f5b2607">llvm::MachineIRBuilder::insertInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af835582e4e7766298680c7d01947036e">llvm::CallLowering::setArgFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-cpp">M68kCallLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/gisel/m68kcalllowering-h">M68kCallLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
