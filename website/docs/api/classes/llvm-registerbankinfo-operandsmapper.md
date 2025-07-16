---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/registerbankinfo/operandsmapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OperandsMapper` Class Reference

<p>Helper class used to get/create the virtual registers that will be used to replace the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> when applying a mapping. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegisterBankInfo::OperandsMapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">llvm/CodeGen/RegisterBankInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45469c8ee7ec955262a7f6dfe57fc2e">OperandsMapper</a> (MachineInstr &amp;MI, const InstructionMapping &amp;InstrMapping, MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> that will hold the information to apply <span class="doxyComputerOutput">InstrMapping</span> to <span class="doxyComputerOutput">MI</span>. <a href="#ac45469c8ee7ec955262a7f6dfe57fc2e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6817453b853abea76fab37803ade6ef4">createVRegs</a> (unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create as many new virtual registers as needed for the mapping of the <span class="doxyComputerOutput">OpIdx-th</span> operand. <a href="#a6817453b853abea76fab37803ade6ef4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10302abbff4a2a12a2bdb34898882b2c">setVRegs</a> (unsigned OpIdx, unsigned PartialMapIdx, Register NewVReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the virtual register of the <span class="doxyComputerOutput">PartialMapIdx-th</span> partial mapping of the OpIdx-th operand to <span class="doxyComputerOutput">NewVReg</span>. <a href="#a10302abbff4a2a12a2bdb34898882b2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af23faa9ae580c4a451da006e3567b297">getVRegs</a> (unsigned OpIdx, bool ForDebug=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get all the virtual registers required to map the <span class="doxyComputerOutput">OpIdx-th</span> operand of the instruction. <a href="#af23faa9ae580c4a451da006e3567b297">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeccd292b19be57132f7f2539d32aac21">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this operands mapper on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream. <a href="#aeccd292b19be57132f7f2539d32aac21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35dd3699ac135501fca0bf3c7087f311">print</a> (raw_ostream &amp;OS, bool ForDebug=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this operands mapper on <span class="doxyComputerOutput">OS</span> stream. <a href="#a35dd3699ac135501fca0bf3c7087f311">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef0616073fc300dd58407933fa608cb">getVRegsMem</a> (unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the range in NewVRegs to store all the partial values for the <span class="doxyComputerOutput">OpIdx-th</span> operand. <a href="#afef0616073fc300dd58407933fa608cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f3cab90690e062dc06adb121bee7fd4">getNewVRegsEnd</a> (unsigned StartIdx, unsigned NumVal) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the end iterator for a range starting at <span class="doxyComputerOutput">StartIdx</span> and spannig <span class="doxyComputerOutput">NumVal</span> in NewVRegs. <a href="#a5f3cab90690e062dc06adb121bee7fd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67a4a4ce4722d08be47db3ff5cf8534b">getNewVRegsEnd</a> (unsigned StartIdx, unsigned NumVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bb5eaa667d20a46b47e088341a889ed">OpToNewVRegIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The OpIdx-th cell contains the index in NewVRegs where the VRegs of the OpIdx-th operand starts. <a href="#a4bb5eaa667d20a46b47e088341a889ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1facfd0df46ab81f55c36aa7871e518">NewVRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hold the registers that will be used to map MI with InstrMapping. <a href="#aa1facfd0df46ab81f55c36aa7871e518">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f0cfa1d46bc148b725137607807a82">MRI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a>, used to create new virtual registers. <a href="#ae7f0cfa1d46bc148b725137607807a82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b302273d91616fa10d60207c3c15878">MI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> being remapped. <a href="#a6b302273d91616fa10d60207c3c15878">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4249551141717cac2b136d6bba8b2318">InstrMapping</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>New mapping of the instruction. <a href="#a4249551141717cac2b136d6bba8b2318">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7d1f7b7c10b0906ecc892f5bae9874">DontKnowIdx</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> value identifying that the index in OpToNewVRegIdx for an operand has not been set yet. <a href="#acc7d1f7b7c10b0906ecc892f5bae9874">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Getters. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a397c999d8b2ead3f13eba866dfc3295e">getMI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b29851bd7d2ce50c53e87b9043532a">getInstrMapping</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The final mapping of the instruction. <a href="#a08b29851bd7d2ce50c53e87b9043532a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a841196bdb378891dcedb1c23a02a30d2">getMRI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> we used to realize the mapping. <a href="#a841196bdb378891dcedb1c23a02a30d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class used to get/create the virtual registers that will be used to replace the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> when applying a mapping.</p>

<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OperandsMapper() {#ac45469c8ee7ec955262a7f6dfe57fc2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterBankInfo::OperandsMapper::OperandsMapper (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp; InstrMapping, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> that will hold the information to apply <span class="doxyComputerOutput">InstrMapping</span> to <span class="doxyComputerOutput">MI</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>InstrMapping.verify(MI)</p></dd>
</dl>


<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createVRegs() {#a6817453b853abea76fab37803ade6ef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterBankInfo::OperandsMapper::createVRegs (unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create as many new virtual registers as needed for the mapping of the <span class="doxyComputerOutput">OpIdx-th</span> operand.</p>


<p>The number of registers is determined by the number of breakdown for the related operand in the instruction mapping. The type of the new registers is a plain scalar of the right size. The proper type is expected to be set when the mapping is applied to the instruction(s) that realizes the mapping.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><a href="#a397c999d8b2ead3f13eba866dfc3295e">getMI()</a>.getOperand(OpIdx).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p>All the partial mapping of the <span class="doxyComputerOutput">OpIdx-th</span> operand have been assigned a new virtual register.</p></dd>
</dl>


<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a0816d52870d885008781168854322987">llvm::RegisterBankInfo::ValueMapping::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a177c87d358c97d054f1b2016dc95c64b">llvm::RegisterBankInfo::ValueMapping::end</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a3f495e9cf115e5d32f21d729c46a484e">llvm::RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#afac28dfebeb6f31c2c87dd1acdcd038f">llvm::RegisterBankInfo::PartialMapping::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ae78f517f813c1983db970736287379e1">llvm::RegisterBankInfo::PartialMapping::RegBank</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#afc5c7be6a4fbeb70b07dde19d8ebc2fd">llvm::RegBankSelect::applyMapping</a>.</p>

</div>
</div>

### dump() {#aeccd292b19be57132f7f2539d32aac21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RegisterBankInfo::OperandsMapper::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this operands mapper on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream.</p>

<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>

</div>
</div>

### getVRegs() {#af23faa9ae580c4a451da006e3567b297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; SmallVectorImpl&lt; Register &gt;::const_iterator &gt; RegisterBankInfo::OperandsMapper::getVRegs (unsigned OpIdx, bool ForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get all the virtual registers required to map the <span class="doxyComputerOutput">OpIdx-th</span> operand of the instruction.</p>


<p>This return an empty range when createVRegs or setVRegs has not been called. The iterator may be invalidated by a call to setVRegs or createVRegs.</p>


<p>When <span class="doxyComputerOutput">ForDebug</span> is true, we will not check that the list of new virtual registers does not contain uninitialized values.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><a href="#a397c999d8b2ead3f13eba866dfc3295e">getMI()</a>.getOperand(OpIdx).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>ForDebug || All partial mappings have been set a register</p></dd>
</dl>


<p>Declaration at line 378 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a3f495e9cf115e5d32f21d729c46a484e">llvm::RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a83b9746150eb1c8820d65bca34b8d950">llvm::RegisterBankInfo::ValueMapping::NumBreakDowns</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#afc5c7be6a4fbeb70b07dde19d8ebc2fd">llvm::RegBankSelect::applyMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afd96526160e781989c15d6879ad1f9f1">llvm::AMDGPURegisterBankInfo::applyMappingSMULU64</a>, <a href="#a35dd3699ac135501fca0bf3c7087f311">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a0f1b1f36c5069336e43ad70639b7f176">substituteSimpleCopyRegs</a>.</p>

</div>
</div>

### print() {#a35dd3699ac135501fca0bf3c7087f311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterBankInfo::OperandsMapper::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool ForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this operands mapper on <span class="doxyComputerOutput">OS</span> stream.</p>

<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a4c3dac40d5cd4191d6c8c8686c93cfb5">llvm::RegisterBankInfo::InstructionMapping::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a3f495e9cf115e5d32f21d729c46a484e">llvm::RegisterBankInfo::getInstrMapping</a>, <a href="#a397c999d8b2ead3f13eba866dfc3295e">getMI</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a3548d4f247cf4c364934abd8f59a0483">llvm::RegisterBankInfo::InstructionMapping::getNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="#af23faa9ae580c4a451da006e3567b297">getVRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a52b346db26e48bf69fbd59454bdbaeb8">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### setVRegs() {#a10302abbff4a2a12a2bdb34898882b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterBankInfo::OperandsMapper::setVRegs (unsigned OpIdx, unsigned PartialMapIdx, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewVReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the virtual register of the <span class="doxyComputerOutput">PartialMapIdx-th</span> partial mapping of the OpIdx-th operand to <span class="doxyComputerOutput">NewVReg</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><a href="#a397c999d8b2ead3f13eba866dfc3295e">getMI()</a>.getOperand(OpIdx).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg()</a></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><a href="#a08b29851bd7d2ce50c53e87b9043532a">getInstrMapping()</a>.getOperandMapping(OpIdx).BreakDown.size() &gt; PartialMapIdx</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>NewReg != 0</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p>the <span class="doxyComputerOutput">PartialMapIdx-th</span> register of the value mapping of the <span class="doxyComputerOutput">OpIdx-th</span> operand has been set.</p></dd>
</dl>


<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a3f495e9cf115e5d32f21d729c46a484e">llvm::RegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getNewVRegsEnd() {#a5f3cab90690e062dc06adb121bee7fd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; Register &gt;::const_iterator RegisterBankInfo::OperandsMapper::getNewVRegsEnd (unsigned StartIdx, unsigned NumVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the end iterator for a range starting at <span class="doxyComputerOutput">StartIdx</span> and spannig <span class="doxyComputerOutput">NumVal</span> in NewVRegs.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>StartIdx + NumVal &lt;= NewVRegs.size()</p></dd>
</dl>


<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>

</div>
</div>

### getNewVRegsEnd() {#a67a4a4ce4722d08be47db3ff5cf8534b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; Register &gt;::iterator RegisterBankInfo::OperandsMapper::getNewVRegsEnd (unsigned StartIdx, unsigned NumVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>

</div>
</div>

### getVRegsMem() {#afef0616073fc300dd58407933fa608cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; SmallVectorImpl&lt; Register &gt;::iterator &gt; RegisterBankInfo::OperandsMapper::getVRegsMem (unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the range in NewVRegs to store all the partial values for the <span class="doxyComputerOutput">OpIdx-th</span> operand.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The iterator range for the space created.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><a href="#a397c999d8b2ead3f13eba866dfc3295e">getMI()</a>.getOperand(OpIdx).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg()</a></p></dd>
</dl>


<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InstrMapping {#a4249551141717cac2b136d6bba8b2318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstructionMapping&amp; llvm::RegisterBankInfo::OperandsMapper::InstrMapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>New mapping of the instruction.</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

### MI {#a6b302273d91616fa10d60207c3c15878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr&amp; llvm::RegisterBankInfo::OperandsMapper::MI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> being remapped.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

### MRI {#ae7f0cfa1d46bc148b725137607807a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::RegisterBankInfo::OperandsMapper::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a>, used to create new virtual registers.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

### NewVRegs {#aa1facfd0df46ab81f55c36aa7871e518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 8&gt; llvm::RegisterBankInfo::OperandsMapper::NewVRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hold the registers that will be used to map MI with InstrMapping.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

### OpToNewVRegIdx {#a4bb5eaa667d20a46b47e088341a889ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;int, 8&gt; llvm::RegisterBankInfo::OperandsMapper::OpToNewVRegIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The OpIdx-th cell contains the index in NewVRegs where the VRegs of the OpIdx-th operand starts.</p>


<p>-1 means we do not have such mapping yet. Note: We use a <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> to avoid heap allocation for most cases.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### DontKnowIdx {#acc7d1f7b7c10b0906ecc892f5bae9874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int RegisterBankInfo::OperandsMapper::DontKnowIdx = -1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> value identifying that the index in OpToNewVRegIdx for an operand has not been set yet.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Getters.



<p>The <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> being remapped.</p>


### getInstrMapping {#a08b29851bd7d2ce50c53e87b9043532a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstructionMapping &amp; llvm::RegisterBankInfo::OperandsMapper::getInstrMapping ()</td>
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

<p>The final mapping of the instruction.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a0c85003f2e4060a7b61ebff7c2fb33cd">llvm::RegisterBankInfo::applyMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a67457fbc2d167a5a1a18124bd446278f">llvm::AMDGPURegisterBankInfo::applyMappingBFE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afb1a8a9ef7b460687963fb7968fb7626">llvm::AMDGPURegisterBankInfo::applyMappingSBufferLoad</a>.</p>

</div>
</div>

### getMI {#a397c999d8b2ead3f13eba866dfc3295e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr &amp; llvm::RegisterBankInfo::OperandsMapper::getMI ()</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a67457fbc2d167a5a1a18124bd446278f">llvm::AMDGPURegisterBankInfo::applyMappingBFE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a1e12ed6a5b2d3f3dd790e2c48f7d7906">llvm::MipsRegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a59ce3aa458b07483cb7422b0303b589b">llvm::AMDGPURegisterBankInfo::applyMappingMAD_64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afb1a8a9ef7b460687963fb7968fb7626">llvm::AMDGPURegisterBankInfo::applyMappingSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afd96526160e781989c15d6879ad1f9f1">llvm::AMDGPURegisterBankInfo::applyMappingSMULU64</a>, <a href="#a35dd3699ac135501fca0bf3c7087f311">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a0f1b1f36c5069336e43ad70639b7f176">substituteSimpleCopyRegs</a>.</p>

</div>
</div>

### getMRI {#a841196bdb378891dcedb1c23a02a30d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo &amp; llvm::RegisterBankInfo::OperandsMapper::getMRI ()</td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> we used to realize the mapping.</p>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a67457fbc2d167a5a1a18124bd446278f">llvm::AMDGPURegisterBankInfo::applyMappingBFE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a1e12ed6a5b2d3f3dd790e2c48f7d7906">llvm::MipsRegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a59ce3aa458b07483cb7422b0303b589b">llvm::AMDGPURegisterBankInfo::applyMappingMAD_64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afb1a8a9ef7b460687963fb7968fb7626">llvm::AMDGPURegisterBankInfo::applyMappingSBufferLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afd96526160e781989c15d6879ad1f9f1">llvm::AMDGPURegisterBankInfo::applyMappingSMULU64</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
