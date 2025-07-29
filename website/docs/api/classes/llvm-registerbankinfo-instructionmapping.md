---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/registerbankinfo/instructionmapping
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstructionMapping` Class

<p>Helper class that represents how the value of an instruction may be mapped and what is the related cost of such mapping. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegisterBankInfo::InstructionMapping { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">llvm/CodeGen/RegisterBankInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3358173059c094cd0ec5ca3cb4e07e">InstructionMapping</a> (unsigned ID, unsigned Cost, const ValueMapping *OperandsMapping, unsigned NumOperands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor for the mapping of an instruction. <a href="#abe3358173059c094cd0ec5ca3cb4e07e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58a261e5cc9ae03a1bed35f56c973447">InstructionMapping</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#a58a261e5cc9ae03a1bed35f56c973447">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c1c4a80c61e8df88647f78ddf6de94e">getCost</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the cost. <a href="#a4c1c4a80c61e8df88647f78ddf6de94e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3dac40d5cd4191d6c8c8686c93cfb5">getID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the ID. <a href="#a4c3dac40d5cd4191d6c8c8686c93cfb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3548d4f247cf4c364934abd8f59a0483">getNumOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of operands. <a href="#a3548d4f247cf4c364934abd8f59a0483">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58103031b7526106f0f27669e62aeee">getOperandMapping</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the value mapping of the ith operand. <a href="#ae58103031b7526106f0f27669e62aeee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d3eca1020d06782fb82e377c6991c9">setOperandsMapping</a> (const ValueMapping *OpdsMapping)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the mapping for all the operands. <a href="#aa6d3eca1020d06782fb82e377c6991c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af484a43d5e4fa2ff1f1790d06f2ca94d">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this object is valid. <a href="#af484a43d5e4fa2ff1f1790d06f2ca94d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e479535d719fb4ec8904104ec1e8ae">verify</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verifiy that this mapping makes sense for <span class="doxyComputerOutput">MI</span>. <a href="#a89e479535d719fb4ec8904104ec1e8ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa302bb0b2c36a3c8b0d7ffbf7ff14be">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream. <a href="#aaa302bb0b2c36a3c8b0d7ffbf7ff14be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8f76a31d98cb9ef889f4971aa58282">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this on <span class="doxyComputerOutput">OS</span>;. <a href="#aaf8f76a31d98cb9ef889f4971aa58282">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad88d2a46f835e86d6781e2592cacbdd">getOperandMapping</a> (unsigned i)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2140e0835c80d314a8d943c1a17fb17f">ID</a> = <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#aabde40ed6dff50ce0fc5922ce428c79d">InvalidMappingID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identifier of the mapping. <a href="#a2140e0835c80d314a8d943c1a17fb17f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a100c72a8ca39a5b1705c72016b9f6">Cost</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cost of this mapping. <a href="#ab8a100c72a8ca39a5b1705c72016b9f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b4aaf35c9a0badec92ecc21508c80b">OperandsMapping</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of all the operands. <a href="#a65b4aaf35c9a0badec92ecc21508c80b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f14ade9e0c20454bc851801c6a61bd">NumOperands</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of operands. <a href="#a25f14ade9e0c20454bc851801c6a61bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper class that represents how the value of an instruction may be mapped and what is the related cost of such mapping.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstructionMapping() {#abe3358173059c094cd0ec5ca3cb4e07e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterBankInfo::InstructionMapping::InstructionMapping (unsigned ID, unsigned Cost, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> * OperandsMapping, unsigned NumOperands)</td>
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

<p>Constructor for the mapping of an instruction.</p>


<p><span class="doxyComputerOutput">NumOperands</span> must be equal to number of all the operands of the related instruction. The rationale is that it is more efficient for the optimizers to be able to assume that the mapping of the ith operand is at the index i.</p>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="#ae58103031b7526106f0f27669e62aeee">getOperandMapping</a>.</p>

</div>
</div>

### InstructionMapping() {#a58a261e5cc9ae03a1bed35f56c973447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterBankInfo::InstructionMapping::InstructionMapping ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default constructor.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this constructor to express that the mapping is invalid.</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#aaa302bb0b2c36a3c8b0d7ffbf7ff14be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RegisterBankInfo::InstructionMapping::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream.</p>

<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>

</div>
</div>

### getCost() {#a4c1c4a80c61e8df88647f78ddf6de94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::InstructionMapping::getCost ()</td>
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

<p>Get the cost.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac7d08af4bb81846173b6186f568fcc8b">llvm::RegBankSelect::computeMapping</a> and <a href="#aaf8f76a31d98cb9ef889f4971aa58282">print</a>.</p>

</div>
</div>

### getID() {#a4c3dac40d5cd4191d6c8c8686c93cfb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::InstructionMapping::getID ()</td>
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

<p>Get the ID.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a0c85003f2e4060a7b61ebff7c2fb33cd">llvm::RegisterBankInfo::applyMapping</a>, <a href="#af484a43d5e4fa2ff1f1790d06f2ca94d">isValid</a>, <a href="#aaf8f76a31d98cb9ef889f4971aa58282">print</a> and <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a35dd3699ac135501fca0bf3c7087f311">llvm::RegisterBankInfo::OperandsMapper::print</a>.</p>

</div>
</div>

### getNumOperands() {#a3548d4f247cf4c364934abd8f59a0483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::InstructionMapping::getNumOperands ()</td>
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

<p>Get the number of operands.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac7d08af4bb81846173b6186f568fcc8b">llvm::RegBankSelect::computeMapping</a> and <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a35dd3699ac135501fca0bf3c7087f311">llvm::RegisterBankInfo::OperandsMapper::print</a>.</p>

</div>
</div>

### getOperandMapping() {#ae58103031b7526106f0f27669e62aeee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ValueMapping &amp; llvm::RegisterBankInfo::InstructionMapping::getOperandMapping (unsigned i)</td>
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

<p>Get the value mapping of the ith operand.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The mapping for the ith operand has been set.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>The ith operand is a register.</p></dd>
</dl>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Reference <a href="#abe3358173059c094cd0ec5ca3cb4e07e">InstructionMapping</a>.</p>

</div>
</div>

### isValid() {#af484a43d5e4fa2ff1f1790d06f2ca94d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegisterBankInfo::InstructionMapping::isValid ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this object is valid.</p>


<p>This is a lightweight check for obvious wrong instance.</p>


<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>References <a href="#a4c3dac40d5cd4191d6c8c8686c93cfb5">getID</a> and <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#aabde40ed6dff50ce0fc5922ce428c79d">llvm::RegisterBankInfo::InvalidMappingID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac7d08af4bb81846173b6186f568fcc8b">llvm::RegBankSelect::computeMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#ab3d2615f7c9c9159d1e883ba8dd8eab7">llvm::AArch64RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#abb21f77ed3dc15eb330b93b3efaa94ba">llvm::AMDGPURegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/armregisterbankinfo/#af59ec25334715d44d5eecd8568b29e36">llvm::ARMRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterbankinfo/#a1c1174fbc250d7fa3773584dfd942728">llvm::M68kRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterbankinfo/#a7394a9cae0a48251b9ccaca67393ef89">llvm::MipsRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#aece2fca4cd44244cdd43227c3d530368">llvm::PPCRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a3f495e9cf115e5d32f21d729c46a484e">llvm::RegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvregisterbankinfo/#a9a34245bb11e89a64a45063a8fc9e201">llvm::RISCVRegisterBankInfo::getInstrMapping</a> and <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#ab84d39303f3dab27a9cf03cd488b23c6">llvm::X86RegisterBankInfo::getInstrMapping</a>.</p>

</div>
</div>

### print() {#aaf8f76a31d98cb9ef889f4971aa58282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterBankInfo::InstructionMapping::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this on <span class="doxyComputerOutput">OS</span>;.</p>

<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="#a4c1c4a80c61e8df88647f78ddf6de94e">getCost</a> and <a href="#a4c3dac40d5cd4191d6c8c8686c93cfb5">getID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2c6f762add10012845afc5fdcc1ba604">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### setOperandsMapping() {#aa6d3eca1020d06782fb82e377c6991c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegisterBankInfo::InstructionMapping::setOperandsMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> * OpdsMapping)</td>
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

<p>Set the mapping for all the operands.</p>


<p>In other words, OpdsMapping should hold at least getNumOperands <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a>.</p>


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

### verify() {#a89e479535d719fb4ec8904104ec1e8ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterBankInfo::InstructionMapping::verify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verifiy that this mapping makes sense for <span class="doxyComputerOutput">MI</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">MI</span> must be connected to a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p></dd>
</dl>



:::info
<p>This method does not check anything when assertions are disabled.</p>
:::


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True is the check was successful.</p></dd>
</dl>


<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a9768b8e3c00648b38189b95d6603729b">llvm::TargetSubtargetInfo::getRegBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp/#a0cb62142f69902f353d393ed831f83a4">isCopyLike</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#aa9467bf23c0dfb8176a54358477962fa">llvm::RegisterBankInfo::RegisterBankInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a6778093ec4b236fadf3c13e2fe1e2ee9">llvm::RegisterBankInfo::ValueMapping::verify</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a6553ca5670588f279c72f84d46b05033">llvm::RegBankSelect::assignInstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getOperandMapping() {#aad88d2a46f835e86d6781e2592cacbdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ValueMapping &amp; llvm::RegisterBankInfo::InstructionMapping::getOperandMapping (unsigned i)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Cost {#ab8a100c72a8ca39a5b1705c72016b9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::InstructionMapping::Cost = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cost of this mapping.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

### ID {#a2140e0835c80d314a8d943c1a17fb17f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::InstructionMapping::ID = <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#aabde40ed6dff50ce0fc5922ce428c79d">InvalidMappingID</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identifier of the mapping.</p>


<p>This is used to communicate between the target and the optimizers which mapping should be realized.</p>


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

### NumOperands {#a25f14ade9e0c20454bc851801c6a61bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::InstructionMapping::NumOperands = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of operands.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

### OperandsMapping {#a65b4aaf35c9a0badec92ecc21508c80b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ValueMapping* llvm::RegisterBankInfo::InstructionMapping::OperandsMapping = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping of all the operands.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

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
