---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineinstrbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineInstrBuilder` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachineInstrBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b0e0d732ea36290a9b6ed6c9960836">MachineInstrBuilder</a> (MachineFunction &amp;F, MachineInstr *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for manipulating an existing instruction. <a href="#a54b0e0d732ea36290a9b6ed6c9960836">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84817b0c66ff61de71f1c2f9d371c818">MachineInstrBuilder</a> (MachineFunction &amp;F, MachineBasicBlock::iterator I)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33a06b5978e8d3166504593034ca005">operator MachineInstr *</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow automatic conversion to the machine instruction we are working on. <a href="#ab33a06b5978e8d3166504593034ca005">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68b659f056c0f4bc576bd3075d3ab966">operator-&gt;</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c89530d336b36f8ca450f9041831eb">operator MachineBasicBlock::iterator</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af066b2b6a1013299bfca84fe8b798a0b">getInstr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If conversion operators fail, use this method to get the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> explicitly. <a href="#af066b2b6a1013299bfca84fe8b798a0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c5fadb14ff1d77faad0cb58a43252ab">getReg</a> (unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the register for the operand index. <a href="#a1c5fadb14ff1d77faad0cb58a43252ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927857fc69e4b4f0cde307f86f180df5">addReg</a> (Register RegNo, unsigned flags=0, unsigned SubReg=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new virtual register operand. <a href="#a927857fc69e4b4f0cde307f86f180df5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af584d2eb0342e655d6ec597c0f7958db">addDef</a> (Register RegNo, unsigned Flags=0, unsigned SubReg=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a virtual register definition operand. <a href="#af584d2eb0342e655d6ec597c0f7958db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88e27102395957e457fed8e73a085cf">addUse</a> (Register RegNo, unsigned Flags=0, unsigned SubReg=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a virtual register use operand. <a href="#ad88e27102395957e457fed8e73a085cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1f959947905135c7dd215b64957654">addImm</a> (int64_t Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new immediate operand. <a href="#a6c1f959947905135c7dd215b64957654">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3348f4e81264ccfe03832f141fdf44a3">addCImm</a> (const ConstantInt *Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95c7b5ed23471212aeaba1eee6501261">addFPImm</a> (const ConstantFP *Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1febf2a98f588146548a3a485d3838">addMBB</a> (MachineBasicBlock *MBB, unsigned TargetFlags=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a93dd8ddbce120d8c3101c16bc3cc6">addFrameIndex</a> (int Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88177c2ee5d3e579e50128cf83de5ba6">addConstantPoolIndex</a> (unsigned Idx, int Offset=0, unsigned TargetFlags=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bc7ed8aefe042984bce6ea95ad5f1ec">addTargetIndex</a> (unsigned Idx, int64_t Offset=0, unsigned TargetFlags=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa7ad3e87d858a3ed3b3dc8b05b70078">addJumpTableIndex</a> (unsigned Idx, unsigned TargetFlags=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9117be19af857a7bdcee7bdf0279024c">addGlobalAddress</a> (const GlobalValue *GV, int64_t Offset=0, unsigned TargetFlags=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a1feca92679c24a46b0b824a6de269">addExternalSymbol</a> (const char *FnName, unsigned TargetFlags=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb17a3fc032cb29dbc1908f1d4ba046">addBlockAddress</a> (const BlockAddress *BA, int64_t Offset=0, unsigned TargetFlags=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8880ccaea51a4ee9b48c3c8d7fbfebf4">addRegMask</a> (const uint32_t *Mask) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae565d45627e1678a3e37bd6a016c561c">addMemOperand</a> (MachineMemOperand *MMO) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dfb0ae952397bf4c6d5cbcaff4c4b6d">setMemRefs</a> (ArrayRef&lt; MachineMemOperand * &gt; MMOs) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad84ebe08bb098cd283e922fd186f77e9">cloneMemRefs</a> (const MachineInstr &amp;OtherMI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a8d0cceecd0424aefb44ea46a27be4d">cloneMergedMemRefs</a> (ArrayRef&lt; const MachineInstr * &gt; OtherMIs) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a713eab58694282971c413a0d6de5975c">add</a> (const MachineOperand &amp;MO) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8acc898589174182420d6c720ef0fc7c">add</a> (ArrayRef&lt; MachineOperand &gt; MOs) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f54f5772ba80cc1f7c4a92203f14e57">addMetadata</a> (const MDNode *MD) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4e67777edb24fac492ef4ae15e69ba">addCFIIndex</a> (unsigned CFIIndex) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac6e2ee4b04561d22ba0bdc2d32897f">addIntrinsicID</a> (Intrinsic::ID ID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d40d83c14042582354b5d875ed7f2d8">addPredicate</a> (CmpInst::Predicate Pred) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846993bea18636f4fd47bbe401fece04">addShuffleMask</a> (ArrayRef&lt; int &gt; Val) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ffeb5b3940506a54e69e72e26e2a6cd">addSym</a> (MCSymbol *Sym, unsigned char TargetFlags=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf25b569ca308aacc819a2331626ed5d">setMIFlags</a> (unsigned Flags) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a632680dcf899466c32c0095a40e7e89e">setMIFlag</a> (MachineInstr::MIFlag Flag) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ffb8b95e5b75eeb68be7d300eb9618">setOperandDead</a> (unsigned OpIdx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9189968ba471dec34e7806413bd019cd">addDisp</a> (const MachineOperand &amp;Disp, int64_t off, unsigned char TargetFlags=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdda4cba7788bae87378a6cbdc81dbe2">setPCSections</a> (MDNode *MD) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72cc8dc853a4823eccff58bc0269b306">setMMRAMetadata</a> (MDNode *MMRA) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4cfeb86ad3780d71eb022485e91d211">copyImplicitOps</a> (const MachineInstr &amp;OtherMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy all the implicit operands from OtherMI onto this one. <a href="#ae4cfeb86ad3780d71eb022485e91d211">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa238cd5a6fee2e66e4b5bd3fc2040c19">constrainAllUses</a> (const TargetInstrInfo &amp;TII, const TargetRegisterInfo &amp;TRI, const RegisterBankInfo &amp;RBI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8b924aaad7e94be6087514fe925434">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761967790440ac0a1975282e4fa24ab1">MI</a> = nullptr</td>
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


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineInstrBuilder() {#a4958726a2fb346aec8c8dffb9e7212b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineInstrBuilder::MachineInstrBuilder ()</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Referenced by <a href="#a8acc898589174182420d6c720ef0fc7c">add</a>, <a href="#a713eab58694282971c413a0d6de5975c">add</a>, <a href="#a6eb17a3fc032cb29dbc1908f1d4ba046">addBlockAddress</a>, <a href="#a3e4e67777edb24fac492ef4ae15e69ba">addCFIIndex</a>, <a href="#a3348f4e81264ccfe03832f141fdf44a3">addCImm</a>, <a href="#af584d2eb0342e655d6ec597c0f7958db">addDef</a>, <a href="#a9189968ba471dec34e7806413bd019cd">addDisp</a>, <a href="#a30a1feca92679c24a46b0b824a6de269">addExternalSymbol</a>, <a href="#a95c7b5ed23471212aeaba1eee6501261">addFPImm</a>, <a href="#a86a93dd8ddbce120d8c3101c16bc3cc6">addFrameIndex</a>, <a href="#a9117be19af857a7bdcee7bdf0279024c">addGlobalAddress</a>, <a href="#a6c1f959947905135c7dd215b64957654">addImm</a>, <a href="#a7ac6e2ee4b04561d22ba0bdc2d32897f">addIntrinsicID</a>, <a href="#aaa7ad3e87d858a3ed3b3dc8b05b70078">addJumpTableIndex</a>, <a href="#abf1febf2a98f588146548a3a485d3838">addMBB</a>, <a href="#ae565d45627e1678a3e37bd6a016c561c">addMemOperand</a>, <a href="#a7f54f5772ba80cc1f7c4a92203f14e57">addMetadata</a>, <a href="#a6d40d83c14042582354b5d875ed7f2d8">addPredicate</a>, <a href="#a927857fc69e4b4f0cde307f86f180df5">addReg</a>, <a href="#a8880ccaea51a4ee9b48c3c8d7fbfebf4">addRegMask</a>, <a href="#a846993bea18636f4fd47bbe401fece04">addShuffleMask</a>, <a href="#a7ffeb5b3940506a54e69e72e26e2a6cd">addSym</a>, <a href="#a0bc7ed8aefe042984bce6ea95ad5f1ec">addTargetIndex</a>, <a href="#ad88e27102395957e457fed8e73a085cf">addUse</a>, <a href="#ad84ebe08bb098cd283e922fd186f77e9">cloneMemRefs</a>, <a href="#a632680dcf899466c32c0095a40e7e89e">setMIFlag</a>, <a href="#adf25b569ca308aacc819a2331626ed5d">setMIFlags</a>, <a href="#a72cc8dc853a4823eccff58bc0269b306">setMMRAMetadata</a>, <a href="#a45ffb8b95e5b75eeb68be7d300eb9618">setOperandDead</a> and <a href="#abdda4cba7788bae87378a6cbdc81dbe2">setPCSections</a>.</p>

</div>
</div>

### MachineInstrBuilder() {#a54b0e0d732ea36290a9b6ed6c9960836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineInstrBuilder::MachineInstrBuilder (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> for manipulating an existing instruction.</p>


<p>F must be the machine function that was used to allocate I.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### MachineInstrBuilder() {#a84817b0c66ff61de71f1c2f9d371c818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineInstrBuilder::MachineInstrBuilder (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator MachineBasicBlock::iterator() {#a86c89530d336b36f8ca450f9041831eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineInstrBuilder::operator MachineBasicBlock::iterator ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

### operator MachineInstr \*() {#ab33a06b5978e8d3166504593034ca005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineInstrBuilder::operator MachineInstr * ()</td>
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

<p>Allow automatic conversion to the machine instruction we are working on.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

### operator-&gt;() {#a68b659f056c0f4bc576bd3075d3ab966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::MachineInstrBuilder::operator-&gt; ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a713eab58694282971c413a0d6de5975c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::add (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ade27a165903cbaaf156adfd59a7c684b">llvm::InstrEmitter::AddDbgValueLocationOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748a1633a6bba78f4ecb55256c937bde">llvm::addOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a00870d00a6899aedeef7ebdd65fc1724">addOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a631f336d06a6088837d505bf1332001e">AdjustBaseAndOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aec0904aef5bec338f4fea047c49455aa">llvm::ARMBaseInstrInfo::breakPartialRegDependency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfe6e5ec3e8d8ad4632758a0af06b8f9">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a66ba876f71016493af6fd1dc6980d912">buildMUBUFOffsetLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aee485429210d9273f05a2ffc2d1f38d6">llvm::ARMBaseInstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a31aa4c781d7a65b275b3de1882180675">llvm::SIInstrInfo::buildShrunkInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a4db3746fd517a6ce4e428b4ead57cb3d">CMSEPopCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#ada53f9e75a087c02dcea98064c69900b">CMSEPushCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxpeephole-cpp/#ae48b9308a21e92c2301831dfc8d75ac9">CombineCVTAToLocal</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv/#a8c2c7a46bf3359100068e45134218920">anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a73f427af3525340f74d7e85b984b82d6">convertCalleeSaveRestoreToSPPrePostIncDec</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacer/#ac2f0a7b9e407c886d61a39616fb89439">anonymous{X86DomainReassignment.cpp}::InstrReplacer::convertInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacerdstcopy/#a3a3c75969a49f4cec641a3af56b4bc37">anonymous{X86DomainReassignment.cpp}::InstrReplacerDstCOPY::convertInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacewithcopy/#ae1da1f845036d0455d283680da1e614b">anonymous{X86DomainReassignment.cpp}::InstrReplaceWithCopy::convertInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a414af156e6dae8024f5321babf41afb2">llvm::SystemZInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a3b6290d83ecf58d4693ea6442be7b23e">llvm::ARMBaseInstrInfo::copyFromCPSR</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abef9f720617461778f1a2e49d17ea159">llvm::ARMBaseInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a4d30d32e32d7be938a8b0a0f4dd21418">llvm::Thumb2InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a654fa7da7f95a667f9663b3d6a130293">llvm::ARMBaseInstrInfo::copyToCPSR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#abe83de329645327b1d40bee0d304aff8">createCallWithOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a7bec9e5fa4cafeca001d506741b38f0f">createPostIncLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyregisterinfo/#ac8db545cfaf863844d25944e00814ba1">llvm::CSKYRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/loongarchregisterinfo/#a14277e449886ad06b196b805fad006ec">llvm::LoongArchRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a2d8b50ff5c8dad758eb8d36c4d98bcaf">emitAlignedDPRCS2Restores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a3046f0367b644d6feafcc16f8da39967">emitAlignedDPRCS2Spills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a0bd30ba570d7cadf1358f8054ffe4af3">emitAligningInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae917ff404aade469cb9d3780515660ad">llvm::emitARMRegPlusImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a5973091849912847746aa5b158772e8b">llvm::VETargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a51c3d43bee1dec655ecaec65afc94c82">llvm::ARMFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a6289c3b215e791396217e90177ad28a5">llvm::Thumb1FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa92b03a9781f6914ffdef83ecf323708">llvm::AArch64TargetLowering::EmitFill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ab69231adafff5e2e89dfae5a21ba246b">emitIndirectDst</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e4563cae7f10b41cdff9a61f1f6aaab">llvm::ARMBaseRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abe4e954d4fb2e34a8edd0c54c9682606">emitPostLd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa331364e481586cffcf94e6dca45df86">emitPostSt</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#abfcb7ab0b2bd202bc7e048d531897a3a">emitPrologueEpilogueSPUpdate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaee29fd8c447694396529bd6a468a6f">llvm::emitT2RegPlusImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a8a9cca3d1c6515fbf780f033644ace85">emitThumb2LoadConstPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaeed6b0c7995c9000819c8bed932e551">llvm::emitThumbRegPlusImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a4c17381dc1cacb65f1dd6d31d15100e0">emitThumbRegPlusImmInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a34c1693d3ce9979ba45e1e9425cc806e">llvm::AArch64TargetLowering::EmitTileLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab0a615cb68b545ea3a9c88243a0ab4d9">emitVFROUND_NOEXCEPT_MASK</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a20e848fbe4dcba24cc443837166728a8">llvm::AArch64TargetLowering::EmitZAInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94b0ff91bd18235291da52ddf1e7cc1a">llvm::AArch64TargetLowering::EmitZero</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa695d49f883b21889c91b61d86437995">llvm::AArch64TargetLowering::EmitZTInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a83de3f9ab24662688a50952de742a4dd">llvm::ARMBaseInstrInfo::expandLoadStackGuardBase</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abe2c3303ec55393902e579d316051289">llvm::ARMBaseInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#ab4228d105bd5b126170c562e6f8acdfd">llvm::M68kInstrInfo::ExpandPUSH_POP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ab8ebdf9a381ab517c0225f7f0719cf45">expandSpillPPRToZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a99607ebccc8847200c641528a876b420">llvm::HexagonInstrInfo::expandVGatherPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa8aa7be4bd12d2e18b08a87805017131">llvm::RISCVInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a64c6eca16f58ce5cef19b84d78d3adb7">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldCopyToVGPROfScalarAddOfFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a52300ffc2cad932b8451cdd3ae41a470">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad41786bff2f31140c40979fdd64b6769">forceReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#aa8a34f3a734cc8a58ab08ce66250b1e1">fuseInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a38268e602b0a8770e7e8ce3412b2b6e8">fuseTwoAddrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a875d4d0bf620bc2515b57e5554a510fb">genNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a451ac66d74cbee6582c570a71254ae26">genTPEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd62dcc07699f0f98ae897208c1529ae">genTPLoopBody</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ad23868fe0e42fbdb124476527f50ac03">getIndirectSGPRIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a69f73e1b5f8a3e376c63293408b6786e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeByOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acbccd3fb66e9075690f45dea7440cf9e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeCoopMatr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ae5869468359515f460a588357f1737cf">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVArrayType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8bdd4c60453b10074293349820f8bdcf">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVBoolType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acab67f583801f5c01ee9ac2162f5e27d">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVPointerType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f224f7bdbbd3667e44b205c571b30d2">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4791c0c5f18aaa298445226456f15547">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvextract-cpp/#a88486e318adbd7333b898816348c8e7c">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a0ef7652ff781ab8a179fa049c170351d">llvm::ARCInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa2351273089a9b61efc8258cc7778093">llvm::ARMBaseInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a2c95253334e2a487e24d6b1d561395b5">llvm::CSKYInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a75708a12cbe3a8f421f759cbb0f070b7">llvm::LoongArchInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstrinfo/#a2c07b28605263dabce813e1b41b1907e">llvm::NVPTXInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ac73a2a13806418aeb40c26ea794c3dd7">llvm::PPCInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a2bc4c29964a242a574a8e9b78df0bb31">llvm::RISCVInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a8b7067629b6a083fe938e1e73d0b505b">llvm::VEInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a9568834e4871e98bac63dda4a5d546c8">llvm::WebAssemblyInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a7e56a357662b8329b718e0d8ae12983b">llvm::ARMBaseInstrInfo::insertOutlinedCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a5c50c1e0000377affb5eec391c213df1">insertSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad88bfb92ca2f7d419adc7e6645406a7c">llvm::SIInstrInfo::insertVectorSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0673c8aeb9b580e1be469133adba37e5">llvm::SIInstrInfo::legalizeOperandsVOP3</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a4cb529d6108d5dfdf8479ac3b03c9812">llvm::SIInstrInfo::legalizeOpWithMove</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#a49a30e74a8632576007b3678649c9fb9">llvm::ARMCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#aff4b98ad5bdf4630720ecebfeb5253bd">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::lowerSpecialCase</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ac02c01e89c0ac7acc53bb50aeac772ac">llvm::ARMBaseRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a1eab543e55a7220697eb4e72651e2e17">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeConstOffsetInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a0810cb27406ba2cd135a1a2166b08366">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeNarrowZeroStores</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmovemerger-cpp-/riscvmovemerge/#accee7cec1672950ec100570be21cce47">anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::mergePairedInsns</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a006d92e5eae5fd3ca76b72ec1b749a1b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeUpdateInsn</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#afc26610b4c561e17a9ceb497233f34cc">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::modifyCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a606d158739fd7cd13395bd7db9fc3e36">MSA2OpIntrinsicToGeneric</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#ad90722edae1f87193dcefae806cae4b8">MSA3OpIntrinsicToGeneric</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aeaeffb171ae383d18f217fbd278c8717">llvm::RISCVInstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a55d733ab1cd738ca996fd3e415b59c99">llvm::RISCVInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a680a4b1885f1217b238bbada1e936512">llvm::Thumb2InstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#af3659f9d7092d775e6bb2451b39aa440">popRegsFromStack</a>, <a href="/web-llvm/docs/api/structs/anonymous-armslshardening-cpp-/slsblrthunkinserter/#a4c1c2b4d7e1a18edf5b0fb0c26a1bb71">anonymous{ARMSLSHardening.cpp}::SLSBLRThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae5781ad71db6e0e3bf84f10c4490e291">llvm::PPCInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afd3a31cde29e70e208055c76fc41bd9a">llvm::SystemZInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#a83cbf55cc29b8e364bc11d81165caaed">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::processBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a664436e80e651ce40c1abcf063d58fa9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::promoteLoadFromStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#a24366f8644cf1d6492c2abf2999311a1">pushRegsToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a220e5ab986bbeae53290cfb49f913fed">llvm::X86InstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a49c5e597ebff3776f7a43c3d7f181680">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithBRcc</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a22b62d53bdcd603d84866e9bf8a4fb45">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithCmpBcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad30a7e0e8650626f5a5ca4b7002ac267">llvm::RevertDoLoopStart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd46906c25e4d5703a8e422283d03bde">llvm::RevertLoopDec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abaa69285a8e74b69f9d178c1b7a8c1cd">llvm::RevertLoopEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a16ff599a0020f57765f08298aaa0b157">RevertWhileLoopSetup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9061b9ab01f65a05033f729a2f12e91a">llvm::RevertWhileLoopStartLR</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#acb75d3ebfc904675aed50ee39f619373">llvm::ThumbRegisterInfo::rewriteFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a0d70a38e8f0622515630e7e8672df270">selectMergeValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a8a476245face103d65c519250257e499">SelectMSA3OpIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a0f9992c5e3a519e4128db320ba2d2e18">llvm::FastISel::selectStackmap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a838cd050490773e0349589c0d78618fc">selectUnmergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284276bdba816c71f6c16ee08e842b41">llvm::FastISel::selectXRayCustomEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a8c80b7d55789b6712c22642d4f94b90d">llvm::FastISel::selectXRayTypedEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5b3180edf81915b106633986034d7a01">llvm::ARMBaseInstrInfo::setExecutionDomain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abc74d2caa2627808c02a43aa418a68f7">setM0ToIndexFromSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a77dc4905d180a52615d00a760b111f9a">llvm::ARMFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#af07ce77a4beea41a98862690cee5ec2d">llvm::Thumb1FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8a7868df2562a3b48d08d24c9db87b98">llvm::ARMBaseInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a7c842ead18aca7681bd1cd596a3c8ba3">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::tryMoveVGPRConstToSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvpushpopoptimizer-cpp-/riscvpushpopopt/#a9c82d545821ce74a71125df227cde299">anonymous{RISCVPushPopOptimizer.cpp}::RISCVPushPopOpt::usePopRet</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a34005879daabad613a9f682bc30c0fb1">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSERT</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa4f08d12a02cc1685e8ea788f818ac1a">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSviGPR</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a>.</p>

</div>
</div>

### add() {#a8acc898589174182420d6c720ef0fc7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::add (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; MOs)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Reference <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>

</div>
</div>

### addBlockAddress() {#a6eb17a3fc032cb29dbc1908f1d4ba046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addBlockAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> * BA, int64_t Offset=0, unsigned TargetFlags=0)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad3ad3b0e833c44eb432854df8e3bff6a">llvm::MachineOperand::CreateBA</a>, <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a9189968ba471dec34e7806413bd019cd">addDisp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae83cc330c36190cf8ee9618a28e9a300">llvm::MachineIRBuilder::buildBlockAddress</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>.</p>

</div>
</div>

### addCFIIndex() {#a3e4e67777edb24fac492ef4ae15e69ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addCFIIndex (unsigned CFIIndex)</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3cf19eb005905508319869685dda19ec">llvm::MachineOperand::CreateCFIIndex</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ab08619b14fe0d6edc17b186c5a452e9e">buildCFAOffs</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#af0ba757b047f4e00f4a68fa33db9b50d">llvm::MSP430FrameLowering::BuildCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aef0079a40a972f2942156b2d73bbf190">llvm::X86FrameLowering::BuildCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a28391c59e5f478e4513f021226549734">buildDefCFAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a73f427af3525340f74d7e85b984b82d6">convertCalleeSaveRestoreToSPPrePostIncDec</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvframelowering-cpp-/cfirestoreregisteremitter/#a92aa2c10d7a31b9713443dd938973738">anonymous{RISCVFrameLowering.cpp}::CFIRestoreRegisterEmitter::emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvframelowering-cpp-/cfisaveregisteremitter/#aeaf54bb6240fb6bea4e1cd52e6a74ae1">anonymous{RISCVFrameLowering.cpp}::CFISaveRegisterEmitter::emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a6b6e001aaffc1977dbbfa8570ffe6565">EmitCfiOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a794b27dd421465dc20f1f47855a75a5c">EmitDefCfaOffset</a>, <a href="/web-llvm/docs/api/structs/anonymous-armframelowering-cpp-/stackadjustinginsts/#a042cf3c899a8ad17fe7a9509c1ed60c4">anonymous{ARMFrameLowering.cpp}::StackAdjustingInsts::emitDefCFAOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#ae193832c4a427e1aa8a6ad3240a0898e">EmitDefCfaRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1886741049357a9b7cea7f8e8784a818">emitDefineCFAWithFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#a181216377a992592ea7e30fc0ce07f0d">emitPACCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a198d0eb07bb9ae2ff6dba28a16264342">llvm::SparcFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a02cddefc96e08fba507c3d0eac7f6c1f">emitShadowCallStackEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ae5f813adf7cab5ad0f7a542b681ca95c">emitShadowCallStackPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#aa1ef43d8b6e30020194591f4e5a914ac">emitVGSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2faad2c2b19346a6b6d4e497e3619169">insertCFISameValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a313dff6a75b3ae9c5c5d6802f3007a56">insertRememberRestorePair</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a5c22366d9b2f68fba8285148c794a74d">llvm::AArch64FrameLowering::resetCFIToInitialState</a>.</p>

</div>
</div>

### addCImm() {#a3348f4e81264ccfe03832f141fdf44a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addCImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Val)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a5e7a07b4efeaec2afcb83a6551b38441">llvm::MachineOperand::CreateCImm</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7eb536540d37a55860c52b81778b013e">llvm::FastISel::lowerDbgValue</a>.</p>

</div>
</div>

### addConstantPoolIndex() {#a88177c2ee5d3e579e50128cf83de5ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addConstantPoolIndex (unsigned Idx, int Offset=0, unsigned TargetFlags=0)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aebe6fe7948d0ae093aba94381c73ed67">llvm::MachineOperand::CreateCPI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7525b6ff9464d7873516ad91ec061c23">llvm::addConstantPoolReference</a>, <a href="#a9189968ba471dec34e7806413bd019cd">addDisp</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a6159cb24e3496f5b8bd5e830e052aba1">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3068d2fa3c2556694ca3db57b7c197dd">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e4563cae7f10b41cdff9a61f1f6aaab">llvm::ARMBaseRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a55668c464aef1136badb1b58eeec19c6">emitThumb1LoadConstPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a8a9cca3d1c6515fbf780f033644ace85">emitThumb2LoadConstPool</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9fa574f4bc0ad6d1cd8335fdf7aba857">llvm::CSKYInstrInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a3ca4c3ddc5d302c21716484fa8de528d">llvm::XCoreInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a4ca63570c656522c8e6a423ae926ba5e">llvm::XtensaInstrInfo::loadImmediate</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>.</p>

</div>
</div>

### addDef() {#af584d2eb0342e655d6ec597c0f7958db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo, unsigned Flags=0, unsigned SubReg=0)</td>
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

<p>Add a virtual register definition operand.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="#a927857fc69e4b4f0cde307f86f180df5">addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dstop/#a45141d649d02a2ed17b51b5419ee884d">llvm::DstOp::addDefToMIB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvprelegalizercombiner-cpp-/#a99fb6c2c4ea3a52f8977eeb8d2c2f425">anonymous{SPIRVPreLegalizerCombiner.cpp}::applySPIRVDistance</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17fda1a191d8f69587355e32c5f15618">llvm::buildAtomicFlagInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abaf31a84826d881e8cebb369b37c6ff1">llvm::buildAtomicFloatingRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa24e8200fb460e1454ce71de5921fc7b">llvm::buildAtomicLoadInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acec38968fb25d9da84d9d606eca35d7d">llvm::buildAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae83cc330c36190cf8ee9618a28e9a300">llvm::MachineIRBuilder::buildBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6aee777d2869b23ba59b88b9ceb32cfe">llvm::SPIRVGlobalRegistry::buildConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#affb04c244423615aa0df24ee36f2de20">llvm::SPIRVGlobalRegistry::buildConstantInt</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4280c0cdf83d31309a8ad8d0d6815e66">llvm::SPIRVGlobalRegistry::buildConstantSampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a81a7959d3e7f624343ecdf6905e251dd">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a8dcc4e0c146cff251e73a2a59123683b">buildOpBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp/#a3b8f2c8dafaf2b1007b8661546ce5aca">convertPtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ade00a4708e793e75a00a3030325cbf84">llvm::AArch64InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afbb3d2344086d40fa845201e37538d85">llvm::SystemZInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a2abcc0dade6e762f2145f49e3158a71c">doInsertBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a36db540eb7d0490cab86e4cf12ac9116">emitLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a97c69ea577c9578ecadf9469189438d0">emitStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94b0ff91bd18235291da52ddf1e7cc1a">llvm::AArch64TargetLowering::EmitZero</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#aec1517c8d806609cb368f431ddab1bc7">llvm::VEInstrInfo::expandGetStackTopPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8997d907b1de0e1b433c59102335b06a">llvm::AArch64InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a404db50d68f1ca8d28396b5e2deb061d">llvm::VEInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#abbd7ca528e7bfb2362adfeece0fa9a8c">expandPseudoLogM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748bbd916eb5b48b009f8ee2e6a6afc9">llvm::generateAsyncCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae60b3860c5a2f98d349a53660758ddd9">llvm::generateCastToPtrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a884a65fc47e7cf521d37505e1548e9ca">llvm::generateConvertInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515c6055dea0a74d18c4549511921e8c">llvm::generateDotOrFMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e92ead0d298bfaef08370c3877e05c9">llvm::generateEnqueueInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aebcace45f75d5389e0c72effb52530b6">llvm::generateExtInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a610c7b58032f5eac1b06aa0c66cadb6a">llvm::generateGroupUniformInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa2920e81d3e11168548e83a60ddaaf">llvm::generateImageMiscQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa258d22bc5ca54e36dc15a8c3e724e52">llvm::generateIntelSubgroupsInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9c060a884e9461f06d7601681d2bcf">llvm::generateKernelClockInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfd0973871508362181539a1e103e0ed">llvm::generateRelationalInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab25d01b38cf3d0b9e22fe06c673243d6">llvm::generateVectorLoadStoreInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd62dcc07699f0f98ae897208c1529ae">genTPLoopBody</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af54e9ce01961e65d9b74fef2193a8d95">llvm::SPIRVGlobalRegistry::getOrCreateConstFP</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a08f607435df14840793b848f2b3c0257">llvm::SPIRVGlobalRegistry::getOrCreateConstInt</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af99db04834e1ae3fc23466a80045a4d9">llvm::SPIRVGlobalRegistry::getOrCreateConstNullPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a138bc82a9943aa3008ab86bec2d2c91a">getOrCreateFrameHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a69f73e1b5f8a3e376c63293408b6786e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeByOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acbccd3fb66e9075690f45dea7440cf9e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeCoopMatr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abeddeff35f8dd231213915a6f77f0920">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeDeviceEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4cd2c03c778450920cd3b53acdcb4fba">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a0067190a151de0ad367e8d1e56c1016a">llvm::SPIRVGlobalRegistry::getOrCreateOpTypePipe</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8cdc39b963a62003cd157541feca56f6">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampledImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea914eb511a3b8ebf605c62c07e8ab44">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampler</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ae5869468359515f460a588357f1737cf">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVArrayType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8bdd4c60453b10074293349820f8bdcf">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVBoolType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acab67f583801f5c01ee9ac2162f5e27d">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVPointerType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f224f7bdbbd3667e44b205c571b30d2">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4791c0c5f18aaa298445226456f15547">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a35c2ba2ad91e2fe027f8f64e92a7502f">llvm::SPIRVGlobalRegistry::getOrCreateUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ae7ec7dfcb6babc9f95a9d27ca37dddcc">llvm::PPCRegisterInfo::lowerWACCSpilling</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a1eab543e55a7220697eb4e72651e2e17">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeConstOffsetInsn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d5aaa74bb3796fbcd85861222730ab">llvm::processInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a014d1ebf94ebd54347ec5c6da3af5ea2">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::selectDot4AddPacked</a> and <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a8139fddffe4387e1752fb124e92a822b">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::selectDot4AddPackedExpansion</a>.</p>

</div>
</div>

### addDisp() {#a9189968ba471dec34e7806413bd019cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addDisp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Disp, int64_t off, unsigned char TargetFlags=0)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="#a6eb17a3fc032cb29dbc1908f1d4ba046">addBlockAddress</a>, <a href="#a88177c2ee5d3e579e50128cf83de5ba6">addConstantPoolIndex</a>, <a href="#a9117be19af857a7bdcee7bdf0279024c">addGlobalAddress</a>, <a href="#a6c1f959947905135c7dd215b64957654">addImm</a>, <a href="#aaa7ad3e87d858a3ed3b3dc8b05b70078">addJumpTableIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a94f5b10f666acf5a0cddd5ac8302d0b8">llvm::MachineOperand::getBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a0fcdaab1a4c3134b8f80aa74cabeb970">llvm::MachineOperand::getGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab06dda088d3c7686f7dfcdb2b96323f5">llvm::MachineOperand::getTargetFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab313591ae4ea1e3a4ab59121a7dc2a2b">llvm::MachineOperand::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">llvm::MachineOperand::MO_BlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">llvm::MachineOperand::MO_ConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">llvm::MachineOperand::MO_JumpTableIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a00870d00a6899aedeef7ebdd65fc1724">addOperands</a>.</p>

</div>
</div>

### addExternalSymbol() {#a30a1feca92679c24a46b0b824a6de269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addExternalSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FnName, unsigned TargetFlags=0)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2871c33d3a1264270d23ec72b71f1399">llvm::MachineOperand::CreateES</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorprint-cpp/#ac83650c39910df4efe637a37279fa674">addAsmInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aac8f5d5c66c21056b3144508e8142639">llvm::ARCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acfee0aff6a62996ec1dbee56ef35ad88">llvm::AArch64TargetLowering::EmitGetSMESaveSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#adfd69c79b4eb159ce76cbc8cf5b06073">emitGPDisp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac78e4ff0f9a757b578b967d5bd1f70ee">llvm::WebAssemblyFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#ace182ca668404b3d23cae8329d941ba4">llvm::MipsFunctionInfo::initGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ab997f379e36469df72be3d7c59f17d2a">llvm::VETargetLowering::prepareSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/structs/anonymous-m68kinstrinfo-cpp-/m68kglobalbasereg/#a04412e72586680e6bfb4ced5a69102c2">anonymous{M68kInstrInfo.cpp}::M68kGlobalBaseReg::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/cgbr/#ae7e54015b8e4160365d925c1bd46004f">anonymous{X86InstrInfo.cpp}::CGBR::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86returnthunks-cpp-/x86returnthunks/#ab4a10d58e295ec66ff8c9c1d3eeb0529">anonymous{X86ReturnThunks.cpp}::X86ReturnThunks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9f7b01772fb64eab764bc071e84b860e">llvm::FastISel::selectCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#acfa976b571bd6001d4e8f4ccba059162">llvm::WebAssemblyFrameLowering::writeSPToGlobal</a>.</p>

</div>
</div>

### addFPImm() {#a95c7b5ed23471212aeaba1eee6501261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addFPImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * Val)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2cd605d7476194cf38e7ef6d2c57391a">llvm::MachineOperand::CreateFPImm</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a81a7959d3e7f624343ecdf6905e251dd">llvm::MachineIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aba7be31f2606d1565335458953610fcd">llvm::FastISel::fastEmitInst_f</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7eb536540d37a55860c52b81778b013e">llvm::FastISel::lowerDbgValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>.</p>

</div>
</div>

### addFrameIndex() {#a86a93dd8ddbce120d8c3101c16bc3cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addFrameIndex (int Idx)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afda3f1971b3e44709267be818ffd3035">llvm::MachineOperand::CreateFI</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ade27a165903cbaaf156adfd59a7c684b">llvm::InstrEmitter::AddDbgValueLocationOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensainstrinfo-cpp/#afb2753bad8eb2a132f72925416a0ac4c">addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24df964fef5537043b85294a38037ca1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb2d11e8b17ef23a86d57b4105fba8e1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e8b1da7820b3f19cfb702d4312410ce">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7db1f138a21ec2b83c9e9fca39bce6af">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a67931ef18efe0f1710e3f2e39ddfb8f6">llvm::M68k::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a2d8b50ff5c8dad758eb8d36c4d98bcaf">emitAlignedDPRCS2Restores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a2ed887f0677d391bc6f9d7e77b761695">llvm::AArch64TargetLowering::EmitInitTPIDR2Object</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaf673a1e44074d7088008437112159fa">emitSplitF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a39e2fe24f8016760f80ca14ba3476ebc">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#aaf94fccaa261871e44881773bcdc5ee7">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a93533d35a661d5dc48a03c624839b8e4">llvm::RISCVInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#aa31003f66af0241b32a8572e8b33d7c4">llvm::Mips16InstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#abf65c6f3a770509d24a75efbbe785a67">llvm::MipsSEInstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ad96e959009cbe91d2814bcdfe4fcd51c">llvm::ARCInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#aa3221ba2a1b01836c1f02c48d2bd2c4e">llvm::AVRInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#a3ab811022aee0c0ea9656dd6ccefdd99">llvm::BPFInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a2c4630e6b74de7b52933845fe4f48f01">llvm::CSKYInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad3b3220844622daec97aeb14080a66e4">llvm::HexagonInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a330d9342644a019e77040182050f9b6a">llvm::LanaiInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#afa83048a6e09247f7f6310ffc0681909">llvm::LoongArchInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a3a04d16772e68de8d911d305070f0e0b">llvm::MSP430InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abe4a49e8ceb6213fe44eb0ebc9869eb1">llvm::SIInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a38be8eeeb68d45e0a914cd8f3237ce83">llvm::SparcInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a6d4af3948133ad97770947f7d1242561">llvm::VEInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a541a292af69ae4be75a66b7994e89abb">llvm::XCoreInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab1601d92ffdfcf6fe48b40b6a7cf8d59">loadRegPairFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a7321f8d9c50eb416611a0309a3fd9742">llvm::AArch64RegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ac02c01e89c0ac7acc53bb50aeac772ac">llvm::ARMBaseRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ab0c9dd2c74f5a4d226e5f57423aa53b9">llvm::PPCRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a497ba80da227001f952a7d30cfe0552f">llvm::RISCVRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a06c8d8abacb01c870f729e8d2027364f">llvm::SIRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#afb4c3921369b6b1fef886bfa979b6d2a">storeRegPairToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#ac808bf28cfa407acff2b367a0bb383ba">llvm::MipsSEInstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aeba4e73d60d1b4cedc120d06114c0620">llvm::AArch64InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a687fecaf502080080ba5069e6b211a65">llvm::ARCInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8a7868df2562a3b48d08d24c9db87b98">llvm::ARMBaseInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a90829bf41a9e8e4c4e4ad59eab490719">llvm::AVRInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#a41c0bd4e75d4643a8387fe6d56eca337">llvm::BPFInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a647cde93263cdcab73a72f5e459041c6">llvm::CSKYInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a9644f3506784b55b500d2f73f94d79e0">llvm::HexagonInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ae93380d9a76c25ec34ee034e13b3a8fd">llvm::LanaiInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aed611129b85082f7e6459907b50a8cd5">llvm::LoongArchInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#ae215353a37be6d2f533a4858bd96be74">llvm::MSP430InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ec207a1c12adfc61c6566436e5a2cd7">llvm::SIInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#abc124725b4afa4a9d9449c6e2cfb3d73">llvm::SparcInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a2132749e515b00c60255bdb4acfba223">llvm::VEInstrInfo::storeRegToStackSlot</a> and <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a915259afe54d2619524ed03c9c273c57">llvm::XCoreInstrInfo::storeRegToStackSlot</a>.</p>

</div>
</div>

### addGlobalAddress() {#a9117be19af857a7bdcee7bdf0279024c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addGlobalAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, int64_t Offset=0, unsigned TargetFlags=0)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ace112d8a86396bd55e99738cd41005b6">llvm::MachineOperand::CreateGA</a>, <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a9189968ba471dec34e7806413bd019cd">addDisp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6006bd8b7a7155240e3a11c12d104c50">llvm::AMDGPULegalizerInfo::buildPCRelGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a8d1d93bb20bf72c7782cf68446e5bf9f">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::CreateFailCheckSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a83de3f9ab24662688a50952de742a4dd">llvm::ARMBaseInstrInfo::expandLoadStackGuardBase</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8997d907b1de0e1b433c59102335b06a">llvm::AArch64InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#ace182ca668404b3d23cae8329d941ba4">llvm::MipsFunctionInfo::initGlobalBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a7e56a357662b8329b718e0d8ae12983b">llvm::ARMBaseInstrInfo::insertOutlinedCall</a>.</p>

</div>
</div>

### addImm() {#a6c1f959947905135c7dd215b64957654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addImm (int64_t Val)</td>
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

<p>Add a new immediate operand.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab09679b541a6ba1219b3602569847364">llvm::MachineOperand::CreateImm</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorprint-cpp/#ac83650c39910df4efe637a37279fa674">addAsmInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7525b6ff9464d7873516ad91ec061c23">llvm::addConstantPoolReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff98f30548a2233baed77a73408842a2">llvm::addDirectMem</a>, <a href="#a9189968ba471dec34e7806413bd019cd">addDisp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensainstrinfo-cpp/#afb2753bad8eb2a132f72925416a0ac4c">addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24df964fef5537043b85294a38037ca1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e8b1da7820b3f19cfb702d4312410ce">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7db1f138a21ec2b83c9e9fca39bce6af">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a67931ef18efe0f1710e3f2e39ddfb8f6">llvm::M68k::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a52716532c3562bbe9c3fc343761c3c8a">llvm::SITargetLowering::AddMemOpInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a3c62fedeccc54762c292a1a19fa7252b">addMemoryOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a33cabf82e98c7c5f94d04a12179356e3">addMemoryOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2426fcc21a9819b2f48f2f7db8a23844">llvm::addNumImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748a1633a6bba78f4ecb55256c937bde">llvm::addOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f23de662df5c947a914f6ac433f3344">llvm::addOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ae4f0e11a6107b18bffcb5daf2e08772e">llvm::M68k::addOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#afd41e1bf7be73c5e667a9f0a1f4a6c15">addOperandsForVFMK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1aa408e30d1bdfe5eccc8979992ffefd">llvm::addPredicatedMveVpredNOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ad283cfc77268d18405882cb6588c337f">llvm::M68k::addRegIndirectWithDisp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d45e5dba16959552ccd6e0e3615e84e">llvm::addRegReg</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b728ee981ed802e7ed4fd2211e8d72">llvm::addStringImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7bc392573220746bf1ef1f95fa98b46">llvm::addUnpredicatedMveVpredNOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a66f49b91bc14b1efa661b26e7f2bb8d4">addZeroImm</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#abada5e68ca1f455ee3b38dda17180c6f">llvm::M68kInstrInfo::AddZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a631f336d06a6088837d505bf1332001e">AdjustBaseAndOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#aa4909014e5875c7b2d1cd6fdd7ab7e89">llvm::RISCVRegisterInfo::adjustReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#a5029a9a110d5000ca84dfcd7e972e393">llvm::MipsSEInstrInfo::adjustStackPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a932b9562347f2f18d278c611c83268b5">llvm::XtensaInstrInfo::adjustStackPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a83aa1663ebe23169979a76be989b1144">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::adjustTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aec0904aef5bec338f4fea047c49455aa">llvm::ARMBaseInstrInfo::breakPartialRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a1f2aa5be123d8c29912da422ca2e32a3">llvm::Mips16InstrInfo::BuildAddiuSpImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#adf3d2a21deea258c4c4a961586114ef9">llvm::MachineIRBuilder::buildAssertInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9a7f5712e4a4603a0bdd87cc08e9b1d6">llvm::AArch64InstrInfo::buildClearRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad9c4463170797dc633ce8dfa192f132b">llvm::X86InstrInfo::buildClearRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4280c0cdf83d31309a8ad8d0d6815e66">llvm::SPIRVGlobalRegistry::buildConstantSampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a030150151483c64bff02ae4f89a50c96">llvm::R600InstrInfo::buildDefaultInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a21f358f36e1ae7fc91568266264f760e">llvm::MachineIRBuilder::buildFence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a2d1eb7b0207905141f6ddb1f228f3696">buildGitPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfe6e5ec3e8d8ad4632758a0af06b8f9">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2daca542c8dc98439d2a5a86196e0fc8">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a66ba876f71016493af6fd1dc6980d912">buildMUBUFOffsetLoadStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a985ab67fe6c5e51cb42dc97aaf6b300f">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a686587ed0b5b8437aa621630cf56d147">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec2c920f97cffa508fee51ee5e722056">llvm::buildOpSpirvDecorations</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6006bd8b7a7155240e3a11c12d104c50">llvm::AMDGPULegalizerInfo::buildPCRelGlobalAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a7bc05bcba45ed1e4e903c1c952d09178">buildRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a544e5e38d5032dd862ab44953c2c173b">buildScratchExecCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1271e8babb762355bcb15d461f8f6a1c">llvm::SITargetLowering::bundleInstWithWaitcnt</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a3ea2369e6bcfa35889cf566047e3ca3f">llvm::PPCInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv/#a8c2c7a46bf3359100068e45134218920">anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a73f427af3525340f74d7e85b984b82d6">convertCalleeSaveRestoreToSPPrePostIncDec</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a414af156e6dae8024f5321babf41afb2">llvm::SystemZInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a3b6290d83ecf58d4693ea6442be7b23e">llvm::ARMBaseInstrInfo::copyFromCPSR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#acd4e3782462bd215bc07bd1f9b2b01b5">llvm::AArch64InstrInfo::copyGPRRegTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ade00a4708e793e75a00a3030325cbf84">llvm::AArch64InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#ae8be35955783557ba6a8d97bcf8353e7">llvm::CSKYInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a75c1ba5e07585f5eafbd2a56ba489b5e">llvm::LanaiInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a759a3354d37a7d694ba126ace98547f0">llvm::LoongArchInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#a28dc5e4998fe0b9c82c9a30f9c20ca08">llvm::MipsSEInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a3e0a4dad177be52a38a07e782fc9207f">llvm::PPCInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5e29efc37d9738b891d35308524d7d5b">llvm::RISCVInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a519410003771768aef013bd57efa6cf4">llvm::SIInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afbb3d2344086d40fa845201e37538d85">llvm::SystemZInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad8b8d94aaf80cefc49bc3263f05cd741">llvm::VEInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#aba4687efa0edb8b976493fdea89e719c">llvm::XCoreInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#a669f90d5fe703ecfe25fb738553f6ea5">copyPhysSubRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a654fa7da7f95a667f9663b3d6a130293">llvm::ARMBaseInstrInfo::copyToCPSR</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a8d1d93bb20bf72c7782cf68446e5bf9f">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::CreateFailCheckSequence</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a7e1b709b5200ebfeeb1feff10a572fe9">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::createNewWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a1b8a0415e101fcd1f76e5f8ee95172ee">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::createNewWaitcnt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a7bec9e5fa4cafeca001d506741b38f0f">createPostIncLoadStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instrinfo-cpp-/aarch64pipelinerloopinfo/#a3225760dca7855181b535133948ea278">anonymous{AArch64InstrInfo.cpp}::AArch64PipelinerLoopInfo::createRemainingIterationsGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-armbaseinstrinfo-cpp-/armpipelinerloopinfo/#a2afe54a3f381a7c3f67db172f886d734">anonymous{ARMBaseInstrInfo.cpp}::ARMPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a08073cedfc0efeff220a6af9b84d2cb6">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loongarchexpandatomicpseudoinsts-cpp-/#a64e613bd4dc479933ae0ec4c701ef699">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::doAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#a849e02093ed0423e32e7a0bb24def54b">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::doAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a6159cb24e3496f5b8bd5e830e052aba1">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3068d2fa3c2556694ca3db57b7c197dd">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loongarchexpandatomicpseudoinsts-cpp-/#a47c1617a975f5b87a9c3c3cb9e3de32e">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::doMaskedAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#aec87b1447d0efa73d10bb35550a9a7cd">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::doMaskedAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a430f53d8e433993ae806a386a4870efc">llvm::AVRFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ab30ade3265bd079731057aafc0ff6e9f">llvm::MSP430FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a63c498f1fcb62301a44ad58e2dc8e7fc">llvm::PPCFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#afb457df257778163977aebad1d1165e8">llvm::SIFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a0ab2cc201e1521acab599966d10b815d">llvm::XCoreFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a5846a629f1d7d7cc33ecf2a63319e14a">llvm::AVRRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/bpfregisterinfo/#a849e9ef6e1cc9fdb4a18b27bf6eadef7">llvm::BPFRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyregisterinfo/#ac8db545cfaf863844d25944e00814ba1">llvm::CSKYRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/lanairegisterinfo/#acd4d1d9eb28b9bca2ca401487bdf529e">llvm::LanaiRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/loongarchregisterinfo/#a14277e449886ad06b196b805fad006ec">llvm::LoongArchRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430registerinfo/#a1ae0b9564ca66a61628084c4bb858ea8">llvm::MSP430RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/sparcregisterinfo/#a5e8cc743ac1b84dd6f00bcee3c9e125d">llvm::SparcRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a1e101bcf68a4448908d194d220029861">llvm::SystemZRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a2d8b50ff5c8dad758eb8d36c4d98bcaf">emitAlignedDPRCS2Restores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a3046f0367b644d6feafcc16f8da39967">emitAlignedDPRCS2Spills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a0bd30ba570d7cadf1358f8054ffe4af3">emitAligningInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab812d774aa563ffc2c67030a9ba1be39">llvm::AArch64TargetLowering::EmitAllocateSMESaveBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae917ff404aade469cb9d3780515660ad">llvm::emitARMRegPlusImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinserthardclauses-cpp-/siinserthardclauses/#afea2f73a2971b1c2238c0996efdb1201">anonymous{SIInsertHardClauses.cpp}::SIInsertHardClauses::emitClause</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ad04238a3223242e0565e4f98df0461a6">llvm::SIFrameLowering::emitCSRSpillRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a84c4c1518f3593f9c1d0b10f8364ebb8">llvm::SIFrameLowering::emitCSRSpillStores</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#a7cdd14f8272a87151d5bd4f1aeeeb4de">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::emitDelayAlu</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a056f22c11083630d8bcc82299cb783af">llvm::PPCTargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a43f6667038342a819037b705ab34277a">llvm::SystemZTargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a5973091849912847746aa5b158772e8b">llvm::VETargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aac8f5d5c66c21056b3144508e8142639">llvm::ARCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a487d00503c99000990bb90458b08702c">llvm::AVRFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#a188a6b8252a69aa600405ee5308b96ff">llvm::LanaiFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a3a9df23d95cdadc6a77b12dc3377a331">llvm::MSP430FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#ab1be113dfec8a96458235eea8ac0797f">llvm::VEFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#adbe9a36b5d064d3fe4667e4c1b47af85">llvm::WebAssemblyFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a756acce5a5adef291dc50593ce6d56a4">llvm::XCoreFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a0ae07475a5705c0ed37023fc64008c7b">llvm::VEFrameLowering::emitEpilogueInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab6a60676cdf39d45ae2ec66a7ea4aada">llvm::AArch64TargetLowering::EmitF128CSEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a9c2ee381172db4d044e61d3438031d6b">llvm::HexagonDAGToDAGISel::emitFunctionEntryCode</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a82e453c9e7f441c185009164f0136fa8">llvm::SITargetLowering::emitGWSMemViolTestLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a1041b4042ad87c8a306b5e0edc9fced4">emitIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ab69231adafff5e2e89dfae5a21ba246b">emitIndirectDst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a071d8b84e530f1a6e725aea09fdc6407">emitIndirectSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a2ed887f0677d391bc6f9d7e77b761695">llvm::AArch64TargetLowering::EmitInitTPIDR2Object</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae6e03361f09a5b06dc299f6ee1c76ca4">llvm::AArch64TargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#acd40e68d03e3f43b4f7563d083d0e2ee">llvm::RISCVTargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a89a6b95d310330e345c3aee6a07ffd96">llvm::X86TargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a36db540eb7d0490cab86e4cf12ac9116">emitLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e4563cae7f10b41cdff9a61f1f6aaab">llvm::ARMBaseRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a476adf24d3374520fb31b2785f331d58">emitLoadScalarOpsFromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvindirectbranchtracking-cpp/#a3b59a09876eac0e33446f0367f8960c1">emitLpad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#aff663b5af9761f53e2f0d42ce09c408f">emitPACSymOffsetIntoX16</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abe4e954d4fb2e34a8edd0c54c9682606">emitPostLd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa331364e481586cffcf94e6dca45df86">emitPostSt</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#a1cc86e82857e8ff7bceddf8838830577">llvm::LanaiFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a921a457b786497c2309b9f63abd9c951">llvm::MSP430FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#aad707aff5fcbdc8180deb9e6695f0c32">llvm::NVPTXFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a58cebd1e96489b04d18f2a7c39c250f8">llvm::SystemZXPLINKFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#ab3c8272ea0652d9ab75b889488f2717f">llvm::VEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac78e4ff0f9a757b578b967d5bd1f70ee">llvm::WebAssemblyFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#abfcb7ab0b2bd202bc7e048d531897a3a">emitPrologueEpilogueSPUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a59e84300cf3bfbf40a89fdeaf965097f">llvm::VEFrameLowering::emitPrologueInsns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a94be4f19deb3ce06a8fcde89fb4b639b">emitPseudoCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a9de3850aa5bea6fb60e5c61162bf22e9">emitPseudoXVINSGR2VR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcframelowering-cpp/#a23d4062f31c06d23731cccff25e7eb44">emitRegUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a02cddefc96e08fba507c3d0eac7f6c1f">emitShadowCallStackEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ae5f813adf7cab5ad0f7a542b681ca95c">emitShadowCallStackPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaf673a1e44074d7088008437112159fa">emitSplitF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a2e28f3159a4ec003bae892a828ae295b">llvm::M68kFrameLowering::emitSPUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aa8a605a58ebdee20705834400bdbb922">llvm::X86FrameLowering::emitSPUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6a6cb0d8b5d8e3b35dee29f5e752d31c">llvm::X86FrameLowering::emitStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a97c69ea577c9578ecadf9469189438d0">emitStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaee29fd8c447694396529bd6a468a6f">llvm::emitT2RegPlusImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a55668c464aef1136badb1b58eeec19c6">emitThumb1LoadConstPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaeed6b0c7995c9000819c8bed932e551">llvm::emitThumbRegPlusImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a4c17381dc1cacb65f1dd6d31d15100e0">emitThumbRegPlusImmInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13a9214d6e92afcb3e956a5891522bed">emitXBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ae0196eca3002f5fd8c339ea859ddd12f">llvm::SIInstrInfo::enforceOperandRCAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#accecdb72ed09118005742bcd44b08440">ensureEntrySetPrio</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#aec1517c8d806609cb368f431ddab1bc7">llvm::VEInstrInfo::expandGetStackTopPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a83de3f9ab24662688a50952de742a4dd">llvm::ARMBaseInstrInfo::expandLoadStackGuardBase</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad8e9b54f022eddc33ee49305e85d6b7f">llvm::SIInstrInfo::expandMovDPP64</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a44f31fb5ea31b5062b22b05cb8fddee4">expandNOVLXStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8997d907b1de0e1b433c59102335b06a">llvm::AArch64InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a7941fd2c7d339dfe155c4327fd95fab0">llvm::PPCInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#afdfbfb84a63a295205139121a3a02685">llvm::SparcInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a404db50d68f1ca8d28396b5e2deb061d">llvm::VEInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6203308c1da11d69cb3bd6c23b90b207">expandSHXDROT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ab8ebdf9a381ab517c0225f7f0719cf45">expandSpillPPRToZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a99607ebccc8847200c641528a876b420">llvm::HexagonInstrInfo::expandVGatherPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2586ad27c00166b367fe4d171be2bfaf">extractRsrcPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a738eff0daa8e9f33ff056da16adefb4d">llvm::FastISel::fastEmitInst_i</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aef1cb331526de21d6b1729a42a72d74f">llvm::FastISel::fastEmitInst_ri</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a91124ff314dcb25457d0a4bd31fa5c52">llvm::FastISel::fastEmitInst_rii</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ae348a9f69bb94b326d0e722c74dfaf7b">llvm::FastISel::fastEmitInst_rri</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a39e2fe24f8016760f80ca14ba3476ebc">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#aaf94fccaa261871e44881773bcdc5ee7">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kcollapsemovempass-cpp-/m68kcollapsemovem/#a6f7b069c3605517327ae9c48af7c9781">anonymous{M68kCollapseMOVEMPass.cpp}::M68kCollapseMOVEM::Finish</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19209407d5758bdcecfe6e8f5cea0c2d">llvm::finishBuildOpDecorate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#acc3031d4170d4a972043c6dfa34508c2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::fixSCCCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#acced35ebfd644d56dc0bcc060bb1bd8d">llvm::SystemZInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a93533d35a661d5dc48a03c624839b8e4">llvm::RISCVInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad41786bff2f31140c40979fdd64b6769">forceReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silatebranchlowering-cpp/#a2fa9fe1bc3c4ca4168ea98c54c5090e2">generateEndPgm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aebcace45f75d5389e0c72effb52530b6">llvm::generateExtInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcframelowering-cpp/#a26b9bb9c6af7500bfeac678ddf1bf601">generateStackAdjustment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab25d01b38cf3d0b9e22fe06c673243d6">llvm::generateVectorLoadStoreInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad7dacfdd99d94fce20ccc2450bf5eb76">genFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a451ac66d74cbee6582c570a71254ae26">genTPEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd62dcc07699f0f98ae897208c1529ae">genTPLoopBody</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ad23868fe0e42fbdb124476527f50ac03">getIndirectSGPRIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a138bc82a9943aa3008ab86bec2d2c91a">getOrCreateFrameHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4cd2c03c778450920cd3b53acdcb4fba">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a0067190a151de0ad367e8d1e56c1016a">llvm::SPIRVGlobalRegistry::getOrCreateOpTypePipe</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acab67f583801f5c01ee9ac2162f5e27d">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVPointerType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8f224f7bdbbd3667e44b205c571b30d2">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4791c0c5f18aaa298445226456f15547">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5b2c69041e8c83952d7cdd75cf7a36e8">llvm::SITargetLowering::getPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a246b64254ae742fe382729fc2b810508">IfNeededExtSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a640ceaa2f3dbdb0a8b226534cb72fa7e">IfNeededLDAWSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsplitconst32andconst64-cpp/#a79661f41f9eef555922452344ae54280">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvextract-cpp/#a88486e318adbd7333b898816348c8e7c">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertreadwritecsr-cpp/#a93ca2859094e3f43227290d2f88472c9">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#a91bdbe4fa62b27dc742255dd1d9b16f4">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#ad056b2534ea3030fc135769c9e2fe51c">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::insertAcquire</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa2351273089a9b61efc8258cc7778093">llvm::ARMBaseInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a150e7cedb8221a184efe28d747fd3382">llvm::LanaiInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a4c21224e6322bedc01805410f79a6699">llvm::MSP430InstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ac73a2a13806418aeb40c26ea794c3dd7">llvm::PPCInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#afbb00c84e6a7ad45d3b6b3839ee51e6c">llvm::SparcInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a1974be33e69e1cda7a0d2e6da445c12d">llvm::SystemZInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ab1f5181c16c1e183fdccc4f4552ba887">llvm::X86InstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a9fe5f8d86815ba379552a73645b0f430">llvm::XtensaInstrInfo::insertBranchAtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a7d4bb69b0d32d7faede599d671289c15">llvm::XtensaInstrInfo::insertConstBranchAtInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a8c0efd377a713687b369602245dbe9da">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a75f3e392bd9cff57dcd444d521d7fd94">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad94f2f559486e50040a794798454f67f">llvm::SIInstrInfo::insertEQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a9189604a4845165a94dd42f19b31e7b4">InsertFPImmInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#aa0cefa4c61cc43ff6fd225bc7b4f917e">InsertLDR_STR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad64501a368789645f6f80afbce82da90">llvm::insertMultibyteShift</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#acae141c2c150567424d8cc080976608e">llvm::SIInstrInfo::insertNE</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a67adde1f2510be0a20eaf7ecce8954fa">llvm::AArch64InstrInfo::insertNoop</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a35a34ad93d12d742710032a33f3ecb57">llvm::SIInstrInfo::insertNoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#ad06cd42e4a7a1a08c8570fb02ded9fac">insertNoopsInBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a20491e3d4f88b3e92bb223d6f23480c6">llvm::MipsInstrInfo::insertNop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64a53fix835769-cpp/#a4d4ea7006c2ea29075404529ec9e977f">insertNopBeforeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a4c5be0dce0caceff8b457e09b8a998fc">llvm::AArch64InstrInfo::insertOutlinedCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#abd7e366e4bb57f129d2e7204e4359498">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::insertRelease</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx90acachecontrol/#a86d0c030b48e2942c893d0a483248d4f">anonymous{SIMemoryLegalizer.cpp}::SIGfx90ACacheControl::insertRelease</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx940cachecontrol/#a4ce0cfef837f200c15610c1fb1d5971f">anonymous{SIMemoryLegalizer.cpp}::SIGfx940CacheControl::insertRelease</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a2d04c20f5631c0950af280cb294db89d">llvm::SIInstrInfo::insertReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ef020b54917711fa4fbe9b8ad48258b">llvm::SIInstrInfo::insertScratchExecCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a7f43397146b3eee4bcd4ff73ec27335f">InsertSEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a5c50c1e0000377affb5eec391c213df1">insertSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a029c7ad54d8731492ed559aa860e3395">llvm::AArch64InstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a953f3ddec823a0c7db75e73dbf550632">llvm::SIInstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a9ccd38f29c70497c158cca6c739f458d">llvm::SystemZInstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a29c37970b1c079bbbc4515cb00e112fe">llvm::X86InstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/classes/anonymous-simoderegister-cpp-/simoderegister/#ac5cb23515382def14508d54ee39bcc5f">anonymous{SIModeRegister.cpp}::SIModeRegister::insertSetreg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7dbf2885fa89980322c2f4b58f85ff18">llvm::SIInstrInfo::insertSimulatedTrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#ae88297df93601a3a0929300e6a6b58d7">InsertSPConstInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a830c556c1d7adec01904fdfe8cd50949">InsertSPImmInst</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad88bfb92ca2f7d419adc7e6645406a7c">llvm::SIInstrInfo::insertVectorSelect</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#adbdd3b28d00cd76ee5e8ec0caf4443dc">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::insertWait</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#a0569f01e3d6c805c55d479767678e539">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::insertWait</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx6cachecontrol/#af78f627db81fe741605f4d60420ba145">anonymous{SIMemoryLegalizer.cpp}::SIGfx6CacheControl::insertWait</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx12cachecontrol/#afd2b540da970228602da10afc6023333">anonymous{SIMemoryLegalizer.cpp}::SIGfx12CacheControl::insertWaitsBeforeSystemScopeStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aff7dfc9d1d4355acbd741d76ce27fca1">llvm::AMDGPULegalizerInfo::legalizeTrapEndpgm</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a6d68551280f423f1894b605eb2c5a872">llvm::ARCInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#acd22577c1abdac8d676fc8dc30e7c223">llvm::Mips16InstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#aa40f4913df15aca03301144b7f1673df">llvm::MipsSEInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afc45f79c5209c1eb89dc79708ff46a6b">llvm::SystemZInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a3ca4c3ddc5d302c21716484fa8de528d">llvm::XCoreInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a4ca63570c656522c8e6a423ae926ba5e">llvm::XtensaInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#aa31003f66af0241b32a8572e8b33d7c4">llvm::Mips16InstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#abf65c6f3a770509d24a75efbbe785a67">llvm::MipsSEInstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ad96e959009cbe91d2814bcdfe4fcd51c">llvm::ARCInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#aa3221ba2a1b01836c1f02c48d2bd2c4e">llvm::AVRInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#a3ab811022aee0c0ea9656dd6ccefdd99">llvm::BPFInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a2c4630e6b74de7b52933845fe4f48f01">llvm::CSKYInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad3b3220844622daec97aeb14080a66e4">llvm::HexagonInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a330d9342644a019e77040182050f9b6a">llvm::LanaiInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#afa83048a6e09247f7f6310ffc0681909">llvm::LoongArchInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a3a04d16772e68de8d911d305070f0e0b">llvm::MSP430InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abe4a49e8ceb6213fe44eb0ebc9869eb1">llvm::SIInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a38be8eeeb68d45e0a914cd8f3237ce83">llvm::SparcInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a6d4af3948133ad97770947f7d1242561">llvm::VEInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a541a292af69ae4be75a66b7994e89abb">llvm::XCoreInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab1601d92ffdfcf6fe48b40b6a7cf8d59">loadRegPairFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#accc5aa5171b3bf3b455bbbac12dd405e">llvm::X86InstrInfo::loadStoreTileReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a82f1da052b54c0bd8969fea523e25066">llvm::RISCVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a6cf0eec5c3acd7ff97e6e5dec15a97d6">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesFromI1</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aa90550e5d59f68a547e28c8beeefb3ed">llvm::PPCRegisterInfo::lowerCRBitRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a38572a53736b568d95a5adc23bcd67f0">llvm::PPCRegisterInfo::lowerCRBitSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a7f3c8b41556bad389b00bd408c9b969f">llvm::PPCRegisterInfo::lowerCRRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a49453cd92df6e63d0c2c45e1d5ace04b">llvm::PPCRegisterInfo::lowerCRSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7eb536540d37a55860c52b81778b013e">llvm::FastISel::lowerDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4d0bcb536bd3b6491c535f206275ad89">llvm::PPCRegisterInfo::lowerDynamicAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4b9f5c287ed918ba764f534b79876702">llvm::PPCRegisterInfo::lowerDynamicAreaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ace03d9ed2825d1401093a441f164ecdf">llvm::X86CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a293e39e43b6f68064cdfd37061c84128">llvm::RISCVRegisterInfo::lowerVRELOAD</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a7238a4dd92fc1bb51c004c49c2b22263">llvm::RISCVRegisterInfo::lowerVSPILL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a7809852647bc7e8ceed1f287b2d03125">lowerWaveReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a1ae314e6d4d78cd50108dbe69ad317b0">llvm::Mips16InstrInfo::makeFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a7f0acc0d3658c3a054537b9e4aeb893c">makeM0Inst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a7321f8d9c50eb416611a0309a3fd9742">llvm::AArch64RegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#ac02c01e89c0ac7acc53bb50aeac772ac">llvm::ARMBaseRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ab0c9dd2c74f5a4d226e5f57423aa53b9">llvm::PPCRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a497ba80da227001f952a7d30cfe0552f">llvm::RISCVRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a06c8d8abacb01c870f729e8d2027364f">llvm::SIRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a9fac55ed154a25a20608a5f71dc833c0">llvm::SIInstrInfo::materializeImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a844ba3afb5257d4a9f567d42c54c95cb">llvm::PPCInstrInfo::materializeImmPostRA</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a1eab543e55a7220697eb4e72651e2e17">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeConstOffsetInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a0810cb27406ba2cd135a1a2166b08366">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeNarrowZeroStores</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a006d92e5eae5fd3ca76b72ec1b749a1b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeUpdateInsn</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#afc26610b4c561e17a9ceb497233f34cc">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::modifyCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9511cb46b0b012a8ae67edfbbe7b71a1">llvm::CSKYInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7444176eeeddb4d660fb6a84629abcc4">llvm::LoongArchInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a148f25a7131bb353315edfc43df0c79c">llvm::RISCVInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a1b4c9c49e603e4b80b3d052b54945426">llvm::RISCVInstrInfo::mulImm</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#aa26fba7384acba48becbf2f67547c437">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::optimizeLdStInterleave</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a55d733ab1cd738ca996fd3e415b59c99">llvm::RISCVInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a370295a9498306cec66248f1c1fd8416">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::optimizeVectElement</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#aa0294873aedbdc7244e1ca9aa115889e">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ac6d61a8fec7e62b7b19947fe5820860d">llvm::ARMBaseInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae5781ad71db6e0e3bf84f10c4490e291">llvm::PPCInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afd3a31cde29e70e208055c76fc41bd9a">llvm::SystemZInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ac7c906625fab2baf872e16248962b859">llvm::SGPRSpillBuilder::prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a355a1f30be913f4dc74c51af277fd74a">llvm::PPCRegisterInfo::prepareDynamicAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7bb08436f2b077eb1cd53997a9d9b2b2">llvm::VETargetLowering::prepareMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ab997f379e36469df72be3d7c59f17d2a">llvm::VETargetLowering::prepareSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/copygeneration/#add974c22e80e417ae81566ae9ed683a6">anonymous{HexagonBitSimplify.cpp}::CopyGeneration::processBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#a83cbf55cc29b8e364bc11d81165caaed">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a62a1e2af50ab6132cd2d8d168835ef57">llvm::PPCInstrInfo::promoteInstr32To64ForElimEXTSW</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a664436e80e651ce40c1abcf063d58fa9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::promoteLoadFromStore</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac5b6ac3924041b35531d4e9bf66c3df4">llvm::SIInstrInfo::readlaneVGPRToSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a220e5ab986bbeae53290cfb49f913fed">llvm::X86InstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a20d1f65e3dcb870550c1c8340fc7a286">llvm::X86InstrInfo::replaceBranchWithTailCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcregisterinfo-cpp/#a0c88fcf3221639302fa4045777473205">replaceFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcregisterinfo-cpp/#ac30c350ebdcaa96e93852ea6e7ace1c3">replaceFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae0793a0ace15ba8cf0d9ee31e30dc2c5">llvm::PPCInstrInfo::replaceInstrWithLI</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a49c5e597ebff3776f7a43c3d7f181680">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithBRcc</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a22b62d53bdcd603d84866e9bf8a4fb45">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithCmpBcc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab5fe151eb7f6fa13e78ed30cb5f1ad72">llvm::M68kFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a15d74c0d6159ac707f99c91219d0c6a5">llvm::SystemZELFFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a3d043cad28262fefa366ecc64c9591f1">llvm::SystemZXPLINKFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#aa742ec29cd5bc4d080c170cb881d050b">llvm::Mips16InstrInfo::restoreFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a2d7f004a3c47587d6342bd03a5ec9cb1">RestoreSpillList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab49c96f446ff54d9f4d51653b4542581">llvm::restoreStatusRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a535388ac574e0f8d844662d315997b3d">llvm::X86FrameLowering::restoreWin32EHStackPointers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd46906c25e4d5703a8e422283d03bde">llvm::RevertLoopDec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abaa69285a8e74b69f9d178c1b7a8c1cd">llvm::RevertLoopEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a16ff599a0020f57765f08298aaa0b157">RevertWhileLoopSetup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9061b9ab01f65a05033f729a2f12e91a">llvm::RevertWhileLoopStartLR</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-patchablefunction-cpp-/patchablefunction/#a11d99203cc91bbd49c59f32943541747">anonymous{PatchableFunction.cpp}::PatchableFunction::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a873bcbe8d28d96773cbdf2fd2c9ce07e">anonymous{PPCBranchSelector.cpp}::PPCBSel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#acf62b36239ac36c52ffc9a58a18332ab">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvlandingpadsetup-cpp-/riscvlandingpadsetup/#a76b9ad374c6d52f071aa57de58479f70">anonymous{RISCVLandingPadSetup.cpp}::RISCVLandingPadSetup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmakecompressible-cpp-/riscvmakecompressibleopt/#a76561cc6613d04a06e24640760923da2">anonymous{RISCVMakeCompressible.cpp}::RISCVMakeCompressibleOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#a2f96cc01100e6467c2b124371cf417c0">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupsetcc-cpp-/x86fixupsetccpass/#a88ff40585130ceeb06ea67057cc33b5d">anonymous{X86FixupSetCC.cpp}::X86FixupSetCCPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/cgbr/#ae7e54015b8e4160365d925c1bd46004f">anonymous{X86InstrInfo.cpp}::CGBR::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionrethardening-cpp-/x86loadvalueinjectionrethardeningpass/#a555db007ae6df71fb9fa02662e2c8643">anonymous{X86LoadValueInjectionRetHardening.cpp}::X86LoadValueInjectionRetHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86speculativeloadhardening-cpp-/x86speculativeloadhardeningpass/#a862b3b4b5ed250fcfb2d6f9a130f4a0c">anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9f7b01772fb64eab764bc071e84b860e">llvm::FastISel::selectCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a0f9992c5e3a519e4128db320ba2d2e18">llvm::FastISel::selectStackmap</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5b3180edf81915b106633986034d7a01">llvm::ARMBaseInstrInfo::setExecutionDomain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abc74d2caa2627808c02a43aa418a68f7">setM0ToIndexFromSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a77dc4905d180a52615d00a760b111f9a">llvm::ARMFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a3bbbc37b2cd9470b51560df8c20e66e2">llvm::M68kFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a9db07f97c8d52e506e689b789b231f0c">llvm::SystemZXPLINKFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#af07ce77a4beea41a98862690cee5ec2d">llvm::Thumb1FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#afb4c3921369b6b1fef886bfa979b6d2a">storeRegPairToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a59a4a03c8f10059fe2fed96077fc311c">llvm::Mips16InstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#ac808bf28cfa407acff2b367a0bb383ba">llvm::MipsSEInstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a687fecaf502080080ba5069e6b211a65">llvm::ARCInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8a7868df2562a3b48d08d24c9db87b98">llvm::ARMBaseInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a90829bf41a9e8e4c4e4ad59eab490719">llvm::AVRInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#a41c0bd4e75d4643a8387fe6d56eca337">llvm::BPFInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a647cde93263cdcab73a72f5e459041c6">llvm::CSKYInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a9644f3506784b55b500d2f73f94d79e0">llvm::HexagonInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ae93380d9a76c25ec34ee034e13b3a8fd">llvm::LanaiInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aed611129b85082f7e6459907b50a8cd5">llvm::LoongArchInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#ae215353a37be6d2f533a4858bd96be74">llvm::MSP430InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ec207a1c12adfc61c6566436e5a2cd7">llvm::SIInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#abc124725b4afa4a9d9449c6e2cfb3d73">llvm::SparcInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a2132749e515b00c60255bdb4acfba223">llvm::VEInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a915259afe54d2619524ed03c9c273c57">llvm::XCoreInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a08d97216cdc088a0055e5cd597814ddb">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitADDSSUBS</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a9cdd873b7d4271334f198670b51934f4">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitADDSUB</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a1aeb260a435d4ca4ca00e380df4546c6">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitAND</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a2a2a5cd18017a50ad5e469ac95a910f3">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitCSEL</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a34005879daabad613a9f682bc30c0fb1">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSERT</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa4f08d12a02cc1685e8ea788f818ac1a">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSviGPR</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a763775ab82c6fd6290a1f15b1f36c4cf">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitUBFMXri</a>.</p>

</div>
</div>

### addIntrinsicID() {#a7ac6e2ee4b04561d22ba0bdc2d32897f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addIntrinsicID (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID)</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af7cf8fdf7e933b17b3fdf1d49b67e195">llvm::MachineOperand::CreateIntrinsicID</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-spirvprelegalizercombiner-cpp-/#a99fb6c2c4ea3a52f8977eeb8d2c2f425">anonymous{SPIRVPreLegalizerCombiner.cpp}::applySPIRVDistance</a>.</p>

</div>
</div>

### addJumpTableIndex() {#aaa7ad3e87d858a3ed3b3dc8b05b70078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addJumpTableIndex (unsigned Idx, unsigned TargetFlags=0)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab3700e1a41d8d584dc6e1720b803b2f6">llvm::MachineOperand::CreateJTI</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="#a9189968ba471dec34e7806413bd019cd">addDisp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aaf1013659ccc9708197f76c0bd724936">llvm::MachineIRBuilder::buildBrJT</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>.</p>

</div>
</div>

### addMBB() {#abf1febf2a98f588146548a3a485d3838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, unsigned TargetFlags=0)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af38d24646cd711efc334aee49919cdf5">llvm::MachineOperand::CreateMBB</a>, <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#ac2fc7f2c8237332f8b99c6e88af1b678">addIncomingValuesToPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a9f9292339308898a6ebf6021c35d3034">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::AddPHIOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a844dfba8ffcebffad1f2f43287740c96">llvm::AVRInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a5fbf08fc2002106c8e39caa9c2c84cd8">llvm::M68kInstrInfo::AnalyzeBranchImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0ae44597e21d583e46c8bdfa52e56fa3">llvm::MachineIRBuilder::buildBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a8d1d93bb20bf72c7782cf68446e5bf9f">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::CreateFailCheckSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae5fdb7e682e1d04dab7282c473a3641b">llvm::PeelingModuloScheduleExpander::CreateLCSSAExitingBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ac438bed7ae6afbb9ff9e0be02099ad0f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a22444fb95050a5bef1c689e5bc9b064e">createPHIsForCMOVsInSinkBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3c4c42f79d79638f6b67532d3f81df58">createPHIsForSelects</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loongarchexpandatomicpseudoinsts-cpp-/#a64e613bd4dc479933ae0ec4c701ef699">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::doAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#a849e02093ed0423e32e7a0bb24def54b">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::doAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loongarchexpandatomicpseudoinsts-cpp-/#a47c1617a975f5b87a9c3c3cb9e3de32e">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::doMaskedAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#aec87b1447d0efa73d10bb35550a9a7cd">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::doMaskedAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab6a60676cdf39d45ae2ec66a7ea4aada">llvm::AArch64TargetLowering::EmitF128CSEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a82e453c9e7f441c185009164f0136fa8">llvm::SITargetLowering::emitGWSMemViolTestLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a336444d567b931e2ced0dd4f844148ab">llvm::AVRTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a476adf24d3374520fb31b2785f331d58">emitLoadScalarOpsFromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13a9214d6e92afcb3e956a5891522bed">emitXBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8997d907b1de0e1b433c59102335b06a">llvm::AArch64InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a222d82bcc0b1cb30a36ed1bf3bbeac63">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3e3daf4218b791b2796b808627b7f864">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a451ac66d74cbee6582c570a71254ae26">genTPEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd62dcc07699f0f98ae897208c1529ae">genTPLoopBody</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab8903896a25679d038ebd3e8769233f6">llvm::AArch64InstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a0ef7652ff781ab8a179fa049c170351d">llvm::ARCInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa2351273089a9b61efc8258cc7778093">llvm::ARMBaseInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a75bcfbf5fa68f5673c7898237251f065">llvm::AVRInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#a023248ea245a9ca71aca7f8575cf63a6">llvm::BPFInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a2c95253334e2a487e24d6b1d561395b5">llvm::CSKYInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a76f8dfae3796fd187aebe3f8f60643ec">llvm::HexagonInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a150e7cedb8221a184efe28d747fd3382">llvm::LanaiInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a75708a12cbe3a8f421f759cbb0f070b7">llvm::LoongArchInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a4056479b94115f8015762f8a51c6c16c">llvm::M68kInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a69844bca212f09027ea41fa010fafe10">llvm::MipsInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a4c21224e6322bedc01805410f79a6699">llvm::MSP430InstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstrinfo/#a2c07b28605263dabce813e1b41b1907e">llvm::NVPTXInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ac73a2a13806418aeb40c26ea794c3dd7">llvm::PPCInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a648e69f41d62376b996b0b5209022fbd">llvm::R600InstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a2bc4c29964a242a574a8e9b78df0bb31">llvm::RISCVInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad73e9b3e610bd8cac60e740a61fcf5bf">llvm::SIInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#afbb00c84e6a7ad45d3b6b3839ee51e6c">llvm::SparcInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinstrinfo/#af7d4484ec824ca52d0363a66479278bc">llvm::SPIRVInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a1974be33e69e1cda7a0d2e6da445c12d">llvm::SystemZInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a8b7067629b6a083fe938e1e73d0b505b">llvm::VEInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a9568834e4871e98bac63dda4a5d546c8">llvm::WebAssemblyInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ab1f5181c16c1e183fdccc4f4552ba887">llvm::X86InstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#ab90baf87e2ab1c07dc084dd9e6293323">llvm::XCoreInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a897a84cae1d80922e012bf7c700c1e78">llvm::XtensaInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a9fe5f8d86815ba379552a73645b0f430">llvm::XtensaInstrInfo::insertBranchAtInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a75f3e392bd9cff57dcd444d521d7fd94">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a65dd43006ce58e3e599b020487f94df8">llvm::AVRInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a8e7acd0466662074bd2486d1964cd173">insertPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7dbf2885fa89980322c2f4b58f85ff18">llvm::SIInstrInfo::insertSimulatedTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aff7dfc9d1d4355acbd741d76ce27fca1">llvm::AMDGPULegalizerInfo::legalizeTrapEndpgm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a7809852647bc7e8ceed1f287b2d03125">lowerWaveReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aeaeffb171ae383d18f217fbd278c8717">llvm::RISCVInstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae5781ad71db6e0e3bf84f10c4490e291">llvm::PPCInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7bb08436f2b077eb1cd53997a9d9b2b2">llvm::VETargetLowering::prepareMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a49c5e597ebff3776f7a43c3d7f181680">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithBRcc</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a22b62d53bdcd603d84866e9bf8a4fb45">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithCmpBcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9061b9ab01f65a05033f729a2f12e91a">llvm::RevertWhileLoopStartLR</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a873bcbe8d28d96773cbdf2fd2c9ce07e">anonymous{PPCBranchSelector.cpp}::PPCBSel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#a2f96cc01100e6467c2b124371cf417c0">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a72a62fe526ad0cd3c24cfe003d363df0">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae708a0dc9c80038ba6d971c94eb9db5c">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a747abf73a79323919b62fb98e61aeaf2">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>.</p>

</div>
</div>

### addMemOperand() {#ae565d45627e1678a3e37bd6a016c561c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addMemOperand (<a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afc4107c92fd8d37e8d0cb596f2a25d98">llvm::MachineInstr::addMemOperand</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensainstrinfo-cpp/#afb2753bad8eb2a132f72925416a0ac4c">addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24df964fef5537043b85294a38037ca1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb2d11e8b17ef23a86d57b4105fba8e1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a67931ef18efe0f1710e3f2e39ddfb8f6">llvm::M68k::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#a40fe21a4879ff8f132c4fb676738c5b1">llvm::M68k::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae57ad469173d1ad36cb91dde447623ce">llvm::MachineIRBuilder::buildMemTransferInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaf673a1e44074d7088008437112159fa">emitSplitF64Pseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a83de3f9ab24662688a50952de742a4dd">llvm::ARMBaseInstrInfo::expandLoadStackGuardBase</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8997d907b1de0e1b433c59102335b06a">llvm::AArch64InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9fa574f4bc0ad6d1cd8335fdf7aba857">llvm::CSKYInstrInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a1b25635def2844fb5e6c8a79f3af0a6c">InsertFPConstInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a9189604a4845165a94dd42f19b31e7b4">InsertFPImmInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#ae88297df93601a3a0929300e6a6b58d7">InsertSPConstInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a830c556c1d7adec01904fdfe8cd50949">InsertSPImmInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#aa31003f66af0241b32a8572e8b33d7c4">llvm::Mips16InstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#abf65c6f3a770509d24a75efbbe785a67">llvm::MipsSEInstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ad96e959009cbe91d2814bcdfe4fcd51c">llvm::ARCInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#aa3221ba2a1b01836c1f02c48d2bd2c4e">llvm::AVRInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a2c4630e6b74de7b52933845fe4f48f01">llvm::CSKYInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad3b3220844622daec97aeb14080a66e4">llvm::HexagonInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#afa83048a6e09247f7f6310ffc0681909">llvm::LoongArchInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a3a04d16772e68de8d911d305070f0e0b">llvm::MSP430InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abe4a49e8ceb6213fe44eb0ebc9869eb1">llvm::SIInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a38be8eeeb68d45e0a914cd8f3237ce83">llvm::SparcInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a6d4af3948133ad97770947f7d1242561">llvm::VEInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a541a292af69ae4be75a66b7994e89abb">llvm::XCoreInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab1601d92ffdfcf6fe48b40b6a7cf8d59">loadRegPairFromStackSlot</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a293e39e43b6f68064cdfd37061c84128">llvm::RISCVRegisterInfo::lowerVRELOAD</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a7238a4dd92fc1bb51c004c49c2b22263">llvm::RISCVRegisterInfo::lowerVSPILL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcregisterinfo-cpp/#ac30c350ebdcaa96e93852ea6e7ace1c3">replaceFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a2d7f004a3c47587d6342bd03a5ec9cb1">RestoreSpillList</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#afb4c3921369b6b1fef886bfa979b6d2a">storeRegPairToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a59a4a03c8f10059fe2fed96077fc311c">llvm::Mips16InstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#ac808bf28cfa407acff2b367a0bb383ba">llvm::MipsSEInstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a687fecaf502080080ba5069e6b211a65">llvm::ARCInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8a7868df2562a3b48d08d24c9db87b98">llvm::ARMBaseInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a90829bf41a9e8e4c4e4ad59eab490719">llvm::AVRInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a647cde93263cdcab73a72f5e459041c6">llvm::CSKYInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a9644f3506784b55b500d2f73f94d79e0">llvm::HexagonInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aed611129b85082f7e6459907b50a8cd5">llvm::LoongArchInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#ae215353a37be6d2f533a4858bd96be74">llvm::MSP430InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ec207a1c12adfc61c6566436e5a2cd7">llvm::SIInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#abc124725b4afa4a9d9449c6e2cfb3d73">llvm::SparcInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a2132749e515b00c60255bdb4acfba223">llvm::VEInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a915259afe54d2619524ed03c9c273c57">llvm::XCoreInstrInfo::storeRegToStackSlot</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a9922ec95e157a3432c8ccd4a8a6a2653">llvm::AArch64GISelUtils::tryEmitBZero</a>.</p>

</div>
</div>

### addMetadata() {#a7f54f5772ba80cc1f7c4a92203f14e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MD)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a903091abda5acf43af8ade829181b9b4">llvm::MachineOperand::CreateMetadata</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aff0ca26ef3d127a6fdf638cdf937f730">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac97a9a17e6fb3e143741bb48451a0959">llvm::buildDbgValueForSpill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfe6e5ec3e8d8ad4632758a0af06b8f9">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2daca542c8dc98439d2a5a86196e0fc8">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a3ec97d2a9d814aa73cc7ede2fd0d617f">llvm::InstrEmitter::EmitDbgLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a71936ccaaca62faa835ddf1887cb2626">llvm::InstrEmitter::EmitDbgValueList</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a52bb01c018d9c9a9bda3d127ab5c7189">llvm::FastISel::handleDbgInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7eb536540d37a55860c52b81778b013e">llvm::FastISel::lowerDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a9f7b01772fb64eab764bc071e84b860e">llvm::FastISel::selectCall</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a58217c3769fe3ee4ac0d221b836849f0">llvm::FastISel::selectIntrinsicCall</a>.</p>

</div>
</div>

### addPredicate() {#a6d40d83c14042582354b5d875ed7f2d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a985d3c6d580d9dad7efe3129606150ae">llvm::MachineOperand::CreatePredicate</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a>.</p>

</div>
</div>

### addReg() {#a927857fc69e4b4f0cde307f86f180df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo, unsigned flags=0, unsigned SubReg=0)</td>
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

<p>Add a new virtual register operand.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a2fee1a7db4e84247a193a9af1f907013">llvm::RegState::Dead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a14af644ca4aff07a3768974c824ac9d5">llvm::RegState::Debug</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5acf55f329675ba5045a4863c7a018209b">llvm::RegState::EarlyClobber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a7fcf0a8c65265b4519b79fa537bbd8a0">llvm::RegState::InternalRead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a4c5b26e761294db59c1ad1cc6fc1d0ba">llvm::RegState::Renamable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5ab502f975742e9bff6d6dd7b49439b806">llvm::RegState::Undef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7525b6ff9464d7873516ad91ec061c23">llvm::addConstantPoolReference</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ade27a165903cbaaf156adfd59a7c684b">llvm::InstrEmitter::AddDbgValueLocationOps</a>, <a href="#af584d2eb0342e655d6ec597c0f7958db">addDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff98f30548a2233baed77a73408842a2">llvm::addDirectMem</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a396ce0a5b70320d155c9959a080d543f">llvm::ARMBaseInstrInfo::AddDReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7b24fcad0f9310a088627066269508e2">addExclusiveRegPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24df964fef5537043b85294a38037ca1">llvm::addFrameReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41229d95ec1712486d97ae6c27a0ba8a">llvm::addFullAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#ac2fc7f2c8237332f8b99c6e88af1b678">addIncomingValuesToPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a9bd7c04e374ad15665430a243dd30d80">llvm::MachineBasicBlock::addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a52716532c3562bbe9c3fc343761c3c8a">llvm::SITargetLowering::AddMemOpInit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748a1633a6bba78f4ecb55256c937bde">llvm::addOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f23de662df5c947a914f6ac433f3344">llvm::addOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#afd41e1bf7be73c5e667a9f0a1f4a6c15">addOperandsForVFMK</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a9f9292339308898a6ebf6021c35d3034">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::AddPHIOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1aa408e30d1bdfe5eccc8979992ffefd">llvm::addPredicatedMveVpredNOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9319edf6358dba177eeb1356563ae053">llvm::addPredicatedMveVpredROp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ad283cfc77268d18405882cb6588c337f">llvm::M68k::addRegIndirectWithDisp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a752b9dfb94f917a9e494fc4ed8cb6208">llvm::addRegOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d45e5dba16959552ccd6e0e3615e84e">llvm::addRegReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#ad0da681a52b5ef146c8a106fe63ded93">addSavedGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16instrinfo-cpp/#a8307fba45b5b2a7e89011a2a789a9a31">addSaveRestoreRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#af1721986b99fa84250a8b09468058f21">llvm::M68kInstrInfo::AddSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a33b1d3e5b49c049ed08f90d38070a751">AddSubReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7bc392573220746bf1ef1f95fa98b46">llvm::addUnpredicatedMveVpredNOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa19514ee903587d4cfaee302cf7ce4d">llvm::addUnpredicatedMveVpredROp</a>, <a href="#ad88e27102395957e457fed8e73a085cf">addUse</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#abada5e68ca1f455ee3b38dda17180c6f">llvm::M68kInstrInfo::AddZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#aa4909014e5875c7b2d1cd6fdd7ab7e89">llvm::RISCVRegisterInfo::adjustReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#a5029a9a110d5000ca84dfcd7e972e393">llvm::MipsSEInstrInfo::adjustStackPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a932b9562347f2f18d278c611c83268b5">llvm::XtensaInstrInfo::adjustStackPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a83aa1663ebe23169979a76be989b1144">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::adjustTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af4262eaffe5f263e48ab59372d7c8acb">attachMEMCPYScratchRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad8756402b6bd331b493dc7c0b3efd984">llvm::X86InstrInfo::breakPartialRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad9c4463170797dc633ce8dfa192f132b">llvm::X86InstrInfo::buildClearRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a030150151483c64bff02ae4f89a50c96">llvm::R600InstrInfo::buildDefaultInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76a671b685940387f88a924858a371d4">llvm::SIInstrInfo::buildExtractSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a2d1eb7b0207905141f6ddb1f228f3696">buildGitPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#aa667006252ada935940ba209eef256e3">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac98e182e817bb53f2ff8135d29637dfb">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a859007fbe974ffb4c1793877e4ada681">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfe6e5ec3e8d8ad4632758a0af06b8f9">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2daca542c8dc98439d2a5a86196e0fc8">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05cdb3fd84788ee9af0824bf14f280e7">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a7bc05bcba45ed1e4e903c1c952d09178">buildRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a57982dfc711f20ecf31431bc37259cd7">llvm::SIRegisterInfo::buildSpillLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a4db3746fd517a6ce4e428b4ead57cb3d">CMSEPopCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#ada53f9e75a087c02dcea98064c69900b">CMSEPushCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxpeephole-cpp/#ae48b9308a21e92c2301831dfc8d75ac9">CombineCVTAToLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a3ea2369e6bcfa35889cf566047e3ca3f">llvm::PPCInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#abb968323ca61fa5d8e99b4523a08f2b2">llvm::FastISel::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv/#a8c2c7a46bf3359100068e45134218920">anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a73f427af3525340f74d7e85b984b82d6">convertCalleeSaveRestoreToSPPrePostIncDec</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/instrreplacerdstcopy/#a3a3c75969a49f4cec641a3af56b4bc37">anonymous{X86DomainReassignment.cpp}::InstrReplacerDstCOPY::convertInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstpreserveoperand/#a9899e618878cac6bb75eafe4d46810f4">anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::convertToSDWA</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a414af156e6dae8024f5321babf41afb2">llvm::SystemZInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a3b6290d83ecf58d4693ea6442be7b23e">llvm::ARMBaseInstrInfo::copyFromCPSR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#acd4e3782462bd215bc07bd1f9b2b01b5">llvm::AArch64InstrInfo::copyGPRRegTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ade00a4708e793e75a00a3030325cbf84">llvm::AArch64InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a741b52aa71d8a88aed13b09b7b6183cb">llvm::ARCInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abef9f720617461778f1a2e49d17ea159">llvm::ARMBaseInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a5bde594eff371b34c5f5bf6222b690f6">llvm::AVRInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#ac0442b8f7343b837eae4c4a0db532cf8">llvm::BPFInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#ae8be35955783557ba6a8d97bcf8353e7">llvm::CSKYInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ac6fc9913b21716cfbd41b6616e8aef4d">llvm::HexagonInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a75c1ba5e07585f5eafbd2a56ba489b5e">llvm::LanaiInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a759a3354d37a7d694ba126ace98547f0">llvm::LoongArchInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a782862328ea598dcc50374eb9086d36b">llvm::M68kInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a851cd4eaa854ab481ba59f5eb9163b8f">llvm::Mips16InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#a28dc5e4998fe0b9c82c9a30f9c20ca08">llvm::MipsSEInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#aa33d04c71419c4cd5825c3cedeee8f4c">llvm::MSP430InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstrinfo/#a888ba228326c2da459a9d81943ec4537">llvm::NVPTXInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a3e0a4dad177be52a38a07e782fc9207f">llvm::PPCInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ae780082016f8641ba5a18009b135d01e">llvm::R600InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5e29efc37d9738b891d35308524d7d5b">llvm::RISCVInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a519410003771768aef013bd57efa6cf4">llvm::SIInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a9cb1dd3dd16025fc64f52adb12c9ce5f">llvm::SparcInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afbb3d2344086d40fa845201e37538d85">llvm::SystemZInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a4d30d32e32d7be938a8b0a0f4dd21418">llvm::Thumb2InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad8b8d94aaf80cefc49bc3263f05cd741">llvm::VEInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a9eb8b24be429abb7d52e2f41f9923e08">llvm::WebAssemblyInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a79b6327f4d0680e2eb8f28cbe3a2abb9">llvm::X86InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#aba4687efa0edb8b976493fdea89e719c">llvm::XCoreInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a6e1e2c2b2879a6a6c0645e538c989331">llvm::XtensaInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#a669f90d5fe703ecfe25fb738553f6ea5">copyPhysSubRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a654fa7da7f95a667f9663b3d6a130293">llvm::ARMBaseInstrInfo::copyToCPSR</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a8d1d93bb20bf72c7782cf68446e5bf9f">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::CreateFailCheckSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae5fdb7e682e1d04dab7282c473a3641b">llvm::PeelingModuloScheduleExpander::CreateLCSSAExitingBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a1b8a0415e101fcd1f76e5f8ee95172ee">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::createNewWaitcnt</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aea3489e1fa192776df90b3f6b8e66511">llvm::SIInstrInfo::createPHIDestinationCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a804530332064e8450f5c01c1291e3ec8">llvm::TargetInstrInfo::createPHIDestinationCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a22444fb95050a5bef1c689e5bc9b064e">createPHIsForCMOVsInSinkBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3c4c42f79d79638f6b67532d3f81df58">createPHIsForSelects</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a454f04c1cce23ff2b87305df8909ab33">llvm::SIInstrInfo::createPHISourceCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aaf9cd5e2258e984d377933b695ccf39b">llvm::TargetInstrInfo::createPHISourceCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a7bec9e5fa4cafeca001d506741b38f0f">createPostIncLoadStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instrinfo-cpp-/aarch64pipelinerloopinfo/#a3225760dca7855181b535133948ea278">anonymous{AArch64InstrInfo.cpp}::AArch64PipelinerLoopInfo::createRemainingIterationsGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-armbaseinstrinfo-cpp-/armpipelinerloopinfo/#a2afe54a3f381a7c3f67db172f886d734">anonymous{ARMBaseInstrInfo.cpp}::ARMPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a08073cedfc0efeff220a6af9b84d2cb6">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loongarchexpandatomicpseudoinsts-cpp-/#a64e613bd4dc479933ae0ec4c701ef699">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::doAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#a849e02093ed0423e32e7a0bb24def54b">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::doAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loongarchexpandatomicpseudoinsts-cpp-/#a47c1617a975f5b87a9c3c3cb9e3de32e">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::doMaskedAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#aec87b1447d0efa73d10bb35550a9a7cd">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::doMaskedAtomicBinOpExpansion</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a430f53d8e433993ae806a386a4870efc">llvm::AVRFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ab30ade3265bd079731057aafc0ff6e9f">llvm::MSP430FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a63c498f1fcb62301a44ad58e2dc8e7fc">llvm::PPCFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#afb457df257778163977aebad1d1165e8">llvm::SIFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a5846a629f1d7d7cc33ecf2a63319e14a">llvm::AVRRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/bpfregisterinfo/#a849e9ef6e1cc9fdb4a18b27bf6eadef7">llvm::BPFRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyregisterinfo/#ac8db545cfaf863844d25944e00814ba1">llvm::CSKYRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/lanairegisterinfo/#acd4d1d9eb28b9bca2ca401487bdf529e">llvm::LanaiRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/loongarchregisterinfo/#a14277e449886ad06b196b805fad006ec">llvm::LoongArchRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430registerinfo/#a1ae0b9564ca66a61628084c4bb858ea8">llvm::MSP430RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a91da910cd583aea849621cbf8147fe28">llvm::PPCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/sparcregisterinfo/#a5e8cc743ac1b84dd6f00bcee3c9e125d">llvm::SparcRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a1e101bcf68a4448908d194d220029861">llvm::SystemZRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaregisterinfo/#a6411a92c3a3ac8af31ab80b05b0b24fe">llvm::XtensaRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a2d8b50ff5c8dad758eb8d36c4d98bcaf">emitAlignedDPRCS2Restores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a3046f0367b644d6feafcc16f8da39967">emitAlignedDPRCS2Spills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a0bd30ba570d7cadf1358f8054ffe4af3">emitAligningInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab812d774aa563ffc2c67030a9ba1be39">llvm::AArch64TargetLowering::EmitAllocateSMESaveBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab9a65a8c0739a72de196022849b4ee67">llvm::AArch64TargetLowering::EmitAllocateZABuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae917ff404aade469cb9d3780515660ad">llvm::emitARMRegPlusImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ad04238a3223242e0565e4f98df0461a6">llvm::SIFrameLowering::emitCSRSpillRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a84c4c1518f3593f9c1d0b10f8364ebb8">llvm::SIFrameLowering::emitCSRSpillStores</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#ae0fecac8378f609fa3740fe1fd51465e">llvm::InstrEmitter::EmitDbgValueFromSingleOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a056f22c11083630d8bcc82299cb783af">llvm::PPCTargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a43f6667038342a819037b705ab34277a">llvm::SystemZTargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a5973091849912847746aa5b158772e8b">llvm::VETargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aac8f5d5c66c21056b3144508e8142639">llvm::ARCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a51c3d43bee1dec655ecaec65afc94c82">llvm::ARMFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a487d00503c99000990bb90458b08702c">llvm::AVRFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a60f61ed13ff961051650fac4c6fa4ec0">llvm::CSKYFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#a188a6b8252a69aa600405ee5308b96ff">llvm::LanaiFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a27812f7473acb8b3398abc5a297ea082">llvm::M68kFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#a21570eb2eb8c108f04a8cd089489d34f">llvm::Mips16FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#aeb6b320000ce736d5ac68e606fcc3519">llvm::MipsSEFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a3a9df23d95cdadc6a77b12dc3377a331">llvm::MSP430FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ace1de8acc8ac15962f04832273df87b1">llvm::SIFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#a675f8b6bd946c7c1a04bee42ff2a0598">llvm::SparcFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a6289c3b215e791396217e90177ad28a5">llvm::Thumb1FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#ab1be113dfec8a96458235eea8ac0797f">llvm::VEFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#adbe9a36b5d064d3fe4667e4c1b47af85">llvm::WebAssemblyFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a756acce5a5adef291dc50593ce6d56a4">llvm::XCoreFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a0461f7f7e4e1f408963beca04c51c6d4">llvm::XtensaFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a0ae07475a5705c0ed37023fc64008c7b">llvm::VEFrameLowering::emitEpilogueInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab6a60676cdf39d45ae2ec66a7ea4aada">llvm::AArch64TargetLowering::EmitF128CSEL</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa92b03a9781f6914ffdef83ecf323708">llvm::AArch64TargetLowering::EmitFill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acfee0aff6a62996ec1dbee56ef35ad88">llvm::AArch64TargetLowering::EmitGetSMESaveSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#adfd69c79b4eb159ce76cbc8cf5b06073">emitGPDisp</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a82e453c9e7f441c185009164f0136fa8">llvm::SITargetLowering::emitGWSMemViolTestLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a1041b4042ad87c8a306b5e0edc9fced4">emitIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ab69231adafff5e2e89dfae5a21ba246b">emitIndirectDst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a071d8b84e530f1a6e725aea09fdc6407">emitIndirectSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a2ed887f0677d391bc6f9d7e77b761695">llvm::AArch64TargetLowering::EmitInitTPIDR2Object</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a336444d567b931e2ced0dd4f844148ab">llvm::AVRTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae6e03361f09a5b06dc299f6ee1c76ca4">llvm::AArch64TargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#acd40e68d03e3f43b4f7563d083d0e2ee">llvm::RISCVTargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a89a6b95d310330e345c3aee6a07ffd96">llvm::X86TargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a44ddc08d3e0ee02a2a8fb36fb4c8ac18">llvm::MachineRegisterInfo::EmitLiveInCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a36db540eb7d0490cab86e4cf12ac9116">emitLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e4563cae7f10b41cdff9a61f1f6aaab">llvm::ARMBaseRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a476adf24d3374520fb31b2785f331d58">emitLoadScalarOpsFromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#aff663b5af9761f53e2f0d42ce09c408f">emitPACSymOffsetIntoX16</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abe4e954d4fb2e34a8edd0c54c9682606">emitPostLd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa331364e481586cffcf94e6dca45df86">emitPostSt</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#a1cc86e82857e8ff7bceddf8838830577">llvm::LanaiFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a921a457b786497c2309b9f63abd9c951">llvm::MSP430FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#aad707aff5fcbdc8180deb9e6695f0c32">llvm::NVPTXFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a58cebd1e96489b04d18f2a7c39c250f8">llvm::SystemZXPLINKFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#ab3c8272ea0652d9ab75b889488f2717f">llvm::VEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac78e4ff0f9a757b578b967d5bd1f70ee">llvm::WebAssemblyFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#abfcb7ab0b2bd202bc7e048d531897a3a">emitPrologueEpilogueSPUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a59e84300cf3bfbf40a89fdeaf965097f">llvm::VEFrameLowering::emitPrologueInsns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a94be4f19deb3ce06a8fcde89fb4b639b">emitPseudoCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a9de3850aa5bea6fb60e5c61162bf22e9">emitPseudoXVINSGR2VR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a055df59820235c32c403d7c78de5494b">emitQuietFCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcframelowering-cpp/#a23d4062f31c06d23731cccff25e7eb44">emitRegUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a02cddefc96e08fba507c3d0eac7f6c1f">emitShadowCallStackEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ae5f813adf7cab5ad0f7a542b681ca95c">emitShadowCallStackPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a2e28f3159a4ec003bae892a828ae295b">llvm::M68kFrameLowering::emitSPUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aa8a605a58ebdee20705834400bdbb922">llvm::X86FrameLowering::emitSPUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a97c69ea577c9578ecadf9469189438d0">emitStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaee29fd8c447694396529bd6a468a6f">llvm::emitT2RegPlusImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a55668c464aef1136badb1b58eeec19c6">emitThumb1LoadConstPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a8a9cca3d1c6515fbf780f033644ace85">emitThumb2LoadConstPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaeed6b0c7995c9000819c8bed932e551">llvm::emitThumbRegPlusImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a4c17381dc1cacb65f1dd6d31d15100e0">emitThumbRegPlusImmInReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a34c1693d3ce9979ba45e1e9425cc806e">llvm::AArch64TargetLowering::EmitTileLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab0a615cb68b545ea3a9c88243a0ab4d9">emitVFROUND_NOEXCEPT_MASK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13a9214d6e92afcb3e956a5891522bed">emitXBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a20e848fbe4dcba24cc443837166728a8">llvm::AArch64TargetLowering::EmitZAInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa695d49f883b21889c91b61d86437995">llvm::AArch64TargetLowering::EmitZTInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ae0196eca3002f5fd8c339ea859ddd12f">llvm::SIInstrInfo::enforceOperandRCAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a47d4233d9f4a5998d0b67ebd1414dc76">Expand2AddrKreg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-cpp/#afee96ecb8e8588a068aa3c1743b63352">Expand2AddrUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#afee96ecb8e8588a068aa3c1743b63352">Expand2AddrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#aec1517c8d806609cb368f431ddab1bc7">llvm::VEInstrInfo::expandGetStackTopPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a83de3f9ab24662688a50952de742a4dd">llvm::ARMBaseInstrInfo::expandLoadStackGuardBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1e962b46ba9784205ea3eba9c0b10ded">expandMOV32r1</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad8e9b54f022eddc33ee49305e85d6b7f">llvm::SIInstrInfo::expandMovDPP64</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a0ea5ffee956540dce97bf5d067051c6b">llvm::M68kInstrInfo::ExpandMOVSZX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8997d907b1de0e1b433c59102335b06a">llvm::AArch64InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abe2c3303ec55393902e579d316051289">llvm::ARMBaseInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a7941fd2c7d339dfe155c4327fd95fab0">llvm::PPCInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#afdfbfb84a63a295205139121a3a02685">llvm::SparcInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a404db50d68f1ca8d28396b5e2deb061d">llvm::VEInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#ab4228d105bd5b126170c562e6f8acdfd">llvm::M68kInstrInfo::ExpandPUSH_POP</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a0cf3c7ba2564fa10526e70ecd607db74">expandSGPRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6203308c1da11d69cb3bd6c23b90b207">expandSHXDROT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ab8ebdf9a381ab517c0225f7f0719cf45">expandSpillPPRToZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a99607ebccc8847200c641528a876b420">llvm::HexagonInstrInfo::expandVGatherPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ab69e2cd15cb4ac3f0262a15fdd65befa">expandXorFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2586ad27c00166b367fe4d171be2bfaf">extractRsrcPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a03ab338e9e5f4ea24b2049ab525525bf">llvm::FastISel::fastEmitInst_extractsubreg</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aba7be31f2606d1565335458953610fcd">llvm::FastISel::fastEmitInst_f</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a738eff0daa8e9f33ff056da16adefb4d">llvm::FastISel::fastEmitInst_i</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a43873dfd861406dc9da68ddcd2bfe1bc">llvm::FastISel::fastEmitInst_r</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aef1cb331526de21d6b1729a42a72d74f">llvm::FastISel::fastEmitInst_ri</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a91124ff314dcb25457d0a4bd31fa5c52">llvm::FastISel::fastEmitInst_rii</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a8d85017ca59fd0d13bde23551dfc5f90">llvm::FastISel::fastEmitInst_rr</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ae348a9f69bb94b326d0e722c74dfaf7b">llvm::FastISel::fastEmitInst_rri</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#afe20d43bd5edcb69d1a401105ad3d38e">llvm::FastISel::fastEmitInst_rrr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a70544884c11636f144c5b3fa4bb939d8">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a3d9eb53bc6802953e1a03c1acc8feb7b">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#a246d108e7d516b651024d7ab2a75e9be">anonymous{X86FastISel.cpp}::X86FastISel::fastSelectInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kcollapsemovempass-cpp-/m68kcollapsemovem/#a6f7b069c3605517327ae9c48af7c9781">anonymous{M68kCollapseMOVEMPass.cpp}::M68kCollapseMOVEM::Finish</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyfixbrtabledefaults-cpp-/#ab7b6f5214428c621e8b32582fd5efe62">anonymous{WebAssemblyFixBrTableDefaults.cpp}::fixBrTableIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#acc3031d4170d4a972043c6dfa34508c2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::fixSCCCopies</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a222d82bcc0b1cb30a36ed1bf3bbeac63">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3e3daf4218b791b2796b808627b7f864">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#acced35ebfd644d56dc0bcc060bb1bd8d">llvm::SystemZInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ad41786bff2f31140c40979fdd64b6769">forceReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silatebranchlowering-cpp/#a2fa9fe1bc3c4ca4168ea98c54c5090e2">generateEndPgm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcframelowering-cpp/#a26b9bb9c6af7500bfeac678ddf1bf601">generateStackAdjustment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#af64fc386f3fc81f753830641399254b9">genFNegatedMAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad7dacfdd99d94fce20ccc2450bf5eb76">genFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6893512d8a2c2aaf9d6758440d1bc583">genMaddR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a012040151268735433380829e4ef0dcd">genSubAdd2SubSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a451ac66d74cbee6582c570a71254ae26">genTPEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd62dcc07699f0f98ae897208c1529ae">genTPLoopBody</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a15fe0ce54453ae7355ee50ef1beb52a0">llvm::SIInstrInfo::getAddNoCarry</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aed0535a6ce0e4e5969a60a1635d0b18a">llvm::SIInstrInfo::getAddNoCarry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02134e88cd18139c71d9274c7d287ac3">llvm::getFunctionLiveInPhysReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#ac20ef8c91eac038ee0e6bcc32be560f5">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9fa574f4bc0ad6d1cd8335fdf7aba857">llvm::CSKYInstrInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a138bc82a9943aa3008ab86bec2d2c91a">getOrCreateFrameHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsfunctioninfo/#ace182ca668404b3d23cae8329d941ba4">llvm::MipsFunctionInfo::initGlobalBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvextract-cpp/#a88486e318adbd7333b898816348c8e7c">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertreadwritecsr-cpp/#a93ca2859094e3f43227290d2f88472c9">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a76f8dfae3796fd187aebe3f8f60643ec">llvm::HexagonInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a648e69f41d62376b996b0b5209022fbd">llvm::R600InstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#afbb00c84e6a7ad45d3b6b3839ee51e6c">llvm::SparcInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#ab90baf87e2ab1c07dc084dd9e6293323">llvm::XCoreInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a9fe5f8d86815ba379552a73645b0f430">llvm::XtensaInstrInfo::insertBranchAtInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa859694dc733dcc4def80843314a9666">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::insertCondBranchBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a7d4bb69b0d32d7faede599d671289c15">llvm::XtensaInstrInfo::insertConstBranchAtInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a23393317cdaeed97903d191dcc6c84f8">llvm::AArch64TargetLowering::insertCopiesSplitCSR</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1dfc6019f3ac9b3b50bfc020a60baf7c">llvm::SITargetLowering::insertCopiesSplitCSR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a4e158f6bc607637bde46f2974a2ecf88">insertCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a04bc45ddbc56deb8b54dacaeea86df8f">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a61e27cf21f938d341d13395bb4e17493">insertCSRSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a8c0efd377a713687b369602245dbe9da">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a75f3e392bd9cff57dcd444d521d7fd94">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad94f2f559486e50040a794798454f67f">llvm::SIInstrInfo::insertEQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a1b25635def2844fb5e6c8a79f3af0a6c">InsertFPConstInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a9189604a4845165a94dd42f19b31e7b4">InsertFPImmInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#aa0cefa4c61cc43ff6fd225bc7b4f917e">InsertLDR_STR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loongarchexpandatomicpseudoinsts-cpp-/#a5f9260ad1fc7fcfb12e282eb5fc48610">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::insertMaskedMerge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#a6cf50014c695d818e35f9bc8a03e3723">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::insertMaskedMerge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad64501a368789645f6f80afbce82da90">llvm::insertMultibyteShift</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#acae141c2c150567424d8cc080976608e">llvm::SIInstrInfo::insertNE</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a20491e3d4f88b3e92bb223d6f23480c6">llvm::MipsInstrInfo::insertNop</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a4c5be0dce0caceff8b457e09b8a998fc">llvm::AArch64InstrInfo::insertOutlinedCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a8e7acd0466662074bd2486d1964cd173">insertPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ef020b54917711fa4fbe9b8ad48258b">llvm::SIInstrInfo::insertScratchExecCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a029c7ad54d8731492ed559aa860e3395">llvm::AArch64InstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#af14abbf5d3082cd072fe85f6f5fe2eea">llvm::PPCInstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a953f3ddec823a0c7db75e73dbf550632">llvm::SIInstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a9ccd38f29c70497c158cca6c739f458d">llvm::SystemZInstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a29c37970b1c079bbbc4515cb00e112fe">llvm::X86InstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loongarchexpandatomicpseudoinsts-cpp-/#a7ec4bec5bc2bbcdc9a1bd2c9835e9744">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::insertSext</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#acfd9f4aff9e242acee783d3156ef3fc2">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::insertSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#ae88297df93601a3a0929300e6a6b58d7">InsertSPConstInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreregisterinfo-cpp/#a830c556c1d7adec01904fdfe8cd50949">InsertSPImmInst</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad88bfb92ca2f7d419adc7e6645406a7c">llvm::SIInstrInfo::insertVectorSelect</a>, <a href="/web-llvm/docs/api/classes/anonymous-simemorylegalizer-cpp-/sigfx10cachecontrol/#adbdd3b28d00cd76ee5e8ec0caf4443dc">anonymous{SIMemoryLegalizer.cpp}::SIGfx10CacheControl::insertWait</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#a350c647ea2f30d644a78ec7ab9dc9684">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::insertWaitcntInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a31612a0bf935add36f82065133267d4a">llvm::SIInstrInfo::legalizeGenericOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#acd22577c1abdac8d676fc8dc30e7c223">llvm::Mips16InstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#aa40f4913df15aca03301144b7f1673df">llvm::MipsSEInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afc45f79c5209c1eb89dc79708ff46a6b">llvm::SystemZInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a4ca63570c656522c8e6a423ae926ba5e">llvm::XtensaInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a696bdea6147585aeab4c74925c3587c3">loadM0FromVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#abf65c6f3a770509d24a75efbbe785a67">llvm::MipsSEInstrInfo::loadRegFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aef098c9f09dc6ea1e32e64d79091a237">llvm::AArch64InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#ad96e959009cbe91d2814bcdfe4fcd51c">llvm::ARCInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a81fe15801547c074b2c33034c00df067">llvm::ARMBaseInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#a3a04d16772e68de8d911d305070f0e0b">llvm::MSP430InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abe4a49e8ceb6213fe44eb0ebc9869eb1">llvm::SIInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3f46048fbf2fe927dc147260fe38b3f7">llvm::Thumb2InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab1601d92ffdfcf6fe48b40b6a7cf8d59">loadRegPairFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#accc5aa5171b3bf3b455bbbac12dd405e">llvm::X86InstrInfo::loadStoreTileReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#af971878700ebbaf8580902e09691cb03">llvm::PPCRegisterInfo::lowerACCRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a3a48db1e7d2f40e7a4ce6aed74b35d6d">llvm::PPCRegisterInfo::lowerACCSpilling</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a6cf0eec5c3acd7ff97e6e5dec15a97d6">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesFromI1</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aa90550e5d59f68a547e28c8beeefb3ed">llvm::PPCRegisterInfo::lowerCRBitRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a38572a53736b568d95a5adc23bcd67f0">llvm::PPCRegisterInfo::lowerCRBitSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a7f3c8b41556bad389b00bd408c9b969f">llvm::PPCRegisterInfo::lowerCRRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a49453cd92df6e63d0c2c45e1d5ace04b">llvm::PPCRegisterInfo::lowerCRSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a4d0bcb536bd3b6491c535f206275ad89">llvm::PPCRegisterInfo::lowerDynamicAlloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#abd8bb8f19f51d30e31b0acac86d8b27c">llvm::PPCRegisterInfo::lowerPrepareProbedAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#acca986611114a82bcfb66e10bb9853f0">llvm::PPCRegisterInfo::lowerQuadwordSpilling</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#ace03d9ed2825d1401093a441f164ecdf">llvm::X86CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a97298a7350df5e0302d0678065f5a1e2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::lowerVGPR2SGPRCopies</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a293e39e43b6f68064cdfd37061c84128">llvm::RISCVRegisterInfo::lowerVRELOAD</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a7238a4dd92fc1bb51c004c49c2b22263">llvm::RISCVRegisterInfo::lowerVSPILL</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ab2c246f45a8786eb5745c6cd9664d088">llvm::PPCRegisterInfo::lowerWACCRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ae7ec7dfcb6babc9f95a9d27ca37dddcc">llvm::PPCRegisterInfo::lowerWACCSpilling</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a7809852647bc7e8ceed1f287b2d03125">lowerWaveReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a1ae314e6d4d78cd50108dbe69ad317b0">llvm::Mips16InstrInfo::makeFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a06c8d8abacb01c870f729e8d2027364f">llvm::SIRegisterInfo::materializeFrameBaseRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a844ba3afb5257d4a9f567d42c54c95cb">llvm::PPCInstrInfo::materializeImmPostRA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblypeephole-cpp/#aa0674cf65bb72bf5302d03cd85c3f14b">maybeRewriteToFallthrough</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a0810cb27406ba2cd135a1a2166b08366">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeNarrowZeroStores</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9511cb46b0b012a8ae67edfbbe7b71a1">llvm::CSKYInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7444176eeeddb4d660fb6a84629abcc4">llvm::LoongArchInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a148f25a7131bb353315edfc43df0c79c">llvm::RISCVInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a1b4c9c49e603e4b80b3d052b54945426">llvm::RISCVInstrInfo::mulImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#aa26fba7384acba48becbf2f67547c437">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::optimizeLdStInterleave</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a370295a9498306cec66248f1c1fd8416">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::optimizeVectElement</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcexpandatomicpseudoinsts-cpp-/#ac2b5ec6cef94d5b2f766c8b61c04c17e">anonymous{PPCExpandAtomicPseudoInsts.cpp}::PairedCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#af3659f9d7092d775e6bb2451b39aa440">popRegsFromStack</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#aa0294873aedbdc7244e1ca9aa115889e">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::populateThunk</a>, <a href="/web-llvm/docs/api/structs/anonymous-armslshardening-cpp-/slsblrthunkinserter/#a4c1c2b4d7e1a18edf5b0fb0c26a1bb71">anonymous{ARMSLSHardening.cpp}::SLSBLRThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/lvithunkinserter/#abdfd94a7acd3b3d9694c88bc642d9269">anonymous{X86IndirectThunks.cpp}::LVIThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ac6d61a8fec7e62b7b19947fe5820860d">llvm::ARMBaseInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae5781ad71db6e0e3bf84f10c4490e291">llvm::PPCInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a4501178e61d2f154d7b9bc4fc519fe68">llvm::R600InstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afd3a31cde29e70e208055c76fc41bd9a">llvm::SystemZInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#ac7c906625fab2baf872e16248962b859">llvm::SGPRSpillBuilder::prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a355a1f30be913f4dc74c51af277fd74a">llvm::PPCRegisterInfo::prepareDynamicAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7bb08436f2b077eb1cd53997a9d9b2b2">llvm::VETargetLowering::prepareMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ab997f379e36469df72be3d7c59f17d2a">llvm::VETargetLowering::prepareSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/copygeneration/#add974c22e80e417ae81566ae9ed683a6">anonymous{HexagonBitSimplify.cpp}::CopyGeneration::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/redundantinstrelimination/#a6221dbe4d8c107be3f19ca24c760f921">anonymous{HexagonBitSimplify.cpp}::RedundantInstrElimination::processBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a9462cc875c5c343ff7ae9b3d68ce6305">llvm::AArch64FrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a62a1e2af50ab6132cd2d8d168835ef57">llvm::PPCInstrInfo::promoteInstr32To64ForElimEXTSW</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a664436e80e651ce40c1abcf063d58fa9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::promoteLoadFromStore</a>, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#afc960ff953a4a9d9fbf91baf590222d2">llvm::SwiftErrorValueTracking::propagateVRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#a24366f8644cf1d6492c2abf2999311a1">pushRegsToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac5b6ac3924041b35531d4e9bf66c3df4">llvm::SIInstrInfo::readlaneVGPRToSGPR</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#aa86a4d647e79dbdeb3d2d43ec301abcd">llvm::SGPRSpillBuilder::readWriteTmpVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a20d1f65e3dcb870550c1c8340fc7a286">llvm::X86InstrInfo::replaceBranchWithTailCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#a34f531a3e81c860e3a04f902568f63c7">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::replaceDstReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcregisterinfo-cpp/#a0c88fcf3221639302fa4045777473205">replaceFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcregisterinfo-cpp/#ac30c350ebdcaa96e93852ea6e7ace1c3">replaceFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae0793a0ace15ba8cf0d9ee31e30dc2c5">llvm::PPCInstrInfo::replaceInstrWithLI</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#aeb9ef6c06b2069f01ba55e3fd2af7b0f">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::ReplaceTLSBaseAddrCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#aa83e2f2005213b888f0f3aa096ad086e">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::replaceTLSBaseAddrCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a49c5e597ebff3776f7a43c3d7f181680">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithBRcc</a>, <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a22b62d53bdcd603d84866e9bf8a4fb45">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithCmpBcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab567bf4900296a78df5fbc74ef1aedce">reportIllegalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ae803619fba0f2282f638ddd36ba004de">llvm::SIRegisterInfo::resolveFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a941b8646dc54e403a97acfb1ee56d774">llvm::SGPRSpillBuilder::restore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aae5bad356a0c0583ebad92fbe899230c">llvm::PPCFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a15d74c0d6159ac707f99c91219d0c6a5">llvm::SystemZELFFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a3d043cad28262fefa366ecc64c9591f1">llvm::SystemZXPLINKFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a94ed22ca5dc3213bfb96e1ddbc41952e">llvm::X86FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcframelowering-cpp/#a4f0f388c4bafdb925e326b829c3f92bd">restoreCRs</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1e3fa2ce8f194193f39ed6428a86c05f">llvm::SIInstrInfo::restoreExec</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#aa742ec29cd5bc4d080c170cb881d050b">llvm::Mips16InstrInfo::restoreFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab49c96f446ff54d9f4d51653b4542581">llvm::restoreStatusRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a535388ac574e0f8d844662d315997b3d">llvm::X86FrameLowering::restoreWin32EHStackPointers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd46906c25e4d5703a8e422283d03bde">llvm::RevertLoopDec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abaa69285a8e74b69f9d178c1b7a8c1cd">llvm::RevertLoopEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a16ff599a0020f57765f08298aaa0b157">RevertWhileLoopSetup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9061b9ab01f65a05033f729a2f12e91a">llvm::RevertWhileLoopStartLR</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#acb75d3ebfc904675aed50ee39f619373">llvm::ThumbRegisterInfo::rewriteFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a71a08885f7838dc5a544816a357e2ec7">llvm::MachineSSAUpdater::RewriteUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-lvlgen-cpp-/lvlgen/#a4d8dd4320b10d7e35f44021a4519ab20">anonymous{LVLGen.cpp}::LVLGen::runOnMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktaggingprera-cpp-/aarch64stacktaggingprera/#a0c1318e709798297e609e0d6cc5ac994">anonymous{AArch64StackTaggingPreRA.cpp}::AArch64StackTaggingPreRA::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a873bcbe8d28d96773cbdf2fd2c9ce07e">anonymous{PPCBranchSelector.cpp}::PPCBSel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmakecompressible-cpp-/riscvmakecompressibleopt/#a76561cc6613d04a06e24640760923da2">anonymous{RISCVMakeCompressible.cpp}::RISCVMakeCompressibleOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siwholequadmode-cpp-/siwholequadmode/#ae53d8e40bdcb428165b0243af4be1dcc">anonymous{SIWholeQuadMode.cpp}::SIWholeQuadMode::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupsetcc-cpp-/x86fixupsetccpass/#a88ff40585130ceeb06ea67057cc33b5d">anonymous{X86FixupSetCC.cpp}::X86FixupSetCCPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/cgbr/#ae7e54015b8e4160365d925c1bd46004f">anonymous{X86InstrInfo.cpp}::CGBR::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionrethardening-cpp-/x86loadvalueinjectionrethardeningpass/#a555db007ae6df71fb9fa02662e2c8643">anonymous{X86LoadValueInjectionRetHardening.cpp}::X86LoadValueInjectionRetHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86speculativeloadhardening-cpp-/x86speculativeloadhardeningpass/#a862b3b4b5ed250fcfb2d6f9a130f4a0c">anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5718bb42ac48e382b259cd668ad38e21">llvm::FastISel::selectFreeze</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#a0a6245fa36ea8b128eec6555f2ab52bb">setCallTargetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5b3180edf81915b106633986034d7a01">llvm::ARMBaseInstrInfo::setExecutionDomain</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#a3c575506b0048149beea9d1f222fdc32">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::SetRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#ae3b597ed71cdeef406aed84ce2e04f52">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::setRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a804c0cf6824955fbb71f0daf42759ae0">llvm::VETargetLowering::setupEntryBlockForSjLj</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a77dc4905d180a52615d00a760b111f9a">llvm::ARMFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#af676cadcef1e3d4d159420f075a083da">llvm::AVRFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a4d6b288488bfee7d307b78a36e230986">llvm::MSP430FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a42ba26b731da85ec85d9f4ebb7d27e02">llvm::PPCFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a9db07f97c8d52e506e689b789b231f0c">llvm::SystemZXPLINKFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#af07ce77a4beea41a98862690cee5ec2d">llvm::Thumb1FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc942a637e5d48a94d4033498b7479dd">llvm::X86FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcregisterinfo-cpp/#aaa14cbf6168e04cf996c5ab314430bb5">spillRegPairs</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#adfdb32bd422a7613ae83c10f2841abf7">spillVGPRtoAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#afb4c3921369b6b1fef886bfa979b6d2a">storeRegPairToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a59a4a03c8f10059fe2fed96077fc311c">llvm::Mips16InstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#ac808bf28cfa407acff2b367a0bb383ba">llvm::MipsSEInstrInfo::storeRegToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aeba4e73d60d1b4cedc120d06114c0620">llvm::AArch64InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a687fecaf502080080ba5069e6b211a65">llvm::ARCInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a8a7868df2562a3b48d08d24c9db87b98">llvm::ARMBaseInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a90829bf41a9e8e4c4e4ad59eab490719">llvm::AVRInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#a41c0bd4e75d4643a8387fe6d56eca337">llvm::BPFInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a647cde93263cdcab73a72f5e459041c6">llvm::CSKYInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a9644f3506784b55b500d2f73f94d79e0">llvm::HexagonInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ae93380d9a76c25ec34ee034e13b3a8fd">llvm::LanaiInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#aed611129b85082f7e6459907b50a8cd5">llvm::LoongArchInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acc65122fa06b8871a427abbbd700b22a">llvm::M68kInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#ae215353a37be6d2f533a4858bd96be74">llvm::MSP430InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ec207a1c12adfc61c6566436e5a2cd7">llvm::SIInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#abc124725b4afa4a9d9449c6e2cfb3d73">llvm::SparcInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a952f199f7cb8a257a40193bcd67a976d">llvm::Thumb1InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a3e0753735e274deee756f4b8961b88b2">llvm::Thumb2InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a2132749e515b00c60255bdb4acfba223">llvm::VEInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aa424b646f1bed0832f4eb126081e6fe5">llvm::X86InstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a915259afe54d2619524ed03c9c273c57">llvm::XCoreInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#aef5d7d851ae3869d7094741795181ae5">llvm::XtensaInstrInfo::storeRegToStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a08bf0b055eab1a86300c18c2b0f9fc7e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a17772fd1beeccd740ec6412abad098f9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldPhiAGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a8562a883d9494266aca5d1b2f8b5dc5e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryOptimizeAGPRPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a598eeebd324ee0050cc856e6e28f4778">unstackifyVRegsUsedInSplitBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a9a5c05172bf1b5e36b42f412c4a176cf">UpdatePredRedefs</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a08d97216cdc088a0055e5cd597814ddb">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitADDSSUBS</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a9cdd873b7d4271334f198670b51934f4">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitADDSUB</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a1aeb260a435d4ca4ca00e380df4546c6">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitAND</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a2a2a5cd18017a50ad5e469ac95a910f3">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitCSEL</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a763775ab82c6fd6290a1f15b1f36c4cf">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitUBFMXri</a> and <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#acfa976b571bd6001d4e8f4ccba059162">llvm::WebAssemblyFrameLowering::writeSPToGlobal</a>.</p>

</div>
</div>

### addRegMask() {#a8880ccaea51a4ee9b48c3c8d7fbfebf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addRegMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c01d756ca363aef75429d61d21c0c14">llvm::MachineOperand::CreateRegMask</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acfee0aff6a62996ec1dbee56ef35ad88">llvm::AArch64TargetLowering::EmitGetSMESaveSize</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armcalllowering/#af3fdfad8a2951ca4c86fd64560c550a7">llvm::ARMCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kcalllowering/#a2c714d045da3eaad01dfd893048e9a0c">llvm::M68kCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afd3a31cde29e70e208055c76fc41bd9a">llvm::SystemZInstrInfo::PredicateInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### addShuffleMask() {#a846993bea18636f4fd47bbe401fece04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Val)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab261a066a6f63f72c705a1d7a40e56de">llvm::MachineOperand::CreateShuffleMask</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>

</div>
</div>

### addSym() {#a7ffeb5b3940506a54e69e72e26e2a6cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addSym (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned char TargetFlags=0)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a081ab7d53b85dfd7a2f8609689147393">llvm::MachineOperand::CreateMCSymbol</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#aff663b5af9761f53e2f0d42ce09c408f">emitPACSymOffsetIntoX16</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/cgbr/#ae7e54015b8e4160365d925c1bd46004f">anonymous{X86InstrInfo.cpp}::CGBR::runOnMachineFunction</a>.</p>

</div>
</div>

### addTargetIndex() {#a0bc7ed8aefe042984bce6ea95ad5f1ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addTargetIndex (unsigned Idx, int64_t Offset=0, unsigned TargetFlags=0)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af3137f95a28140bba664c03c2f350870">llvm::MachineOperand::CreateTargetIndex</a>, <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### addUse() {#ad88e27102395957e457fed8e73a085cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::addUse (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegNo, unsigned Flags=0, unsigned SubReg=0)</td>
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

<p>Add a virtual register use operand.</p>


<p>It is an error for Flags to contain <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">RegState::Define</a></span> when calling this function.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="#a927857fc69e4b4f0cde307f86f180df5">addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/srcop/#aba93d72255e1239b5209e416a1b7f199">llvm::SrcOp::addSrcToMIB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvprelegalizercombiner-cpp-/#a99fb6c2c4ea3a52f8977eeb8d2c2f425">anonymous{SPIRVPreLegalizerCombiner.cpp}::applySPIRVDistance</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17fda1a191d8f69587355e32c5f15618">llvm::buildAtomicFlagInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abaf31a84826d881e8cebb369b37c6ff1">llvm::buildAtomicFloatingRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad914aa705137aa18db88ae760f534f25">llvm::buildAtomicInitInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa24e8200fb460e1454ce71de5921fc7b">llvm::buildAtomicLoadInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acec38968fb25d9da84d9d606eca35d7d">llvm::buildAtomicRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e86010cc9381660c973391ab0034e00">llvm::buildAtomicStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7380fc2046fc70f0b6040466a1a535af">llvm::buildBarrierInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aecf67aca8d78d0136244799c4182e52f">llvm::MachineIRBuilder::buildBrIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aaf1013659ccc9708197f76c0bd724936">llvm::MachineIRBuilder::buildBrJT</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6aee777d2869b23ba59b88b9ceb32cfe">llvm::SPIRVGlobalRegistry::buildConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#affb04c244423615aa0df24ee36f2de20">llvm::SPIRVGlobalRegistry::buildConstantInt</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4280c0cdf83d31309a8ad8d0d6815e66">llvm::SPIRVGlobalRegistry::buildConstantSampler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a8dcc4e0c146cff251e73a2a59123683b">buildOpBitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a985ab67fe6c5e51cb42dc97aaf6b300f">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a686587ed0b5b8437aa621630cf56d147">llvm::buildOpDecorate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2efc2665b84726e69a327b44ca77b50a">llvm::buildOpName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01f1b2c1fbaec02e4f0d0af133830ca6">llvm::buildOpName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec2c920f97cffa508fee51ee5e722056">llvm::buildOpSpirvDecorations</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp/#a3b8f2c8dafaf2b1007b8661546ce5aca">convertPtrToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a2abcc0dade6e762f2145f49e3158a71c">doInsertBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a8997d907b1de0e1b433c59102335b06a">llvm::AArch64InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#abbd7ca528e7bfb2362adfeece0fa9a8c">expandPseudoLogM</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa8aa7be4bd12d2e18b08a87805017131">llvm::RISCVInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a748bbd916eb5b48b009f8ee2e6a6afc9">llvm::generateAsyncCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae60b3860c5a2f98d349a53660758ddd9">llvm::generateCastToPtrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a884a65fc47e7cf521d37505e1548e9ca">llvm::generateConvertInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515c6055dea0a74d18c4549511921e8c">llvm::generateDotOrFMulInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e92ead0d298bfaef08370c3877e05c9">llvm::generateEnqueueInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aebcace45f75d5389e0c72effb52530b6">llvm::generateExtInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2947a09647c5d7fc7429c90d93fd2f17">llvm::generateGroupInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a610c7b58032f5eac1b06aa0c66cadb6a">llvm::generateGroupUniformInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3abab01a19c99b6700cc0aadde16edc2">llvm::generateICarryBorrowInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa2920e81d3e11168548e83a60ddaaf">llvm::generateImageMiscQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa258d22bc5ca54e36dc15a8c3e724e52">llvm::generateIntelSubgroupsInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9c060a884e9461f06d7601681d2bcf">llvm::generateKernelClockInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fc9e18e3a0aeb8c6426eae57a1ab61e">llvm::generateLoadStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac44c583be05bf96fc1323db172608e32">llvm::generateReadImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfd0973871508362181539a1e103e0ed">llvm::generateRelationalInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a519951c274914148448a0942705a1fc2">llvm::generateSampleImageInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab25d01b38cf3d0b9e22fe06c673243d6">llvm::generateVectorLoadStoreInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada8921c7a351b3829e06720c0858f541">llvm::generateWriteImageInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a451ac66d74cbee6582c570a71254ae26">genTPEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd62dcc07699f0f98ae897208c1529ae">genTPLoopBody</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab28508dbb1f9996154ae13f70fa4f2e2">llvm::genWorkgroupQuery</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af54e9ce01961e65d9b74fef2193a8d95">llvm::SPIRVGlobalRegistry::getOrCreateConstFP</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a08f607435df14840793b848f2b3c0257">llvm::SPIRVGlobalRegistry::getOrCreateConstInt</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af99db04834e1ae3fc23466a80045a4d9">llvm::SPIRVGlobalRegistry::getOrCreateConstNullPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a138bc82a9943aa3008ab86bec2d2c91a">getOrCreateFrameHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acbccd3fb66e9075690f45dea7440cf9e">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeCoopMatr</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4cd2c03c778450920cd3b53acdcb4fba">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8cdc39b963a62003cd157541feca56f6">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampledImage</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ae5869468359515f460a588357f1737cf">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVArrayType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#acab67f583801f5c01ee9ac2162f5e27d">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVPointerType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4791c0c5f18aaa298445226456f15547">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a35c2ba2ad91e2fe027f8f64e92a7502f">llvm::SPIRVGlobalRegistry::getOrCreateUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7dbf2885fa89980322c2f4b58f85ff18">llvm::SIInstrInfo::insertSimulatedTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ac8dc1642db124c4da34fbec06040a0c4">llvm::SPIRVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a1eab543e55a7220697eb4e72651e2e17">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeConstOffsetInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d5aaa74bb3796fbcd85861222730ab">llvm::processInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvlandingpadsetup-cpp-/riscvlandingpadsetup/#a76b9ad374c6d52f071aa57de58479f70">anonymous{RISCVLandingPadSetup.cpp}::RISCVLandingPadSetup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a014d1ebf94ebd54347ec5c6da3af5ea2">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::selectDot4AddPacked</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a8139fddffe4387e1752fb124e92a822b">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::selectDot4AddPackedExpansion</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa4f08d12a02cc1685e8ea788f818ac1a">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSviGPR</a>.</p>

</div>
</div>

### cloneMemRefs() {#ad84ebe08bb098cd283e922fd186f77e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::cloneMemRefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; OtherMI)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a3a26f11d1735bf0f25261aefd2bee9c1">llvm::MachineInstr::cloneMemRefs</a> and <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a631f336d06a6088837d505bf1332001e">AdjustBaseAndOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a66ba876f71016493af6fd1dc6980d912">buildMUBUFOffsetLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a7bec9e5fa4cafeca001d506741b38f0f">createPostIncLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a056f22c11083630d8bcc82299cb783af">llvm::PPCTargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a83de3f9ab24662688a50952de742a4dd">llvm::ARMBaseInstrInfo::expandLoadStackGuardBase</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#aa0cefa4c61cc43ff6fd225bc7b4f917e">InsertLDR_STR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>.</p>

</div>
</div>

### cloneMergedMemRefs() {#a0a8d0cceecd0424aefb44ea46a27be4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::cloneMergedMemRefs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; OtherMIs)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a7a5607fcb0a195620036bb0f1217c8a2">llvm::MachineInstr::cloneMergedMemRefs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a0810cb27406ba2cd135a1a2166b08366">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeNarrowZeroStores</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>.</p>

</div>
</div>

### constrainAllUses() {#aa238cd5a6fee2e66e4b5bd3fc2040c19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineInstrBuilder::constrainAllUses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &amp; RBI)</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a2abcc0dade6e762f2145f49e3158a71c">doInsertBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ac8dc1642db124c4da34fbec06040a0c4">llvm::SPIRVCallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a285142054aed60907906550e49ed07e2">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a014d1ebf94ebd54347ec5c6da3af5ea2">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::selectDot4AddPacked</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a8139fddffe4387e1752fb124e92a822b">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::selectDot4AddPackedExpansion</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a8a476245face103d65c519250257e499">SelectMSA3OpIntrinsic</a>.</p>

</div>
</div>

### copyImplicitOps() {#ae4cfeb86ad3780d71eb022485e91d211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::copyImplicitOps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; OtherMI)</td>
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

<p>Copy all the implicit operands from OtherMI onto this one.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a67f26cdb79c726f4616b1cd7ae1996cd">llvm::MachineInstr::copyImplicitOps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#af3659f9d7092d775e6bb2451b39aa440">popRegsFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a20d1f65e3dcb870550c1c8340fc7a286">llvm::X86InstrInfo::replaceBranchWithTailCall</a>.</p>

</div>
</div>

### getInstr() {#af066b2b6a1013299bfca84fe8b798a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::MachineInstrBuilder::getInstr ()</td>
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

<p>If conversion operators fail, use this method to get the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> explicitly.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2426fcc21a9819b2f48f2f7db8a23844">llvm::addNumImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#a66ba876f71016493af6fd1dc6980d912">buildMUBUFOffsetLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a9cb1dd3dd16025fc64f52adb12c9ce5f">llvm::SparcInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad8b8d94aaf80cefc49bc3263f05cd741">llvm::VEInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#a669f90d5fe703ecfe25fb738553f6ea5">copyPhysSubRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#abe83de329645327b1d40bee0d304aff8">createCallWithOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyregisterinfo/#ac8db545cfaf863844d25944e00814ba1">llvm::CSKYRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae6e03361f09a5b06dc299f6ee1c76ca4">llvm::AArch64TargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#acd40e68d03e3f43b4f7563d083d0e2ee">llvm::RISCVTargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a89a6b95d310330e345c3aee6a07ffd96">llvm::X86TargetLowering::EmitKCFICheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1e962b46ba9784205ea3eba9c0b10ded">expandMOV32r1</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acf82a3fa2657200bf3068a0273939229">llvm::M68kInstrInfo::ExpandMOVSZX_RM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a0ea5ffee956540dce97bf5d067051c6b">llvm::M68kInstrInfo::ExpandMOVSZX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a6388048852214c02aa209e16f10b588a">llvm::M68kInstrInfo::ExpandMOVX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a404db50d68f1ca8d28396b5e2deb061d">llvm::VEInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#ab4228d105bd5b126170c562e6f8acdfd">llvm::M68kInstrInfo::ExpandPUSH_POP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ab8ebdf9a381ab517c0225f7f0719cf45">expandSpillPPRToZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a6d68551280f423f1894b605eb2c5a872">llvm::ARCInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a3ca4c3ddc5d302c21716484fa8de528d">llvm::XCoreInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a72a62fe526ad0cd3c24cfe003d363df0">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::runOnMachineFunction</a>.</p>

</div>
</div>

### getReg() {#a1c5fadb14ff1d77faad0cb58a43252ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::MachineInstrBuilder::getReg (unsigned Idx)</td>
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

<p>Get the register for the operand index.</p>


<p>The operand at the index should be a register (asserted by <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>).</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#ac9275cee4b272a43dca3299ab8b6144c">anonymous{AArch64PostLegalizerLowering.cpp}::applyLowerVectorFCMP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a580c192e2fc41ab69e61d087027ceabf">anonymous{AArch64PostLegalizerLowering.cpp}::applyNonConstInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#af5f0f04b137494bbf8fb56286dea2762">buildAnyextOrCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#afc84382af091d9a0de9586212e16a195">buildLogBase2</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#afee96ecb8e8588a068aa3c1743b63352">Expand2AddrUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6fbe25c9b97dceec5e6265b2bca2f716">expandLoadStackGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1e962b46ba9784205ea3eba9c0b10ded">expandMOV32r1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#acf2585460bbea1e2bac210c9588d4bc4">expandNOVLXLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a44f31fb5ea31b5062b22b05cb8fddee4">expandNOVLXStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6203308c1da11d69cb3bd6c23b90b207">expandSHXDROT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpucalllowering-cpp-/#af49a6097a8071a69f37f57febd91c05c">anonymous{AMDGPUCallLowering.cpp}::extendRegisterMin32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4c0f443e3b75e7b2ffaf53d2ab73fc0">llvm::extractVectorParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a2f1d26ea9bced931d104b4dd8b26775f">getMemsetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a867592b1a0963211ea415ea436a976e5">llvm::MipsLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af4667ecbc4447b41863430fb572d8f82">llvm::AMDGPULegalizerInfo::legalizeLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a376125f5ee6f0a21fdd6336557fa3913">llvm::AMDGPULegalizerInfo::legalizePointerAsRsrcIntrin</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac29774c06843a7c183ae3fd328d43bc8">llvm::LegalizerHelper::lowerVECTOR_COMPRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a0d70a38e8f0622515630e7e8672df270">selectMergeValues</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arminstructionselector-cpp/#a838cd050490773e0349589c0d78618fc">selectUnmergeValues</a>.</p>

</div>
</div>

### setMemRefs() {#a1dfb0ae952397bf4c6d5cbcaff4c4b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::setMemRefs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * &gt; MMOs)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5981137a17cad3d9b2276ad63e15ee40">llvm::MachineInstr::setMemRefs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a73f427af3525340f74d7e85b984b82d6">convertCalleeSaveRestoreToSPPrePostIncDec</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a5973091849912847746aa5b158772e8b">llvm::VETargetLowering::emitEHSjLjLongJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ab8ebdf9a381ab517c0225f7f0719cf45">expandSpillPPRToZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a1eab543e55a7220697eb4e72651e2e17">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeConstOffsetInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a006d92e5eae5fd3ca76b72ec1b749a1b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeUpdateInsn</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>.</p>

</div>
</div>

### setMIFlag() {#a632680dcf899466c32c0095a40e7e89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::setMIFlag (<a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518">MachineInstr::MIFlag</a> Flag)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aba86b0738c2ab2a52688b846c45bfe59">llvm::MachineInstr::setFlag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#aa4909014e5875c7b2d1cd6fdd7ab7e89">llvm::RISCVRegisterInfo::adjustReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#af0ba757b047f4e00f4a68fa33db9b50d">llvm::MSP430FrameLowering::BuildCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aef0079a40a972f2942156b2d73bbf190">llvm::X86FrameLowering::BuildCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#a2f84e624e7227bb33f6c14fe98f36715">BuildPACM</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvframelowering-cpp-/cfirestoreregisteremitter/#a92aa2c10d7a31b9713443dd938973738">anonymous{RISCVFrameLowering.cpp}::CFIRestoreRegisterEmitter::emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvframelowering-cpp-/cfisaveregisteremitter/#aeaf54bb6240fb6bea4e1cd52e6a74ae1">anonymous{RISCVFrameLowering.cpp}::CFISaveRegisterEmitter::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a51c3d43bee1dec655ecaec65afc94c82">llvm::ARMFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a60f61ed13ff961051650fac4c6fa4ec0">llvm::CSKYFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a27812f7473acb8b3398abc5a297ea082">llvm::M68kFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a3a9df23d95cdadc6a77b12dc3377a331">llvm::MSP430FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ace1de8acc8ac15962f04832273df87b1">llvm::SIFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a6289c3b215e791396217e90177ad28a5">llvm::Thumb1FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a353d6967ff6cb7d22110de97773d65d8">llvm::X86FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a36db540eb7d0490cab86e4cf12ac9116">emitLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiframelowering/#a1cc86e82857e8ff7bceddf8838830577">llvm::LanaiFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a921a457b786497c2309b9f63abd9c951">llvm::MSP430FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#af5c6e03e6ac66b0eb9389a951593985b">llvm::SIFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a02cddefc96e08fba507c3d0eac7f6c1f">emitShadowCallStackEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ae5f813adf7cab5ad0f7a542b681ca95c">emitShadowCallStackPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#aa8a605a58ebdee20705834400bdbb922">llvm::X86FrameLowering::emitSPUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a97c69ea577c9578ecadf9469189438d0">emitStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a138bc82a9943aa3008ab86bec2d2c91a">getOrCreateFrameHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a7f43397146b3eee4bcd4ff73ec27335f">InsertSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab4a6a57aa863f068433ba056f15c61b1">llvm::RISCVInstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ae1eb226b5600f7802dc31d1903a5040e">llvm::AMDGPUCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7444176eeeddb4d660fb6a84629abcc4">llvm::LoongArchInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a148f25a7131bb353315edfc43df0c79c">llvm::RISCVInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a1b4c9c49e603e4b80b3d052b54945426">llvm::RISCVInstrInfo::mulImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#af3659f9d7092d775e6bb2451b39aa440">popRegsFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab5fe151eb7f6fa13e78ed30cb5f1ad72">llvm::M68kFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#ad8f2dd732e11ab2eed0563516a0128e8">llvm::MSP430FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a94ed22ca5dc3213bfb96e1ddbc41952e">llvm::X86FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a535388ac574e0f8d844662d315997b3d">llvm::X86FrameLowering::restoreWin32EHStackPointers</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86argumentstackslotrebase-cpp-/x86argumentstackslotpass/#af787e4cab9e64467b9aa0a253171fa88">anonymous{X86ArgumentStackSlotRebase.cpp}::X86ArgumentStackSlotPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionrethardening-cpp-/x86loadvalueinjectionrethardeningpass/#a555db007ae6df71fb9fa02662e2c8643">anonymous{X86LoadValueInjectionRetHardening.cpp}::X86LoadValueInjectionRetHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#af41a5f8ba3c70858915a0d6e9ab66400">signOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#af676cadcef1e3d4d159420f075a083da">llvm::AVRFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a3bbbc37b2cd9470b51560df8c20e66e2">llvm::M68kFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a8eced7de6aa2268fa96f3580b9ef01bf">llvm::MipsSEFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a4d6b288488bfee7d307b78a36e230986">llvm::MSP430FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc942a637e5d48a94d4033498b7479dd">llvm::X86FrameLowering::spillCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a23e6d76b3b763236213c20fdd08718ed">llvm::RISCVInstrInfo::storeRegToStackSlot</a>.</p>

</div>
</div>

### setMIFlags() {#adf25b569ca308aacc819a2331626ed5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::setMIFlags (unsigned Flags)</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a264402282f599b6181b6415278fbf849">llvm::MachineInstr::setFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9b0a622dbae74cb8a4b9b87a8b559b25">llvm::AArch64InstrInfo::buildOutlinedFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a31aa4c781d7a65b275b3de1882180675">llvm::SIInstrInfo::buildShrunkInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a73f427af3525340f74d7e85b984b82d6">convertCalleeSaveRestoreToSPPrePostIncDec</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcncreatevopd-cpp-/gcncreatevopd/#afc677780cbd237adfee6dd02bf20541f">anonymous{GCNCreateVOPD.cpp}::GCNCreateVOPD::doReplace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae917ff404aade469cb9d3780515660ad">llvm::emitARMRegPlusImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="/web-llvm/docs/api/structs/anonymous-armframelowering-cpp-/stackadjustinginsts/#a042cf3c899a8ad17fe7a9509c1ed60c4">anonymous{ARMFrameLowering.cpp}::StackAdjustingInsts::emitDefCFAOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a1886741049357a9b7cea7f8e8784a818">emitDefineCFAWithFP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a5e4563cae7f10b41cdff9a61f1f6aaab">llvm::ARMBaseRegisterInfo::emitLoadConstPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-cpp/#a181216377a992592ea7e30fc0ce07f0d">emitPACCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#aa1bd5939c1fd11c05038c583ada0110d">llvm::ARCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a2ca615519139c4956a608c03afc68fc8">llvm::ARMFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#abfcb7ab0b2bd202bc7e048d531897a3a">emitPrologueEpilogueSPUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a02cddefc96e08fba507c3d0eac7f6c1f">emitShadowCallStackEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaee29fd8c447694396529bd6a468a6f">llvm::emitT2RegPlusImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a55668c464aef1136badb1b58eeec19c6">emitThumb1LoadConstPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a8a9cca3d1c6515fbf780f033644ace85">emitThumb2LoadConstPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaeed6b0c7995c9000819c8bed932e551">llvm::emitThumbRegPlusImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumbregisterinfo-cpp/#a4c17381dc1cacb65f1dd6d31d15100e0">emitThumbRegPlusImmInReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a64c6eca16f58ce5cef19b84d78d3adb7">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldCopyToVGPROfScalarAddOfFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a012040151268735433380829e4ef0dcd">genSubAdd2SubSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a5c50c1e0000377affb5eec391c213df1">insertSEH</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a1eab543e55a7220697eb4e72651e2e17">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeConstOffsetInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a006d92e5eae5fd3ca76b72ec1b749a1b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeUpdateInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9511cb46b0b012a8ae67edfbbe7b71a1">llvm::CSKYInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a664436e80e651ce40c1abcf063d58fa9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::promoteLoadFromStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#a24366f8644cf1d6492c2abf2999311a1">pushRegsToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a77dc4905d180a52615d00a760b111f9a">llvm::ARMFrameLowering::spillCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#af07ce77a4beea41a98862690cee5ec2d">llvm::Thumb1FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### setMMRAMetadata() {#a72cc8dc853a4823eccff58bc0269b306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::setMMRAMetadata (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MMRA)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af4e52d47d0f7fa13dd23fae4cfc4f85b">llvm::MachineInstr::setMMRAMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9a381a22976702d096a05acf1605c5bc">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac98e182e817bb53f2ff8135d29637dfb">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa1fe17340600deeeb2a5647e56fc1a2">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a859007fbe974ffb4c1793877e4ada681">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05cdb3fd84788ee9af0824bf14f280e7">llvm::BuildMI</a>.</p>

</div>
</div>

### setOperandDead() {#a45ffb8b95e5b75eeb68be7d300eb9618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::setOperandDead (unsigned OpIdx)</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a64c6eca16f58ce5cef19b84d78d3adb7">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldCopyToVGPROfScalarAddOfFrameIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a06c8d8abacb01c870f729e8d2027364f">llvm::SIRegisterInfo::materializeFrameBaseRegister</a>.</p>

</div>
</div>

### setPCSections() {#abdda4cba7788bae87378a6cbdc81dbe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstrBuilder &amp; llvm::MachineInstrBuilder::setPCSections (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MD)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="#a4958726a2fb346aec8c8dffb9e7212b1">MachineInstrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ae76989792a75b7735546e69711d22209">llvm::MachineInstr::setPCSections</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9a381a22976702d096a05acf1605c5bc">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac98e182e817bb53f2ff8135d29637dfb">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa1fe17340600deeeb2a5647e56fc1a2">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a859007fbe974ffb4c1793877e4ada681">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05cdb3fd84788ee9af0824bf14f280e7">llvm::BuildMI</a> and <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MF {#aea8b924aaad7e94be6087514fe925434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::MachineInstrBuilder::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

### MI {#a761967790440ac0a1975282e4fa24ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::MachineInstrBuilder::MI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
