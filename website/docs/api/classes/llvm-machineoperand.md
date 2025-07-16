---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machineoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineOperand` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> class - Representation of each machine instruction operand. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineOperand { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MachineOperandType : unsigned char { <a href="#af269b990800f72c7cf535c407e8e639b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned char { <a href="#a2a1b2e7b0a13eacf3c015e95ce495360">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Artificial kinds for <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> usage. <a href="#a2a1b2e7b0a13eacf3c015e95ce495360">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae984860b88c448f0d8f7ac9b11077441">MachineInstr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae42703e0d4c147a9765234011797f5dd">MachineRegisterInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4eed935e1417aeaa14cf349c1165b5">DenseMapInfo&lt; MachineOperand &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c94b329f3cec9f4fd23db1d208c0bc8">hash_value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> hash_value overload. <a href="#a5c94b329f3cec9f4fd23db1d208c0bc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3363bdbc0d3161ceb70aa747d998e9af">MachineOperand</a> (MachineOperandType K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af269b990800f72c7cf535c407e8e639b">MachineOperandType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab313591ae4ea1e3a4ab59121a7dc2a2b">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getType - Returns the <a href="#af269b990800f72c7cf535c407e8e639b">MachineOperandType</a> for this operand. <a href="#ab313591ae4ea1e3a4ab59121a7dc2a2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06dda088d3c7686f7dfcdb2b96323f5">getTargetFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a> (unsigned F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace845d7da04db4610b2d051c7b44e832">addTargetFlag</a> (unsigned F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9719077fcba2cd439e84897257a47bb0">getParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getParent - Return the instruction that this operand belongs to. <a href="#a9719077fcba2cd439e84897257a47bb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09f8d34639010d76d48d76754520158">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800c03587b02047d71c6ba2f7b2193eb">clearParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearParent - Reset the parent pointer. <a href="#a800c03587b02047d71c6ba2f7b2193eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c893675dfd5d1b1e4aea1e8211217c7">getOperandNo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the index of this operand in the instruction that it belongs to. <a href="#a0c893675dfd5d1b1e4aea1e8211217c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedeaf186a99c875b4196318a4083ff77">print</a> (raw_ostream &amp;os, const TargetRegisterInfo *TRI=nullptr, const TargetIntrinsicInfo *IntrinsicInfo=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> to <span class="doxyComputerOutput">os</span>. <a href="#aedeaf186a99c875b4196318a4083ff77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76123bb0e0b41f5dbae594726160db22">print</a> (raw_ostream &amp;os, ModuleSlotTracker &amp;MST, LLT TypeToPrint, std::optional&lt; unsigned &gt; OpIdx, bool PrintDef, bool IsStandalone, bool ShouldPrintRegisterTies, unsigned TiedOperandIdx, const TargetRegisterInfo *TRI, const TargetIntrinsicInfo *IntrinsicInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>More complex way of printing a <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>. <a href="#a76123bb0e0b41f5dbae594726160db22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9d3159041bfbc33655256282b6afda">print</a> (raw_ostream &amp;os, LLT TypeToPrint, const TargetRegisterInfo *TRI=nullptr, const TargetIntrinsicInfo *IntrinsicInfo=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as print(os, TRI, IntrinsicInfo), but allows to specify the low-level type to be printed the same way the full version of print(...) does it. <a href="#a3f9d3159041bfbc33655256282b6afda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71453c9c9ea541dab5841a0b590d56ee">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Tests if this is a MO_Register operand. <a href="#a4c9594c955fec80c73ddd964b5efd554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76f61c6784df6dc8402a8b9011041926">isImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Tests if this is a MO_Immediate operand. <a href="#a76f61c6784df6dc8402a8b9011041926">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ea768fbb182d6bbe3ff85ae1eb7031">isCImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isCImm - Test if this is a MO_CImmediate operand. <a href="#a32ea768fbb182d6bbe3ff85ae1eb7031">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcb818bd3e34498f8f72ca555a36d5eb">isFPImm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFPImm - Tests if this is a MO_FPImmediate operand. <a href="#afcb818bd3e34498f8f72ca555a36d5eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe1784e242ce66da6029b3a681896bd2">isMBB</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMBB - Tests if this is a MO_MachineBasicBlock operand. <a href="#afe1784e242ce66da6029b3a681896bd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7213433bd60dc33020246384dc18b9b">isFI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isFI - Tests if this is a MO_FrameIndex operand. <a href="#ad7213433bd60dc33020246384dc18b9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b401e780c5eed0aca1cfbf44d36a545">isCPI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isCPI - Tests if this is a MO_ConstantPoolIndex operand. <a href="#a5b401e780c5eed0aca1cfbf44d36a545">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0890848fb02b90b1f7956063bc61cb3">isTargetIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isTargetIndex - Tests if this is a MO_TargetIndex operand. <a href="#ac0890848fb02b90b1f7956063bc61cb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eb9bf17230a1c4329e26935f44d72eb">isJTI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isJTI - Tests if this is a MO_JumpTableIndex operand. <a href="#a8eb9bf17230a1c4329e26935f44d72eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d1155c8c38e84cbe387998fd2e517e">isGlobal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isGlobal - Tests if this is a MO_GlobalAddress operand. <a href="#ab0d1155c8c38e84cbe387998fd2e517e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5f0ef161b5b4dedad2e9aac9fcfee7">isSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSymbol - Tests if this is a MO_ExternalSymbol operand. <a href="#a7c5f0ef161b5b4dedad2e9aac9fcfee7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abed9003622087a5bbddb7c19b6d02ce6">isBlockAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isBlockAddress - Tests if this is a MO_BlockAddress operand. <a href="#abed9003622087a5bbddb7c19b6d02ce6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55fdcb2a9df9a69067eed1bc17a0b927">isRegMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isRegMask - Tests if this is a MO_RegisterMask operand. <a href="#a55fdcb2a9df9a69067eed1bc17a0b927">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc87d84f8ed5dccb4553a23d1b34843">isRegLiveOut</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isRegLiveOut - Tests if this is a MO_RegisterLiveOut operand. <a href="#a9bc87d84f8ed5dccb4553a23d1b34843">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bce8907b3cea3c34b9eeac6480bc955">isMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMetadata - Tests if this is a MO_Metadata operand. <a href="#a7bce8907b3cea3c34b9eeac6480bc955">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a143ff82a16da33c626da4949180e6b1f">isMCSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04e186512436ffdefdb16ed8aaea57a">isDbgInstrRef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abebd8c425a02eaa5470c40ac6c47c59b">isCFIIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f92ba840149cc7f75e38279341257a">isIntrinsicID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4039d2f36755814cb173552df270bddc">isPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81521682ef12b5e4f681502f9346a4ad">isShuffleMask</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0035d7c1c860501c877c20e6e93297b">getReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getReg - Returns the register number. <a href="#ac0035d7c1c860501c877c20e6e93297b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a028a8c5113d40d8c3f4427053bf36738">getSubReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69544ec8658eadeed98245dc37c3a541">isUse</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75eb135014670ce946e78739cdc9b51b">isDef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf161859e1ad7fd3da485d3cb688d34">isImplicit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee820701392c55ad54235d3d7201206">isDead</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4046212ebc647b17e811837ae4ea3afd">isKill</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1255befbcd6e034394681b1bcd3529ff">isUndef</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isRenamable - Returns true if this register may be renamed, i.e. <a href="#a8be49bc86b5d01b52b90baf1b4477667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3008c73231cdb4922d197fe56525364">isInternalRead</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd6aa9da048ef7a4faeaac6484d5c9a6">isEarlyClobber</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">isDebug</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be9857a09c82046b77a71918b5e214f">readsReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>readsReg - Returns true if this operand reads the previous value of its register. <a href="#a3be9857a09c82046b77a71918b5e214f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d3c4a8df3c60d4d97cc39c300d69c0">isValidExcessOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this operand can validly be appended to an arbitrary operand list. <a href="#a79d3c4a8df3c60d4d97cc39c300d69c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682ba82f42f7903d0000ffbb13ea3b57">setReg</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the register this operand corresponds to. <a href="#a682ba82f42f7903d0000ffbb13ea3b57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a001d31fcea92be51d2999826b806606f">setSubReg</a> (unsigned subReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a5b2fd837189405f1b07a6c9249d4f">substVirtReg</a> (Register Reg, unsigned SubIdx, const TargetRegisterInfo &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>substVirtReg - Substitute the current register with the virtual subregister Reg:SubReg. <a href="#a13a5b2fd837189405f1b07a6c9249d4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9842e6805ce84262b6bbe7da2b26772c">substPhysReg</a> (MCRegister Reg, const TargetRegisterInfo &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>substPhysReg - Substitute the current register with the physical register Reg, taking any existing SubReg into account. <a href="#a9842e6805ce84262b6bbe7da2b26772c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05dc03b6c9921f34aaa7a20c46589a95">setIsUse</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed8d139ece631812f972a8cc074adc55">setIsDef</a> (bool Val=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change a def to a use, or a use to a def. <a href="#aed8d139ece631812f972a8cc074adc55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10e708480cdc97c951368e06c13eac92">setImplicit</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a82683fccdef8a5ef772ef03277aee7">setIsKill</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a42c85bd86c6ca4554e27d33c3f798">setIsDead</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab979122f21b7fa46d3d2d9b21983068b">setIsUndef</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48bcf9eb66f880de8e7f4d0fcc8af320">setIsRenamable</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133a1aff6f7f6a9ea4f641adc88a120d">setIsInternalRead</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fcb795c017b82c1a259882b060ddc06">setIsEarlyClobber</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab986279c9e6cf7ba9afd4c7da198bacf">setIsDebug</a> (bool Val=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b28a85f818b49d8806c150b8a5b4f7">getImm</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e05cd075864928ae65e1751fdc346e">getCImm</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee59c647052fc9557561e596681da3c0">getFPImm</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e64b633278df75c699e6b98ce15031">getMBB</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa68daaf8d7b773d012887c92c2023ce">getIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcdaab1a4c3134b8f80aa74cabeb970">getGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f5b10f666acf5a0cddd5ac8302d0b8">getBlockAddress</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af155da145e58791956c5e922e900fcb3">getMCSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac9865fa1ab348b64b4366cfe103f74">getInstrRefInstrIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082167d36582dece9770d881292f5cf6">getInstrRefOpIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c30c92aa9995b0cc70bfe60294ff65">getCFIIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad21d94ca6aa512e357a993e0e85a921e">getIntrinsicID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d32d967ac31c4e6149c2adb89aa947">getPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a622dee2e5d865699df4407bd0bdbf903">getShuffleMask</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af624ff47eaa512dbe23866accb3837c1">getOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the offset from the symbol in this operand. <a href="#af624ff47eaa512dbe23866accb3837c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab59b255f78cd503133d032152a41d105">getSymbolName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c45ed93ec219927c08e0a8fb77c94d3">clobbersPhysReg</a> (MCRegister PhysReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clobbersPhysReg - Returns true if this RegMask operand clobbers PhysReg. <a href="#a7c45ed93ec219927c08e0a8fb77c94d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6876d59aeec5bc210b359fbdcf6c1ad">getRegMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRegMask - Returns a bit mask of registers preserved by this RegMask operand. <a href="#ae6876d59aeec5bc210b359fbdcf6c1ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b31bc5eda8ac4aeadf920d47aa6df0">getRegLiveOut</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRegLiveOut - Returns a bit mask of live-out registers. <a href="#a19b31bc5eda8ac4aeadf920d47aa6df0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b590606040d1c856a1d43aa0680364">getMetadata</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2feaa1c69335c6b9028076cd68c7a5f5">setImm</a> (int64_t immVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae70dd97002db997dfc96303fa9e6971">setCImm</a> (const ConstantInt *CI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e326b0a22f9a7042019531da7987ccd">setFPImm</a> (const ConstantFP *CFP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a> (int64_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc99c3c37896879abad49e7254a2fb8">setIndex</a> (int Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a71dbedaff60bd7c648f0192c7184b0">setMetadata</a> (const MDNode *MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c47183dc58b861a7b12c97f0a40312b">setInstrRefInstrIndex</a> (unsigned InstrIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d16082ca624c29bb20bc0671d48408">setInstrRefOpIndex</a> (unsigned OpIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e9c9e8ef7cbb6c4aa89a38f21decfa">setMBB</a> (MachineBasicBlock *MBB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c5f27bf78b4d1ce93378885811bf54">setRegMask</a> (const uint32_t *RegMaskPtr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets value of register mask operand referencing Mask. <a href="#a34c5f27bf78b4d1ce93378885811bf54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace13d14a3578b2a7e81a5db41bbfde77">setIntrinsicID</a> (Intrinsic::ID IID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1d6b6ca5842fa071bf1cb3510e1d0ba">setPredicate</a> (unsigned Predicate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a> (const MachineOperand &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this operand is identical to the specified operand except for liveness related flags (isKill, isUndef and isDead). <a href="#ad7f2dc64214551418f486026ffc95fa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b39ecfd6793534206dbb095b0d464c7">ChangeToImmediate</a> (int64_t ImmVal, unsigned TargetFlags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ChangeToImmediate - Replace this operand with a new immediate operand of the specified value. <a href="#a7b39ecfd6793534206dbb095b0d464c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4355c32a39876f8305ede47c1d7220ff">ChangeToFPImmediate</a> (const ConstantFP *FPImm, unsigned TargetFlags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ChangeToFPImmediate - Replace this operand with a new FP immediate operand of the specified value. <a href="#a4355c32a39876f8305ede47c1d7220ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80025569f9c67b220c8938482944bbda">ChangeToES</a> (const char *SymName, unsigned TargetFlags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ChangeToES - Replace this operand with a new external symbol operand. <a href="#a80025569f9c67b220c8938482944bbda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e996ed26eacbf3033314b3df58b133">ChangeToGA</a> (const GlobalValue *GV, int64_t Offset, unsigned TargetFlags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ChangeToGA - Replace this operand with a new global address operand. <a href="#a83e996ed26eacbf3033314b3df58b133">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dcd3550374d734c49f2f09cfe59d92e">ChangeToBA</a> (const BlockAddress *BA, int64_t Offset, unsigned TargetFlags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ChangeToBA - Replace this operand with a new block address operand. <a href="#a8dcd3550374d734c49f2f09cfe59d92e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f6582318ed3f4d326b0d115316f7f0">ChangeToMCSymbol</a> (MCSymbol *Sym, unsigned TargetFlags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ChangeToMCSymbol - Replace this operand with a new MC symbol operand. <a href="#a62f6582318ed3f4d326b0d115316f7f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b9c3d91aaffb22e0119f3467694b69">ChangeToFrameIndex</a> (int Idx, unsigned TargetFlags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace this operand with a frame index. <a href="#a13b9c3d91aaffb22e0119f3467694b69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67cc3c894d3231db9636847712fa3171">ChangeToTargetIndex</a> (unsigned Idx, int64_t Offset, unsigned TargetFlags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace this operand with a target index. <a href="#a67cc3c894d3231db9636847712fa3171">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937dbc7794a81ea51dc91c03feb931bc">ChangeToDbgInstrRef</a> (unsigned InstrIdx, unsigned OpIdx, unsigned TargetFlags=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace this operand with an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Reference. <a href="#a937dbc7794a81ea51dc91c03feb931bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a> (Register Reg, bool isDef, bool isImp=false, bool isKill=false, bool isDead=false, bool isUndef=false, bool isDebug=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ChangeToRegister - Replace this operand with a new register operand of the specified value. <a href="#a9404d5d9e4be534bb544777aae216691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a1f57ce725829ceacb0068b4b5f2d2a">getTargetIndexName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTargetIndexName - If this <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> is a TargetIndex that has a name, attempt to get the name. <a href="#a2a1f57ce725829ceacb0068b4b5f2d2a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65fa704e5b121d106599a9960707edf5">removeRegFromUses</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79f20db4cc2c9c940a70ce458fe8890a">isOnRegUseList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isOnRegUseList - Return true if this operand is on a register use/def list or false if not. <a href="#a79f20db4cc2c9c940a70ce458fe8890a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8435daf56f7cb3a39fdfc76a9f58ac">RegNo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ad6db209d25c087f43741d35624da5">OffsetLo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b57b956f719162c8705ae7eea7aa3e">OpKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OpKind - Specify what kind of operand this is. <a href="#a17b57b956f719162c8705ae7eea7aa3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32671810a5f107fb242fc6abfc4b0a96">SubReg_TargetFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subregister number for MO_Register. <a href="#a32671810a5f107fb242fc6abfc4b0a96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fce8abfb67dd7904f0a3444cdf9bb7d">TiedTo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TiedTo - Non-zero when this register operand is tied to another register operand. <a href="#a1fce8abfb67dd7904f0a3444cdf9bb7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecfd30fa29d989489c5a50a5e9aab397">IsDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsDef - True if this is a def, false if this is a use of the register. <a href="#aecfd30fa29d989489c5a50a5e9aab397">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4958e654888d9088cff368f6413ff602">IsImp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsImp - True if this is an implicit def or use, false if it is explicit. <a href="#a4958e654888d9088cff368f6413ff602">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80877a58aaa58d3e92c40dd2b0573442">IsDeadOrKill</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsDeadOrKill For uses: IsKill - Conservatively indicates the last use of a register on this path through the function. <a href="#a80877a58aaa58d3e92c40dd2b0573442">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc30536b123c1473f15916bec3f1946">IsRenamable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable()</a>. <a href="#a4bc30536b123c1473f15916bec3f1946">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cda16cd0cf564882565648b77ad8669">IsUndef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsUndef - True if this register operand reads an "undef" value, i.e. <a href="#a4cda16cd0cf564882565648b77ad8669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9adece572aa84b7c3eaa96d784f21b94">IsInternalRead</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsInternalRead - True if this operand reads a value that was defined inside the same instruction or bundle. <a href="#a9adece572aa84b7c3eaa96d784f21b94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900f9d28f7f2f45cdcfd85203b5061c1">IsEarlyClobber</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsEarlyClobber - True if this MO_Register 'def' operand is written to by the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> before all input registers are read. <a href="#a900f9d28f7f2f45cdcfd85203b5061c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a360a7ff322871610ec595a28ad3e42f8">IsDebug</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsDebug - True if this MO_Register 'use' operand is in a debug pseudo, not a real instruction. <a href="#a360a7ff322871610ec595a28ad3e42f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/classes/llvm/machineoperand">llvm::MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03a6af3f4880fdb7cd89dc8e7d8b32d7">SmallContents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SmallContents - This really should be part of the Contents union, but lives out here so we can get a better packed struct. <a href="#a03a6af3f4880fdb7cd89dc8e7d8b32d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6174e85d459bd1e9329d42e15dcffc6">ParentMI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParentMI - This is the instruction that this operand is embedded into. <a href="#ae6174e85d459bd1e9329d42e15dcffc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union llvm::MachineOperand::ContentsUnion</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac077ebcc4f9c6402953a003d041083cf">Contents</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c59687e1086bf24ffa307eaee13c3d3">printSubRegIdx</a> (raw_ostream &amp;OS, uint64_t Index, const TargetRegisterInfo *TRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a subreg index operand. <a href="#a2c59687e1086bf24ffa307eaee13c3d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bdc6bcbf7eec4329ba1b6c91ff776d8">printTargetFlags</a> (raw_ostream &amp;OS, const MachineOperand &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print operand target flags. <a href="#a3bdc6bcbf7eec4329ba1b6c91ff776d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04079051720988fb6801f962d034e03">printSymbol</a> (raw_ostream &amp;OS, MCSymbol &amp;Sym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> as an operand. <a href="#af04079051720988fb6801f962d034e03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c42d0e762a9efb66e50b7f349ee4207">printStackObjectReference</a> (raw_ostream &amp;OS, unsigned FrameIndex, bool IsFixed, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print a stack object reference. <a href="#a2c42d0e762a9efb66e50b7f349ee4207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91a415f70087b68402bb454cc1b8fa18">printOperandOffset</a> (raw_ostream &amp;OS, int64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the offset with explicit +/- signs. <a href="#a91a415f70087b68402bb454cc1b8fa18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf41c1517148f1b067536a43623d6a6b">printIRSlotNumber</a> (raw_ostream &amp;OS, int Slot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print an IRSlotNumber. <a href="#aaf41c1517148f1b067536a43623d6a6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ecf5483b94e2bb72967b80cc2008d2">clobbersPhysReg</a> (const uint32_t *RegMask, MCRegister PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clobbersPhysReg - Returns true if this RegMask clobbers PhysReg. <a href="#ae4ecf5483b94e2bb72967b80cc2008d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd1f4d5c1460886c4aa983a2027d944">getRegMaskSize</a> (unsigned NumRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns number of elements needed for a regmask array. <a href="#a9fd1f4d5c1460886c4aa983a2027d944">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab09679b541a6ba1219b3602569847364">CreateImm</a> (int64_t Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7a07b4efeaec2afcb83a6551b38441">CreateCImm</a> (const ConstantInt *CI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd605d7476194cf38e7ef6d2c57391a">CreateFPImm</a> (const ConstantFP *CFP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c351dad09a71aa08e1d85c67ae6e53">CreateReg</a> (Register Reg, bool isDef, bool isImp=false, bool isKill=false, bool isDead=false, bool isUndef=false, bool isEarlyClobber=false, unsigned SubReg=0, bool isDebug=false, bool isInternalRead=false, bool isRenamable=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38d24646cd711efc334aee49919cdf5">CreateMBB</a> (MachineBasicBlock *MBB, unsigned TargetFlags=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda3f1971b3e44709267be818ffd3035">CreateFI</a> (int Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe6fe7948d0ae093aba94381c73ed67">CreateCPI</a> (unsigned Idx, int Offset, unsigned TargetFlags=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3137f95a28140bba664c03c2f350870">CreateTargetIndex</a> (unsigned Idx, int64_t Offset, unsigned TargetFlags=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3700e1a41d8d584dc6e1720b803b2f6">CreateJTI</a> (unsigned Idx, unsigned TargetFlags=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace112d8a86396bd55e99738cd41005b6">CreateGA</a> (const GlobalValue *GV, int64_t Offset, unsigned TargetFlags=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2871c33d3a1264270d23ec72b71f1399">CreateES</a> (const char *SymName, unsigned TargetFlags=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ad3b0e833c44eb432854df8e3bff6a">CreateBA</a> (const BlockAddress *BA, int64_t Offset, unsigned TargetFlags=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c01d756ca363aef75429d61d21c0c14">CreateRegMask</a> (const uint32_t *Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CreateRegMask - Creates a register mask operand referencing Mask. <a href="#a4c01d756ca363aef75429d61d21c0c14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5416f0631d02c0c4404b906af9e3be9">CreateRegLiveOut</a> (const uint32_t *Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a903091abda5acf43af8ade829181b9b4">CreateMetadata</a> (const MDNode *Meta)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a081ab7d53b85dfd7a2f8609689147393">CreateMCSymbol</a> (MCSymbol *Sym, unsigned TargetFlags=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5cfdca0e0de9a0c79714b57b290e8a5">CreateDbgInstrRef</a> (unsigned InstrIdx, unsigned OpIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf19eb005905508319869685dda19ec">CreateCFIIndex</a> (unsigned CFIIndex)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7cf8fdf7e933b17b3fdf1d49b67e195">CreateIntrinsicID</a> (Intrinsic::ID ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a985d3c6d580d9dad7efe3129606150ae">CreatePredicate</a> (unsigned Pred)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab261a066a6f63f72c705a1d7a40e56de">CreateShuffleMask</a> (ArrayRef&lt; int &gt; Mask)</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> class - Representation of each machine instruction operand.</p>


<p>This class isn't a POD type because it has a private constructor, but its destructor must be trivial. Functions like <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">MachineInstr::addOperand()</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a557ce2bfb3c946e43d65d750b2537987">MachineRegisterInfo::moveOperands()</a>, and MF::DeleteMachineInstr() depend on not having to call the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> destructor.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a2a1b2e7b0a13eacf3c015e95ce495360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned char</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Artificial kinds for <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> usage.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_Empty<a id="a2a1b2e7b0a13eacf3c015e95ce495360a9b8362015d356f203a0512e9bafc5ab6"></a></td>
<td class="doxyEnumItemDescription"> (= MO_Last + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_Tombstone<a id="a2a1b2e7b0a13eacf3c015e95ce495360a8880d3d0cf278e4d37a791a975cc17cd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1000 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### MachineOperandType {#af269b990800f72c7cf535c407e8e639b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineOperand::MachineOperandType : unsigned char</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_Register<a id="af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_Immediate<a id="af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6"></a></td>
<td class="doxyEnumItemDescription">Immediate operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_CImmediate<a id="af269b990800f72c7cf535c407e8e639ba5cc9e17457a92caa963ed784d83f6233"></a></td>
<td class="doxyEnumItemDescription">Immediate &gt;64bit operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_FPImmediate<a id="af269b990800f72c7cf535c407e8e639bac4edc21072344f5aafa2a8f307c78b81"></a></td>
<td class="doxyEnumItemDescription">Floating-point immediate operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_MachineBasicBlock<a id="af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> reference</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_FrameIndex<a id="af269b990800f72c7cf535c407e8e639ba97561985119c4a774e3ec6439240fa80"></a></td>
<td class="doxyEnumItemDescription">Abstract Stack Frame Index</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ConstantPoolIndex<a id="af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580"></a></td>
<td class="doxyEnumItemDescription">Address of indexed <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> in <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> Pool</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TargetIndex<a id="af269b990800f72c7cf535c407e8e639babb48fd8c9fa828e23f5d33f46cb0cbbb"></a></td>
<td class="doxyEnumItemDescription">Target-dependent index+offset operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_JumpTableIndex<a id="af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d"></a></td>
<td class="doxyEnumItemDescription">Address of indexed Jump Table for switch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ExternalSymbol<a id="af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119"></a></td>
<td class="doxyEnumItemDescription">Name of external global symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GlobalAddress<a id="af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3"></a></td>
<td class="doxyEnumItemDescription">Address of a global value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_BlockAddress<a id="af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013"></a></td>
<td class="doxyEnumItemDescription">Address of a basic block</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_RegisterMask<a id="af269b990800f72c7cf535c407e8e639ba48257b48932e88a230caff68469fd9f6"></a></td>
<td class="doxyEnumItemDescription">Mask of preserved registers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_RegisterLiveOut<a id="af269b990800f72c7cf535c407e8e639bac72cbca4074e0bc4a26afc03db602da5"></a></td>
<td class="doxyEnumItemDescription">Mask of live-out registers</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_Metadata<a id="af269b990800f72c7cf535c407e8e639babf35c1c1ff9daae15b2dff8efa224623"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> reference (for debug info)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_MCSymbol<a id="af269b990800f72c7cf535c407e8e639ba17c8e891dacb2adc4a2d0ee5b10d6e9f"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> reference (for debug/eh info)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_CFIIndex<a id="af269b990800f72c7cf535c407e8e639ba0270d8f468e7b92dafb486293ecf137d"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a> index</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_IntrinsicID<a id="af269b990800f72c7cf535c407e8e639ba9f104d16987b5384042276466fc2e003"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic">Intrinsic</a> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for ISel</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_Predicate<a id="af269b990800f72c7cf535c407e8e639ba3ab395cc24292a5e8e499e48f1553d94"></a></td>
<td class="doxyEnumItemDescription">Generic predicate for ISel</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ShuffleMask<a id="af269b990800f72c7cf535c407e8e639ba512cc7de4a9ee26228ed614f8447d760"></a></td>
<td class="doxyEnumItemDescription">Other IR <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> for ISel (shuffle masks)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DbgInstrRef<a id="af269b990800f72c7cf535c407e8e639ba87cf4128c65c3799c2189ceb3fb62bd3"></a></td>
<td class="doxyEnumItemDescription">Integer indices referring to an instruction+operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_Last<a id="af269b990800f72c7cf535c407e8e639baa7e0c2da671655aea81e9e8c35bcda37"></a></td>
<td class="doxyEnumItemDescription"> (= MO_DbgInstrRef)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DenseMapInfo&lt; MachineOperand &gt; {#a2b4eed935e1417aeaa14cf349c1165b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639baa7e0c2da671655aea81e9e8c35bcda37">MO_Last</a>.</p>

</div>
</div>

### hash\_value {#a5c94b329f3cec9f4fd23db1d208c0bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> hash_value overload.</p>


<p>Note that this includes the same information in the hash that isIdenticalTo uses for comparison. It is thus suited for use in hash tables which use that function for equality comparisons only. This must stay exactly in sync with isIdenticalTo above.</p>


<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="#aaee820701392c55ad54235d3d7201206">isDead</a>, <a href="#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">isDebug</a>, <a href="#a75eb135014670ce946e78739cdc9b51b">isDef</a>, <a href="#a4046212ebc647b17e811837ae4ea3afd">isKill</a>, <a href="#a1255befbcd6e034394681b1bcd3529ff">isUndef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### MachineInstr {#ae984860b88c448f0d8f7ac9b11077441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 991 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#ae984860b88c448f0d8f7ac9b11077441">MachineInstr</a>.</p>


<p>Referenced by <a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a>, <a href="#a9719077fcba2cd439e84897257a47bb0">getParent</a>, <a href="#af09f8d34639010d76d48d76754520158">getParent</a>, <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable</a> and <a href="#ae984860b88c448f0d8f7ac9b11077441">MachineInstr</a>.</p>

</div>
</div>

### MachineRegisterInfo {#ae42703e0d4c147a9765234011797f5dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#ae42703e0d4c147a9765234011797f5dd">MachineRegisterInfo</a>.</p>


<p>Referenced by <a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a>, <a href="#ae42703e0d4c147a9765234011797f5dd">MachineRegisterInfo</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="#aed8d139ece631812f972a8cc074adc55">setIsDef</a> and <a href="#a682ba82f42f7903d0000ffbb13ea3b57">setReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MachineOperand() {#a3363bdbc0d3161ceb70aa747d998e9af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineOperand::MachineOperand (<a href="#af269b990800f72c7cf535c407e8e639b">MachineOperandType</a> K)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addTargetFlag() {#ace845d7da04db4610b2d051c7b44e832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::addTargetFlag (unsigned F)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#adf62cb0814e5fb37775a82efbe6130aa">llvm::HexagonInstrInfo::immediateExtend</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aa50d150829937efa73527accf23a184d">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADgotAUTH</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>.</p>

</div>
</div>

### ChangeToBA() {#a8dcd3550374d734c49f2f09cfe59d92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToBA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> * BA, int64_t Offset, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ChangeToBA - Replace this operand with a new block address operand.</p>

<p>Declaration at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">MO_BlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a> and <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>.</p>

</div>
</div>

### ChangeToDbgInstrRef() {#a937dbc7794a81ea51dc91c03feb931bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToDbgInstrRef (unsigned InstrIdx, unsigned OpIdx, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace this operand with an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Reference.</p>

<p>Declaration at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#af269b990800f72c7cf535c407e8e639ba87cf4128c65c3799c2189ceb3fb62bd3">MO_DbgInstrRef</a>, <a href="#a0c47183dc58b861a7b12c97f0a40312b">setInstrRefInstrIndex</a>, <a href="#a20d16082ca624c29bb20bc0671d48408">setInstrRefOpIndex</a> and <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>.</p>

</div>
</div>

### ChangeToES() {#a80025569f9c67b220c8938482944bbda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToES (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * SymName, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ChangeToES - Replace this operand with a new external symbol operand.</p>

<p>Declaration at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">MO_ExternalSymbol</a>, <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a> and <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>.</p>

</div>
</div>

### ChangeToFPImmediate() {#a4355c32a39876f8305ede47c1d7220ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToFPImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * FPImm, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ChangeToFPImmediate - Replace this operand with a new FP immediate operand of the specified value.</p>


<p>If an operand is known to be an FP immediate already, the setFPImm method should be used.</p>


<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#af269b990800f72c7cf535c407e8e639bac4edc21072344f5aafa2a8f307c78b81">MO_FPImmediate</a> and <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>.</p>

</div>
</div>

### ChangeToFrameIndex() {#a13b9c3d91aaffb22e0119f3467694b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToFrameIndex (int Idx, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace this operand with a frame index.</p>

<p>Declaration at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#af269b990800f72c7cf535c407e8e639ba97561985119c4a774e3ec6439240fa80">MO_FrameIndex</a>, <a href="#aebc99c3c37896879abad49e7254a2fb8">setIndex</a> and <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### ChangeToGA() {#a83e996ed26eacbf3033314b3df58b133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToGA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, int64_t Offset, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ChangeToGA - Replace this operand with a new global address operand.</p>

<p>Declaration at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a> and <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### ChangeToImmediate() {#a7b39ecfd6793534206dbb095b0d464c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToImmediate (int64_t ImmVal, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ChangeToImmediate - Replace this operand with a new immediate operand of the specified value.</p>


<p>If an operand is known to be an immediate already, the setImm method should be used.</p>


<p>Declaration at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">MO_Immediate</a> and <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#abf7147087fcf4414651e62ff5de5234e">llvm::M68kRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#add5bf0fa8f9875c3f5eb238ca2eacff2">llvm::X86RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a2e94eaf8bec0e356a92dc822d30de554">llvm::X86RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadd4d87bae748ead46249f7a0841cfd5">llvm::rewriteARMFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#acb75d3ebfc904675aed50ee39f619373">llvm::ThumbRegisterInfo::rewriteFrameIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a35b932e3e318fc132ddc4eba034d9a12">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldImmWithOpSel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1f42f634cff46c0380f80cc600c19f3b">llvm::updateDbgValueForSpill</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### ChangeToMCSymbol() {#a62f6582318ed3f4d326b0d115316f7f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToMCSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ChangeToMCSymbol - Replace this operand with a new MC symbol operand.</p>

<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#af269b990800f72c7cf535c407e8e639ba17c8e891dacb2adc4a2d0ee5b10d6e9f">MO_MCSymbol</a> and <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>.</p>

</div>
</div>

### ChangeToRegister() {#a9404d5d9e4be534bb544777aae216691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, bool isDef, bool isImp=false, bool isKill=false, bool isDead=false, bool isUndef=false, bool isDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ChangeToRegister - Replace this operand with a new register operand of the specified value.</p>


<p>If an operand is known to be an register already, the setReg method should be used.</p>


<p>Declaration at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a>, <a href="#a9719077fcba2cd439e84897257a47bb0">getParent</a>, <a href="#aaee820701392c55ad54235d3d7201206">isDead</a>, <a href="#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">isDebug</a>, <a href="#a75eb135014670ce946e78739cdc9b51b">isDef</a>, <a href="#a4046212ebc647b17e811837ae4ea3afd">isKill</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a1255befbcd6e034394681b1bcd3529ff">isUndef</a>, <a href="#ae984860b88c448f0d8f7ac9b11077441">MachineInstr</a>, <a href="#ae42703e0d4c147a9765234011797f5dd">MachineRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">MO_Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0673c8aeb9b580e1be469133adba37e5">llvm::SIInstrInfo::legalizeOperandsVOP3</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a4cb529d6108d5dfdf8479ac3b03c9812">llvm::SIInstrInfo::legalizeOpWithMove</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ae803619fba0f2282f638ddd36ba004de">llvm::SIRegisterInfo::resolveFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>.</p>

</div>
</div>

### ChangeToTargetIndex() {#a67cc3c894d3231db9636847712fa3171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::ChangeToTargetIndex (unsigned Idx, int64_t Offset, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace this operand with a target index.</p>

<p>Declaration at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#af269b990800f72c7cf535c407e8e639babb48fd8c9fa828e23f5d33f46cb0cbbb">MO_TargetIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#aebc99c3c37896879abad49e7254a2fb8">setIndex</a>, <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a> and <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>.</p>

</div>
</div>

### clearParent() {#a800c03587b02047d71c6ba2f7b2193eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::clearParent ()</td>
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

<p>clearParent - Reset the parent pointer.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> copy constructor also copies ParentMI, expecting the original to be deleted. If a <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> is ever stored outside a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, the parent pointer must be cleared.</p>


<p>Never call <a href="#a800c03587b02047d71c6ba2f7b2193eb">clearParent()</a> on an operand in a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### clobbersPhysReg() {#a7c45ed93ec219927c08e0a8fb77c94d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::clobbersPhysReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
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

<p>clobbersPhysReg - Returns true if this RegMask operand clobbers PhysReg.</p>

<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="#ae4ecf5483b94e2bb72967b80cc2008d2">clobbersPhysReg</a> and <a href="#ae6876d59aeec5bc210b359fbdcf6c1ad">getRegMask</a>.</p>

</div>
</div>

### dump() {#a71453c9c9ea541dab5841a0b590d56ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineOperand::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 1037 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#aed1c1aa1329f36eef4940283a1d30859">rescheduleCanonically</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#a47c8a030926eca62aae974bb55ecd995">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::update</a>.</p>

</div>
</div>

### getBlockAddress() {#a94f5b10f666acf5a0cddd5ac8302d0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockAddress * llvm::MachineOperand::getBlockAddress ()</td>
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



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#abed9003622087a5bbddb7c19b6d02ce6">isBlockAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9189968ba471dec34e7806413bd019cd">llvm::MachineInstrBuilder::addDisp</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#aa96ff44598c6c508e109228e15ee8efc">llvm::LanaiMCInstLower::GetBlockAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#aa4b5f0a2f0b72c2a31bb11458f34a1b3">llvm::MSP430MCInstLower::GetBlockAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a5191842b97cefc259bf0689f9565310b">getMCSymbolForTOCPseudoMO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a7687092765d6f25890cefb856f35b881">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ac63e4c740efa7b5b4426caa0de190af6">llvm::M68kMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a153a3f96b2710ef9d924d8168a93482b">llvm::XtensaAsmPrinter::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kasmprinter/#a5474d7cf1a213163c8929c3189e2c166">llvm::M68kAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a1a6d908f749f40987c9bd895ef5c7849">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a8549db3c421967b14bad3b2e6ab53980">llvm::CSKYAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#a83c424197528aeade7d84bfc2be9b074">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a4e9f35f7c792ae53843a921999988ccb">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>.</p>

</div>
</div>

### getCFIIndex() {#a88c30c92aa9995b0cc70bfe60294ff65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::getCFIIndex ()</td>
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



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#abebd8c425a02eaa5470c40ac6c47c59b">isCFIIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### getCImm() {#a29e05cd075864928ae65e1751fdc346e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantInt * llvm::MachineOperand::getCImm ()</td>
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



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a32ea768fbb182d6bbe3ff85ae1eb7031">isCImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#ade8ad153c39e5550054c7873486dd21d">foldConstantsIntoIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#ac962fea3028517b39dcd1f4cff0c0112">foldImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a610c7b58032f5eac1b06aa0c66cadb6a">llvm::generateGroupUniformInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#af999ef1c23f3644af392a2b4633fa8f7">getArrayComponentCount</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a0acd5ca4d907a57e5dc5ee9129dbbbc8">anonymous{Utils.cpp}::getCImmAsAPInt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a21c5d1a680afc10bd790c931150ac04f">anonymous{Utils.cpp}::getCImmOrFPImmAsAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96b61989528fd1061ce48169e066cd14">llvm::getConstFromIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#af6194171586d2f1e13eb57765226d48a">getImmedFromMO</a>, <a href="/web-llvm/docs/api/classes/llvm/gvscale/#a7c67c8f218bb124662af98cc5a846e98">llvm::GVScale::getSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/gstepvector/#a3d228390eddc89596585e7392a679792">llvm::GStepVector::getStep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aefeacc46707017018d95faf6751da717">llvm::LegalizerHelper::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad593882fdec13fdc1832fa224050666e">llvm::CombinerHelper::matchCombineUnmergeConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a61326cd6384971e828511e500b3367c6">processSwitchesConstants</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### getFPImm() {#aee59c647052fc9557561e596681da3c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantFP * llvm::MachineOperand::getFPImm ()</td>
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



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#afcb818bd3e34498f8f72ca555a36d5eb">isFPImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a21c5d1a680afc10bd790c931150ac04f">anonymous{Utils.cpp}::getCImmOrFPImmAsAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblydebugvaluemanager-cpp/#a0101767bf77660a28c873b7b06c2756e">isSameScalarConst</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a297f161b2970f693a98a4bf30c7eb630">llvm::LegalizerHelper::lowerFConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad593882fdec13fdc1832fa224050666e">llvm::CombinerHelper::matchCombineUnmergeConstant</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### getGlobal() {#a0fcdaab1a4c3134b8f80aa74cabeb970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue * llvm::MachineOperand::getGlobal ()</td>
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



<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab0d1155c8c38e84cbe387998fd2e517e">isGlobal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9189968ba471dec34e7806413bd019cd">llvm::MachineInstrBuilder::addDisp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a392dd12827c5ede927d490ccc16f38ab">llvm::BTFDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a0c5eda02c50a11f3dde025afe0675b6e">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::EmitTlsCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae7810a05a90e7fc6d13fa85c0242ab5f">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::getAdjustedFasterLocalExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#aa85a26f5f6b24110a2388e4726cdd282">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ad067184df5d0a7ed4aabb4d359ccb4e6">llvm::AArch64MCInstLower::GetGlobalAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfmcinstlower/#a7a480fc3efe55d6851672d2af88e342f">llvm::BPFMCInstLower::GetGlobalAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#a15dd1c3e4be01f26e04912feff6f36df">llvm::LanaiMCInstLower::GetGlobalAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a89624709f3eb37e3202214ca83d133af">llvm::MSP430MCInstLower::GetGlobalAddressSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a5191842b97cefc259bf0689f9565310b">getMCSymbolForTOCPseudoMO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#aaa9fafc42db7a667c344ce753b989101">GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#a094b53ae338bc1ed10ec35facf8e07b0">llvm::M68kMCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a731bb8307207186d81b2a7353f21f199">getTOCEntryTypeForMO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a3b244792bc2277f0800d9e15c2eb935b">llvm::BTFDebug::InstLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectbranchtracking-cpp/#a708537fa3526cf7f988d3146a9af652b">IsCallReturnTwice</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblydebugvaluemanager-cpp/#a0101767bf77660a28c873b7b06c2756e">isSameScalarConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a349ac25a0317c2e30b66435a5bdede3d">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETFunPLTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a15c1137ef9bebbeafd1060405cb71242">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETTLSAddrAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#adaf899f496f2ac717a79e58b4e439058">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADauthptrstatic</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aa50d150829937efa73527accf23a184d">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADgotAUTH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a3cf266e359a05a56bd9533dff30b3e12">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a153a3f96b2710ef9d924d8168a93482b">llvm::XtensaAsmPrinter::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#acb4de1517ebc1f8095f87eef68f290f7">llvm::AVRMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ab6548436b77ac06129373db3d8e3dece">llvm::WebAssembly::mayThrow</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#a83c424197528aeade7d84bfc2be9b074">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a7ddd6d21450d4f2269de2ab98fc8db6b">llvm::AVRAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#ae59e1e8bb5482399317c14a3b41d81e7">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ab6f8e1481cddfd9f6c8b70c75f7450db">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac246ec9c6b316d2a71621ef3df914da9">llvm::ARMAsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a34e471aa6f0a6f1975d57f3aafc7b2e0">llvm::AsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ae9e91530b7f4d99adc7f3f43b35a00b9">queryCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/detectroundchange/#a23677a404e91b3491d158fb8b0ea3f49">llvm::DetectRoundChange::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#adc3ecee5ecd3f86b45e6779653ca10da">validateFunCall</a>.</p>

</div>
</div>

### getImm() {#a38b28a85f818b49d8806c150b8a5b4f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineOperand::getImm ()</td>
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



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a76f61c6784df6dc8402a8b9011041926">isImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9189968ba471dec34e7806413bd019cd">llvm::MachineInstrBuilder::addDisp</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a54891e94b588b8ba0ba2586547e17e31">llvm::R600InstrInfo::addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a52716532c3562bbe9c3fc343761c3c8a">llvm::SITargetLowering::AddMemOpInit</a>, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#ae5ced970396c0f7c3cb7644340597544">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::adjustCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d95c5a37b4d6002c70248107633b815">llvm::HexagonInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42caa499245638127d7d889ff5716066">llvm::buildBoolRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#aca2b6568c134ce283d74d23db8d6b665">llvm::R600InstrInfo::buildSlotOfVectorInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aab7185336f5a266b994341f14bc8faac">canCombineShiftIntoShXAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a364fb004e57163fc1a3e2adc754af9b1">canCompareBeNewValueJump</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a80ba8826b4f8e7008ae9453968ed35fa">canInstrSubstituteCmpInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#afb8b734da10672ff4ffc3ec7bf04ec1d">llvm::R600InstrInfo::clearFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a08a3820d71cd895d5c69478fad30fd10">collectInlineAsmInstrOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a19e16a0f3c37ba1524eb85c891bfa760">compareMachineOp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ac438bed7ae6afbb9ff9e0be02099ad0f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3c4c42f79d79638f6b67532d3f81df58">createPHIsForSelects</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a46b2b58b4eaac69bb5cf98a05b2ab1be">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::detectAndFoldOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a413489f8f91ace88c20648ec2aa8b776">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::detectAndFoldOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/arcframelowering/#a4689c1a05c58cd8e0dbb57bc84fdc8cf">llvm::ARCFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#a0ab2cc201e1521acab599966d10b815d">llvm::XCoreFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#abf7147087fcf4414651e62ff5de5234e">llvm::M68kRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a8a08ac1d3e9758e48d542db8b3fc10ce">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6203308c1da11d69cb3bd6c23b90b207">expandSHXDROT</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa8aa7be4bd12d2e18b08a87805017131">llvm::RISCVInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af3caca8b1c9e27890d57f5755dc142fe">llvm::MachineInstr::findInlineAsmFlagIdx</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a397a7d129e95cde7da2f0f4a33c82fd9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a4ffd0a0399bead8c2759b5487ea997c6">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingUpdateInsnBackward</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#afa5ee2f4a09f62ebe217673407877974">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingUpdateInsnForward</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a13ac240bf32d04a19ef44ba47f40407c">findRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a69a17a573c98c5ac8ff9fedcc9099807">fixupCalleeSaveRestoreStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a76635e63bbdb187ca4030f7570158552">fixupSEHOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#ac962fea3028517b39dcd1f4cff0c0112">foldImm</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a5278ce924df77790e6a938f5065ba5a0">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a3a67d4b5306c3571138e241d77393283">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#acf5910da93c4e01390c1e29b4a72836f">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldShiftedOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aba82e76518953661f6dcb009c73e1a1f">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcnt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a01f6c42979a72dd229c03417e00f7f96">getArgumentStackToRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a31b4fdfb5932b580324cad2befddf0d4">getArgumentStackToRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a4b49090437c0021f09fa86c3965bb855">getAS</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4a416f1e734b334b8868c3b728baaf4">llvm::HexagonInstrInfo::getBaseAndOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ac8e4876fffd2ceada8ef6428258d7236">llvm::HexagonInstrInfo::getBundleNoShuf</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#aa598b3407f82a894e4f5a82676e5bc43">llvm::ARMAsmPrinter::getCodeViewJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af668609d5285820d674d655ab3990c91">llvm::HexagonInstrInfo::getCompoundOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c64e87ab3dd6ef5ea0c229712f1fd63">llvm::X86InstrInfo::getConstValDefinedInReg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1743a67877bf4ba56d53b235d3573e0">llvm::TargetInstrInfo::getExtractSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a235a0e236caca418542d097c0f0fca9c">llvm::ARMBaseRegisterInfo::getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#adc210f7d04be558143f8a891c892e550">llvm::SIRegisterInfo::getFrameIndexInstrOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a6d97173b919e39b8f1648d50d167e8ce">getHWReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#af6194171586d2f1e13eb57765226d48a">getImmedFromMO</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6c1928eecc56a24a5a6d8bb211a0afb4">llvm::HexagonInstrInfo::getIncrementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractsubvector/#a4d73c6ddaba313a4f41e0fc1b16bb197">llvm::GExtractSubvector::getIndexImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertsubvector/#aa2e5c0f1932c6d84f43c0f2a7ca780eb">llvm::GInsertSubvector::getIndexImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8b94b1143638cb1b18d976bba0b0ec3a">llvm::MachineInstr::getInlineAsmDialect</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#abea536f043de7994bc9b67c634a7c879">llvm::TargetInstrInfo::getInsertSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abc8556ad731efc2f7a407169624d812e">llvm::ARMBaseInstrInfo::getInsertSubregLikeInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseregisterinfo-cpp/#ae4f8119e930e450734d4903391aca1fa">getLoadStoreOffsetSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a4870646ffc5b5a7d4425edd55d6f93de">llvm::X86InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a934f16bd434319b64e63ae8f622991ce">llvm::LanaiInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47bf073dca31bf981a1a425cf537454f">llvm::getNumSizeComponents</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a3dddf52f700258ac37fa137527588809">llvm::SPIRVGlobalRegistry::getOrCreateConsIntVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea5285dbe63b422dcaf313ec0fe7473d">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abea0d5a07369a9502280335b276b3ccb">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a584585671a7593c76cc4499d6d75791e">anonymous{PPCMIPeephole.cpp}::getPredicateToDecImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a47d74d7e9fe3fe56430321c2a238536d">anonymous{PPCMIPeephole.cpp}::getPredicateToIncImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aead7c7f29560bc0cfbfe9959f936b456">getRegImmPairPreventingCompression</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae26cac7943070f09b4d7fa667d1adf95">llvm::TargetInstrInfo::getRegSequenceInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ad864cdbeb2b8c6a7cf87d8141abc5735">llvm::SPIRVGlobalRegistry::getRegType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a61c12dc12b135090e87fcfb959c58f47">getSingleUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ae6f1cb7931164d888acd081fa41e6246">llvm::R600InstrInfo::getSrcs</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#acc4b9161e5bdda1e0f5482ad8b9a64ba">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#aaa5ecbb121a4af66e98e1ddbff7b925d">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a1cfc09d31eaed5d0ca0725d09e044b47">llvm::RISCV::hasEqualFRM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aea349efd44508e36429de592f1437b14">llvm::SIInstrInfo::hasModifiersSet</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8c161f5f015730ac6853c802c3693a41">llvm::MachineInstr::hasUnmodeledSideEffects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvextract-cpp/#a88486e318adbd7333b898816348c8e7c">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18dec717578f39bfcff50e325c2d27c5">llvm::isAArch64FrameOffsetLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a919a65c38470ee5665afa859cda18025">llvm::PPCInstrInfo::isADDIInstrEligibleForFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a75313c138825e233baef675bb1c5c43d">llvm::MipsInstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a4bfef92511266e23c47f58129e287b40">isAddressLdStPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a2510546173c41b2a0bd6c02fedacb656">isAddSub2RegAndConstOnePair</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aaf9df5fbb2543faa0659f9b31f907df9">llvm::MachineInstr::isConvergent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d31fe3409ec7fc543b0adda6fa9b5f9">isConvertibleLEA</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ad1c6e08944b4fbe61244afe2ca4b113d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::isCPEntryInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a31eb3e86e2c774c4c03267a7368cadf0">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::isCPEntryInRange</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a360c1f17e2f45595561f8b80c76dbf8e">anonymous{PPCMIPeephole.cpp}::isEqOrNe</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcndppcombine-cpp/#a2181ae65cf95609a855d58822f5ceb79">isIdentityValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae1d4c0d71423c8fa3d000f7518a4e8ae">llvm::PPCInstrInfo::isImmInstrEligibleForFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a10caa873ff6bab070fa0217d5402267b">llvm::SIInstrInfo::isInlineConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#ae32b2c05b1bcc5413b940dd7d4d5701e">isLdOffsetInRangeOfSt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#afb7db40b967a5d8798362bc1c818917b">isLiteralsPair</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a2baf5026a86db8c593fb7d67cce0a741">llvm::HexagonInstrInfo::isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcoptaddrmode-cpp/#a303e42b6e71e1993ab701f7f6f2d343f">isLoadStoreThatCanHandleDisplacement</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6b26bab239d68047b97e5785f802c183">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::isMatchingMovConstInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#a7ee076808f65d7b724d9a94d48b2cee8">isMatchingStartStopPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a7e62a05741edcd4375c97fd4906b419d">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::isOMod</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#ae773ebcbd5bb0d4b4dea1250877dc716">llvm::GIndexedLoad::isPre</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#a9720bac244d8ac1281ce92b11390d73b">llvm::GIndexedStore::isPre</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#aa1deebfd7340543a82ffa0e8303fd8a7">isRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp/#adf2ee57aa544018b7e0092782fe00170">isRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#a81d02aa4f2d890c694845de489bef4af">isRelevantAddressingMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#abac45c592b45439ab9adbc6eb936c6c4">isSafeToFoldImmIntoCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblydebugvaluemanager-cpp/#a0101767bf77660a28c873b7b06c2756e">isSameScalarConst</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a4eb4dcdccf96e4fd24c31db70617c00e">llvm::SPIRVGlobalRegistry::isScalarOrVectorSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e3efa3451510c4dd3b0360251dd5128">llvm::isScale</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6b98ba8c44d9287df1be03859570b589">llvm::MachineInstr::isStackAligningInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af8e19ecc6875baefa038d0b714d2313c">llvm::HexagonInstrInfo::isStoreToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a72864dd5479176074c3bbcc3b0e50c22">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerFAULTING_OP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a7687092765d6f25890cefb856f35b881">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arcmcinstlower/#ab69d76329fbcf34e06d1e1119fa8c0f5">llvm::ARCMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ac63e4c740efa7b5b4426caa0de190af6">llvm::M68kMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcinstlower/#a5d6f8b2290183d7b3ae500dfce8fbb94">llvm::MipsMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoremcinstlower/#a16bd2e3d32444031e5abc6a96d562314">llvm::XCoreMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#a34e3dd28fecb20679563d191667e9e9c">llvm::SystemZMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ae4bbe4c2ecf0ae95b3c4ffc3bb34ed07">llvm::XtensaAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#af3ec8e57004a88ea5cb892311c3c81ff">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a3cf266e359a05a56bd9533dff30b3e12">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a175c0b6f2f4c39ae659845dcef17f71b">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a010b554002b5c2fdbc6e2d2b64afedb9">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a50863928ef6e46cfbe213995fd4974c2">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#a8022309e0fcca527f4a1a49b8a8ba922">llvm::LoongArchAsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aeb5e4e41c7dda3b942168ed881fa1d13">llvm::SPIRV::make_descr_sampled_image</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afe1802220ee7c164e882ade3d80f1845">llvm::MachineInstr::mayFoldInlineAsmRegOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a682028ac4a06c9e3550fa8e6e1909fa9">llvm::MachineInstr::mayLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinescheduler-cpp/#a069f6bd5e8ca662cfbeeb43f90a5a97a">mayOverlapWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a0810cb27406ba2cd135a1a2166b08366">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeNarrowZeroStores</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a84ac77d42a2a87cb7ed8f4d401bfede7">anonymous{DelaySlotFiller.cpp}::Filler::needsUnimp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ae97bb6b91cff3e18475ab68012287cc2">llvm::SystemZInstrInfo::prepareCompareSwapOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#aa4f40e89e6342970562321ecb4439596">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#abd31e9ad15d84356f971b4c2340bbbd0">llvm::LoongArchAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kasmprinter/#a5474d7cf1a213163c8929c3189e2c166">llvm::M68kAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a84d173786dab5c71b14eef5140521e07">llvm::MipsAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#a2ad9f20f96b8ee1142e75c4e7a5a9c9d">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a1a6d908f749f40987c9bd895ef5c7849">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a83f305aeeb35f8c2272405b7357059f2">llvm::AMDGPUAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6cff8e6e40904c8170d57f5307f73c20">llvm::ARMAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af865b91965a6c4e1082d1510228db5b5">llvm::AsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a8549db3c421967b14bad3b2e6ab53980">llvm::CSKYAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#ae87b9efb9db9ad27a0f5f7d753ce45fd">llvm::LoongArchAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a163b3801bc893a415f20cc091f7a246a">llvm::MipsAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#ab3b56dc8749765fe615f325594493167">llvm::WebAssemblyAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#ae3bd1981fefcc9dadf49e90b2feef3be">llvm::X86AsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a73fc85686d9e85551578bd41142dbb93">llvm::MipsAsmPrinter::printFCCOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#a83c424197528aeade7d84bfc2be9b074">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#adc984afaf62b041cceff164e14cdb889">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a94ccb5d36399ea8c01c40c8c28123454">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a4e9f35f7c792ae53843a921999988ccb">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a7ddd6d21450d4f2269de2ab98fc8db6b">llvm::AVRAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aec3f83e468ca215a70dda2742816745c">llvm::HexagonAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzshorteninst-cpp-/systemzshorteninst/#a38b3d652a50cfafb01e63dca05a1f489">anonymous{SystemZShortenInst.cpp}::SystemZShortenInst::processBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a51b6112b4ae42ce9cd677fcb2bb1af19">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::processSeqRegInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a664436e80e651ce40c1abcf063d58fa9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::promoteLoadFromStore</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a260e4fa04b4392ed7de8a9202292a2ca">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#abbda87d0f5c41ed3eca00b354a53417d">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ae803619fba0f2282f638ddd36ba004de">llvm::SIRegisterInfo::resolveFrameIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a5536577e4a955f5327410bda9cf3e7ed">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::reuseDUP</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a03c6876ed7ada0d971240509db503dc0">llvm::R600InstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#a1ee52a66badadfe0d31d88d614305f41">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86avoidstoreforwardingblocks-cpp-/x86avoidsfbpass/#a42cae0fd23182f6d2b4d4368a4ec21c3">anonymous{X86AvoidStoreForwardingBlocks.cpp}::X86AvoidSFBPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a983032106624c6c737b6d07bc4dcb3be">llvm::HexagonInstrInfo::setBundleNoShuf</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2f4e57397c15057e80f3edaeca9377f4">swapImmOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a64f165f45ca62b4d27bde48f484897da">llvm::SIInstrInfo::swapSourceModifiers</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1124ea4e69342296db6a2b6628121436">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryConstantFoldOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a5e1eb00d7eee7258726795f01822d491">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldOMod</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acab876eafd3f522831a5d002faecc72b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldZeroHighBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acd13e2195957a8e92e36d055dde1ffb8">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryToFoldACImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a7811bc75552090a55dea938981f76c7b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::tryToMergeLdStUpdate</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6c91e92748e13f94700487fcac689e60">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::tryToPairLdStInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a76c206acce516598d664c520bf1223a9">updateOperandIfDifferent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aae9fa37b9f18ba0e8f4c2342d4346494">updateOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#a5ab01ee14799ff74e4ff5e6c5ce8d50c">validateLifetimeStart</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97c94504ca3d3dcb826cd34ec463f98e">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsinstrinfo-cpp/#a1079ef998a5a34ef1215979a25a13ed3">verifyInsExtInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a6643db423ad018f2a7375b8f46e439af">llvm::RISCVInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a51ac6439b177bf76b27b1fd1a4f30ca3">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitCopy</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#ad457d12e54f0a38894c84aa6901838b5">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSvi64lane</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### getIndex() {#aaa68daaf8d7b773d012887c92c2023ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineOperand::getIndex ()</td>
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



<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5b401e780c5eed0aca1cfbf44d36a545">isCPI</a>, <a href="#ad7213433bd60dc33020246384dc18b9b">isFI</a>, <a href="#a8eb9bf17230a1c4329e26935f44d72eb">isJTI</a> and <a href="#ac0890848fb02b90b1f7956063bc61cb3">isTargetIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9189968ba471dec34e7806413bd019cd">llvm::MachineInstrBuilder::addDisp</a>, <a href="/web-llvm/docs/api/structs/llvm/arcregisterinfo/#aaf69a259c2c354f83b367585a37bb14d">llvm::ARCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoreregisterinfo/#a135008911313eaf0a75d1f7a960fe915">llvm::XCoreRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a11d81bc488e34bd6e757c2831ecc5e42">llvm::ARMAsmPrinter::emitJumpTableAddrs</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#aa925bb5b36e9ac03cfbe86ebcd70dd57">llvm::ARMAsmPrinter::emitJumpTableInsts</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a27e1e6e35a8e68da67d5090a6e9f4c0d">llvm::ARMAsmPrinter::emitJumpTableTBInst</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a977522c71b9c7099aa74222cc12bbf17">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::findInRangeCPEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a85299a5742cf6712729343b973727ab7">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::findInRangeCPEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ab5cf6bcc5a1eea788ee5fcc95ea36a8f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::findLongFormInRangeCPEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#a483622360cc22b780b2586da54e48bf9">llvm::LanaiMCInstLower::GetConstantPoolIndexSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#adcac670465a74316ab31a2a168fb8378">llvm::MSP430MCInstLower::GetConstantPoolIndexSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a7b7cfffc907bc917405db5fcb6f58170">llvm::XtensaAsmPrinter::GetConstantPoolIndexSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a7b4dfdd596d675a34ee339b581424255">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a5077615197d034930b58d221032e96f0">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::getCPEAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1562d024e0f385ec92982cd3493001d7">getJumpTableIndexFromAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#ac99087a74e4d732bcf2147e27f1d3b3f">llvm::LanaiMCInstLower::GetJumpTableSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#af31cf7c6a33e5b2cc57085902bc0c436">llvm::MSP430MCInstLower::GetJumpTableSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#aabfc3c15972060a4ce1c13aea0b6fba7">llvm::XtensaAsmPrinter::GetJumpTableSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a5191842b97cefc259bf0689f9565310b">getMCSymbolForTOCPseudoMO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp/#a43f5859dde0766edb4f29aa13b5fb2cb">getStartOrEndSlot</a>, <a href="#a2a1f57ce725829ceacb0068b4b5f2d2a">getTargetIndexName</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#aa196bdc78cb3ed0506c143e872923858">hasSameBaseOpValue</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a2baf5026a86db8c593fb7d67cce0a741">llvm::HexagonInstrInfo::isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a75d714113557721ffd5bd3d06dc79642">llvm::SIInstrInfo::isSGPRStackAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#afb5a8099c7351303ef337ec57d5e8e24">llvm::SIInstrInfo::isStackAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af8e19ecc6875baefa038d0b714d2313c">llvm::HexagonInstrInfo::isStoreToStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#ab55c74c151c09190ab2204e33e77b299">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerHardenedBRJumpTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a7687092765d6f25890cefb856f35b881">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ac63e4c740efa7b5b4426caa0de190af6">llvm::M68kMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa2b80c1201a1baeb6ee4466e970957ba">llvm::AArch64FrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a420e13f932ebcdd50a90e807d5e5674f">llvm::SystemZELFFrameLowering::orderFrameObjects</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a4e9f35f7c792ae53843a921999988ccb">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aec3f83e468ca215a70dda2742816745c">llvm::HexagonAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### getInstrRefInstrIndex() {#a3ac9865fa1ab348b64b4366cfe103f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::getInstrRefInstrIndex ()</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad04e186512436ffdefdb16ed8aaea57a">isDbgInstrRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>.</p>

</div>
</div>

### getInstrRefOpIndex() {#a082167d36582dece9770d881292f5cf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::getInstrRefOpIndex ()</td>
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



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad04e186512436ffdefdb16ed8aaea57a">isDbgInstrRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>.</p>

</div>
</div>

### getIntrinsicID() {#ad21d94ca6aa512e357a993e0e85a921e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID llvm::MachineOperand::getIntrinsicID ()</td>
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



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a44f92ba840149cc7f75e38279341257a">isIntrinsicID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a1511e75a5fe8384a21552151b86eac3b">llvm::AArch64GISelUtils::extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/classes/llvm/gintrinsic/#a5fa14f1396039c08f7b64717bdc2b830">llvm::GIntrinsic::getIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>.</p>

</div>
</div>

### getMBB() {#a57e64b633278df75c699e6b98ce15031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MachineOperand::getMBB ()</td>
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



<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#afe1784e242ce66da6029b3a681896bd2">isMBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#ac2fc7f2c8237332f8b99c6e88af1b678">addIncomingValuesToPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa61674464afddf4b2a24ab65f3833233">llvm::AArch64InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a36c56da02f10d527ab7084e5d172d1d4">llvm::HexagonInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1a1c9931dc5cfff031352bf6a5c7c3ff">llvm::MipsInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstrinfo/#ac741087fd882a50ae09491bdaebcaad9">llvm::NVPTXInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aedb2f85719d229f0c9bc62ab1d17e918">llvm::PPCInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a086f43049b2d52208b7727be22f5e604">llvm::R600InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#ab2592d528f736ade8f940d8b80c8d040">llvm::SparcInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ab536cb6776e394559d7109c0d6840c2e">llvm::VEInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a092553d9bd8edd039d855fb411c6d887">llvm::XCoreInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#ac205677cbd92cecf1a6fcddb4798a12d">llvm::XtensaInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a51f54f2b0fd916f4c01b600905180782">llvm::AArch64InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afa907eb6ba127a5f4167f5a1671efed0">llvm::CombinerHelper::applyOptBrCondByInvertingCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#af6522321d1fc294742102bbee0779b62">BBIsJumpedOver</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsconstantislandpass-cpp/#af6522321d1fc294742102bbee0779b62">BBIsJumpedOver</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyconstantislandpass-cpp/#a69f0bf266f1e42f9d65ec549a6481ba6">bbIsJumpedOver</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#ad73f79350d54fe535469c4a148943e3a">anonymous{EarlyIfConversion.cpp}::SSAIfConv::canConvertIf</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#a561e8197481b2a01d7f75fd567c7801e">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a6e8a4f85c8a56769ce682ff88d5b60f1">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4aadfbe4795304e72a1a7be77ac88be7">findLoopComponents</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3e3daf4218b791b2796b808627b7f864">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#afa8ce195c40d446fbe801e412cbd4634">llvm::HexagonInstrInfo::getDotNewPredJumpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/gphi/#a4e1601b459e7cb36d7a623f500595600">llvm::GPhi::getIncomingBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a963b0137d2dd388aadbfb0e132a6000f">anonymous{PPCMIPeephole.cpp}::getIncomingRegForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#af30efc6374f891c0dd222ed8610919fd">llvm::PeelingModuloScheduleExpander::getPhiCanonicalReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a61c12dc12b135090e87fcfb959c58f47">getSingleUnwindDest</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#a094b53ae338bc1ed10ec35facf8e07b0">llvm::M68kMCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#aaec6e6ec16a011ef89299012d0dbe146">getTargetMBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp/#a3b1b9803f5e070a03a99018fc737babb">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-combinerhelper-cpp-/#abe36a8462243713bdada68a3fc16ee47">anonymous{CombinerHelper.cpp}::InsertInsnsWithoutSideEffectsBeforeUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a8e7acd0466662074bd2486d1964cd173">insertPHI</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a72864dd5479176074c3bbcc3b0e50c22">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerFAULTING_OP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a153a3f96b2710ef9d924d8168a93482b">llvm::XtensaAsmPrinter::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab40d01e80ca225a11dcdb8adbf4e843a">llvm::CombinerHelper::matchOptBrCondByInvertingCond</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a2a11298ee3a7cfcfa678f8b9a3df20db">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::moveAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#ab3b56dc8749765fe615f325594493167">llvm::WebAssemblyAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#a83c424197528aeade7d84bfc2be9b074">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#adc984afaf62b041cceff164e14cdb889">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a4e9f35f7c792ae53843a921999988ccb">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a7ddd6d21450d4f2269de2ab98fc8db6b">llvm::AVRAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aec3f83e468ca215a70dda2742816745c">llvm::HexagonAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a134a21189d056b81b80d0cdf01ef8c46">llvm::MachineBasicBlock::replacePhiUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86flagscopylowering-cpp/#a9d9c7bebc5b5d451511265937418ed6a">splitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#ac47046162deb21d43512581afc16fa7c">updatePHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a87e58e9d24983c7890c502fbe731f950">verifyCFIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97c94504ca3d3dcb826cd34ec463f98e">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyInlineAsm</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### getMCSymbol() {#af155da145e58791956c5e922e900fcb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::MachineOperand::getMCSymbol ()</td>
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



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a143ff82a16da33c626da4949180e6b1f">isMCSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsasmprinter-cpp/#a487192753b68b0e4380e9d999a5b1549">emitDirectiveRelocJalr</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a7687092765d6f25890cefb856f35b881">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ac63e4c740efa7b5b4426caa0de190af6">llvm::M68kMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>.</p>

</div>
</div>

### getMetadata() {#a57b590606040d1c856a1d43aa0680364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MDNode * llvm::MachineOperand::getMetadata ()</td>
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



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7bce8907b3cea3c34b9eeac6480bc955">isMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a819a79471317d350cbad8cfe9ad1c98e">llvm::getMachineInstrType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>.</p>

</div>
</div>

### getOffset() {#af624ff47eaa512dbe23866accb3837c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::MachineOperand::getOffset ()</td>
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

<p>Return the offset from the symbol in this operand.</p>


<p>This always returns 0 for ExternalSymbol operands.</p>


<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abed9003622087a5bbddb7c19b6d02ce6">isBlockAddress</a>, <a href="#a5b401e780c5eed0aca1cfbf44d36a545">isCPI</a>, <a href="#ab0d1155c8c38e84cbe387998fd2e517e">isGlobal</a>, <a href="#a143ff82a16da33c626da4949180e6b1f">isMCSymbol</a>, <a href="#a7c5f0ef161b5b4dedad2e9aac9fcfee7">isSymbol</a> and <a href="#ac0890848fb02b90b1f7956063bc61cb3">isTargetIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9189968ba471dec34e7806413bd019cd">llvm::MachineInstrBuilder::addDisp</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp/#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#adaf899f496f2ac717a79e58b4e439058">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADauthptrstatic</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aa50d150829937efa73527accf23a184d">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADgotAUTH</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a55859f4a9f64b42f225c2f6c63212be5">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfmcinstlower/#ad8be4aad3f7a33a52b5c40cff98b5206">llvm::BPFMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#a9bdd6ed65ae27d68d065f712e0d281de">llvm::LanaiMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ab8310eee0e086d64c49733dd9da4171b">llvm::M68kMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a8520755e983a50f3c24f91e0f8e06d03">llvm::MSP430MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a153a3f96b2710ef9d924d8168a93482b">llvm::XtensaAsmPrinter::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#a5edb97651738551635eb05cc3f9fa77c">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#acb4de1517ebc1f8095f87eef68f290f7">llvm::AVRMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a48efbf9c526eceb30f721ea086dc98fd">llvm::AArch64MCInstLower::lowerSymbolOperandCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ae4b8638e074c6af2301cd209d3d2021c">llvm::AArch64MCInstLower::lowerSymbolOperandMachO</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#ab3b56dc8749765fe615f325594493167">llvm::WebAssemblyAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#ae59e1e8bb5482399317c14a3b41d81e7">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ab6f8e1481cddfd9f6c8b70c75f7450db">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac246ec9c6b316d2a71621ef3df914da9">llvm::ARMAsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a34e471aa6f0a6f1975d57f3aafc7b2e0">llvm::AsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### getOperandNo() {#a0c893675dfd5d1b1e4aea1e8211217c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MachineOperand::getOperandNo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the index of this operand in the instruction that it belongs to.</p>

<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5574b8f058874009cab01e055a44338a">llvm::MachineInstr::getOperandNo</a> and <a href="#a9719077fcba2cd439e84897257a47bb0">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machinetracemetrics-cpp-/datadep/#aa00496b615b9f981c925d33e5c6b54e2">anonymous{MachineTraceMetrics.cpp}::DataDep::DataDep</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#a3d2780b84e165c084f2f392888704a54">getIntegerExtensionOperandEEW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#af957d09b67e374fee8d9cffe19567c3d">getOperandInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#a61b87789dd3c00261742915fc160c69b">getOperandLog2EEW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a3dfd6a2f7a029b96610f42e270317cdb">isCandidateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp/#adecd11022a5f472b5ad0682bd79f479a">isCrossCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a601c42a582df16aaa8a045ec741ebe4a">llvm::SIInstrInfo::isInlineConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a47667f6ac9bbf55b4aa5442354af468d">llvm::SIInstrInfo::isInlineConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#ae22fa2cc6eb289646143ffc4e1a7f3c2">isMaskOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a61053e705b1b4e91859a6c2ed7a60b64">llvm::M68kInstrInfo::isPCRelRegisterOperandLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#a49256459b23d14e1c9152db9b10ece75">isVectorOpUsedAsScalarOp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a23855b574f5790880e0cdfc2b6b39aad">llvm::SIInstrInfo::legalizeOperandsFLAT</a>, <a href="/web-llvm/docs/api/classes/llvm/deadlanedetector/#a0507a9e0fb3ad8b5cbe21a6f19c8714c">llvm::DeadLaneDetector::transferUsedLanes</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a17772fd1beeccd740ec6412abad098f9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldPhiAGPR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#abc6f852e8fc908af6cd1f502743a0b28">vectorPseudoHasAllNBitUsers</a>.</p>

</div>
</div>

### getParent() {#a9719077fcba2cd439e84897257a47bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::MachineOperand::getParent ()</td>
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

<p>getParent - Return the instruction that this operand belongs to.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#ae984860b88c448f0d8f7ac9b11077441">MachineInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">llvm::AnalyzeVirtRegInBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aaaf972edd3d60e198b996c65e05c4a5a">llvm::MachineInstr::changeDebugValuesDefReg</a>, <a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a185de6f70a894f044801931c4956150d">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp/#a70e2de8376b84c468e8a5762fda4c419">createDeadDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinetracemetrics-cpp-/datadep/#aa00496b615b9f981c925d33e5c6b54e2">anonymous{MachineTraceMetrics.cpp}::DataDep::DataDep</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a349ccb69c0901c3188afbce59873f56b">findSingleRegUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ac9883c9ec5baeee39d4215b9af8e0a70">findUseBetween</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a23c3c91648996442b88f0c53cf1415d8">getFoldableImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#af6194171586d2f1e13eb57765226d48a">getImmedFromMO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseregisterinfo-cpp/#ae4f8119e930e450734d4903391aca1fa">getLoadStoreOffsetSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a215563f9d37c9c9cab3f9e52f0507209">getMFIfAvailable</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/valuetracker/#a71b7cfbae828b6dc34596c7019ab029f">anonymous{PeepholeOptimizer.cpp}::ValueTracker::getNextSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#af957d09b67e374fee8d9cffe19567c3d">getOperandInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#a61b87789dd3c00261742915fc160c69b">getOperandLog2EEW</a>, <a href="#a0c893675dfd5d1b1e4aea1e8211217c7">getOperandNo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a904f484cd7cfe20a0e7673399c88cc3c">llvm::MachineInstr::insert</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-combinerhelper-cpp-/#abe36a8462243713bdada68a3fc16ee47">anonymous{CombinerHelper.cpp}::InsertInsnsWithoutSideEffectsBeforeUse</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a857ec99c61bfc201bb60525234551102">llvm::SIInstrInfo::isIgnorableUse</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a601c42a582df16aaa8a045ec741ebe4a">llvm::SIInstrInfo::isInlineConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a47667f6ac9bbf55b4aa5442354af468d">llvm::SIInstrInfo::isInlineConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abecccbf97c3a9d0be384e6c639fcf2dc">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp/#ac0001ca0e66f6badb71cca036c24cab0">isNoReturnDef</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a61053e705b1b4e91859a6c2ed7a60b64">llvm::M68kInstrInfo::isPCRelRegisterOperandLegal</a>, <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#a7e0bd1bbeb16dc218b79375aadf77b1d">isTiedToNotUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#a49256459b23d14e1c9152db9b10ece75">isVectorOpUsedAsScalarOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kerneloperandinfo/#a0780dfcb3a517ab51f5f973dae9e1edb">anonymous{ModuloSchedule.cpp}::KernelOperandInfo::KernelOperandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstextenders-cpp-/hexagonconstextenders/#acd5e632a52045addda819968f7c4dc8f">anonymous{HexagonConstExtenders.cpp}::HexagonConstExtenders::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstoperand/#a2cbad20def038be01a642ef5bc5a0360">anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::potentialToConvert</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwasrcoperand/#a7f2319e3588e98e73879945fdc62b25b">anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::potentialToConvert</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a185f9311cecc76ba862f1420c20db158">printAsmMRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a76421690e64ee4e01b59f44c74fa9c20">printAsmVRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a00d35e3f57b5ac9407316ad4161c83e4">llvm::SPIRVGlobalRegistry::recordFunctionDefinition</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a3bbf276657ebe5de723f93bc95498b6f">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::removeRedundantLIs</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a290f07593ec0820655db5efe88422c44">llvm::CombinerHelper::replaceRegOpWith</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a2fd58763bac8cd7e011630ae06d14656">anonymous{MachineVerifier.cpp}::MachineVerifier::report</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a176bfede6f24b05b428c0f42f9d95390">scavengeVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a781bc33cca080506ba19a20d66c1c255">llvm::RegBankSelect::tryAvoidingSplit</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5a81ca548cc88df15a58aed766bdd890">llvm::FastISel::tryToFoldLoad</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#abc6f852e8fc908af6cd1f502743a0b28">vectorPseudoHasAllNBitUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a015233fe94a42e2294533334811ab899">llvm::MachineRegisterInfo::verifyUseList</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### getParent() {#af09f8d34639010d76d48d76754520158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr * llvm::MachineOperand::getParent ()</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#ae984860b88c448f0d8f7ac9b11077441">MachineInstr</a>.</p>

</div>
</div>

### getPredicate() {#af0d32d967ac31c4e6149c2adb89aa947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::getPredicate ()</td>
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



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4039d2f36755814cb173552df270bddc">isPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a321f2dfbd709348cfd0e1ab66cf0b62c">llvm::CombinerHelper::applyNotCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/ganycmp/#a9b5d6b8ad9231f5abbb1bb86497c0133">llvm::GAnyCmp::getCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>.</p>

</div>
</div>

### getReg() {#ac0035d7c1c860501c877c20e6e93297b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::MachineOperand::getReg ()</td>
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

<p>getReg - Returns the register number.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad0a79b68db2b8f84f92b1ee24352b3ce">llvm::MachineInstr::addRegisterDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af7f7e5eb5b55add81ed8fe39ac83b9c2">llvm::MachineRegisterInfo::addRegOperandToUseList</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a0f958ee7dc9902af4093fe8fabbabd6e">llvm::ScheduleDAGInstrs::addVRegUseDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6cdddfff71264f7e1e744fdea34085d3">llvm::ARMTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/phielimination-cpp/#a126f327d0727647f3daa7cf0da944f9e">allPhiOperandsUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab359f8ff91954b23a1e8366666e59cbb">llvm::AArch64InstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">llvm::AnalyzeVirtRegInBundle</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a2b46e1c0d91a5df6f3f45d573f833b1a">llvm::CombinerHelper::applyBuildFnMO</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac2377979438dcdab9e664ccd5f975dac">llvm::CombinerHelper::applyCombineDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a00301689820a26a9f3b438f6dece6ef0">llvm::CombinerHelper::applyCombineExtendingLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac91aca84eade26acea192464a9cfcde8">llvm::CombinerHelper::applyCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afe9d6cb97689cb5efb1a5b8f9dc68ea0">llvm::CombinerHelper::applyCombineUnmergeZExtToZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#ae26a44292d42d576349e053e3497c18f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa09e8f13910a43ba1b8edc182c7a212c">llvm::CombinerHelper::applyExtendThroughPhis</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a1c822a5562978796947ffc71a1e9a1b0">anonymous{AArch64PostLegalizerLowering.cpp}::applyExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aa20f5e3d228e0f30d2f3c53c53cc6c93">llvm::AMDGPUCombinerHelper::applyFoldableFneg</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#afc5c7be6a4fbeb70b07dde19d8ebc2fd">llvm::RegBankSelect::applyMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afa907eb6ba127a5f4167f5a1671efed0">llvm::CombinerHelper::applyOptBrCondByInvertingCond</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ad8a483afeb99148394d2586c5601e441">llvm::CombinerHelper::applyShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvprelegalizercombiner-cpp-/#a99fb6c2c4ea3a52f8977eeb8d2c2f425">anonymous{SPIRVPreLegalizerCombiner.cpp}::applySPIRVDistance</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d95c5a37b4d6002c70248107633b815">llvm::HexagonInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#ab07fa640d6b044c04371e8cc8bde6a02">attemptDebugCopyProp</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#a5a71ccecb00de06004fb421a568dd7b4">llvm::CriticalAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aec0904aef5bec338f4fea047c49455aa">llvm::ARMBaseInstrInfo::breakPartialRegDependency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76a671b685940387f88a924858a371d4">llvm::SIInstrInfo::buildExtractSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a881c9e75128e7e943b6d8f33606ccc74">llvm::SPIRVGlobalRegistry::buildGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfe6e5ec3e8d8ad4632758a0af06b8f9">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a7bc05bcba45ed1e4e903c1c952d09178">buildRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#aca2b6568c134ce283d74d23db8d6b665">llvm::R600InstrInfo::buildSlotOfVectorInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-cpp/#a665946cb74a98ed20ca7e0acf68d9b03">buildSpirvTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpandermve/#a8b570f6c1b94d49245ad3cee2887acf3">llvm::ModuloScheduleExpanderMVE::canApply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a41d64a5fd52ca16e16ee50f916ab845a">canCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a8a77823ca1d474b22f9b923674749a14">canCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae77d286780a8c426db7adb6c10b9a643">canCombineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#ad73f79350d54fe535469c4a148943e3a">anonymous{EarlyIfConversion.cpp}::SSAIfConv::canConvertIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a2a5ba8caf566b63bea759399eb58927f">canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#acc9e7924e2ef2b569d74df940b3dc0fb">canEmitConjunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4ab4c0bfcb70883e983a325153b5a44e">llvm::HexagonInstrInfo::canExecuteInBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a848f5b2d82a5d809fe4785b96e6bdb95">canFoldCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a435084f5e140c85f72921239385f9edb">canRenameUntilSecondLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af848272aaea9ac1f976aaf56fd31cb8d">canRenameUpToDef</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae844768b9501609ab55c31b3c4f6ea5">llvm::SIInstrInfo::canShrink</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a9d84441ae7638d9c27873f5a3810cb88">castBufferRsrcArgToV4I32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a78249707a06ea5161d8c6bbb442ea46c">castBufferRsrcFromV4I32</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aaaf972edd3d60e198b996c65e05c4a5a">llvm::MachineInstr::changeDebugValuesDefReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#af2048f0f8425833d77baeb4baeadc779">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::checkMovImmInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#a148883092b4d2dfdc994bc095ec153d7">anonymous{PPCMacroFusion.cpp}::checkOpConstraints</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a084d504a7f8b42657e1c910ba098ad94">clearKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad4a32b52ea36d2c35a9860fe263d0574">llvm::MachineInstr::clearRegisterDeads</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad61dd8c3be8a7f284aa7ac8f2c8bca5b">llvm::MachineInstr::clearRegisterKills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6b1057a57ff0d013cd3a78bb69f43db2">cloneInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ad8ddb8460838860b8d1d38555049f08b">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::collectIncomingValuesFromPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a08a3820d71cd895d5c69478fad30fd10">collectInlineAsmInstrOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp/#aef8f01c925c0c7beb94976a8f86a9af1">collectRegDefs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8853b2033702691c17576d5acc430460">anonymous{PPCMIPeephole.cpp}::collectUnprimedAccPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxpeephole-cpp/#ae48b9308a21e92c2301831dfc8d75ac9">CombineCVTAToLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a19e16a0f3c37ba1524eb85c891bfa760">compareMachineOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac7d08af4bb81846173b6186f568fcc8b">llvm::RegBankSelect::computeMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#ac1e0d325060a529e2c20cc9eebc23351">ConsecutiveInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e6b3672f7d7a310e9b45dc48d464ee8">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/regbankselecthelper/#ae56b2250d41c0820f12319e553d76084">RegBankSelectHelper::constrainRegBankUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ab8b249a6f01a1f333bc2bfbc6463251c">llvm::PPCInstrInfo::convertToImmediateForm</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#abe83de329645327b1d40bee0d304aff8">createCallWithOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/#ae5e50a6a8cb928fb34cd4fde19384381">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::createCRLogicalOpInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a8d1d93bb20bf72c7782cf68446e5bf9f">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::CreateFailCheckSequence</a>, <a href="/web-llvm/docs/api/classes/anonymous-armbaseinstrinfo-cpp-/armpipelinerloopinfo/#a2afe54a3f381a7c3f67db172f886d734">anonymous{ARMBaseInstrInfo.cpp}::ARMPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#afb8c24d6929051d24b35af1ef0550e54">llvm::ScheduleDAGInstrs::deadDefHasNoUse</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a46b2b58b4eaac69bb5cf98a05b2ab1be">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::detectAndFoldOffset</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8be157bc7b2bed40b10198e8b6a2bfcf">anonymous{PPCMIPeephole.cpp}::eligibleForCompareElimination</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a096fcb1d6b0da7425a8cc7dbb8ddd526">llvm::HexagonRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ab69231adafff5e2e89dfae5a21ba246b">emitIndirectDst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a071d8b84e530f1a6e725aea09fdc6407">emitIndirectSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aafc82eb49e1de126caa8907eaca9f46e">llvm::HexagonHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a182825202fb7b104e8e823825d4f2fb1">llvm::RISCVInstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#a12db326dc5ce11745051db706e75a3e0">eraseGPOpnd</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kinstrinfo-cpp/#afee96ecb8e8588a068aa3c1743b63352">Expand2AddrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acd9a409ba62041c36090fe42bfdf16d7">llvm::M68kInstrInfo::ExpandCCR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a74416995ef682b11e2df10e9a94d4402">llvm::M68kInstrInfo::ExpandMOVEM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acf82a3fa2657200bf3068a0273939229">llvm::M68kInstrInfo::ExpandMOVSZX_RM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a0ea5ffee956540dce97bf5d067051c6b">llvm::M68kInstrInfo::ExpandMOVSZX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a6388048852214c02aa209e16f10b588a">llvm::M68kInstrInfo::ExpandMOVX_RR</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#ab4228d105bd5b126170c562e6f8acdfd">llvm::M68kInstrInfo::ExpandPUSH_POP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a9dec32763bff61fb024d352592596f99">expandSMEPPRToZPRSpillPseudos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#a1511e75a5fe8384a21552151b86eac3b">llvm::AArch64GISelUtils::extractPtrauthBlendDiscriminators</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a274a99ee4eac8fbc5e112f80cd84c71e">llvm::PPCInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kframelowering-cpp/#ae82cb5b8bd04147ce1ebe063f447c718">findDeadCallerSavedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4aadfbe4795304e72a1a7be77ac88be7">findLoopComponents</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a9b60466dac10eaf9d8a8b4f955b77b24">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingConstOffsetBackward</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a397a7d129e95cde7da2f0f4a33c82fd9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmovemerger-cpp-/riscvmovemerge/#a2c18d64812a6868d590fb3f27d938312">anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::findMatchingInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6b4a3c0105d0c1835725eaa33867b526">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a4ffd0a0399bead8c2759b5487ea997c6">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingUpdateInsnBackward</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#afa5ee2f4a09f62ebe217673407877974">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingUpdateInsnForward</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a13ac240bf32d04a19ef44ba47f40407c">findRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#ad60e02442ef62d5d7f19fd7f73aa0508">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::findRegistersToSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6f42d93281a5cbf5360f836c09166c06">llvm::MachineInstr::findRegisterUseOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyexplicitlocals-cpp/#a125b8a4a3a9e2088275b98ed22e2378c">findStartOfTree</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4dc06d4fb42d48a6ade1958f76334826">llvm::ScheduleDAGInstrs::fixupKills</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#ade8ad153c39e5550054c7873486dd21d">foldConstantsIntoIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a9eb43774a0046a364f5c45f94576bc43">llvm::PPCInstrInfo::foldFrameOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#ac962fea3028517b39dcd1f4cff0c0112">foldImm</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a5278ce924df77790e6a938f5065ba5a0">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a3a67d4b5306c3571138e241d77393283">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a52300ffc2cad932b8451cdd3ae41a470">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#acf5910da93c4e01390c1e29b4a72836f">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldShiftedOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a4862e12e65a868264ab84a2252104dda">llvm::RISCVInstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6875e5a149ffdf299b10e8f969d379d4">llvm::TargetInstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a9a34bef43457f75fa60fb4186af2ef">llvm::generateImageSizeQueryInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#af64fc386f3fc81f753830641399254b9">genFNegatedMAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad7dacfdd99d94fce20ccc2450bf5eb76">genFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6893512d8a2c2aaf9d6758440d1bc583">genMaddR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a012040151268735433380829e4ef0dcd">genSubAdd2SubSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#af999ef1c23f3644af392a2b4633fa8f7">getArrayComponentCount</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#ac0bde568b3078ec6c6fce434997dcfe5">llvm::GIndexedLoad::getBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#a697bae68deffc62d869832a6a9d618a8">llvm::GIndexedStore::getBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertsubvector/#a7f5a93aed60bbe1badb84e5e06f46b31">llvm::GInsertSubvector::getBigVec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee97b28988a36d015094f659294ef99d">llvm::getBlockStructInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#a5f4001f2227b1489a7588246ba7c8d54">getCallTargetRegOpnd</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af668609d5285820d674d655ab3990c91">llvm::HexagonInstrInfo::getCompoundOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a627e6584be398e0555f4b38d8f26f546">llvm::SIRegisterInfo::getConstrainedRegClassForOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c64e87ab3dd6ef5ea0c229712f1fd63">llvm::X86InstrInfo::getConstValDefinedInReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc8c7c7ca66d38ff9fd8c34f64a0fd4e">llvm::getDefInstrMaybeConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a827d52327fbe1bd7bf22242e7c18847d">getDefRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/ganyload/#a4fe5ff0257f5b8749cbe223b848b2570">llvm::GAnyLoad::getDstReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#aa4a6851394161d4ede155772de827f68">llvm::GIndexedLoad::getDstReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertvectorelement/#adedb063efa4089b32b852b1fc2df03e2">llvm::GInsertVectorElement::getElementReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1743a67877bf4ba56d53b235d3573e0">llvm::TargetInstrInfo::getExtractSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#afc76a889f289a0e841775d80aa0338ba">llvm::ARMBaseInstrInfo::getExtractSubregLikeInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a817d92911624542113807dc07a46bfb5">llvm::MachineInstr::getFirst2RegLLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a31012ec441c425a3eeb652d31ab0a8ab">llvm::MachineInstr::getFirst3RegLLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a80edb692b5f12ebc13ea0c6558e2cc85">llvm::MachineInstr::getFirst4RegLLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1345402d2906eacc2db93c4bb59cf861">llvm::MachineInstr::getFirst5RegLLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0df98b068b652d32c3529381db723b9c">llvm::PPCInstrInfo::getFMAPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a56884e76d8fbf3b9f59ed904d50ba245">getFMULPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a337903856769965870a905f37f63790d">getFNEGPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a23c3c91648996442b88f0c53cf1415d8">getFoldableImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#aa6438c766cdab5c1e26d802ef9ad14ff">getFPReg</a>, <a href="/web-llvm/docs/api/structs/llvm/machineinstrexpressiontrait/#a3344d356ddabbe21340a4b078300a789">llvm::MachineInstrExpressionTrait::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#abd3b799a5199979babb67c1211b73c7c">llvm::ARMBankConflictHazardRecognizer::getHazardType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#af6194171586d2f1e13eb57765226d48a">getImmedFromMO</a>, <a href="/web-llvm/docs/api/classes/llvm/gphi/#a75d330f905b8fad10f17f93c05dca4bb">llvm::GPhi::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#ad8f4a9eb24c60d6e6d0102d17ae180ae">llvm::GExtractVectorElement::getIndexReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertvectorelement/#a8bb403957bec222954776225dcb40117">llvm::GInsertVectorElement::getIndexReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ad23868fe0e42fbdb124476527f50ac03">getIndirectSGPRIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#abea536f043de7994bc9b67c634a7c879">llvm::TargetInstrInfo::getInsertSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abc8556ad731efc2f7a407169624d812e">llvm::ARMBaseInstrInfo::getInsertSubregLikeInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#af196b990f6f506c44a4512bad4a36cef">getInstReadLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/armregisterbankinfo/#af59ec25334715d44d5eecd8568b29e36">llvm::ARMRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8e8f884db0a3faadefc981023902a1ec">llvm::SIInstrInfo::getInstructionUniformity</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a643ff7dd8c287dd58e75cbe79556e74c">llvm::ScheduleDAGInstrs::getLaneMaskForMO</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinopcarryout/#abc631c430bcd8a73482dd4ea8495a38a">llvm::GBinOpCarryOut::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gsucmp/#aa63d83a3ebb133b4cb37bd2d1e72b8d0">llvm::GSUCmp::getLHSReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#acdf9051278b18a64c83cc047a3080de3">anonymous{LiveDebugVariables.cpp}::UserValue::getLocationNo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a819a79471317d350cbad8cfe9ad1c98e">llvm::getMachineInstrType</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#ad0d350086d0170ad8429e57516ba5a17">llvm::ReachingDefAnalysis::getMIOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#ae42ae7520e86040563aa828fc9d5eb91">getMopState</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#af58cbab9cb762f2d2a4baae6177e30e4">getNewSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/copyrewriter/#af6a7bff7d1f79439d9cef76fd17c6688">anonymous{PeepholeOptimizer.cpp}::CopyRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/extractsubregrewriter/#a79218c7fe32c8fb42e07cebb08c578e4">anonymous{PeepholeOptimizer.cpp}::ExtractSubregRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/insertsubregrewriter/#aae0a3466d999e3c2435e10e766335499">anonymous{PeepholeOptimizer.cpp}::InsertSubregRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/regsequencerewriter/#af67bc5de34066daeefa8468bc983e737">anonymous{PeepholeOptimizer.cpp}::RegSequenceRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/uncoalescablerewriter/#af703b6af11073fc6bb738c43fcbada3e">anonymous{PeepholeOptimizer.cpp}::UncoalescableRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fasttileconfig-cpp/#a10096b4ed26c2b9a8fe283a459e4d81e">getNumDefTiles</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#a55ae2aa029e53a42aeac16f01e0c42ad">llvm::GIndexedLoad::getOffsetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#a11b1c0ab42243c261e9876a66ee11d05">llvm::GIndexedStore::getOffsetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ab5db29ece2631cd6c9f36b99fe92feab">llvm::ARMBaseInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4cbbdd3795a958b1e24bd85cf48a0519">llvm::HexagonInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a836e5efd0e3634abca5e8a1c02ef6232">llvm::PPCInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abab34b1cb73af8519772979270773492">llvm::SPIRVGlobalRegistry::getOrCreateConstIntArray</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a8cdc39b963a62003cd157541feca56f6">llvm::SPIRVGlobalRegistry::getOrCreateOpTypeSampledImage</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a51539193cc8ad7ae2884993bbb57ddea">llvm::ARMBaseInstrInfo::getPartialRegUpdateClearance</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#af94193776566ea8e90fc662cb038b0a1">llvm::X86InstrInfo::getPartialRegUpdateClearance</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#af30efc6374f891c0dd222ed8610919fd">llvm::PeelingModuloScheduleExpander::getPhiCanonicalReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a6d986da977a884fc79751da79c4e6f84">llvm::SPIRVGlobalRegistry::getPointeeType</a>, <a href="/web-llvm/docs/api/classes/llvm/gloadstore/#a0a7fb170c5d3165c1a9f3cf5fee5b4ca">llvm::GLoadStore::getPointerReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a55bb47729cc153812bf4c00989460022">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::GetPoisonVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#a6825b86f34e17792a882f599423f5485">getRC32</a>, <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a09a1c19b999c807cb52c21541a2c7de4">llvm::PPCRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ab6e454de3dfa112cc7e30219ac7298cd">llvm::SPIRVGlobalRegistry::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aae4eaf548fa62f15dc35f4018fef3707">llvm::SIRegisterInfo::getRegClassForOperandReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a3cb505493f51b96cbb394d89b93f686e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::getRegSeqInit</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae26cac7943070f09b4d7fa667d1adf95">llvm::TargetInstrInfo::getRegSequenceInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aba7f60edec8e7b982c598aa278f9420c">llvm::ARMBaseInstrInfo::getRegSequenceLikeInputs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ad864cdbeb2b8c6a7cf87d8141abc5735">llvm::SPIRVGlobalRegistry::getRegType</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac3cfa17f907e7258d898433ddfeb3fbf">llvm::RegBankSelect::getRepairCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gbinopcarryout/#a9f92d09b678eb63420aade92877ee278">llvm::GBinOpCarryOut::getRHSReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gsucmp/#a0231b89d00ac00db99eabe02a0225aed">llvm::GSUCmp::getRHSReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp/#a894fb383cc3e3a326646b5f3366881d2">getSalvageOpsForTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/gsplatvector/#ac79651a4264897232305a8abf81dbe76">llvm::GSplatVector::getScalarReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshl/#aa8482d32667b4117740e52c87ff6c45a">llvm::GShl::getShiftReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#aef7abd9e585da4743700d2c04b17ab77">getShuffleComment</a>, <a href="/web-llvm/docs/api/classes/llvm/gfreeze/#a3eb22715cd9f29136f9d6f7ba914c5ef">llvm::GFreeze::getSourceReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gunmerge/#a5f5a5fac10a0aadbff8eb0ec3cad5b60">llvm::GUnmerge::getSourceReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshufflevector/#a54b06a5a5effc72c6bc4b9b678f20be2">llvm::GShuffleVector::getSrc1Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshufflevector/#a4ae3c15df3186decf42fd763ef386c43">llvm::GShuffleVector::getSrc2Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/gcastop/#afd9f4526a055452535916c9c12810415">llvm::GCastOp::getSrcReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gshl/#af0470ee08a8edb0aea1b769274cf853d">llvm::GShl::getSrcReg</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ae6f1cb7931164d888acd081fa41e6246">llvm::R600InstrInfo::getSrcs</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractsubvector/#a46b0ae0d1f1b432d5c49b1e0103cab23">llvm::GExtractSubvector::getSrcVec</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#aff059e4f5e8216de3172acd39a6e0ff8">anonymous{PPCMIPeephole.cpp}::getSrcVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertsubvector/#a2045dc53a7fe26b15fca8c2904955fa0">llvm::GInsertSubvector::getSubVec</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad64a5996fef41f1e035a44837da865c2">getTypeReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad526a98b9842792511d37f5499693349">llvm::X86InstrInfo::getUndefRegClearance</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#a34948b6b7734673470a3d7fcc5a16676">llvm::GIndexedStore::getValueReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gstore/#ab80d0571fdf63877734e0f7bea4e886b">llvm::GStore::getValueReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gextractvectorelement/#a9bdb58d595df6f79845de5cf0139ad8c">llvm::GExtractVectorElement::getVectorReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ginsertvectorelement/#a1e833adbe8c062dc441eb3426bad4390">llvm::GInsertVectorElement::getVectorReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7c6fd268e11e2eb6e8d13ed32b1820c">llvm::getVRegDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ca6bbc21c19a9a6b005aff44ca8562f">llvm::getVRegSubRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedload/#a863dae0fbf6415e6c7cf58ac82f348e7">llvm::GIndexedLoad::getWritebackReg</a>, <a href="/web-llvm/docs/api/classes/llvm/gindexedstore/#abf110cb21758b8ed3417e46417434b06">llvm::GIndexedStore::getWritebackReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a334e7c41df90efd700b045c03de6777d">anonymous{ARMLowOverheadLoops.cpp}::VPTState::hasImplicitlyValidVPT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#a801fcd2cb84f0d0292a77e675c7c492c">hasLiveThroughUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp/#a3454a39a1e2c87adcca0ddf016f3ca20">hasMoreUses</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab7919507c578187e698ff01a1f204478">llvm::RISCVInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6034cfb230c4698caa60bdc3a9bf209b">llvm::TargetInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a2f1cfe9c040112cbf97a025655d3595e">llvm::RISCVInstrInfo::hasReassociableSibling</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#aea784a4f9e9aba7792c23484e2498e8d">llvm::TargetInstrInfo::hasReassociableSibling</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a5523ffd2d5ced60566f3493c2b48e0e3">hasRegisterDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad890cb0ba6262569913be1269acbf590">llvm::MachineInstr::hasRegisterImplicitUseOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#aa196bdc78cb3ed0506c143e872923858">hasSameBaseOpValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#a181a7487eafd6c6972d51d10b2107101">anonymous{RISCVInsertVSETVLI.cpp}::hasUndefinedPassthru</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a76f8dfae3796fd187aebe3f8f60643ec">llvm::HexagonInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a38691dc780e36d270e9f13eeb4fdb28f">anonymous{DelaySlotFiller.cpp}::Filler::insertCallDefsUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa859694dc733dcc4def80843314a9666">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::insertCondBranchBefore</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaidelayslotfiller-cpp-/filler/#afca8ae34e03582f93e75d11b23cbe245">anonymous{LanaiDelaySlotFiller.cpp}::Filler::insertDefsUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a8c0efd377a713687b369602245dbe9da">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a75f3e392bd9cff57dcd444d521d7fd94">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a5c50c1e0000377affb5eec391c213df1">insertSEH</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagoncp/#afbd23f1436bf2680a83324a63b37dbe4">anonymous{HexagonRDFOpt.cpp}::HexagonCP::interpretAsCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a195a0fee60fb5a1164767ec13d9729dd">llvm::AArch64InstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a4b5fcf3c38734c224904ec0203c965b1">llvm::ARMBaseInstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a75313c138825e233baef675bb1c5c43d">llvm::MipsInstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a89651558e264c97ec3977357ce4f0422">llvm::RISCVInstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a58db20676cb0ff354eca34b86f0c3ab1">isAGPRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a32b9b3cc2b63db0558c672148f375cae">isArithmeticBccPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp/#a3dd013ff6aef799059f3caafe7f9b968">isBackwardPropagatableCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a596366d4034015c0668d2070e597425f">llvm::GIMatchTableExecutor::isBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmovemerger-cpp-/riscvmovemerge/#ac2bebd1f8090a2e93e2c53c4d206c5bc">anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::isCandidateToMergeMVSA01</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a1403d0f29e96c05811fe277c8c68eae6">llvm::WebAssembly::isChild</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a6fbf0d819e9a71ced3199693268238ce">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::isClamp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#aecef689b4ba2a5bf1d3609151f448180">llvm::AArch64GISelUtils::isCMN</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a37fa340555fb189bce42efadf42c5253">llvm::MachineInstr::isConstantValuePHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#aa737e66804d935143b89db74d5646610">isConstReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d31fe3409ec7fc543b0adda6fa9b5f9">isConvertibleLEA</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sipeepholesdwa-cpp-/#a2bc160bdefcc7e1d3000ac78dcec0e0d">anonymous{SIPeepholeSDWA.cpp}::isConvertibleToSDWA</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp/#adecd11022a5f472b5ad0682bd79f479a">isCrossCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb834744243c11cb677261382ac15bea">llvm::MachineInstr::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a791f9b87aba84585f9777360bb26d84b">llvm::AArch64InstrInfo::isExtendLikelyToBeFolded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a44896316bcf65958ba14a3afa8fa193f">isExtractHiElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#aef241765e05d84992ebe4133862b899d">isFIPlusImmOrVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#aea53813ca1c1efc9ef06b5b9844be967">isIdenticalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aab9a96f10af025498520e00ff044bec1">llvm::MachineInstr::isIdenticalTo</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#add5255eb40b106f13738476389bfa5a6">llvm::MachineInstr::isIdentityCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a857ec99c61bfc201bb60525234551102">llvm::SIInstrInfo::isIgnorableUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae1d4c0d71423c8fa3d000f7518a4e8ae">llvm::PPCInstrInfo::isImmInstrEligibleForFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#afe78f37f6711d1eba5a7066809cae1b6">isInvariantStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#aa5a8087086656299167f931f805778bb">isLdStSafeToCluster</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab65e8335ea0b5232a7f07f8fd5ec3566">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abecccbf97c3a9d0be384e6c639fcf2dc">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600packetizer-cpp-/r600packetizerlist/#ae14c145aa6237db91a7bca044488de25">anonymous{R600Packetizer.cpp}::R600PacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmasking-cpp/#a53203d01639150127e4a03f777068276">isLogicalOpOnExec</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ab34a636a3a33052e76df78342c72627e">llvm::SMSchedule::isLoopCarriedDefOfUse</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a78e274f7aa81fdeddac470d645c3c6e8">llvm::SwingSchedulerDAG::isLoopCarriedDep</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#ae22fa2cc6eb289646143ffc4e1a7f3c2">isMaskOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a6b26bab239d68047b97e5785f802c183">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::isMatchingMovConstInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#a7ee076808f65d7b724d9a94d48b2cee8">isMatchingStartStopPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#a342872157c6313a8196ae30b373f9f61">isMMSourceRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#ae235754dfc792615f66d369a52a1625a">isMMThreeBitGPRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#abed37e9eeb67324751569d54ac13c0ef">isNonFoldablePartialRegisterLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a7e62a05741edcd4375c97fd4906b419d">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::isOMod</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#aa29ae3958e21ba305518fbad7c6ec004">llvm::GIMatchTableExecutor::isOperandImmEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#a3b6f8318fa97ea96ea30725e31e85fea">isOperandKill</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a7cf619a6fa8097611add0bd3cc2014d8">isPromotableZeroStoreInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#aa1deebfd7340543a82ffa0e8303fd8a7">isRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiinstrinfo-cpp/#adf2ee57aa544018b7e0092782fe00170">isRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a5898b6ed934ad744eefecc5d5297a3a8">isRegInClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#a81d02aa4f2d890c694845de489bef4af">isRelevantAddressingMode</a>, <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a1c1669c081e93349baa5bcf3ca5aaae4">IsSafeAndProfitableToMove</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a2142c4566b7d15a35687f955d946a277">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::isSafetoMove</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a75d714113557721ffd5bd3d06dc79642">llvm::SIInstrInfo::isSGPRStackAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#afb5a8099c7351303ef337ec57d5e8e24">llvm::SIInstrInfo::isStackAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#adbb4dcc227f28ef32563170ce820d498">isSubRegOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#a6dd59c68c09f54df98dfea454a222fe1">isSVERegOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastpretileconfig-cpp/#ae94c5a52f65a4cd106e987ad131eddb2">isTileDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastpretileconfig-cpp/#a615f09a9d7f696517872c55ae51e0f58">isTileRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4475ef8d36797ed68e422e259b7b4cf">llvm::HexagonInstrInfo::isToBeScheduledASAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp/#a11329b543886f5ac685e48ab2d45ee6c">isTwoAddrUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#aa524a697f0c6f94cef4d7a1f48f856e9">isValidRegDefOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#a0ca5780a94eb690d0ccf6cdda9c16df9">isValidRegUseOf</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a809bcfaa5a36e8e145a700b3e0e21926">llvm::PPCInstrInfo::isValidToBeChangedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a544e5e236fec930c7f0478c3f6e3b43e">isVirtualRegisterOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a80ca145710cb63f6d1484dacf37a8620">isWaitInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kerneloperandinfo/#a0780dfcb3a517ab51f5f973dae9e1edb">anonymous{ModuloSchedule.cpp}::KernelOperandInfo::KernelOperandInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#aa48b853fae2f40e3e483078a944ab8d1">llvm::AArch64LegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a23855b574f5790880e0cdfc2b6b39aad">llvm::SIInstrInfo::legalizeOperandsFLAT</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad5c2911f44ee301ccf57ae61b7915b5a">llvm::SIInstrInfo::legalizeOperandsSMRD</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0673c8aeb9b580e1be469133adba37e5">llvm::SIInstrInfo::legalizeOperandsVOP3</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a68b7b9c491045c788173e83be1ba5d2b">llvm::TargetInstrInfo::lowerCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a72864dd5479176074c3bbcc3b0e50c22">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerFAULTING_OP</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a349ac25a0317c2e30b66435a5bdede3d">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETFunPLTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#ac5cfd4fb19000475fc0153c2301ab56b">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETGOTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ab74cde0c8282be6c158a967ff13642a3">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::LowerGETPCXAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a7687092765d6f25890cefb856f35b881">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arcmcinstlower/#ab69d76329fbcf34e06d1e1119fa8c0f5">llvm::ARCMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ac63e4c740efa7b5b4426caa0de190af6">llvm::M68kMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcinstlower/#a5d6f8b2290183d7b3ae500dfce8fbb94">llvm::MipsMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoremcinstlower/#a16bd2e3d32444031e5abc6a96d562314">llvm::XCoreMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#a34e3dd28fecb20679563d191667e9e9c">llvm::SystemZMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ae4bbe4c2ecf0ae95b3c4ffc3bb34ed07">llvm::XtensaAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a010b554002b5c2fdbc6e2d2b64afedb9">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a50863928ef6e46cfbe213995fd4974c2">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#a8022309e0fcca527f4a1a49b8a8ba922">llvm::LoongArchAsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/binaryop-match/#aa22431f74a092ef2095e5e7fdfa9e9c9">llvm::MIPatternMatch::BinaryOp_match&lt; LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/binaryopc-match/#a7a3bed68c87689c4510c602f959f32f0">llvm::MIPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/compareop-match/#afdb133294564dd07699c439079f2c1ee">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/ternaryop-match/#a0fd9be9076c83aab0325acd8d4ef55fd">llvm::MIPatternMatch::TernaryOp_match&lt; Src0Ty, Src1Ty, Src2Ty, Opcode &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/unaryop-match/#a03468639caa1fb6be4bb742a181faf81">llvm::MIPatternMatch::UnaryOp_match&lt; SrcTy, Opcode &gt;::match</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a597eabfac4d80feedf71d122bbaf4e00">llvm::CombinerHelper::matchAddOfVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a54d65481969f8d9628b5ee128c99212b">llvm::CombinerHelper::matchCombineFAddFMAFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a246c328def50bbd9e892666ae3fb1947">llvm::CombinerHelper::matchCombineFAddFpExtFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af73a2a8f01e0df7eb8908768292dd30e">llvm::CombinerHelper::matchCombineFAddFpExtFMulToFMadOrFMAAggressive</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#a5d07561addd0b024b31991b0d09c6beb">llvm::AMDGPUCombinerHelper::matchCombineFmulWithSelectToFldexp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ade46635032e4ec34657bc9b237d37e0b">llvm::CombinerHelper::matchCombineFSubFNegFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a4c9b7bf9027b6c116d92fbebd2ba8372">llvm::CombinerHelper::matchCombineFSubFpExtFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac4a2ebe747c416cbe4efb4b77ba2b588">llvm::CombinerHelper::matchCombineFSubFpExtFNegFMulToFMadOrFMA</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a570b6dfed72efec6554e992d5afdd1e4">llvm::CombinerHelper::matchCombineInsertVecElts</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adb530600a4235ed32fefcd44dbf454b4">llvm::CombinerHelper::matchCombineTruncOfShift</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa1cd7c807d2387bd9f8efe4a88cf1eb8">llvm::CombinerHelper::matchConstantFPOp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac975f07f5ebdceac6c93312485b74af2">llvm::CombinerHelper::matchConstantOp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a0f3bc0c5478dd84e0831b5d78a274b47">llvm::CombinerHelper::matchEqualDefs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a045bd704a82578777117625df4358b32">anonymous{AArch64PreLegalizerCombiner.cpp}::matchExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a6288bdc9c0864757a314ab233c31590d">anonymous{AArch64PostLegalizerLowering.cpp}::matchExtMulToMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a21a291953b9b99793faf8bea9286ebd7">llvm::CombinerHelper::matchExtractVecEltBuildVec</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a74c47491ee867baa1f14586d759342ee">anonymous{AArch64PostLegalizerCombiner.cpp}::matchExtractVecEltPairwiseAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a2a97e27cc61249c732f88ca2b63ce73f">llvm::CombinerHelper::matchExtractVectorElementWithBuildVectorTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3d2f7a0f835e800e04b1fae871054e01">llvm::CombinerHelper::matchExtractVectorElementWithDifferentIndices</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a8106e2049da0be5e2759557e0c7cd971">anonymous{AArch64PreLegalizerCombiner.cpp}::matchExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucombinerhelper/#aca13b2618c4733bb6b46c2667fbd847b">llvm::AMDGPUCombinerHelper::matchFoldableFneg</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae2bd5329e5726d560529de68df90503c">llvm::CombinerHelper::matchFreezeOfSingleMaybePoisonOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aab86990eacd037e1c72749c3342d410e">llvm::CombinerHelper::matchHoistLogicOpWithSameOpcodeHands</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#aafc3cb0155754ef1fb6ed53375e4d3dd">anonymous{PPCMacroFusion.cpp}::matchingRegOps</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a56ee7200c7a0fb8ed2b9f98288d83ff2">llvm::CombinerHelper::matchMulOfVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a59e682863250eb07290a348d548eee0d">llvm::CombinerHelper::matchNarrowBinopFeedingAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a2f87fb73ebb3f5d6d7e49e99fa478fa3">llvm::CombinerHelper::matchNonNegZext</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a846bbee244f8b3e7ec21bc20f002ed9f">llvm::CombinerHelper::matchOperandIsKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adf1110382dae21e5397a098cc5a08554">llvm::CombinerHelper::matchOperandIsUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3acff99aeccfa086e7fbef44df8c0ce1">llvm::CombinerHelper::matchPtrAddImmedChain</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9098323777f98b3dd53bef412554961c">llvm::CombinerHelper::matchSelectIMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5036ae118b8d8b9debc1c596eff93259">llvm::CombinerHelper::matchSextOfTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a33c6405fe05b24b5d3f9c0ec0ed7f9ae">llvm::CombinerHelper::matchShiftImmedChain</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8434510d79fe87971bb903ab82cc1fc3">llvm::CombinerHelper::matchShiftOfShiftedLogic</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5b5001e37af42df3e8202151fe08b3c9">llvm::CombinerHelper::matchShlOfVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac88c813e35b6d1a4966b0ee24a5c8b9a">llvm::CombinerHelper::matchSubOfVScale</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a12794dfd41dd116d9e295524d932f6c0">llvm::CombinerHelper::matchUnmergeValuesAnyExtBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a27942d2942b84e3453b75e3417def841">llvm::CombinerHelper::matchZextOfTrunc</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a1eab543e55a7220697eb4e72651e2e17">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeConstOffsetInsn</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmovemerger-cpp-/riscvmovemerge/#accee7cec1672950ec100570be21cce47">anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::mergePairedInsns</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp/#ad007531739421e7b54a41c3fefaefa4e">MIIsInTerminatorSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a25a4c14864c6f574bc99e19e15a8b4d2">llvm::LegalizerHelper::moreElementsVectorDst</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4da36cb65ef881f12fe1d40a47223a61">MoveVPNOTBeforeFirstUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a776834e825e7fd9cd90c27f7ace1d9d2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::needToBeConvertedToVALU</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#abc0f8152bb9c4cdd79a31196933bb5df">llvm::AArch64InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#afbc1088fd64459bec1157940aa59eb69">llvm::X86InstrInfo::optimizeLoadInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a55d733ab1cd738ca996fd3e415b59c99">llvm::RISCVInstrInfo::optimizeSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ab7cbed44cf5366935e93c0a0182dfd5f">llvm::CallLowering::parametersInCSRMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstoperand/#a2cbad20def038be01a642ef5bc5a0360">anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::potentialToConvert</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#aa4f40e89e6342970562321ecb4439596">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#aae9a08c74656cb725f4a193b38270780">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#abde207ef38a93406cc8cb0908d270969">llvm::ARMAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#afc0dd8f7a1ebe899a2cd3eb553610f49">llvm::CSKYAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#abd31e9ad15d84356f971b4c2340bbbd0">llvm::LoongArchAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kasmprinter/#a5474d7cf1a213163c8929c3189e2c166">llvm::M68kAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a84d173786dab5c71b14eef5140521e07">llvm::MipsAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a185f9311cecc76ba862f1420c20db158">printAsmMRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#a2ad9f20f96b8ee1142e75c4e7a5a9c9d">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a1a6d908f749f40987c9bd895ef5c7849">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a83f305aeeb35f8c2272405b7357059f2">llvm::AMDGPUAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6cff8e6e40904c8170d57f5307f73c20">llvm::ARMAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#abb1c33c814741adb78a9ff7f10ff3552">llvm::AVRAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a8549db3c421967b14bad3b2e6ab53980">llvm::CSKYAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a81e38a8f99bc74ae4acb4d135d1b7278">llvm::HexagonAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#ae87b9efb9db9ad27a0f5f7d753ce45fd">llvm::LoongArchAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a163b3801bc893a415f20cc091f7a246a">llvm::MipsAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#aafef1c064474b274f8515a78234f99e1">llvm::SystemZAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a76421690e64ee4e01b59f44c74fa9c20">printAsmVRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#a83c424197528aeade7d84bfc2be9b074">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#adc984afaf62b041cceff164e14cdb889">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a94ccb5d36399ea8c01c40c8c28123454">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a4e9f35f7c792ae53843a921999988ccb">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a7ddd6d21450d4f2269de2ab98fc8db6b">llvm::AVRAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aec3f83e468ca215a70dda2742816745c">llvm::HexagonAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#a83cbf55cc29b8e364bc11d81165caaed">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::processBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#af352e338e2b9a8cd58a97aca55d421e4">processNewInstrs</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a51b6112b4ae42ce9cd677fcb2bb1af19">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::processSeqRegInst</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a62a1e2af50ab6132cd2d8d168835ef57">llvm::PPCInstrInfo::promoteInstr32To64ForElimEXTSW</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a664436e80e651ce40c1abcf063d58fa9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::promoteLoadFromStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#aa3fe888e13e687c808085c0cfba933c3">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneValues</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a374fc9d9064a93ef8a408f269d02389d">llvm::MachineInstr::readsWritesVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/regbankselecthelper/#a9c19f0d81ecc0282828c546f12bc5b36">RegBankSelectHelper::reAssignRegBankOnDef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#ac1753e9184a776f25f017ac1022f2a13">TransferTracker::redefVar</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600optimizevectorregisters-cpp-/regseqinfo/#ada4ca4cc367bbafb748df1e73214d3f3">anonymous{R600OptimizeVectorRegisters.cpp}::RegSeqInfo::RegSeqInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a4c5b93703bfd35ff033b6fd30c2b8ee7">llvm::WebAssemblyAsmPrinter::regToString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#aeae677889401c02a8def9a0508e858c7">reinsertVectorIndexAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a744bd116065744fe9e1f41d4d63f87c0">llvm::ARMBaseInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a220e5ab986bbeae53290cfb49f913fed">llvm::X86InstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armconstantislandpass-cpp/#a68cd342c50f56c8da7e9c41ce92d14b1">RemoveDeadAddBetweenLEAAndJT</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#aea6bca2d194dea4aa5634cf5c394ebdc">llvm::MachineRegisterInfo::removeRegOperandFromUseList</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a536d28604beba413c49c1f731df008a7">llvm::LiveVariables::removeVirtualRegistersKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a40139f3ca5fa604f87136efa9ca611ca">llvm::RegBankSelect::RepairingPlacement::RepairingPlacement</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#aed1c1aa1329f36eef4940283a1d30859">rescheduleCanonically</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a5536577e4a955f5327410bda9cf3e7ed">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::reuseDUP</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a03c6876ed7ada0d971240509db503dc0">llvm::R600InstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kernelrewriter/#a2e7a99d381fd8c317ade905833ae3138">anonymous{ModuloSchedule.cpp}::KernelRewriter::rewrite</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a71a08885f7838dc5a544816a357e2ec7">llvm::MachineSSAUpdater::RewriteUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64collectloh-cpp-/aarch64collectloh/#a4bee2d3457dd2d22962d67c658644125">anonymous{AArch64CollectLOH.cpp}::AArch64CollectLOH::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64storepairsuppress-cpp-/aarch64storepairsuppress/#ab876191f2b64955413fe0423a672c3b2">anonymous{AArch64StorePairSuppress.cpp}::AArch64StorePairSuppress::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-liverangeshrink-cpp-/liverangeshrink/#ab45325824e5e6352ef04ee2d7bc639fb">anonymous{LiveRangeShrink.cpp}::LiveRangeShrink::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600expandspecialinstrs-cpp-/r600expandspecialinstrspass/#a38dc359e925f1a8fd75ba272f45b4736">anonymous{R600ExpandSpecialInstrs.cpp}::R600ExpandSpecialInstrsPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoreframetoargsoffsetelim-cpp-/xcoreftaoelim/#a2ef5edc1bc3d0736ef24263d9e6b0d69">anonymous{XCoreFrameToArgsOffsetElim.cpp}::XCoreFTAOElim::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fa258f0e297563fcec4bb619d2a759">llvm::MachineFunction::salvageCopySSAImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#abe1c22281512c39286cbb9bca97ae7b8">llvm::R600SchedStrategy::schedNode</a>, <a href="#a48bcf9eb66f880de8e7f4d0fcc8af320">setIsRenamable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abc74d2caa2627808c02a43aa418a68f7">setM0ToIndexFromSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2afcfcff9187a2201549d75d4e16149">llvm::MachineInstr::setPhysRegsDeadExcept</a>, <a href="#a682ba82f42f7903d0000ffbb13ea3b57">setReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a05427132a2cb380432ed752b5f2dea6b">llvm::MachineInstr::setRegisterDefReadUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpumacrofusion-cpp-/#af5da450a1411e5b2e09527cb36568ff1">anonymous{AMDGPUMacroFusion.cpp}::shouldScheduleAdjacent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae3e589c970e020448b5a5ade20d07d7e">shouldUseFormStridedPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a316803c463af8ba2c38182332fb3c8a4">SinkingPreventsImplicitNullCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9f59e1f6dd6677348ba082a10fc09061">llvm::MachineInstr::substituteRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a781bc33cca080506ba19a20d66c1c255">llvm::RegBankSelect::tryAvoidingSplit</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#aaaa5a895e6a8003daae912a9bf636040">llvm::LegalizationArtifactCombiner::tryCombineExtract</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a08bf0b055eab1a86300c18c2b0f9fc7e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a5e1eb00d7eee7258726795f01822d491">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldOMod</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a17772fd1beeccd740ec6412abad098f9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldPhiAGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a553d8629e18f8acb82dbadd0a160b877">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldRegSequence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/classes/amdgpuregbanklegalizecombiner/#a7c833b32f9576a77193082ed28b7a5cf">AMDGPURegBankLegalizeCombiner::tryMatch</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a7c842ead18aca7681bd1cd596a3c8ba3">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::tryMoveVGPRConstToSGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a8562a883d9494266aca5d1b2f8b5dc5e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryOptimizeAGPRPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9a9739cf49c46adcb76ac7e2dc13545c">llvm::CombinerHelper::tryReassocBinOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acd13e2195957a8e92e36d055dde1ffb8">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryToFoldACImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#a47c8a030926eca62aae974bb55ecd995">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::update</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#ad6a7db5730cb47b326439993daad033e">UpdateCPSRDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a8efbb19aded8e33e51da4553499bc975">UpdateCPSRUse</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a062ea093e135121a384a1c6c4cd3d96c">llvm::HexagonPacketizerList::updateOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a77dea00ee37a964ad5edf6072fb35071">UpdateOperandRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1216c0733931de570c17ed44556139bf">updateOperandRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a02230ca194a9c8e52170cc7c426decb2">UseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1f6067626e3318b8569835d83acbd92e">llvm::SIInstrInfo::usesConstantBus</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad6611e7ee084ecf0ef7b23ca25b50db0">validateAccessChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#afdb11d0b5d726b02916f412453587951">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateMVEInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ac6789e73101dcf0d746feb6343f4aae6">validatePtrUnwrapStructField</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a22414e0619deaa2a695fd6d31002bb9d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateTailPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a89e479535d719fb4ec8904104ec1e8ae">llvm::RegisterBankInfo::InstructionMapping::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a9797c6d6b9fdb29489ea309649a0ef4a">VerifyLowRegs</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a015233fe94a42e2294533334811ab899">llvm::MachineRegisterInfo::verifyUseList</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a51ac6439b177bf76b27b1fd1a4f30ca3">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitCopy</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#ad457d12e54f0a38894c84aa6901838b5">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSvi64lane</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa4f08d12a02cc1685e8ea788f818ac1a">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSviGPR</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### getRegLiveOut() {#a19b31bc5eda8ac4aeadf920d47aa6df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * llvm::MachineOperand::getRegLiveOut ()</td>
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

<p>getRegLiveOut - Returns a bit mask of live-out registers.</p>

<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a9bc87d84f8ed5dccb4553a23d1b34843">isRegLiveOut</a>.</p>


<p>Referenced by <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>.</p>

</div>
</div>

### getRegMask() {#ae6876d59aeec5bc210b359fbdcf6c1ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * llvm::MachineOperand::getRegMask ()</td>
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

<p>getRegMask - Returns a bit mask of registers preserved by this RegMask operand.</p>

<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a55fdcb2a9df9a69067eed1bc17a0b927">isRegMask</a>.</p>


<p>Referenced by <a href="#a7c45ed93ec219927c08e0a8fb77c94d3">clobbersPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4dc06d4fb42d48a6ade1958f76334826">llvm::ScheduleDAGInstrs::fixupKills</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#aba7fb21a2d5ab45963fa25629ad883aa">anonymous{MachineCopyPropagation.cpp}::CopyTracker::getPreservedRegUnits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#a7ee076808f65d7b724d9a94d48b2cee8">isMatchingStartStopPair</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0909a505055aae0cb9dee8e5730b3724">llvm::MIRParserImpl::setupRegisterInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### getShuffleMask() {#a622dee2e5d865699df4407bd0bdbf903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; int &gt; llvm::MachineOperand::getShuffleMask ()</td>
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



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a81521682ef12b5e4f681502f9346a4ad">isShuffleMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gshufflevector/#accb4d1c10e950e995f808829b4f3a106">llvm::GShuffleVector::getMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a44896316bcf65958ba14a3afa8fa193f">isExtractHiElt</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizercombiner-cpp-/#a74c47491ee867baa1f14586d759342ee">anonymous{AArch64PostLegalizerCombiner.cpp}::matchExtractVecEltPairwiseAdd</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### getSubReg() {#a028a8c5113d40d8c3f4427053bf36738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::getSubReg ()</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad0a79b68db2b8f84f92b1ee24352b3ce">llvm::MachineInstr::addRegisterDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d95c5a37b4d6002c70248107633b815">llvm::HexagonInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#ab07fa640d6b044c04371e8cc8bde6a02">attemptDebugCopyProp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76a671b685940387f88a924858a371d4">llvm::SIInstrInfo::buildExtractSubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a848f5b2d82a5d809fe4785b96e6bdb95">canFoldCopy</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a4d40a357c884c36942205713e7bf3244">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ad8ddb8460838860b8d1d38555049f08b">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::collectIncomingValuesFromPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ac9883c9ec5baeee39d4215b9af8e0a70">findUseBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a7cfc0ecfec922ebf19bd023f3b675604">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#af18310512508f6a0ace33730b2f9de83">foldPatchpoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4a416f1e734b334b8868c3b728baaf4">llvm::HexagonInstrInfo::getBaseAndOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a827d52327fbe1bd7bf22242e7c18847d">getDefRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1743a67877bf4ba56d53b235d3573e0">llvm::TargetInstrInfo::getExtractSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#afc76a889f289a0e841775d80aa0338ba">llvm::ARMBaseInstrInfo::getExtractSubregLikeInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#abea536f043de7994bc9b67c634a7c879">llvm::TargetInstrInfo::getInsertSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abc8556ad731efc2f7a407169624d812e">llvm::ARMBaseInstrInfo::getInsertSubregLikeInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#af196b990f6f506c44a4512bad4a36cef">getInstReadLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a643ff7dd8c287dd58e75cbe79556e74c">llvm::ScheduleDAGInstrs::getLaneMaskForMO</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#acdf9051278b18a64c83cc047a3080de3">anonymous{LiveDebugVariables.cpp}::UserValue::getLocationNo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#af58cbab9cb762f2d2a4baae6177e30e4">getNewSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/copyrewriter/#af6a7bff7d1f79439d9cef76fd17c6688">anonymous{PeepholeOptimizer.cpp}::CopyRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/extractsubregrewriter/#a79218c7fe32c8fb42e07cebb08c578e4">anonymous{PeepholeOptimizer.cpp}::ExtractSubregRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/insertsubregrewriter/#aae0a3466d999e3c2435e10e766335499">anonymous{PeepholeOptimizer.cpp}::InsertSubregRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/regsequencerewriter/#af67bc5de34066daeefa8468bc983e737">anonymous{PeepholeOptimizer.cpp}::RegSequenceRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/uncoalescablerewriter/#af703b6af11073fc6bb738c43fcbada3e">anonymous{PeepholeOptimizer.cpp}::UncoalescableRewriter::getNextRewritableSource</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a9190a9fa370b0c81005613f21afed7d7">llvm::SIInstrInfo::getOpSize</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a51539193cc8ad7ae2884993bbb57ddea">llvm::ARMBaseInstrInfo::getPartialRegUpdateClearance</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#a6825b86f34e17792a882f599423f5485">getRC32</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a09a1c19b999c807cb52c21541a2c7de4">llvm::PPCRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ad490ad7663a07141538a6f4049299550">llvm::RISCVRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a88f8cb24fba67649c1f32531d0f6ab90">llvm::MachineInstr::getRegClassConstraintEffect</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aae4eaf548fa62f15dc35f4018fef3707">llvm::SIRegisterInfo::getRegClassForOperandReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a3cb505493f51b96cbb394d89b93f686e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::getRegSeqInit</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae26cac7943070f09b4d7fa667d1adf95">llvm::TargetInstrInfo::getRegSequenceInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aba7f60edec8e7b982c598aa278f9420c">llvm::ARMBaseInstrInfo::getRegSequenceLikeInputs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagoncp/#afbd23f1436bf2680a83324a63b37dbe4">anonymous{HexagonRDFOpt.cpp}::HexagonCP::interpretAsCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a58db20676cb0ff354eca34b86f0c3ab1">isAGPRCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a6fbf0d819e9a71ced3199693268238ce">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::isClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/detectdeadlanes-cpp/#adecd11022a5f472b5ad0682bd79f479a">isCrossCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6ee45760c97bf2dda6bee91508e6946e">llvm::MachineInstr::isFullCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a407338aee0ea958defdef5cb3993f1da">llvm::TargetInstrInfo::isFullCopyInstr</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#add5255eb40b106f13738476389bfa5a6">llvm::MachineInstr::isIdentityCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abecccbf97c3a9d0be384e6c639fcf2dc">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a7e62a05741edcd4375c97fd4906b419d">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::isOMod</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/mirparser-cpp/#a3739959eaa5952384fc45bcc0d9a92da">isSSA</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a776834e825e7fd9cd90c27f7ace1d9d2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::needToBeConvertedToVALU</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#afbc1088fd64459bec1157940aa59eb69">llvm::X86InstrInfo::optimizeLoadInstr</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#aa3fe888e13e687c808085c0cfba933c3">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneValues</a>, <a href="#a3be9857a09c82046b77a71918b5e214f">readsReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a374fc9d9064a93ef8a408f269d02389d">llvm::MachineInstr::readsWritesVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a05427132a2cb380432ed752b5f2dea6b">llvm::MachineInstr::setRegisterDefReadUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae3e589c970e020448b5a5ade20d07d7e">shouldUseFormStridedPseudo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="#a9842e6805ce84262b6bbe7da2b26772c">substPhysReg</a>, <a href="#a13a5b2fd837189405f1b07a6c9249d4f">substVirtReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a5e1eb00d7eee7258726795f01822d491">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldOMod</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a553d8629e18f8acb82dbadd0a160b877">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldRegSequence</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a8562a883d9494266aca5d1b2f8b5dc5e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryOptimizeAGPRPhis</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acd13e2195957a8e92e36d055dde1ffb8">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryToFoldACImm</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a51ac6439b177bf76b27b1fd1a4f30ca3">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitCopy</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#aa54146eb85b736f6f42bba1e44963eb7">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitORR</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a137403167e291d2e011441ce02d51898">llvm::VirtRegAuxInfo::weightCalcHelper</a>.</p>

</div>
</div>

### getSymbolName() {#ab59b255f78cd503133d032152a41d105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::MachineOperand::getSymbolName ()</td>
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



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7c5f0ef161b5b4dedad2e9aac9fcfee7">isSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a392dd12827c5ede927d490ccc16f38ab">llvm::BTFDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a8a08ac1d3e9758e48d542db8b3fc10ce">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a1474f541013883f4a531e90759e287d4">llvm::AArch64MCInstLower::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfmcinstlower/#a4093256615d2d6d555715b7f6ef27550">llvm::BPFMCInstLower::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#a368bfc9bb0e9ebc36e5c881f8c06560a">llvm::LanaiMCInstLower::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a757204fd88b25eccdac74a4a0020cff7">llvm::MSP430MCInstLower::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#aaa9fafc42db7a667c344ce753b989101">GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#a094b53ae338bc1ed10ec35facf8e07b0">llvm::M68kMCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a349ac25a0317c2e30b66435a5bdede3d">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETFunPLTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a15c1137ef9bebbeafd1060405cb71242">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETTLSAddrAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a153a3f96b2710ef9d924d8168a93482b">llvm::XtensaAsmPrinter::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ab6548436b77ac06129373db3d8e3dece">llvm::WebAssembly::mayThrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#a64e13a8c3c0d483c21941a99f473f8c2">optimizeCall</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#ab3b56dc8749765fe615f325594493167">llvm::WebAssemblyAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#a83c424197528aeade7d84bfc2be9b074">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a7ddd6d21450d4f2269de2ab98fc8db6b">llvm::AVRAsmPrinter::printOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>.</p>

</div>
</div>

### getTargetFlags() {#ab06dda088d3c7686f7dfcdb2b96323f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::getTargetFlags ()</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9189968ba471dec34e7806413bd019cd">llvm::MachineInstrBuilder::addDisp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsasmprinter-cpp/#a487192753b68b0e4380e9d999a5b1549">emitDirectiveRelocJalr</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a5278ce924df77790e6a938f5065ba5a0">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a3a67d4b5306c3571138e241d77393283">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#aa4b5f0a2f0b72c2a31bb11458f34a1b3">llvm::MSP430MCInstLower::GetBlockAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#adcac670465a74316ab31a2a168fb8378">llvm::MSP430MCInstLower::GetConstantPoolIndexSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#ab4d10aeb6baa9b7d22a3e7a108243e7a">llvm::LoongArchII::getDirectFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a757204fd88b25eccdac74a4a0020cff7">llvm::MSP430MCInstLower::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ad067184df5d0a7ed4aabb4d359ccb4e6">llvm::AArch64MCInstLower::GetGlobalAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a89624709f3eb37e3202214ca83d133af">llvm::MSP430MCInstLower::GetGlobalAddressSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#af31cf7c6a33e5b2cc57085902bc0c436">llvm::MSP430MCInstLower::GetJumpTableSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp/#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a731bb8307207186d81b2a7353f21f199">getTOCEntryTypeForMO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchii/#a2f9fa0e4abfc14d359493021fdef57ca">llvm::LoongArchII::hasRelaxFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#abefb312df5790c0f83c5e739316b9047">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::isGOTPLDpc</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#a34e3dd28fecb20679563d191667e9e9c">llvm::SystemZMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a55859f4a9f64b42f225c2f6c63212be5">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#a9bdd6ed65ae27d68d065f712e0d281de">llvm::LanaiMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ab8310eee0e086d64c49733dd9da4171b">llvm::M68kMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a8520755e983a50f3c24f91e0f8e06d03">llvm::MSP430MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#a5edb97651738551635eb05cc3f9fa77c">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#acb4de1517ebc1f8095f87eef68f290f7">llvm::AVRMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#aab3177d726a52bd1f3a26e580f6c4eda">llvm::CSKYMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a48efbf9c526eceb30f721ea086dc98fd">llvm::AArch64MCInstLower::lowerSymbolOperandCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ae4b8638e074c6af2301cd209d3d2021c">llvm::AArch64MCInstLower::lowerSymbolOperandMachO</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac246ec9c6b316d2a71621ef3df914da9">llvm::ARMAsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2f4e57397c15057e80f3edaeca9377f4">swapImmOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### getTargetIndexName() {#a2a1f57ce725829ceacb0068b4b5f2d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * MachineOperand::getTargetIndexName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getTargetIndexName - If this <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> is a TargetIndex that has a name, attempt to get the name.</p>


<p>Returns nullptr if the TargetIndex does not have a name. Asserts if MO is not a TargetIndex.</p>


<p>Declaration at line 814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="#aaa68daaf8d7b773d012887c92c2023ce">getIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a> and <a href="#a2a1f57ce725829ceacb0068b4b5f2d2a">getTargetIndexName</a>.</p>


<p>Referenced by <a href="#a2a1f57ce725829ceacb0068b4b5f2d2a">getTargetIndexName</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>.</p>

</div>
</div>

### getType() {#ab313591ae4ea1e3a4ab59121a7dc2a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperandType llvm::MachineOperand::getType ()</td>
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

<p>getType - Returns the <a href="#af269b990800f72c7cf535c407e8e639b">MachineOperandType</a> for this operand.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9189968ba471dec34e7806413bd019cd">llvm::MachineInstrBuilder::addDisp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a19e16a0f3c37ba1524eb85c891bfa760">compareMachineOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#aa85a26f5f6b24110a2388e4726cdd282">getCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a5191842b97cefc259bf0689f9565310b">getMCSymbolForTOCPseudoMO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a731bb8307207186d81b2a7353f21f199">getTOCEntryTypeForMO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#ae0f8a358fed16b3154b337f7e8aea2c0">IsAnAddressOperand</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmcinstlower/#a6d050903b1d4eb1403389e782f6cec1c">llvm::SPIRVMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a349ac25a0317c2e30b66435a5bdede3d">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETFunPLTAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a15c1137ef9bebbeafd1060405cb71242">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::lowerGETTLSAddrAndEmitMCInsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a7687092765d6f25890cefb856f35b881">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arcmcinstlower/#ab69d76329fbcf34e06d1e1119fa8c0f5">llvm::ARCMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ac63e4c740efa7b5b4426caa0de190af6">llvm::M68kMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcinstlower/#a5d6f8b2290183d7b3ae500dfce8fbb94">llvm::MipsMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoremcinstlower/#a16bd2e3d32444031e5abc6a96d562314">llvm::XCoreMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#a34e3dd28fecb20679563d191667e9e9c">llvm::SystemZMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ae4bbe4c2ecf0ae95b3c4ffc3bb34ed07">llvm::XtensaAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a010b554002b5c2fdbc6e2d2b64afedb9">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a50863928ef6e46cfbe213995fd4974c2">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#a8022309e0fcca527f4a1a49b8a8ba922">llvm::LoongArchAsmPrinter::LowerSTATEPOINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kasmprinter/#a5474d7cf1a213163c8929c3189e2c166">llvm::M68kAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a1a6d908f749f40987c9bd895ef5c7849">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#abb1c33c814741adb78a9ff7f10ff3552">llvm::AVRAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#a8549db3c421967b14bad3b2e6ab53980">llvm::CSKYAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#ae87b9efb9db9ad27a0f5f7d753ce45fd">llvm::LoongArchAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#ab3b56dc8749765fe615f325594493167">llvm::WebAssemblyAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#ae3bd1981fefcc9dadf49e90b2feef3be">llvm::X86AsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#a83c424197528aeade7d84bfc2be9b074">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#adc984afaf62b041cceff164e14cdb889">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmprinter-cpp-/veasmprinter/#a94ccb5d36399ea8c01c40c8c28123454">anonymous{VEAsmPrinter.cpp}::VEAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a4e9f35f7c792ae53843a921999988ccb">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a7ddd6d21450d4f2269de2ab98fc8db6b">llvm::AVRAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aec3f83e468ca215a70dda2742816745c">llvm::HexagonAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a77eadb151cd5208de6a45a14ea61c0a9">llvm::XtensaAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isBlockAddress() {#abed9003622087a5bbddb7c19b6d02ce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isBlockAddress ()</td>
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

<p>isBlockAddress - Tests if this is a MO_BlockAddress operand.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">MO_BlockAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="#a94f5b10f666acf5a0cddd5ac8302d0b8">getBlockAddress</a>, <a href="#af624ff47eaa512dbe23866accb3837c1">getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#a73660507cf04c478fea7b5f9b33ecd21">isValidDispOp</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#abd31e9ad15d84356f971b4c2340bbbd0">llvm::LoongArchAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a> and <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a>.</p>

</div>
</div>

### isCFIIndex() {#abebd8c425a02eaa5470c40ac6c47c59b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isCFIIndex ()</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba0270d8f468e7b92dafb486293ecf137d">MO_CFIIndex</a>.</p>


<p>Referenced by <a href="#a88c30c92aa9995b0cc70bfe60294ff65">getCFIIndex</a>.</p>

</div>
</div>

### isCImm() {#a32ea768fbb182d6bbe3ff85ae1eb7031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isCImm ()</td>
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

<p>isCImm - Test if this is a MO_CImmediate operand.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba5cc9e17457a92caa963ed784d83f6233">MO_CImmediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a610c7b58032f5eac1b06aa0c66cadb6a">llvm::generateGroupUniformInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabf50e80c80c98fd130ff1cb70553742">llvm::generateSpecConstantInst</a>, <a href="#a29e05cd075864928ae65e1751fdc346e">getCImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a0acd5ca4d907a57e5dc5ee9129dbbbc8">anonymous{Utils.cpp}::getCImmAsAPInt</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a21c5d1a680afc10bd790c931150ac04f">anonymous{Utils.cpp}::getCImmOrFPImmAsAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96b61989528fd1061ce48169e066cd14">llvm::getConstFromIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#af6194171586d2f1e13eb57765226d48a">getImmedFromMO</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="#aae70dd97002db997dfc96303fa9e6971">setCImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>.</p>

</div>
</div>

### isCPI() {#a5b401e780c5eed0aca1cfbf44d36a545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isCPI ()</td>
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

<p>isCPI - Tests if this is a MO_ConstantPoolIndex operand.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">MO_ConstantPoolIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a977522c71b9c7099aa74222cc12bbf17">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::findInRangeCPEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="#aaa68daaf8d7b773d012887c92c2023ce">getIndex</a>, <a href="#af624ff47eaa512dbe23866accb3837c1">getOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#a3abad49282c799b7daeacb2b1bd5272b">isAnImmediateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#a73660507cf04c478fea7b5f9b33ecd21">isValidDispOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands/#aaf4297850ccff6052205f45bc2ba2f87">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::runOnMachineFunction</a>, <a href="#aebc99c3c37896879abad49e7254a2fb8">setIndex</a>, <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>.</p>

</div>
</div>

### isDbgInstrRef() {#ad04e186512436ffdefdb16ed8aaea57a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isDbgInstrRef ()</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba87cf4128c65c3799c2189ceb3fb62bd3">MO_DbgInstrRef</a>.</p>


<p>Referenced by <a href="#a3ac9865fa1ab348b64b4366cfe103f74">getInstrRefInstrIndex</a>, <a href="#a082167d36582dece9770d881292f5cf6">getInstrRefOpIndex</a>, <a href="#a0c47183dc58b861a7b12c97f0a40312b">setInstrRefInstrIndex</a> and <a href="#a20d16082ca624c29bb20bc0671d48408">setInstrRefOpIndex</a>.</p>

</div>
</div>

### isDead() {#aaee820701392c55ad54235d3d7201206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isDead ()</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6cdddfff71264f7e1e744fdea34085d3">llvm::ARMTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af408efad64e3aa0eef6c3a37c7794a83">llvm::MachineInstr::allDefsAreDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a39f79b8dd21fa75c7c273ebb9177a6a7">llvm::MachineInstr::allImplicitDefsAreDead</a>, <a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a4d40a357c884c36942205713e7bf3244">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtDef</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="#af2c351dad09a71aa08e1d85c67ae6e53">CreateReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#a9287c2118799a2ad22328ce4c1945427">doesInstructionSetFPSW</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a309b19640cc1989cb6c46600e274cf45">llvm::ARMBaseInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86flagscopylowering-cpp/#adcc6b20dc2c8fad2a6aac24e970f15c7">getClobberType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#ae42ae7520e86040563aa828fc9d5eb91">getMopState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="#a5c94b329f3cec9f4fd23db1d208c0bc8">hash_value</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf735f22db2a6cb417e73392e0934bb1">llvm::X86InstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a597bb5d7ef9a22f44dbe867d8eaa7fd6">anonymous{InlineSpiller.cpp}::HoistSpillHelper::hoistAllSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abb834744243c11cb677261382ac15bea">llvm::MachineInstr::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aab9a96f10af025498520e00ff044bec1">llvm::MachineInstr::isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ac671c3b34aac49144d2688fd6ed160bc">llvm::X86InstrInfo::setSpecialOperandAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#ad6a7db5730cb47b326439993daad033e">UpdateCPSRDef</a>.</p>

</div>
</div>

### isDebug() {#aa2d3a60e597b4a6cf24ee4ac12d2cdbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isDebug ()</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af848272aaea9ac1f976aaf56fd31cb8d">canRenameUpToDef</a>, <a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="#af2c351dad09a71aa08e1d85c67ae6e53">CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="#a5c94b329f3cec9f4fd23db1d208c0bc8">hash_value</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="#aed8d139ece631812f972a8cc074adc55">setIsDef</a>, <a href="#a8a82683fccdef8a5ef772ef03277aee7">setIsKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isDef() {#a75eb135014670ce946e78739cdc9b51b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isDef ()</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a56fbc3f460289602ce8a51538ebc1e26">llvm::ScheduleDAGInstrs::addPhysRegDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#af7f7e5eb5b55add81ed8fe39ac83b9c2">llvm::MachineRegisterInfo::addRegOperandToUseList</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6cdddfff71264f7e1e744fdea34085d3">llvm::ARMTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">llvm::AnalyzeVirtRegInBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a392dd12827c5ede927d490ccc16f38ab">llvm::BTFDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#a5a71ccecb00de06004fb421a568dd7b4">llvm::CriticalAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af848272aaea9ac1f976aaf56fd31cb8d">canRenameUpToDef</a>, <a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a08a3820d71cd895d5c69478fad30fd10">collectInlineAsmInstrOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ab8b249a6f01a1f333bc2bfbc6463251c">llvm::PPCInstrInfo::convertToImmediateForm</a>, <a href="#af2c351dad09a71aa08e1d85c67ae6e53">CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aafc82eb49e1de126caa8907eaca9f46e">llvm::HexagonHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kframelowering-cpp/#ae82cb5b8bd04147ce1ebe063f447c718">findDeadCallerSavedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a7ee47bba7fdfe2b4de0b767f6d493c26">findDefIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a0402c8e75bccfb666de451d465cd0ac5">findUseIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4dc06d4fb42d48a6ade1958f76334826">llvm::ScheduleDAGInstrs::fixupKills</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a7cfc0ecfec922ebf19bd023f3b675604">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a827d52327fbe1bd7bf22242e7c18847d">getDefRegMask</a>, <a href="/web-llvm/docs/api/structs/llvm/machineinstrexpressiontrait/#a3344d356ddabbe21340a4b078300a789">llvm::MachineInstrExpressionTrait::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#af196b990f6f506c44a4512bad4a36cef">getInstReadLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aa88dfb98a274ef5f8da3ce147c8c45eb">llvm::PPCInstrInfo::getInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9839b7e1d8811ea9d41f901ab6a0f23b">llvm::MachineInstr::getNumExplicitDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac3cfa17f907e7258d898433ddfeb3fbf">llvm::RegBankSelect::getRepairCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#a5c94b329f3cec9f4fd23db1d208c0bc8">hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a5523ffd2d5ced60566f3493c2b48e0e3">hasRegisterDependency</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a597bb5d7ef9a22f44dbe867d8eaa7fd6">anonymous{InlineSpiller.cpp}::HoistSpillHelper::hoistAllSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaidelayslotfiller-cpp-/filler/#afca8ae34e03582f93e75d11b23cbe245">anonymous{LanaiDelaySlotFiller.cpp}::Filler::insertDefsUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a1403d0f29e96c05811fe277c8c68eae6">llvm::WebAssembly::isChild</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aab9a96f10af025498520e00ff044bec1">llvm::MachineInstr::isIdenticalTo</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6df9a6b70a33aee123056cec0ed052c4">llvm::MachineInstr::isRegTiedToUseOperand</a>, <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a1c1669c081e93349baa5bcf3ca5aaae4">IsSafeAndProfitableToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#a8710828eaf6aafddaeb91b5bcdc236da">isValidRegDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp/#ad007531739421e7b54a41c3fefaefa4e">MIIsInTerminatorSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#afbc1088fd64459bec1157940aa59eb69">llvm::X86InstrInfo::optimizeLoadInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a031c20be27e7c8b8bedd6345f209d7cb">printImplicitRegisterFlag</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/bitsimplification/#a7ae2252105ba3f43b639d6648a219a85">anonymous{HexagonBitSimplify.cpp}::BitSimplification::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a3bbf276657ebe5de723f93bc95498b6f">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::removeRedundantLIs</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a40139f3ca5fa604f87136efa9ca611ca">llvm::RegBankSelect::RepairingPlacement::RepairingPlacement</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#aed1c1aa1329f36eef4940283a1d30859">rescheduleCanonically</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2afcfcff9187a2201549d75d4e16149">llvm::MachineInstr::setPhysRegsDeadExcept</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="#a9842e6805ce84262b6bbe7da2b26772c">substPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa37e31e5df481d2f8a6f9f022886cf5e">llvm::MachineInstr::tieOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a781bc33cca080506ba19a20d66c1c255">llvm::RegBankSelect::tryAvoidingSplit</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#a47c8a030926eca62aae974bb55ecd995">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::update</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a8efbb19aded8e33e51da4553499bc975">UpdateCPSRUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isEarlyClobber() {#abd6aa9da048ef7a4faeaac6484d5c9a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isEarlyClobber ()</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp/#a70e2de8376b84c468e8a5762fda4c419">createDeadDef</a>, <a href="#af2c351dad09a71aa08e1d85c67ae6e53">CreateReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a3a62b5d1e83ec172369441613b538fce">dumpMachineInstrRangeWithSlotIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#ae42ae7520e86040563aa828fc9d5eb91">getMopState</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>.</p>

</div>
</div>

### isFI() {#ad7213433bd60dc33020246384dc18b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isFI ()</td>
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

<p>isFI - Tests if this is a MO_FrameIndex operand.</p>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba97561985119c4a774e3ec6439240fa80">MO_FrameIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a22926b4547ee17e802fe12e69ca53915">anonymous{SIFoldOperands.cpp}::FoldCandidate::FoldCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a64c6eca16f58ce5cef19b84d78d3adb7">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldCopyToVGPROfScalarAddOfFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a66eb61143b269793cb50e67646375778">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::frameIndexMayFold</a>, <a href="#aaa68daaf8d7b773d012887c92c2023ce">getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#aef241765e05d84992ebe4133862b899d">isFIPlusImmOrVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a835ce544e7ae111f1889501136ea6b3d">llvm::SIInstrInfo::isImmOperandLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#aa5a8087086656299167f931f805778bb">isLdStSafeToCluster</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a3d9b286b0c8c32ae52faedcc2a6130a7">llvm::SIInstrInfo::isLegalVSrcOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a2baf5026a86db8c593fb7d67cce0a741">llvm::HexagonInstrInfo::isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aa196e9f76f5a5bdc8a8aca82f95cd2b3">isRegOrFI</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a75d714113557721ffd5bd3d06dc79642">llvm::SIInstrInfo::isSGPRStackAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#afb5a8099c7351303ef337ec57d5e8e24">llvm::SIInstrInfo::isStackAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af8e19ecc6875baefa038d0b714d2313c">llvm::HexagonInstrInfo::isStoreToStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa2b80c1201a1baeb6ee4466e970957ba">llvm::AArch64FrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a420e13f932ebcdd50a90e807d5e5674f">llvm::SystemZELFFrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ae803619fba0f2282f638ddd36ba004de">llvm::SIRegisterInfo::resolveFrameIndex</a>, <a href="#aebc99c3c37896879abad49e7254a2fb8">setIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a77dea00ee37a964ad5edf6072fb35071">UpdateOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isFPImm() {#afcb818bd3e34498f8f72ca555a36d5eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isFPImm ()</td>
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

<p>isFPImm - Tests if this is a MO_FPImmediate operand.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639bac4edc21072344f5aafa2a8f307c78b81">MO_FPImmediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a21c5d1a680afc10bd790c931150ac04f">anonymous{Utils.cpp}::getCImmOrFPImmAsAPInt</a>, <a href="#aee59c647052fc9557561e596681da3c0">getFPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblydebugvaluemanager-cpp/#a0101767bf77660a28c873b7b06c2756e">isSameScalarConst</a>, <a href="#a3e326b0a22f9a7042019531da7987ccd">setFPImm</a> and <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### isGlobal() {#ab0d1155c8c38e84cbe387998fd2e517e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isGlobal ()</td>
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

<p>isGlobal - Tests if this is a MO_GlobalAddress operand.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">MO_GlobalAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a392dd12827c5ede927d490ccc16f38ab">llvm::BTFDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ac915411e77e361580ea305fb31325">createCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ae7810a05a90e7fc6d13fa85c0242ab5f">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::getAdjustedFasterLocalExpr</a>, <a href="#a0fcdaab1a4c3134b8f80aa74cabeb970">getGlobal</a>, <a href="#af624ff47eaa512dbe23866accb3837c1">getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ae6f1cb7931164d888acd081fa41e6246">llvm::R600InstrInfo::getSrcs</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#aaa9fafc42db7a667c344ce753b989101">GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#a094b53ae338bc1ed10ec35facf8e07b0">llvm::M68kMCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a38691dc780e36d270e9f13eeb4fdb28f">anonymous{DelaySlotFiller.cpp}::Filler::insertCallDefsUses</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a3b244792bc2277f0800d9e15c2eb935b">llvm::BTFDebug::InstLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#a3abad49282c799b7daeacb2b1bd5272b">isAnImmediateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectbranchtracking-cpp/#a708537fa3526cf7f988d3146a9af652b">IsCallReturnTwice</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#abefb312df5790c0f83c5e739316b9047">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::isGOTPLDpc</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a835ce544e7ae111f1889501136ea6b3d">llvm::SIInstrInfo::isImmOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a3d9b286b0c8c32ae52faedcc2a6130a7">llvm::SIInstrInfo::isLegalVSrcOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblydebugvaluemanager-cpp/#a0101767bf77660a28c873b7b06c2756e">isSameScalarConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a78b9ad4b9b246aab32ff14d856f5769a">llvm::PPCInstrInfo::isSignOrZeroExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#a73660507cf04c478fea7b5f9b33ecd21">isValidDispOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#aa50d150829937efa73527accf23a184d">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADgotAUTH</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a3cf266e359a05a56bd9533dff30b3e12">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a175c0b6f2f4c39ae659845dcef17f71b">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#acb4de1517ebc1f8095f87eef68f290f7">llvm::AVRMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ab6548436b77ac06129373db3d8e3dece">llvm::WebAssembly::mayThrow</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#abd31e9ad15d84356f971b4c2340bbbd0">llvm::LoongArchAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af865b91965a6c4e1082d1510228db5b5">llvm::AsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac246ec9c6b316d2a71621ef3df914da9">llvm::ARMAsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a34e471aa6f0a6f1975d57f3aafc7b2e0">llvm::AsmPrinter::PrintSymbolOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctlsdynamiccall-cpp-/ppctlsdynamiccall/#ac8ec7eb90b39efbbc47fd93406e93737">anonymous{PPCTLSDynamicCall.cpp}::PPCTLSDynamicCall::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ae9e91530b7f4d99adc7f3f43b35a00b9">queryCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/detectroundchange/#a23677a404e91b3491d158fb8b0ea3f49">llvm::DetectRoundChange::runOnMachineFunction</a>, <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a>.</p>

</div>
</div>

### isIdenticalTo() {#ad7f2dc64214551418f486026ffc95fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineOperand::isIdenticalTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this operand is identical to the specified operand except for liveness related flags (isKill, isUndef and isDead).</p>


<p>isIdenticalTo - Return true if this operand is identical to the specified operand.</p>


<p>Note that this should stay in sync with the hash_value overload below.</p>


<p>Declaration at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="#a94f5b10f666acf5a0cddd5ac8302d0b8">getBlockAddress</a>, <a href="#a88c30c92aa9995b0cc70bfe60294ff65">getCFIIndex</a>, <a href="#a29e05cd075864928ae65e1751fdc346e">getCImm</a>, <a href="#aee59c647052fc9557561e596681da3c0">getFPImm</a>, <a href="#a0fcdaab1a4c3134b8f80aa74cabeb970">getGlobal</a>, <a href="#a38b28a85f818b49d8806c150b8a5b4f7">getImm</a>, <a href="#aaa68daaf8d7b773d012887c92c2023ce">getIndex</a>, <a href="#a3ac9865fa1ab348b64b4366cfe103f74">getInstrRefInstrIndex</a>, <a href="#a082167d36582dece9770d881292f5cf6">getInstrRefOpIndex</a>, <a href="#ad21d94ca6aa512e357a993e0e85a921e">getIntrinsicID</a>, <a href="#a57e64b633278df75c699e6b98ce15031">getMBB</a>, <a href="#af155da145e58791956c5e922e900fcb3">getMCSymbol</a>, <a href="#a57b590606040d1c856a1d43aa0680364">getMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a>, <a href="#af624ff47eaa512dbe23866accb3837c1">getOffset</a>, <a href="#af0d32d967ac31c4e6149c2adb89aa947">getPredicate</a>, <a href="#ac0035d7c1c860501c877c20e6e93297b">getReg</a>, <a href="#ae6876d59aeec5bc210b359fbdcf6c1ad">getRegMask</a>, <a href="#a9fd1f4d5c1460886c4aa983a2027d944">getRegMaskSize</a>, <a href="#a622dee2e5d865699df4407bd0bdbf903">getShuffleMask</a>, <a href="#a028a8c5113d40d8c3f4427053bf36738">getSubReg</a>, <a href="#ab59b255f78cd503133d032152a41d105">getSymbolName</a>, <a href="#ab06dda088d3c7686f7dfcdb2b96323f5">getTargetFlags</a>, <a href="#ab313591ae4ea1e3a4ab59121a7dc2a2b">getType</a>, <a href="#a75eb135014670ce946e78739cdc9b51b">isDef</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">MO_BlockAddress</a>, <a href="#af269b990800f72c7cf535c407e8e639ba0270d8f468e7b92dafb486293ecf137d">MO_CFIIndex</a>, <a href="#af269b990800f72c7cf535c407e8e639ba5cc9e17457a92caa963ed784d83f6233">MO_CImmediate</a>, <a href="#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">MO_ConstantPoolIndex</a>, <a href="#af269b990800f72c7cf535c407e8e639ba87cf4128c65c3799c2189ceb3fb62bd3">MO_DbgInstrRef</a>, <a href="#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">MO_ExternalSymbol</a>, <a href="#af269b990800f72c7cf535c407e8e639bac4edc21072344f5aafa2a8f307c78b81">MO_FPImmediate</a>, <a href="#af269b990800f72c7cf535c407e8e639ba97561985119c4a774e3ec6439240fa80">MO_FrameIndex</a>, <a href="#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">MO_GlobalAddress</a>, <a href="#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">MO_Immediate</a>, <a href="#af269b990800f72c7cf535c407e8e639ba9f104d16987b5384042276466fc2e003">MO_IntrinsicID</a>, <a href="#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">MO_JumpTableIndex</a>, <a href="#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">MO_MachineBasicBlock</a>, <a href="#af269b990800f72c7cf535c407e8e639ba17c8e891dacb2adc4a2d0ee5b10d6e9f">MO_MCSymbol</a>, <a href="#af269b990800f72c7cf535c407e8e639babf35c1c1ff9daae15b2dff8efa224623">MO_Metadata</a>, <a href="#af269b990800f72c7cf535c407e8e639ba3ab395cc24292a5e8e499e48f1553d94">MO_Predicate</a>, <a href="#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">MO_Register</a>, <a href="#af269b990800f72c7cf535c407e8e639bac72cbca4074e0bc4a26afc03db602da5">MO_RegisterLiveOut</a>, <a href="#af269b990800f72c7cf535c407e8e639ba48257b48932e88a230caff68469fd9f6">MO_RegisterMask</a>, <a href="#af269b990800f72c7cf535c407e8e639ba512cc7de4a9ee26228ed614f8447d760">MO_ShuffleMask</a>, <a href="#af269b990800f72c7cf535c407e8e639babb48fd8c9fa828e23f5d33f46cb0cbbb">MO_TargetIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#a76f229e9f5c9ffd689f6b437accb522d">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::AddVCTP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad304b10479d6791deee8ad1b157fb37f">llvm::X86InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a23fc03605ab508eb40a5fb968a78e139">llvm::AArch64InstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a00f254751a3efe88d446fe5fdba2d7c4">llvm::LanaiInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a878d28bcb9d1575d5f5e56c5b1bcf064">llvm::PPCInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#afc0ac4e187f1865c16f5dd0814e7fa5b">llvm::RISCVInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#acdf9051278b18a64c83cc047a3080de3">anonymous{LiveDebugVariables.cpp}::UserValue::getLocationNo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#aea53813ca1c1efc9ef06b5b9844be967">isIdenticalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aab9a96f10af025498520e00ff044bec1">llvm::MachineInstr::isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ac71ff55e5082eff77950ab8122aad429">isImplicitOperandIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a5cfcaf632d98be49b27f2ff3a3c8cbb1">IsVPNOTEquivalent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinescheduler-cpp/#a069f6bd5e8ca662cfbeeb43f90a5a97a">mayOverlapWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a2929348b6b6f3ad543717d42b201640d">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldCndMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a> and <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### isImm() {#a76f61c6784df6dc8402a8b9011041926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isImm ()</td>
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

<p>isImm - Tests if this is a MO_Immediate operand.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">MO_Immediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a5c028845ee14a6e2218b8b79d66d200a">llvm::HexagonInstrInfo::analyzeCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#aa67934d23b1e9ff1901ec570930128e4">areCombinableOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a8d95c5a37b4d6002c70248107633b815">llvm::HexagonInstrInfo::areMemAccessesTriviallyDisjoint</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#aca2b6568c134ce283d74d23db8d6b665">llvm::R600InstrInfo::buildSlotOfVectorInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a364fb004e57163fc1a3e2adc754af9b1">canCompareBeNewValueJump</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a80ba8826b4f8e7008ae9453968ed35fa">canInstrSubstituteCmpInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a08a3820d71cd895d5c69478fad30fd10">collectInlineAsmInstrOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#adf5d3b4379e4e570f14f6700d6e87467">llvm::SIInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a8a08ac1d3e9758e48d542db8b3fc10ce">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/hexagonconstevaluator/#ad86353e56a3963118b327c0f528a5004">anonymous{HexagonConstPropagation.cpp}::HexagonConstEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af3caca8b1c9e27890d57f5755dc142fe">llvm::MachineInstr::findInlineAsmFlagIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a22926b4547ee17e802fe12e69ca53915">anonymous{SIFoldOperands.cpp}::FoldCandidate::FoldCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a64c6eca16f58ce5cef19b84d78d3adb7">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldCopyToVGPROfScalarAddOfFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a727184c28151d2b605686087351b8d7b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldInstOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#acf5910da93c4e01390c1e29b4a72836f">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldShiftedOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4a416f1e734b334b8868c3b728baaf4">llvm::HexagonInstrInfo::getBaseAndOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ac8e4876fffd2ceada8ef6428258d7236">llvm::HexagonInstrInfo::getBundleNoShuf</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af668609d5285820d674d655ab3990c91">llvm::HexagonInstrInfo::getCompoundOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c64e87ab3dd6ef5ea0c229712f1fd63">llvm::X86InstrInfo::getConstValDefinedInReg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#ac9e87818c9d13b4d6a636f2691b4d21d">anonymous{RISCVInsertVSETVLI.cpp}::getDemanded</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1743a67877bf4ba56d53b235d3573e0">llvm::TargetInstrInfo::getExtractSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#abe6350749fb33b3fb889a5cb8b5d4ba4">llvm::R600InstrInfo::getFlagOp</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#adc210f7d04be558143f8a891c892e550">llvm::SIRegisterInfo::getFrameIndexInstrOffset</a>, <a href="#a38b28a85f818b49d8806c150b8a5b4f7">getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#af6194171586d2f1e13eb57765226d48a">getImmedFromMO</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acdc089f7e9f2dddcf2412615f90690a9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::getImmOrMaterializedImm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6c1928eecc56a24a5a6d8bb211a0afb4">llvm::HexagonInstrInfo::getIncrementValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#abea536f043de7994bc9b67c634a7c879">llvm::TargetInstrInfo::getInsertSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a9f95e557fb675ab6ef80f2fc4b8b3e01">llvm::AArch64InstrInfo::getMemOpBaseRegImmOfsOffsetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a4870646ffc5b5a7d4425edd55d6f93de">llvm::X86InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a934f16bd434319b64e63ae8f622991ce">llvm::LanaiInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aead7c7f29560bc0cfbfe9959f936b456">getRegImmPairPreventingCompression</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae26cac7943070f09b4d7fa667d1adf95">llvm::TargetInstrInfo::getRegSequenceInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ae6f1cb7931164d888acd081fa41e6246">llvm::R600InstrInfo::getSrcs</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#adf62cb0814e5fb37775a82efbe6130aa">llvm::HexagonInstrInfo::immediateExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a38691dc780e36d270e9f13eeb4fdb28f">anonymous{DelaySlotFiller.cpp}::Filler::insertCallDefsUses</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a919a65c38470ee5665afa859cda18025">llvm::PPCInstrInfo::isADDIInstrEligibleForFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a75313c138825e233baef675bb1c5c43d">llvm::MipsInstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a2510546173c41b2a0bd6c02fedacb656">isAddSub2RegAndConstOnePair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#a3abad49282c799b7daeacb2b1bd5272b">isAnImmediateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d31fe3409ec7fc543b0adda6fa9b5f9">isConvertibleLEA</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sipeepholesdwa-cpp-/#a2bc160bdefcc7e1d3000ac78dcec0e0d">anonymous{SIPeepholeSDWA.cpp}::isConvertibleToSDWA</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a252a85dbac85d89e26fae5f8e3b87eff">llvm::MachineInstr::isDebugOffsetImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#aef241765e05d84992ebe4133862b899d">isFIPlusImmOrVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcndppcombine-cpp/#a2181ae65cf95609a855d58822f5ceb79">isIdentityValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae1d4c0d71423c8fa3d000f7518a4e8ae">llvm::PPCInstrInfo::isImmInstrEligibleForFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a835ce544e7ae111f1889501136ea6b3d">llvm::SIInstrInfo::isImmOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a10caa873ff6bab070fa0217d5402267b">llvm::SIInstrInfo::isInlineConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#afe78f37f6711d1eba5a7066809cae1b6">isInvariantStore</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a3d9b286b0c8c32ae52faedcc2a6130a7">llvm::SIInstrInfo::isLegalVSrcOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a2baf5026a86db8c593fb7d67cce0a741">llvm::HexagonInstrInfo::isLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcoptaddrmode-cpp/#a303e42b6e71e1993ab701f7f6f2d343f">isLoadStoreThatCanHandleDisplacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a7e62a05741edcd4375c97fd4906b419d">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::isOMod</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#a81d02aa4f2d890c694845de489bef4af">isRelevantAddressingMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#abac45c592b45439ab9adbc6eb936c6c4">isSafeToFoldImmIntoCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblydebugvaluemanager-cpp/#a0101767bf77660a28c873b7b06c2756e">isSameScalarConst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e3efa3451510c4dd3b0360251dd5128">llvm::isScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af8e19ecc6875baefa038d0b714d2313c">llvm::HexagonInstrInfo::isStoreToStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#a73660507cf04c478fea7b5f9b33ecd21">isValidDispOp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a3cf266e359a05a56bd9533dff30b3e12">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a175c0b6f2f4c39ae659845dcef17f71b">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerPATCHPOINT</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afe1802220ee7c164e882ade3d80f1845">llvm::MachineInstr::mayFoldInlineAsmRegOp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac786791624fc85886f2db5c5e0601f1b">llvm::SIInstrInfo::moveFlatAddrToVGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinescheduler-cpp/#ac516dd9d290b4fbd2b4cf47ba79c23d8">needReorderStoreMI</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a84ac77d42a2a87cb7ed8f4d401bfede7">anonymous{DelaySlotFiller.cpp}::Filler::needsUnimp</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a29513f18e551370b1b438f95403efc04">llvm::TargetInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#aa4f40e89e6342970562321ecb4439596">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#abd31e9ad15d84356f971b4c2340bbbd0">llvm::LoongArchAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a84d173786dab5c71b14eef5140521e07">llvm::MipsAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#a2ad9f20f96b8ee1142e75c4e7a5a9c9d">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a1a6d908f749f40987c9bd895ef5c7849">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a83f305aeeb35f8c2272405b7357059f2">llvm::AMDGPUAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6cff8e6e40904c8170d57f5307f73c20">llvm::ARMAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af865b91965a6c4e1082d1510228db5b5">llvm::AsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#ae87b9efb9db9ad27a0f5f7d753ce45fd">llvm::LoongArchAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a163b3801bc893a415f20cc091f7a246a">llvm::MipsAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#ae3bd1981fefcc9dadf49e90b2feef3be">llvm::X86AsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#a214541a34766cccead8dbfa6ed8f917f">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::printSrcMemOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a51b6112b4ae42ce9cd677fcb2bb1af19">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::processSeqRegInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6f29e4d965b091ebc05433240206eff">llvm::recomputeVPTBlockMask</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ae803619fba0f2282f638ddd36ba004de">llvm::SIRegisterInfo::resolveFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a983032106624c6c737b6d07bc4dcb3be">llvm::HexagonInstrInfo::setBundleNoShuf</a>, <a href="#a2feaa1c69335c6b9028076cd68c7a5f5">setImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1124ea4e69342296db6a2b6628121436">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryConstantFoldOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acab876eafd3f522831a5d002faecc72b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldZeroHighBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acd13e2195957a8e92e36d055dde1ffb8">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryToFoldACImm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97c94504ca3d3dcb826cd34ec463f98e">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsinstrinfo-cpp/#a1079ef998a5a34ef1215979a25a13ed3">verifyInsExtInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a6643db423ad018f2a7375b8f46e439af">llvm::RISCVInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a>.</p>

</div>
</div>

### isImplicit() {#a3bf161859e1ad7fd3da485d3cb688d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isImplicit ()</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#ab7263c22653c86a22ff72bc5385e8835">llvm::AggressiveAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a67f26cdb79c726f4616b1cd7ae1996cd">llvm::MachineInstr::copyImplicitOps</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aafc82eb49e1de126caa8907eaca9f46e">llvm::HexagonHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#ad60e02442ef62d5d7f19fd7f73aa0508">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::findRegistersToSpill</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aa88dfb98a274ef5f8da3ce147c8c45eb">llvm::PPCInstrInfo::getInstrLatency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#ae42ae7520e86040563aa828fc9d5eb91">getMopState</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9839b7e1d8811ea9d41f901ab6a0f23b">llvm::MachineInstr::getNumExplicitDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a56b7fed94faeb5bc67ee2b71608d2665">llvm::MachineInstr::getNumExplicitOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4cbbdd3795a958b1e24bd85cf48a0519">llvm::HexagonInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a597bb5d7ef9a22f44dbe867d8eaa7fd6">anonymous{InlineSpiller.cpp}::HoistSpillHelper::hoistAllSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a5c50c1e0000377affb5eec391c213df1">insertSEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a1403d0f29e96c05811fe277c8c68eae6">llvm::WebAssembly::isChild</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a857ec99c61bfc201bb60525234551102">llvm::SIInstrInfo::isIgnorableUse</a>, <a href="#a79d3c4a8df3c60d4d97cc39c300d69c0">isValidExcessOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a7687092765d6f25890cefb856f35b881">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/arcmcinstlower/#ab69d76329fbcf34e06d1e1119fa8c0f5">llvm::ARCMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ac63e4c740efa7b5b4426caa0de190af6">llvm::M68kMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcinstlower/#a5d6f8b2290183d7b3ae500dfce8fbb94">llvm::MipsMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoremcinstlower/#a16bd2e3d32444031e5abc6a96d562314">llvm::XCoreMCInstLower::LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#ae4bbe4c2ecf0ae95b3c4ffc3bb34ed07">llvm::XtensaAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a031c20be27e7c8b8bedd6345f209d7cb">printImplicitRegisterFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ad6408dc62ff8fa8de6c9c6daa57b897f">llvm::PPCInstrInfo::replaceInstrOperandWithImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kernelrewriter/#a2e7a99d381fd8c317ade905833ae3138">anonymous{ModuloSchedule.cpp}::KernelRewriter::rewrite</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizeexecmaskingprera-cpp-/sioptimizeexecmaskingprera/#a7e75a4f6568424bf0940a7c509a6d18c">anonymous{SIOptimizeExecMaskingPreRA.cpp}::SIOptimizeExecMaskingPreRA::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86speculativeloadhardening-cpp-/x86speculativeloadhardeningpass/#a862b3b4b5ed250fcfb2d6f9a130f4a0c">anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1f6067626e3318b8569835d83acbd92e">llvm::SIInstrInfo::usesConstantBus</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97c94504ca3d3dcb826cd34ec463f98e">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a9797c6d6b9fdb29489ea309649a0ef4a">VerifyLowRegs</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isInternalRead() {#ad3008c73231cdb4922d197fe56525364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isInternalRead ()</td>
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



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="#af2c351dad09a71aa08e1d85c67ae6e53">CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="#a3be9857a09c82046b77a71918b5e214f">readsReg</a>.</p>

</div>
</div>

### isIntrinsicID() {#a44f92ba840149cc7f75e38279341257a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isIntrinsicID ()</td>
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



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba9f104d16987b5384042276466fc2e003">MO_IntrinsicID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="#ad21d94ca6aa512e357a993e0e85a921e">getIntrinsicID</a>, <a href="#ace13d14a3578b2a7e81a5db41bbfde77">setIntrinsicID</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isJTI() {#a8eb9bf17230a1c4329e26935f44d72eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isJTI ()</td>
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

<p>isJTI - Tests if this is a MO_JumpTableIndex operand.</p>

<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">MO_JumpTableIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="#aaa68daaf8d7b773d012887c92c2023ce">getIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1562d024e0f385ec92982cd3493001d7">getJumpTableIndexFromAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmcinstlower-cpp/#a5d48c2fbd54413cd08a7ada69f05e7f2">GetSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#a73660507cf04c478fea7b5f9b33ecd21">isValidDispOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a55859f4a9f64b42f225c2f6c63212be5">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfmcinstlower/#ad8be4aad3f7a33a52b5c40cff98b5206">llvm::BPFMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaimcinstlower/#a9bdd6ed65ae27d68d065f712e0d281de">llvm::LanaiMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ab8310eee0e086d64c49733dd9da4171b">llvm::M68kMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430mcinstlower/#a8520755e983a50f3c24f91e0f8e06d03">llvm::MSP430MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#a5edb97651738551635eb05cc3f9fa77c">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrmcinstlower/#acb4de1517ebc1f8095f87eef68f290f7">llvm::AVRMCInstLower::lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a48efbf9c526eceb30f721ea086dc98fd">llvm::AArch64MCInstLower::lowerSymbolOperandCOFF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#ae4b8638e074c6af2301cd209d3d2021c">llvm::AArch64MCInstLower::lowerSymbolOperandMachO</a>, <a href="#aebc99c3c37896879abad49e7254a2fb8">setIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>.</p>

</div>
</div>

### isKill() {#a4046212ebc647b17e811837ae4ea3afd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isKill ()</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a185de6f70a894f044801931c4956150d">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtUse</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad61dd8c3be8a7f284aa7ac8f2c8bca5b">llvm::MachineInstr::clearRegisterKills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a3e1a0dd2de88c2c34c60cc5d4e127d94">copyFlagsToImplicitVCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="#af2c351dad09a71aa08e1d85c67ae6e53">CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6f42d93281a5cbf5360f836c09166c06">llvm::MachineInstr::findRegisterUseOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a9eb43774a0046a364f5c45f94576bc43">llvm::PPCInstrInfo::foldFrameOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6a733ae5364b0de2225af33223f383a5">llvm::TargetInstrInfo::foldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#af64fc386f3fc81f753830641399254b9">genFNegatedMAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad7dacfdd99d94fce20ccc2450bf5eb76">genFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a012040151268735433380829e4ef0dcd">genSubAdd2SubSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#ae42ae7520e86040563aa828fc9d5eb91">getMopState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="#a5c94b329f3cec9f4fd23db1d208c0bc8">hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a8c0efd377a713687b369602245dbe9da">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a75f3e392bd9cff57dcd444d521d7fd94">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp/#a3dd013ff6aef799059f3caafe7f9b968">isBackwardPropagatableCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aab9a96f10af025498520e00ff044bec1">llvm::MachineInstr::isIdenticalTo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae1d4c0d71423c8fa3d000f7518a4e8ae">llvm::PPCInstrInfo::isImmInstrEligibleForFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#a3b6f8318fa97ea96ea30725e31e85fea">isOperandKill</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a809bcfaa5a36e8e145a700b3e0e21926">llvm::PPCInstrInfo::isValidToBeChangedReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a68b7b9c491045c788173e83be1ba5d2b">llvm::TargetInstrInfo::lowerCopy</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7fc0854a9d3fced0dedf2c7f61fe7a72">preserveCondRegFlags</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a51b6112b4ae42ce9cd677fcb2bb1af19">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::processSeqRegInst</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a536d28604beba413c49c1f731df008a7">llvm::LiveVariables::removeVirtualRegistersKilled</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a8efbb19aded8e33e51da4553499bc975">UpdateCPSRUse</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#ac4d437dc2fa86f5a19219d3e8aa0d20b">updateKillStatus</a>.</p>

</div>
</div>

### isMBB() {#afe1784e242ce66da6029b3a681896bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isMBB ()</td>
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

<p>isMBB - Tests if this is a MO_MachineBasicBlock operand.</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">MO_MachineBasicBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a36c56da02f10d527ab7084e5d172d1d4">llvm::HexagonInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aedb2f85719d229f0c9bc62ab1d17e918">llvm::PPCInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#ac205677cbd92cecf1a6fcddb4798a12d">llvm::XtensaInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#afa8ce195c40d446fbe801e412cbd4634">llvm::HexagonInstrInfo::getDotNewPredJumpOp</a>, <a href="#a57e64b633278df75c699e6b98ce15031">getMBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#a094b53ae338bc1ed10ec35facf8e07b0">llvm::M68kMCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#aaec6e6ec16a011ef89299012d0dbe146">getTargetMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#adf62cb0814e5fb37775a82efbe6130aa">llvm::HexagonInstrInfo::immediateExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#a73660507cf04c478fea7b5f9b33ecd21">isValidDispOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a55859f4a9f64b42f225c2f6c63212be5">anonymous{X86MCInstLower.cpp}::X86MCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#ab8310eee0e086d64c49733dd9da4171b">llvm::M68kMCInstLower::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#a5edb97651738551635eb05cc3f9fa77c">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmcinstlower-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#a931cec5e0b9faa60b9b6943de522e49b">lowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a29513f18e551370b1b438f95403efc04">llvm::TargetInstrInfo::PredicateInstruction</a>, <a href="#a98e9c9e8ef7cbb6c4aa89a38f21decfa">setMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97c94504ca3d3dcb826cd34ec463f98e">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyInlineAsm</a>.</p>

</div>
</div>

### isMCSymbol() {#a143ff82a16da33c626da4949180e6b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isMCSymbol ()</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba17c8e891dacb2adc4a2d0ee5b10d6e9f">MO_MCSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsasmprinter-cpp/#a487192753b68b0e4380e9d999a5b1549">emitDirectiveRelocJalr</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a413a71e2c9cce53190ed87f9f7827ba4">llvm::MipsInstrInfo::genInstrWithNewOpc</a>, <a href="#af155da145e58791956c5e922e900fcb3">getMCSymbol</a>, <a href="#af624ff47eaa512dbe23866accb3837c1">getOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#a73660507cf04c478fea7b5f9b33ecd21">isValidDispOp</a>, <a href="#a79d3c4a8df3c60d4d97cc39c300d69c0">isValidExcessOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#abd31e9ad15d84356f971b4c2340bbbd0">llvm::LoongArchAsmPrinter::PrintAsmMemoryOperand</a> and <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a>.</p>

</div>
</div>

### isMetadata() {#a7bce8907b3cea3c34b9eeac6480bc955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isMetadata ()</td>
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

<p>isMetadata - Tests if this is a MO_Metadata operand.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639babf35c1c1ff9daae15b2dff8efa224623">MO_Metadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a08a3820d71cd895d5c69478fad30fd10">collectInlineAsmInstrOperands</a>, <a href="#a57b590606040d1c856a1d43aa0680364">getMetadata</a>, <a href="#a79d3c4a8df3c60d4d97cc39c300d69c0">isValidExcessOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a> and <a href="#a6a71dbedaff60bd7c648f0192c7184b0">setMetadata</a>.</p>

</div>
</div>

### isPredicate() {#a4039d2f36755814cb173552df270bddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isPredicate ()</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba3ab395cc24292a5e8e499e48f1553d94">MO_Predicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="#af0d32d967ac31c4e6149c2adb89aa947">getPredicate</a> and <a href="#ab1d6b6ca5842fa071bf1cb3510e1d0ba">setPredicate</a>.</p>

</div>
</div>

### isReg() {#a4c9594c955fec80c73ddd964b5efd554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isReg ()</td>
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

<p>isReg - Tests if this is a MO_Register operand.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">MO_Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#af6e18ff9d3e123fa8f958b846796e531">llvm::GISelInstProfileBuilder::addNodeIDMachineOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="#ace845d7da04db4610b2d051c7b44e832">addTargetFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6cdddfff71264f7e1e744fdea34085d3">llvm::ARMTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af408efad64e3aa0eef6c3a37c7794a83">llvm::MachineInstr::allDefsAreDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a39f79b8dd21fa75c7c273ebb9177a6a7">llvm::MachineInstr::allImplicitDefsAreDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">llvm::AnalyzeVirtRegInBundle</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a392dd12827c5ede927d490ccc16f38ab">llvm::BTFDebug::beginInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#a5a71ccecb00de06004fb421a568dd7b4">llvm::CriticalAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62f51194838248f650985e8299d7a97">llvm::buildAtomicCompareExchangeInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfe6e5ec3e8d8ad4632758a0af06b8f9">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpandermve/#a8b570f6c1b94d49245ad3cee2887acf3">llvm::ModuloScheduleExpanderMVE::canApply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a41d64a5fd52ca16e16ee50f916ab845a">canCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a8a77823ca1d474b22f9b923674749a14">canCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae77d286780a8c426db7adb6c10b9a643">canCombineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4ab4c0bfcb70883e983a325153b5a44e">llvm::HexagonInstrInfo::canExecuteInBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#aa9430ae4ad548095743aa0a26b235d82">llvm::AArch64InstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5f995c01e70eb23dbcd2af7d64a49fd8">llvm::RISCVInstrInfo::canFoldIntoAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#ac257b1d3de2b7254c046a5591191e26c">llvm::HexagonPacketizerList::canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#af848272aaea9ac1f976aaf56fd31cb8d">canRenameUpToDef</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae844768b9501609ab55c31b3c4f6ea5">llvm::SIInstrInfo::canShrink</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#aa577b8bdb7ed00babf58c076a4978f38">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::canUseImmWithOpSel</a>, <a href="#a8dcd3550374d734c49f2f09cfe59d92e">ChangeToBA</a>, <a href="#a937dbc7794a81ea51dc91c03feb931bc">ChangeToDbgInstrRef</a>, <a href="#a80025569f9c67b220c8938482944bbda">ChangeToES</a>, <a href="#a4355c32a39876f8305ede47c1d7220ff">ChangeToFPImmediate</a>, <a href="#a13b9c3d91aaffb22e0119f3467694b69">ChangeToFrameIndex</a>, <a href="#a83e996ed26eacbf3033314b3df58b133">ChangeToGA</a>, <a href="#a7b39ecfd6793534206dbb095b0d464c7">ChangeToImmediate</a>, <a href="#a62f6582318ed3f4d326b0d115316f7f0">ChangeToMCSymbol</a>, <a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a>, <a href="#a67cc3c894d3231db9636847712fa3171">ChangeToTargetIndex</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#a148883092b4d2dfdc994bc095ec153d7">anonymous{PPCMacroFusion.cpp}::checkOpConstraints</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ae26854c9925fc93880d644c0dcac8ba7">llvm::MachineInstr::clearKillInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad61dd8c3be8a7f284aa7ac8f2c8bca5b">llvm::MachineInstr::clearRegisterKills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a08a3820d71cd895d5c69478fad30fd10">collectInlineAsmInstrOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#adf5d3b4379e4e570f14f6700d6e87467">llvm::SIInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac7d08af4bb81846173b6186f568fcc8b">llvm::RegBankSelect::computeMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ab8b249a6f01a1f333bc2bfbc6463251c">llvm::PPCInstrInfo::convertToImmediateForm</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstoperand/#ae86f2900b76b99dd19e12c819c5449cd">anonymous{SIPeepholeSDWA.cpp}::SDWADstOperand::convertToSDWA</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a67f26cdb79c726f4616b1cd7ae1996cd">llvm::MachineInstr::copyImplicitOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ac915411e77e361580ea305fb31325">createCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#abe83de329645327b1d40bee0d304aff8">createCallWithOps</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ab69231adafff5e2e89dfae5a21ba246b">emitIndirectDst</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonhazardrecognizer/#aafc82eb49e1de126caa8907eaca9f46e">llvm::HexagonHazardRecognizer::EmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#a12db326dc5ce11745051db706e75a3e0">eraseGPOpnd</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kframelowering-cpp/#ae82cb5b8bd04147ce1ebe063f447c718">findDeadCallerSavedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a7ee47bba7fdfe2b4de0b767f6d493c26">findDefIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#ad60e02442ef62d5d7f19fd7f73aa0508">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::findRegistersToSpill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6f42d93281a5cbf5360f836c09166c06">llvm::MachineInstr::findRegisterUseOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a0402c8e75bccfb666de451d465cd0ac5">findUseIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4dc06d4fb42d48a6ade1958f76334826">llvm::ScheduleDAGInstrs::fixupKills</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#acf5910da93c4e01390c1e29b4a72836f">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldShiftedOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#aa8a34f3a734cc8a58ab08ce66250b1e1">fuseInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2475576febdb5d6a1929ef786a57a03">llvm::getAddressFromInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#af999ef1c23f3644af392a2b4633fa8f7">getArrayComponentCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee97b28988a36d015094f659294ef99d">llvm::getBlockStructInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#a5f4001f2227b1489a7588246ba7c8d54">getCallTargetRegOpnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a827d52327fbe1bd7bf22242e7c18847d">getDefRegMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a1f24abade2ffdb0e55559d552552692c">getFMAPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a56884e76d8fbf3b9f59ed904d50ba245">getFMULPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a23c3c91648996442b88f0c53cf1415d8">getFoldableImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#aa6438c766cdab5c1e26d802ef9ad14ff">getFPReg</a>, <a href="/web-llvm/docs/api/structs/llvm/machineinstrexpressiontrait/#a3344d356ddabbe21340a4b078300a789">llvm::MachineInstrExpressionTrait::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#af6194171586d2f1e13eb57765226d48a">getImmedFromMO</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#af196b990f6f506c44a4512bad4a36cef">getInstReadLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aa88dfb98a274ef5f8da3ce147c8c45eb">llvm::PPCInstrInfo::getInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/armregisterbankinfo/#af59ec25334715d44d5eecd8568b29e36">llvm::ARMRegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a8e8f884db0a3faadefc981023902a1ec">llvm::SIInstrInfo::getInstructionUniformity</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#acdf9051278b18a64c83cc047a3080de3">anonymous{LiveDebugVariables.cpp}::UserValue::getLocationNo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a054d573171c2fcf38b33a60e412dba7b">getMaddPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a515e8a223dcc58a4e478f70ec88d9520">llvm::HexagonInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a4870646ffc5b5a7d4425edd55d6f93de">llvm::X86InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7b433600072030cfe435557b2bd5f0ec">llvm::AArch64InstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a934f16bd434319b64e63ae8f622991ce">llvm::LanaiInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#abff39d910bc625295862cc04a7cd3c5e">llvm::PPCInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a675ef8fa9eef12d497fd0a57e931bd37">llvm::RISCVInstrInfo::getMemOperandWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#ad0d350086d0170ad8429e57516ba5a17">llvm::ReachingDefAnalysis::getMIOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fasttileconfig-cpp/#a10096b4ed26c2b9a8fe283a459e4d81e">getNumDefTiles</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9839b7e1d8811ea9d41f901ab6a0f23b">llvm::MachineInstr::getNumExplicitDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a56b7fed94faeb5bc67ee2b71608d2665">llvm::MachineInstr::getNumExplicitOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a4cbbdd3795a958b1e24bd85cf48a0519">llvm::HexagonInstrInfo::getOperandLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a9190a9fa370b0c81005613f21afed7d7">llvm::SIInstrInfo::getOpSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#add65febd7d533102fe2c2c2a7e244751">getPostIncrementOperand</a>, <a href="#ac0035d7c1c860501c877c20e6e93297b">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a88f8cb24fba67649c1f32531d0f6ab90">llvm::MachineInstr::getRegClassConstraintEffect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#acbfeec0c25233691b4e70d7a527eebda">getRegOrUndef</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a3cb505493f51b96cbb394d89b93f686e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::getRegSeqInit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac3cfa17f907e7258d898433ddfeb3fbf">llvm::RegBankSelect::getRepairCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#aef7abd9e585da4743700d2c04b17ab77">getShuffleComment</a>, <a href="#a028a8c5113d40d8c3f4427053bf36738">getSubReg</a>, <a href="#ab06dda088d3c7686f7dfcdb2b96323f5">getTargetFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ca6bbc21c19a9a6b005aff44ca8562f">llvm::getVRegSubRegDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a334e7c41df90efd700b045c03de6777d">anonymous{ARMLowOverheadLoops.cpp}::VPTState::hasImplicitlyValidVPT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervals-cpp/#a801fcd2cb84f0d0292a77e675c7c492c">hasLiveThroughUse</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#ab7919507c578187e698ff01a1f204478">llvm::RISCVInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6034cfb230c4698caa60bdc3a9bf209b">llvm::TargetInstrInfo::hasReassociableOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a5523ffd2d5ced60566f3493c2b48e0e3">hasRegisterDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad890cb0ba6262569913be1269acbf590">llvm::MachineInstr::hasRegisterImplicitUseOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#aa196bdc78cb3ed0506c143e872923858">hasSameBaseOpValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a597bb5d7ef9a22f44dbe867d8eaa7fd6">anonymous{InlineSpiller.cpp}::HoistSpillHelper::hoistAllSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a904f484cd7cfe20a0e7673399c88cc3c">llvm::MachineInstr::insert</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a38691dc780e36d270e9f13eeb4fdb28f">anonymous{DelaySlotFiller.cpp}::Filler::insertCallDefsUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaidelayslotfiller-cpp-/filler/#afca8ae34e03582f93e75d11b23cbe245">anonymous{LanaiDelaySlotFiller.cpp}::Filler::insertDefsUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a5c50c1e0000377affb5eec391c213df1">insertSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a195a0fee60fb5a1164767ec13d9729dd">llvm::AArch64InstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a4b5fcf3c38734c224904ec0203c965b1">llvm::ARMBaseInstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a75313c138825e233baef675bb1c5c43d">llvm::MipsInstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a89651558e264c97ec3977357ce4f0422">llvm::RISCVInstrInfo::isAddImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-cpp/#a32b9b3cc2b63db0558c672148f375cae">isArithmeticBccPair</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a596366d4034015c0668d2070e597425f">llvm::GIMatchTableExecutor::isBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a1403d0f29e96c05811fe277c8c68eae6">llvm::WebAssembly::isChild</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a6fbf0d819e9a71ced3199693268238ce">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::isClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#aa737e66804d935143b89db74d5646610">isConstReg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sipeepholesdwa-cpp-/#a2bc160bdefcc7e1d3000ac78dcec0e0d">anonymous{SIPeepholeSDWA.cpp}::isConvertibleToSDWA</a>, <a href="#aaee820701392c55ad54235d3d7201206">isDead</a>, <a href="#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">isDebug</a>, <a href="#a75eb135014670ce946e78739cdc9b51b">isDef</a>, <a href="#abd6aa9da048ef7a4faeaac6484d5c9a6">isEarlyClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-cpp/#aef241765e05d84992ebe4133862b899d">isFIPlusImmOrVGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#abefb312df5790c0f83c5e739316b9047">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::isGOTPLDpc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#aea53813ca1c1efc9ef06b5b9844be967">isIdenticalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aab9a96f10af025498520e00ff044bec1">llvm::MachineInstr::isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a6fe0144adffd7bad0aeca668f4468b28">isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#ae1d4c0d71423c8fa3d000f7518a4e8ae">llvm::PPCInstrInfo::isImmInstrEligibleForFolding</a>, <a href="#a3bf161859e1ad7fd3da485d3cb688d34">isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ae4c4f9c9cf73f1c869a1c0eae73c150f">llvm::MachineInstr::isIndirectDebugValue</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a10caa873ff6bab070fa0217d5402267b">llvm::SIInstrInfo::isInlineConstant</a>, <a href="#ad3008c73231cdb4922d197fe56525364">isInternalRead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelicm-cpp/#afe78f37f6711d1eba5a7066809cae1b6">isInvariantStore</a>, <a href="#a4046212ebc647b17e811837ae4ea3afd">isKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#aa5a8087086656299167f931f805778bb">isLdStSafeToCluster</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abecccbf97c3a9d0be384e6c639fcf2dc">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a2526f4f46289ec5bfb0201a6963b6a1b">llvm::HexagonPacketizerList::isLegalToPacketizeTogether</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#acbbc2f6b22e0c1dfd00546ef61cc0ac3">llvm::SIInstrInfo::isLegalToSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a3d9b286b0c8c32ae52faedcc2a6130a7">llvm::SIInstrInfo::isLegalVSrcOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmasking-cpp/#a53203d01639150127e4a03f777068276">isLogicalOpOnExec</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ab34a636a3a33052e76df78342c72627e">llvm::SMSchedule::isLoopCarriedDefOfUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#ae22fa2cc6eb289646143ffc4e1a7f3c2">isMaskOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#a7ee076808f65d7b724d9a94d48b2cee8">isMatchingStartStopPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#a342872157c6313a8196ae30b373f9f61">isMMSourceRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#ae235754dfc792615f66d369a52a1625a">isMMThreeBitGPRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a7e62a05741edcd4375c97fd4906b419d">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::isOMod</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#aa29ae3958e21ba305518fbad7c6ec004">llvm::GIMatchTableExecutor::isOperandImmEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a61053e705b1b4e91859a6c2ed7a60b64">llvm::M68kInstrInfo::isPCRelRegisterOperandLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-cpp/#aa1deebfd7340543a82ffa0e8303fd8a7">isRedundantFlagInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a5898b6ed934ad744eefecc5d5297a3a8">isRegInClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#aa196e9f76f5a5bdc8a8aca82f95cd2b3">isRegOrFI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a391694f8040173dc0670bd273b170502">llvm::MachineInstr::isRegTiedToDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6df9a6b70a33aee123056cec0ed052c4">llvm::MachineInstr::isRegTiedToUseOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#a81d02aa4f2d890c694845de489bef4af">isRelevantAddressingMode</a>, <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#a1c1669c081e93349baa5bcf3ca5aaae4">IsSafeAndProfitableToMove</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a2142c4566b7d15a35687f955d946a277">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::isSafetoMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#a6dd59c68c09f54df98dfea454a222fe1">isSVERegOp</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastpretileconfig-cpp/#ae94c5a52f65a4cd106e987ad131eddb2">isTileDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastpretileconfig-cpp/#a615f09a9d7f696517872c55ae51e0f58">isTileRegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4475ef8d36797ed68e422e259b7b4cf">llvm::HexagonInstrInfo::isToBeScheduledASAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp/#a11329b543886f5ac685e48ab2d45ee6c">isTwoAddrUse</a>, <a href="#a1255befbcd6e034394681b1bcd3529ff">isUndef</a>, <a href="#a69544ec8658eadeed98245dc37c3a541">isUse</a>, <a href="#a79d3c4a8df3c60d4d97cc39c300d69c0">isValidExcessOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a544e5e236fec930c7f0478c3f6e3b43e">isVirtualRegisterOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0673c8aeb9b580e1be469133adba37e5">llvm::SIInstrInfo::legalizeOperandsVOP3</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a4cb529d6108d5dfdf8479ac3b03c9812">llvm::SIInstrInfo::legalizeOpWithMove</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/operand-type-match/#a34433a396caf8cd75d115eb5a76a54e4">llvm::MIPatternMatch::operand_type_match::match</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa1cd7c807d2387bd9f8efe4a88cf1eb8">llvm::CombinerHelper::matchConstantFPOp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ac975f07f5ebdceac6c93312485b74af2">llvm::CombinerHelper::matchConstantOp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a0f3bc0c5478dd84e0831b5d78a274b47">llvm::CombinerHelper::matchEqualDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aab86990eacd037e1c72749c3342d410e">llvm::CombinerHelper::matchHoistLogicOpWithSameOpcodeHands</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmacrofusion-cpp-/#aafc3cb0155754ef1fb6ed53375e4d3dd">anonymous{PPCMacroFusion.cpp}::matchingRegOps</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#adf1110382dae21e5397a098cc5a08554">llvm::CombinerHelper::matchOperandIsUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#ae7773e6945ecc33b1e3ab0d47f293665">mergeOperations</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegencommonisel-cpp/#ad007531739421e7b54a41c3fefaefa4e">MIIsInTerminatorSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7overrides/#a4bb20a752a698ed16d84ddbc8abde037">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85overrides/#a32fabf22f4eddbf43f775ba273dde96e">llvm::anonymous{ARMLatencyMutations.cpp}::M85Overrides::modifyBypasses</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#adbc2dabbd1e76342acf894af01937c8a">oneUseDominatesOtherUses</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#afbc1088fd64459bec1157940aa59eb69">llvm::X86InstrInfo::optimizeLoadInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#adf35a52665d3f70d22acefe2846cb50f">anonymous{MIParser.cpp}::MIParser::parseMachineOperandAndTargetFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a29513f18e551370b1b438f95403efc04">llvm::TargetInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#aa4f40e89e6342970562321ecb4439596">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#aae9a08c74656cb725f4a193b38270780">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#abde207ef38a93406cc8cb0908d270969">llvm::ARMAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a94b063824e30c0f9c3e2a2f466f36ae0">llvm::AVRAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmprinter/#afc0dd8f7a1ebe899a2cd3eb553610f49">llvm::CSKYAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmprinter/#abd31e9ad15d84356f971b4c2340bbbd0">llvm::LoongArchAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a84d173786dab5c71b14eef5140521e07">llvm::MipsAsmPrinter::PrintAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#a2ad9f20f96b8ee1142e75c4e7a5a9c9d">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a1a6d908f749f40987c9bd895ef5c7849">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#a83f305aeeb35f8c2272405b7357059f2">llvm::AMDGPUAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6cff8e6e40904c8170d57f5307f73c20">llvm::ARMAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af865b91965a6c4e1082d1510228db5b5">llvm::AsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#abb1c33c814741adb78a9ff7f10ff3552">llvm::AVRAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a81e38a8f99bc74ae4acb4d135d1b7278">llvm::HexagonAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a163b3801bc893a415f20cc091f7a246a">llvm::MipsAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#aafef1c064474b274f8515a78234f99e1">llvm::SystemZAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#ae3bd1981fefcc9dadf49e90b2feef3be">llvm::X86AsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/bitsimplification/#a7ae2252105ba3f43b639d6648a219a85">anonymous{HexagonBitSimplify.cpp}::BitSimplification::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a62a1e2af50ab6132cd2d8d168835ef57">llvm::PPCInstrInfo::promoteInstr32To64ForElimEXTSW</a>, <a href="#a3be9857a09c82046b77a71918b5e214f">readsReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a374fc9d9064a93ef8a408f269d02389d">llvm::MachineInstr::readsWritesVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#ac1753e9184a776f25f017ac1022f2a13">TransferTracker::redefVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymcinstlower-cpp/#a35043b20e128ef142a010db3ff501a17">removeRegisterOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a536d28604beba413c49c1f731df008a7">llvm::LiveVariables::removeVirtualRegistersKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a40139f3ca5fa604f87136efa9ca611ca">llvm::RegBankSelect::RepairingPlacement::RepairingPlacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#aed1c1aa1329f36eef4940283a1d30859">rescheduleCanonically</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kernelrewriter/#a2e7a99d381fd8c317ade905833ae3138">anonymous{ModuloSchedule.cpp}::KernelRewriter::rewrite</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64storepairsuppress-cpp-/aarch64storepairsuppress/#ab876191f2b64955413fe0423a672c3b2">anonymous{AArch64StorePairSuppress.cpp}::AArch64StorePairSuppress::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/r600schedstrategy/#abe1c22281512c39286cbb9bca97ae7b8">llvm::R600SchedStrategy::schedNode</a>, <a href="#a10e708480cdc97c951368e06c13eac92">setImplicit</a>, <a href="#a61a42c85bd86c6ca4554e27d33c3f798">setIsDead</a>, <a href="#ab986279c9e6cf7ba9afd4c7da198bacf">setIsDebug</a>, <a href="#aed8d139ece631812f972a8cc074adc55">setIsDef</a>, <a href="#a9fcb795c017b82c1a259882b060ddc06">setIsEarlyClobber</a>, <a href="#a133a1aff6f7f6a9ea4f641adc88a120d">setIsInternalRead</a>, <a href="#a8a82683fccdef8a5ef772ef03277aee7">setIsKill</a>, <a href="#a48bcf9eb66f880de8e7f4d0fcc8af320">setIsRenamable</a>, <a href="#ab979122f21b7fa46d3d2d9b21983068b">setIsUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2afcfcff9187a2201549d75d4e16149">llvm::MachineInstr::setPhysRegsDeadExcept</a>, <a href="#a001d31fcea92be51d2999826b806606f">setSubReg</a>, <a href="#ad407b071bad6c9a435cade250ec8c8b6">setTargetFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adef06ef7e91c27f8cca2b635c3f1a178">llvm::PPCInstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae3e589c970e020448b5a5ade20d07d7e">shouldUseFormStridedPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a316803c463af8ba2c38182332fb3c8a4">SinkingPreventsImplicitNullCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9f59e1f6dd6677348ba082a10fc09061">llvm::MachineInstr::substituteRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a2929348b6b6f3ad543717d42b201640d">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldCndMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#ac9ca747a6b6297f53d182bfe78514963">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldFoldableCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a5e1eb00d7eee7258726795f01822d491">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldOMod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a7c842ead18aca7681bd1cd596a3c8ba3">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::tryMoveVGPRConstToSGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acd13e2195957a8e92e36d055dde1ffb8">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryToFoldACImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8e66e9ca7739874b25b9337940c26a0a">llvm::MachineInstr::untieRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdelayslotfiller-cpp-/regdefsuses/#a47c8a030926eca62aae974bb55ecd995">anonymous{MipsDelaySlotFiller.cpp}::RegDefsUses::update</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#ad6a7db5730cb47b326439993daad033e">UpdateCPSRDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a8efbb19aded8e33e51da4553499bc975">UpdateCPSRUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#ac4d437dc2fa86f5a19219d3e8aa0d20b">updateKillStatus</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a77dea00ee37a964ad5edf6072fb35071">UpdateOperandRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1216c0733931de570c17ed44556139bf">updateOperandRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a02230ca194a9c8e52170cc7c426decb2">UseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1f6067626e3318b8569835d83acbd92e">llvm::SIInstrInfo::usesConstantBus</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#afdb11d0b5d726b02916f412453587951">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateMVEInst</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a89e479535d719fb4ec8904104ec1e8ae">llvm::RegisterBankInfo::InstructionMapping::verify</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97c94504ca3d3dcb826cd34ec463f98e">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a6643db423ad018f2a7375b8f46e439af">llvm::RISCVInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a9797c6d6b9fdb29489ea309649a0ef4a">VerifyLowRegs</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a015233fe94a42e2294533334811ab899">llvm::MachineRegisterInfo::verifyUseList</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a9434209a25739262432f55e8fe33ccc7">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineInstrBefore</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isRegLiveOut() {#a9bc87d84f8ed5dccb4553a23d1b34843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isRegLiveOut ()</td>
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

<p>isRegLiveOut - Tests if this is a MO_RegisterLiveOut operand.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639bac72cbca4074e0bc4a26afc03db602da5">MO_RegisterLiveOut</a>.</p>


<p>Referenced by <a href="#a19b31bc5eda8ac4aeadf920d47aa6df0">getRegLiveOut</a>.</p>

</div>
</div>

### isRegMask() {#a55fdcb2a9df9a69067eed1bc17a0b927}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isRegMask ()</td>
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

<p>isRegMask - Tests if this is a MO_RegisterMask operand.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba48257b48932e88a230caff68469fd9f6">MO_RegisterMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a67f26cdb79c726f4616b1cd7ae1996cd">llvm::MachineInstr::copyImplicitOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a4dc06d4fb42d48a6ade1958f76334826">llvm::ScheduleDAGInstrs::fixupKills</a>, <a href="#ae6876d59aeec5bc210b359fbdcf6c1ad">getRegMask</a>, <a href="#a79d3c4a8df3c60d4d97cc39c300d69c0">isValidExcessOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2afcfcff9187a2201549d75d4e16149">llvm::MachineInstr::setPhysRegsDeadExcept</a>, <a href="#a34c5f27bf78b4d1ce93378885811bf54">setRegMask</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0909a505055aae0cb9dee8e5730b3724">llvm::MIRParserImpl::setupRegisterInfo</a>.</p>

</div>
</div>

### isRenamable() {#a8be49bc86b5d01b52b90baf1b4477667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineOperand::isRenamable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isRenamable - Returns true if this register may be renamed, i.e.</p>


<p>it does not generate a value that is somehow read in a way that is not represented by the Machine IR (e.g. to meet an ABI or ISA requirement). This is only valid on physical register operands. Virtual registers are assumed to always be renamable regardless of the value of this field.</p>


<p>Operands that are renamable can freely be changed to any other register that is a member of the register class returned by MI-&gt;getRegClassConstraint().</p>


<p>isRenamable can return false for several different reasons:</p>


<ul class="doxyList ">
<li>ABI constraints (since liveness is not always precisely modeled). We conservatively handle these cases by setting all physical register operands that didn’t start out as virtual regs to not be renamable. Also any physical register operands created after register allocation or whose register is changed after register allocation will not be renamable. This state is tracked in the MachineOperand::IsRenamable bit.</li>
<li>Opcode/target constraints: for opcodes that have complex register class requirements (e.g. that depend on other operands/instructions), we set hasExtraSrcRegAllocReq/hasExtraDstRegAllocReq in the machine opcode description. Operands belonging to instructions with opcodes that are marked hasExtraSrcRegAllocReq/hasExtraDstRegAllocReq return false from <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable()</a>. Additionally, the AllowRegisterRenaming target property prevents any operands from being marked renamable for targets that don't have detailed opcode hasExtraSrcRegAllocReq/hasExtraDstRegAllocReq values.</li>
</ul>

<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9719077fcba2cd439e84897257a47bb0">getParent</a>, <a href="#ac0035d7c1c860501c877c20e6e93297b">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a26e1467ec6a91a35dfc32239e50f0fb5aa87e833111cd757568924c1c4b80e337">llvm::MachineInstr::IgnoreBundle</a>, <a href="#a75eb135014670ce946e78739cdc9b51b">isDef</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a69544ec8658eadeed98245dc37c3a541">isUse</a>, <a href="#ae984860b88c448f0d8f7ac9b11077441">MachineInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="#af2c351dad09a71aa08e1d85c67ae6e53">CreateReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#ae42ae7520e86040563aa828fc9d5eb91">getMopState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp/#a3dd013ff6aef799059f3caafe7f9b968">isBackwardPropagatableCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a68b7b9c491045c788173e83be1ba5d2b">llvm::TargetInstrInfo::lowerCopy</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isShuffleMask() {#a81521682ef12b5e4f681502f9346a4ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isShuffleMask ()</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba512cc7de4a9ee26228ed614f8447d760">MO_ShuffleMask</a>.</p>


<p>Referenced by <a href="#a622dee2e5d865699df4407bd0bdbf903">getShuffleMask</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a>.</p>

</div>
</div>

### isSymbol() {#a7c5f0ef161b5b4dedad2e9aac9fcfee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isSymbol ()</td>
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

<p>isSymbol - Tests if this is a MO_ExternalSymbol operand.</p>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">MO_ExternalSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a8a08ac1d3e9758e48d542db8b3fc10ce">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitInstruction</a>, <a href="#af624ff47eaa512dbe23866accb3837c1">getOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#aaa9fafc42db7a667c344ce753b989101">GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#a094b53ae338bc1ed10ec35facf8e07b0">llvm::M68kMCInstLower::GetSymbolFromOperand</a>, <a href="#ab59b255f78cd503133d032152a41d105">getSymbolName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinelateinstrscleanup-cpp/#a1705fe175d6d933d516bee5ba700abaa">isCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a6be60178ba29200fe8a89e8da7e01326">llvm::HexagonInstrInfo::isConstExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#ae0bc5ec495ebea6b079d0546bee65f83">isSimilarDispOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#a73660507cf04c478fea7b5f9b33ecd21">isValidDispOp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ab6548436b77ac06129373db3d8e3dece">llvm::WebAssembly::mayThrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#a64e13a8c3c0d483c21941a99f473f8c2">optimizeCall</a> and <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a>.</p>

</div>
</div>

### isTargetIndex() {#ac0890848fb02b90b1f7956063bc61cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isTargetIndex ()</td>
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

<p>isTargetIndex - Tests if this is a MO_TargetIndex operand.</p>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639babb48fd8c9fa828e23f5d33f46cb0cbbb">MO_TargetIndex</a>.</p>


<p>Referenced by <a href="#aaa68daaf8d7b773d012887c92c2023ce">getIndex</a>, <a href="#af624ff47eaa512dbe23866accb3837c1">getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a835ce544e7ae111f1889501136ea6b3d">llvm::SIInstrInfo::isImmOperandLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a3d9b286b0c8c32ae52faedcc2a6130a7">llvm::SIInstrInfo::isLegalVSrcOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#af7ee4c22ed353efa8afd9ea35e4af06f">llvm::SIInstrInfo::isOperandLegal</a>, <a href="#aebc99c3c37896879abad49e7254a2fb8">setIndex</a> and <a href="#aa233a8fe996a2045f5b02f5161e145c2">setOffset</a>.</p>

</div>
</div>

### isTied() {#a894030fbf6d0f6c70991f05fff650930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isTied ()</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a658106b791878eeee6470ffb48c58c42">canRenameMOP</a>, <a href="#a8dcd3550374d734c49f2f09cfe59d92e">ChangeToBA</a>, <a href="#a937dbc7794a81ea51dc91c03feb931bc">ChangeToDbgInstrRef</a>, <a href="#a80025569f9c67b220c8938482944bbda">ChangeToES</a>, <a href="#a4355c32a39876f8305ede47c1d7220ff">ChangeToFPImmediate</a>, <a href="#a13b9c3d91aaffb22e0119f3467694b69">ChangeToFrameIndex</a>, <a href="#a83e996ed26eacbf3033314b3df58b133">ChangeToGA</a>, <a href="#a7b39ecfd6793534206dbb095b0d464c7">ChangeToImmediate</a>, <a href="#a62f6582318ed3f4d326b0d115316f7f0">ChangeToMCSymbol</a>, <a href="#a67cc3c894d3231db9636847712fa3171">ChangeToTargetIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a187aaa5a843dd80a268ebfd242a03284">llvm::TargetLoweringBase::emitPatchPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a904f484cd7cfe20a0e7673399c88cc3c">llvm::MachineInstr::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a391694f8040173dc0670bd273b170502">llvm::MachineInstr::isRegTiedToDefOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6df9a6b70a33aee123056cec0ed052c4">llvm::MachineInstr::isRegTiedToUseOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#a7e0bd1bbeb16dc218b79375aadf77b1d">isTiedToNotUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa37e31e5df481d2f8a6f9f022886cf5e">llvm::MachineInstr::tieOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8e66e9ca7739874b25b9337940c26a0a">llvm::MachineInstr::untieRegOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isUndef() {#a1255befbcd6e034394681b1bcd3529ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isUndef ()</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/phielimination-cpp/#a126f327d0727647f3daa7cf0da944f9e">allPhiOperandsUndefined</a>, <a href="#a9404d5d9e4be534bb544777aae216691">ChangeToRegister</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a3e1a0dd2de88c2c34c60cc5d4e127d94">copyFlagsToImplicitVCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#abe83de329645327b1d40bee0d304aff8">createCallWithOps</a>, <a href="#af2c351dad09a71aa08e1d85c67ae6e53">CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ab2790230883e599a288a12ded77463bc">llvm::HexagonInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a6203308c1da11d69cb3bd6c23b90b207">expandSHXDROT</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#ad60e02442ef62d5d7f19fd7f73aa0508">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::findRegistersToSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ac9883c9ec5baeee39d4215b9af8e0a70">findUseBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af1743a67877bf4ba56d53b235d3573e0">llvm::TargetInstrInfo::getExtractSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#afc76a889f289a0e841775d80aa0338ba">llvm::ARMBaseInstrInfo::getExtractSubregLikeInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#abea536f043de7994bc9b67c634a7c879">llvm::TargetInstrInfo::getInsertSubregInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abc8556ad731efc2f7a407169624d812e">llvm::ARMBaseInstrInfo::getInsertSubregLikeInputs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#af196b990f6f506c44a4512bad4a36cef">getInstReadLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siformmemoryclauses-cpp/#ae42ae7520e86040563aa828fc9d5eb91">getMopState</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#acbfeec0c25233691b4e70d7a527eebda">getRegOrUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae26cac7943070f09b4d7fa667d1adf95">llvm::TargetInstrInfo::getRegSequenceInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aba7f60edec8e7b982c598aa278f9420c">llvm::ARMBaseInstrInfo::getRegSequenceLikeInputs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5bbb47ecb2be0bf50b8cafb94dee081">llvm::getRegState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ca6bbc21c19a9a6b005aff44ca8562f">llvm::getVRegSubRegDef</a>, <a href="#a5c94b329f3cec9f4fd23db1d208c0bc8">hash_value</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#a181a7487eafd6c6972d51d10b2107101">anonymous{RISCVInsertVSETVLI.cpp}::hasUndefinedPassthru</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a76f8dfae3796fd187aebe3f8f60643ec">llvm::HexagonInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#a7e0bd1bbeb16dc218b79375aadf77b1d">isTiedToNotUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a68b7b9c491045c788173e83be1ba5d2b">llvm::TargetInstrInfo::lowerCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#ae7773e6945ecc33b1e3ab0d47f293665">mergeOperations</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7fc0854a9d3fced0dedf2c7f61fe7a72">preserveCondRegFlags</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#aa3fe888e13e687c808085c0cfba933c3">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneValues</a>, <a href="#a3be9857a09c82046b77a71918b5e214f">readsReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a374fc9d9064a93ef8a408f269d02389d">llvm::MachineInstr::readsWritesVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#ad6a7db5730cb47b326439993daad033e">UpdateCPSRDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#a8efbb19aded8e33e51da4553499bc975">UpdateCPSRUse</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isUse() {#a69544ec8658eadeed98245dc37c3a541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isUse ()</td>
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



<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a101c3c30a65314c6f3fe10fbc1fa1539">llvm::HexagonSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#af408efad64e3aa0eef6c3a37c7794a83">llvm::MachineInstr::allDefsAreDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a39f79b8dd21fa75c7c273ebb9177a6a7">llvm::MachineInstr::allImplicitDefsAreDead</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#a5a71ccecb00de06004fb421a568dd7b4">llvm::CriticalAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ae26854c9925fc93880d644c0dcac8ba7">llvm::MachineInstr::clearKillInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad61dd8c3be8a7f284aa7ac8f2c8bca5b">llvm::MachineInstr::clearRegisterKills</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e6b3672f7d7a310e9b45dc48d464ee8">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a6f42d93281a5cbf5360f836c09166c06">llvm::MachineInstr::findRegisterUseOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsoptimizepiccall-cpp/#a5f4001f2227b1489a7588246ba7c8d54">getCallTargetRegOpnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#af196b990f6f506c44a4512bad4a36cef">getInstReadLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a5523ffd2d5ced60566f3493c2b48e0e3">hasRegisterDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad890cb0ba6262569913be1269acbf590">llvm::MachineInstr::hasRegisterImplicitUseOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-delayslotfiller-cpp-/filler/#a38691dc780e36d270e9f13eeb4fdb28f">anonymous{DelaySlotFiller.cpp}::Filler::insertCallDefsUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaidelayslotfiller-cpp-/filler/#afca8ae34e03582f93e75d11b23cbe245">anonymous{LanaiDelaySlotFiller.cpp}::Filler::insertDefsUses</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a391694f8040173dc0670bd273b170502">llvm::MachineInstr::isRegTiedToDefOperand</a>, <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/twoaddressinstructionpass-cpp/#a11329b543886f5ac685e48ab2d45ee6c">isTwoAddrUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/reachingdefanalysis-cpp/#ac3b2a46d9d056196ea4b3d2be7b1dcb8">isValidRegUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="#a3be9857a09c82046b77a71918b5e214f">readsReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a374fc9d9064a93ef8a408f269d02389d">llvm::MachineInstr::readsWritesVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa37e31e5df481d2f8a6f9f022886cf5e">llvm::MachineInstr::tieOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb2sizereduction-cpp/#ad6a7db5730cb47b326439993daad033e">UpdateCPSRDef</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1f6067626e3318b8569835d83acbd92e">llvm::SIInstrInfo::usesConstantBus</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#afdb11d0b5d726b02916f412453587951">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateMVEInst</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isValidExcessOperand() {#a79d3c4a8df3c60d4d97cc39c300d69c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isValidExcessOperand ()</td>
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

<p>Return true if this operand can validly be appended to an arbitrary operand list.</p>


<p>i.e. this behaves like an implicit operand.</p>


<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="#a3bf161859e1ad7fd3da485d3cb688d34">isImplicit</a>, <a href="#a143ff82a16da33c626da4949180e6b1f">isMCSymbol</a>, <a href="#a7bce8907b3cea3c34b9eeac6480bc955">isMetadata</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a> and <a href="#a55fdcb2a9df9a69067eed1bc17a0b927">isRegMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### print() {#aedeaf186a99c875b4196318a4083ff77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo">TargetIntrinsicInfo</a> * IntrinsicInfo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> to <span class="doxyComputerOutput">os</span>.</p>


<p>Providing a valid <span class="doxyComputerOutput">TRI</span> and <span class="doxyComputerOutput">IntrinsicInfo</span> results in a more target-specific printing. If <span class="doxyComputerOutput">TRI</span> and <span class="doxyComputerOutput">IntrinsicInfo</span> are null, the function will try to pick it up from the parent.</p>


<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="#aedeaf186a99c875b4196318a4083ff77">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5cd55a3a92d69b01b8f899cb5ce9f786">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="#aedeaf186a99c875b4196318a4083ff77">print</a>, <a href="#a3f9d3159041bfbc33655256282b6afda">print</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a2fd58763bac8cd7e011630ae06d14656">anonymous{MachineVerifier.cpp}::MachineVerifier::report</a>.</p>

</div>
</div>

### print() {#a76123bb0e0b41f5dbae594726160db22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> TypeToPrint, std::optional&lt; unsigned &gt; OpIdx, bool PrintDef, bool IsStandalone, bool ShouldPrintRegisterTies, unsigned TiedOperandIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo">TargetIntrinsicInfo</a> * IntrinsicInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>More complex way of printing a <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TypeToPrint</td>
<td class="doxyParamItemDescription"><p>specifies the generic type to be printed on uses and defs. It can be determined using <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9dbc9a748353035febcc488160ba9956">MachineInstr::getTypeToPrint</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OpIdx</td>
<td class="doxyParamItemDescription"><p>- specifies the index of the operand in machine instruction. This will be used by target dependent MIR formatter. Could be std::nullopt if the index is unknown, e.g. called by <a href="#a71453c9c9ea541dab5841a0b590d56ee">dump()</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PrintDef</td>
<td class="doxyParamItemDescription"><p>- whether we want to print <span class="doxyComputerOutput">def</span> on an operand which isDef. Sometimes, if the operand is printed before '=', we don't print <span class="doxyComputerOutput">def</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsStandalone</td>
<td class="doxyParamItemDescription"><p>- whether we want a verbose output of the MO. This prints extra information that can be easily inferred when printing the whole function, but not when printing only a fragment of it.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ShouldPrintRegisterTies</td>
<td class="doxyParamItemDescription"><p>- whether we want to print register ties. Sometimes they are easily determined by the instruction's descriptor (MachineInstr::hasComplexRegiterTies can determine if it's needed).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TiedOperandIdx</td>
<td class="doxyParamItemDescription"><p>- if we need to print register ties this needs to provide the index of the tied register. If not, it will be ignored.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TRI</td>
<td class="doxyParamItemDescription"><p>- provide more target-specific information to the printer. Unlike the previous function, this one will not try and get the information from it's parent.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IntrinsicInfo</td>
<td class="doxyParamItemDescription"><p>- same as <span class="doxyComputerOutput">TRI</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aac36688686cd311fab09e6b55efb7f96">llvm::Intrinsic::getBaseName</a>, <a href="#a94f5b10f666acf5a0cddd5ac8302d0b8">getBlockAddress</a>, <a href="#a88c30c92aa9995b0cc70bfe60294ff65">getCFIIndex</a>, <a href="#a29e05cd075864928ae65e1751fdc346e">getCImm</a>, <a href="#aee59c647052fc9557561e596681da3c0">getFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#abb524f716e3a2a50acacf3e3df344662">llvm::BlockAddress::getFunction</a>, <a href="#a0fcdaab1a4c3134b8f80aa74cabeb970">getGlobal</a>, <a href="#a38b28a85f818b49d8806c150b8a5b4f7">getImm</a>, <a href="#aaa68daaf8d7b773d012887c92c2023ce">getIndex</a>, <a href="#a3ac9865fa1ab348b64b4366cfe103f74">getInstrRefInstrIndex</a>, <a href="#a082167d36582dece9770d881292f5cf6">getInstrRefOpIndex</a>, <a href="#ad21d94ca6aa512e357a993e0e85a921e">getIntrinsicID</a>, <a href="#a57e64b633278df75c699e6b98ce15031">getMBB</a>, <a href="#af155da145e58791956c5e922e900fcb3">getMCSymbol</a>, <a href="#a57b590606040d1c856a1d43aa0680364">getMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo/#a8294593b54352497d463272d9c268fcd">llvm::TargetIntrinsicInfo::getName</a>, <a href="#af624ff47eaa512dbe23866accb3837c1">getOffset</a>, <a href="#a9719077fcba2cd439e84897257a47bb0">getParent</a>, <a href="#af0d32d967ac31c4e6149c2adb89aa947">getPredicate</a>, <a href="#ac0035d7c1c860501c877c20e6e93297b">getReg</a>, <a href="#a19b31bc5eda8ac4aeadf920d47aa6df0">getRegLiveOut</a>, <a href="#ae6876d59aeec5bc210b359fbdcf6c1ad">getRegMask</a>, <a href="#a622dee2e5d865699df4407bd0bdbf903">getShuffleMask</a>, <a href="#a028a8c5113d40d8c3f4427053bf36738">getSubReg</a>, <a href="#ab59b255f78cd503133d032152a41d105">getSymbolName</a>, <a href="#a2a1f57ce725829ceacb0068b4b5f2d2a">getTargetIndexName</a>, <a href="#ab313591ae4ea1e3a4ab59121a7dc2a2b">getType</a>, <a href="#aaee820701392c55ad54235d3d7201206">isDead</a>, <a href="#a75eb135014670ce946e78739cdc9b51b">isDef</a>, <a href="#abd6aa9da048ef7a4faeaac6484d5c9a6">isEarlyClobber</a>, <a href="#a3bf161859e1ad7fd3da485d3cb688d34">isImplicit</a>, <a href="#ad3008c73231cdb4922d197fe56525364">isInternalRead</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad73f009e1b3b060bcdf6c2c1dd86600e">llvm::CmpInst::isIntPredicate</a>, <a href="#a4046212ebc647b17e811837ae4ea3afd">isKill</a>, <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable</a>, <a href="#a894030fbf6d0f6c70991f05fff650930">isTied</a>, <a href="#a1255befbcd6e034394681b1bcd3529ff">isUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="#ae42703e0d4c147a9765234011797f5dd">MachineRegisterInfo</a>, <a href="#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">MO_BlockAddress</a>, <a href="#af269b990800f72c7cf535c407e8e639ba0270d8f468e7b92dafb486293ecf137d">MO_CFIIndex</a>, <a href="#af269b990800f72c7cf535c407e8e639ba5cc9e17457a92caa963ed784d83f6233">MO_CImmediate</a>, <a href="#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">MO_ConstantPoolIndex</a>, <a href="#af269b990800f72c7cf535c407e8e639ba87cf4128c65c3799c2189ceb3fb62bd3">MO_DbgInstrRef</a>, <a href="#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">MO_ExternalSymbol</a>, <a href="#af269b990800f72c7cf535c407e8e639bac4edc21072344f5aafa2a8f307c78b81">MO_FPImmediate</a>, <a href="#af269b990800f72c7cf535c407e8e639ba97561985119c4a774e3ec6439240fa80">MO_FrameIndex</a>, <a href="#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">MO_GlobalAddress</a>, <a href="#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">MO_Immediate</a>, <a href="#af269b990800f72c7cf535c407e8e639ba9f104d16987b5384042276466fc2e003">MO_IntrinsicID</a>, <a href="#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">MO_JumpTableIndex</a>, <a href="#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">MO_MachineBasicBlock</a>, <a href="#af269b990800f72c7cf535c407e8e639ba17c8e891dacb2adc4a2d0ee5b10d6e9f">MO_MCSymbol</a>, <a href="#af269b990800f72c7cf535c407e8e639babf35c1c1ff9daae15b2dff8efa224623">MO_Metadata</a>, <a href="#af269b990800f72c7cf535c407e8e639ba3ab395cc24292a5e8e499e48f1553d94">MO_Predicate</a>, <a href="#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">MO_Register</a>, <a href="#af269b990800f72c7cf535c407e8e639bac72cbca4074e0bc4a26afc03db602da5">MO_RegisterLiveOut</a>, <a href="#af269b990800f72c7cf535c407e8e639ba48257b48932e88a230caff68469fd9f6">MO_RegisterMask</a>, <a href="#af269b990800f72c7cf535c407e8e639ba512cc7de4a9ee26228ed614f8447d760">MO_ShuffleMask</a>, <a href="#af269b990800f72c7cf535c407e8e639babb48fd8c9fa828e23f5d33f46cb0cbbb">MO_TargetIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#abea60f56bef2a0f9437eed8c8bb9ec58">llvm::Metadata::printAsOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a62213d5211c9d944e5ede1f0059a6ae2">llvm::Value::printAsOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a294946bd7b49d5ef31f4f42120f75b92">printFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#aab0de54b603828aac17031e3d6c8ce17">llvm::MIRFormatter::printImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a39e0c396e9ae881eddc29a02ebc40956">printIRBlockReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4610639927aff734aeacb607c43f01f2">llvm::printJumpTableEntryReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef01c7734472703b7f3d76c5af23e1d3">llvm::printLLVMNameWithoutPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#a91a415f70087b68402bb454cc1b8fa18">printOperandOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84f1f18b0f13167b8e9c455b9524b58d">llvm::printRegClassOrBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a390a2d47af94ecd445ec74a3fdadca5a">PrintRegMaskNumRegs</a>, <a href="#af04079051720988fb6801f962d034e03">printSymbol</a>, <a href="#a3bdc6bcbf7eec4329ba1b6c91ff776d8">printTargetFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### print() {#a3f9d3159041bfbc33655256282b6afda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> TypeToPrint, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetintrinsicinfo">TargetIntrinsicInfo</a> * IntrinsicInfo=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as print(os, TRI, IntrinsicInfo), but allows to specify the low-level type to be printed the same way the full version of print(...) does it.</p>

<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="#aedeaf186a99c875b4196318a4083ff77">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#ab48e3dab3c79330a34264424247f0276">tryToGetTargetInfo</a>.</p>

</div>
</div>

### readsReg() {#a3be9857a09c82046b77a71918b5e214f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::readsReg ()</td>
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

<p>readsReg - Returns true if this operand reads the previous value of its register.</p>


<p>A use operand with the &lt;undef&gt; flag set doesn't read its register. A sub-register def implicitly reads the other parts of the register being redefined unless the &lt;undef&gt; flag is set.</p>


<p>This refers to reading the register value from before the current instruction or bundle. Internal bundle reads are not included.</p>


<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a028a8c5113d40d8c3f4427053bf36738">getSubReg</a>, <a href="#ad3008c73231cdb4922d197fe56525364">isInternalRead</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#a1255befbcd6e034394681b1bcd3529ff">isUndef</a> and <a href="#a69544ec8658eadeed98245dc37c3a541">isUse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">llvm::AnalyzeVirtRegInBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetschedule-cpp/#a0402c8e75bccfb666de451d465cd0ac5">findUseIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a51539193cc8ad7ae2884993bbb57ddea">llvm::ARMBaseInstrInfo::getPartialRegUpdateClearance</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#af94193776566ea8e90fc662cb038b0a1">llvm::X86InstrInfo::getPartialRegUpdateClearance</a>.</p>

</div>
</div>

### setCImm() {#aae70dd97002db997dfc96303fa9e6971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setCImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * CI)</td>
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



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a32ea768fbb182d6bbe3ff85ae1eb7031">isCImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### setFPImm() {#a3e326b0a22f9a7042019531da7987ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setFPImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * CFP)</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#afcb818bd3e34498f8f72ca555a36d5eb">isFPImm</a>.</p>

</div>
</div>

### setImm() {#a2feaa1c69335c6b9028076cd68c7a5f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setImm (int64_t immVal)</td>
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



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a76f61c6784df6dc8402a8b9011041926">isImm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a54891e94b588b8ba0ba2586547e17e31">llvm::R600InstrInfo::addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#aca2b6568c134ce283d74d23db8d6b665">llvm::R600InstrInfo::buildSlotOfVectorInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#afb8b734da10672ff4ffc3ec7bf04ec1d">llvm::R600InstrInfo::clearFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#af76e71e7ea189719baa6f8819724fac5">llvm::ARMBaseInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwasrcoperand/#a8257623efa7db9d91500e6ea06cb9027">anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::convertToSDWA</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyregisterinfo/#a730597be2894305014350ccb7800b3b5">llvm::WebAssemblyRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktaggingprera-cpp-/aarch64stacktaggingprera/#a7e7be476481e8e24c35c332a9e6e26ad">anonymous{AArch64StackTaggingPreRA.cpp}::AArch64StackTaggingPreRA::findFirstSlotCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a69a17a573c98c5ac8ff9fedcc9099807">fixupCalleeSaveRestoreStackOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a76635e63bbdb187ca4030f7570158552">fixupSEHOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a9eb43774a0046a364f5c45f94576bc43">llvm::PPCInstrInfo::foldFrameOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a08517d2919480dbf25deba8c5306dd39">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a9fcd68a333f3123b4b1cfb871ef3d89a">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aba82e76518953661f6dcb009c73e1a1f">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::generateWaitcnt</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a648e69f41d62376b996b0b5209022fbd">llvm::R600InstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ac6d61a8fec7e62b7b19947fe5820860d">llvm::ARMBaseInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a29513f18e551370b1b438f95403efc04">llvm::TargetInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ae97bb6b91cff3e18475ab68012287cc2">llvm::SystemZInstrInfo::prepareCompareSwapOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzshorteninst-cpp-/systemzshorteninst/#a38b3d652a50cfafb01e63dca05a1f489">anonymous{SystemZShortenInst.cpp}::SystemZShortenInst::processBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6f29e4d965b091ebc05433240206eff">llvm::recomputeVPTBlockMask</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ae803619fba0f2282f638ddd36ba004de">llvm::SIRegisterInfo::resolveFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a03c6876ed7ada0d971240509db503dc0">llvm::R600InstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600controlflowfinalizer-cpp-/r600controlflowfinalizer/#aab0c0f47a6a686867561fa0275a393b1">anonymous{R600ControlFlowFinalizer.cpp}::R600ControlFlowFinalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a983032106624c6c737b6d07bc4dcb3be">llvm::HexagonInstrInfo::setBundleNoShuf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2f4e57397c15057e80f3edaeca9377f4">swapImmOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a64f165f45ca62b4d27bde48f484897da">llvm::SIInstrInfo::swapSourceModifiers</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a08bf0b055eab1a86300c18c2b0f9fc7e">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a5e1eb00d7eee7258726795f01822d491">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldOMod</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinsertwaitcnts-cpp/#a76c206acce516598d664c520bf1223a9">updateOperandIfDifferent</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aae9fa37b9f18ba0e8f4c2342d4346494">updateOperands</a>.</p>

</div>
</div>

### setImplicit() {#a10e708480cdc97c951368e06c13eac92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setImplicit (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad88bfb92ca2f7d419adc7e6645406a7c">llvm::SIInstrInfo::insertVectorSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a798b9343e8af92bf7dc5fc20b4f4ffbd">makeImplicit</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a567798554f5c662fc4a85150a9058b69">llvm::ARMBaseInstrInfo::optimizeSelect</a> and <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a6817e8885f6d121b601aeff0a59677fd">llvm::LanaiInstrInfo::optimizeSelect</a>.</p>

</div>
</div>

### setIndex() {#aebc99c3c37896879abad49e7254a2fb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setIndex (int Idx)</td>
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



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5b401e780c5eed0aca1cfbf44d36a545">isCPI</a>, <a href="#ad7213433bd60dc33020246384dc18b9b">isFI</a>, <a href="#a8eb9bf17230a1c4329e26935f44d72eb">isJTI</a> and <a href="#ac0890848fb02b90b1f7956063bc61cb3">isTargetIndex</a>.</p>


<p>Referenced by <a href="#a13b9c3d91aaffb22e0119f3467694b69">ChangeToFrameIndex</a>, <a href="#a67cc3c894d3231db9636847712fa3171">ChangeToTargetIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a977522c71b9c7099aa74222cc12bbf17">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::findInRangeCPEntry</a> and <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>.</p>

</div>
</div>

### setInstrRefInstrIndex() {#a0c47183dc58b861a7b12c97f0a40312b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setInstrRefInstrIndex (unsigned InstrIdx)</td>
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



<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad04e186512436ffdefdb16ed8aaea57a">isDbgInstrRef</a>.</p>


<p>Referenced by <a href="#a937dbc7794a81ea51dc91c03feb931bc">ChangeToDbgInstrRef</a>.</p>

</div>
</div>

### setInstrRefOpIndex() {#a20d16082ca624c29bb20bc0671d48408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setInstrRefOpIndex (unsigned OpIdx)</td>
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



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ad04e186512436ffdefdb16ed8aaea57a">isDbgInstrRef</a>.</p>


<p>Referenced by <a href="#a937dbc7794a81ea51dc91c03feb931bc">ChangeToDbgInstrRef</a>.</p>

</div>
</div>

### setIntrinsicID() {#ace13d14a3578b2a7e81a5db41bbfde77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setIntrinsicID (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID)</td>
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



<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a44f92ba840149cc7f75e38279341257a">isIntrinsicID</a>.</p>

</div>
</div>

### setIsDead() {#a61a42c85bd86c6ca4554e27d33c3f798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setIsDead (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siframelowering-cpp/#a544e5e38d5032dd862ab44953c2c173b">buildScratchExecCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad4a32b52ea36d2c35a9860fe263d0574">llvm::MachineInstr::clearRegisterDeads</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ef020b54917711fa4fbe9b8ad48258b">llvm::SIInstrInfo::insertScratchExecCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblypeephole-cpp/#a838442534a7db8c9a083268f8df2d342">maybeRewriteToDrop</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a241b0b6bb1961190125114fb88db4a27">llvm::SIInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#aa3fe888e13e687c808085c0cfba933c3">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneValues</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#aa86a4d647e79dbdeb3d2d43ec301abcd">llvm::SGPRSpillBuilder::readWriteTmpVGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a3bbf276657ebe5de723f93bc95498b6f">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::removeRedundantLIs</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a535388ac574e0f8d844662d315997b3d">llvm::X86FrameLowering::restoreWin32EHStackPointers</a>, <a href="/web-llvm/docs/api/classes/anonymous-sishrinkinstructions-cpp-/sishrinkinstructions/#a2d4969e8e07a8085b166f5b83efc5a8c">anonymous{SIShrinkInstructions.cpp}::SIShrinkInstructions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86speculativeloadhardening-cpp-/x86speculativeloadhardeningpass/#a862b3b4b5ed250fcfb2d6f9a130f4a0c">anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a45ffb8b95e5b75eeb68be7d300eb9618">llvm::MachineInstrBuilder::setOperandDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2afcfcff9187a2201549d75d4e16149">llvm::MachineInstr::setPhysRegsDeadExcept</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ac671c3b34aac49144d2688fd6ed160bc">llvm::X86InstrInfo::setSpecialOperandAttr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzinstrinfo-cpp/#a24181d1b7cdfbb8fd9710139d861ca6c">transferDeadCC</a>.</p>

</div>
</div>

### setIsDebug() {#ab986279c9e6cf7ba9afd4c7da198bacf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setIsDebug (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>.</p>

</div>
</div>

### setIsDef() {#aed8d139ece631812f972a8cc074adc55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::setIsDef (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change a def to a use, or a use to a def.</p>

<p>Declaration at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a>, <a href="#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">isDebug</a>, <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>, <a href="#ae42703e0d4c147a9765234011797f5dd">MachineRegisterInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6cdddfff71264f7e1e744fdea34085d3">llvm::ARMTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd46906c25e4d5703a8e422283d03bde">llvm::RevertLoopDec</a> and <a href="#a05dc03b6c9921f34aaa7a20c46589a95">setIsUse</a>.</p>

</div>
</div>

### setIsEarlyClobber() {#a9fcb795c017b82c1a259882b060ddc06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setIsEarlyClobber (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a469e271fba3a9b52dad4fa54eaf44e2b">llvm::MachineInstr::addOperand</a>.</p>

</div>
</div>

### setIsInternalRead() {#a133a1aff6f7f6a9ea4f641adc88a120d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setIsInternalRead (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### setIsKill() {#a8a82683fccdef8a5ef772ef03277aee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setIsKill (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">isDebug</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e9425c046cf742bfbb9ebb96466d8e5">llvm::ScheduleDAGInstrs::addPhysRegDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a084d504a7f8b42657e1c910ba098ad94">clearKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ae26854c9925fc93880d644c0dcac8ba7">llvm::MachineInstr::clearKillInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad61dd8c3be8a7f284aa7ac8f2c8bca5b">llvm::MachineInstr::clearRegisterKills</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0e3a31dc0490f96016dc6f83eb363213">llvm::PPCInstrInfo::combineRLWINM</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwasrcoperand/#a8257623efa7db9d91500e6ea06cb9027">anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::convertToSDWA</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ae780082016f8641ba5a18009b135d01e">llvm::R600InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad73e9b3e610bd8cac60e740a61fcf5bf">llvm::SIInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a8c0efd377a713687b369602245dbe9da">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a75f3e392bd9cff57dcd444d521d7fd94">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#accc5aa5171b3bf3b455bbbac12dd405e">llvm::X86InstrInfo::loadStoreTileReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4da36cb65ef881f12fe1d40a47223a61">MoveVPNOTBeforeFirstUser</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7fc0854a9d3fced0dedf2c7f61fe7a72">preserveCondRegFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a3bbf276657ebe5de723f93bc95498b6f">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::removeRedundantLIs</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a536d28604beba413c49c1f731df008a7">llvm::LiveVariables::removeVirtualRegistersKilled</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonnewvaluejump-cpp-/hexagonnewvaluejump/#a59b6a751c071a2b0a6c3d5617fb83719">anonymous{HexagonNewValueJump.cpp}::HexagonNewValueJump::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a553d8629e18f8acb82dbadd0a160b877">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldRegSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#ac4d437dc2fa86f5a19219d3e8aa0d20b">updateKillStatus</a>.</p>

</div>
</div>

### setIsRenamable() {#a48bcf9eb66f880de8e7f4d0fcc8af320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::setIsRenamable (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac0035d7c1c860501c877c20e6e93297b">getReg</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>.</p>

</div>
</div>

### setIsUndef() {#ab979122f21b7fa46d3d2d9b21983068b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setIsUndef (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a10acc9310a21d9a8191d3d84916bdffb">llvm::ScheduleDAGInstrs::addVRegDefDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad73e9b3e610bd8cac60e740a61fcf5bf">llvm::SIInstrInfo::insertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#ae7773e6945ecc33b1e3ab0d47f293665">mergeOperations</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a7fc0854a9d3fced0dedf2c7f61fe7a72">preserveCondRegFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#aa3fe888e13e687c808085c0cfba933c3">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneValues</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a05427132a2cb380432ed752b5f2dea6b">llvm::MachineInstr::setRegisterDefReadUndef</a>, <a href="#a9842e6805ce84262b6bbe7da2b26772c">substPhysReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### setIsUse() {#a05dc03b6c9921f34aaa7a20c46589a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setIsUse (bool Val=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#aed8d139ece631812f972a8cc074adc55">setIsDef</a>.</p>

</div>
</div>

### setMBB() {#a98e9c9e8ef7cbb6c4aa89a38f21decfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afe1784e242ce66da6029b3a681896bd2">isMBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afa907eb6ba127a5f4167f5a1671efed0">llvm::CombinerHelper::applyOptBrCondByInvertingCond</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a222d82bcc0b1cb30a36ed1bf3bbeac63">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3e3daf4218b791b2796b808627b7f864">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a2a11298ee3a7cfcfa678f8b9a3df20db">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::moveAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a29513f18e551370b1b438f95403efc04">llvm::TargetInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a134a21189d056b81b80d0cdf01ef8c46">llvm::MachineBasicBlock::replacePhiUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#ac47046162deb21d43512581afc16fa7c">updatePHIs</a>.</p>

</div>
</div>

### setMetadata() {#a6a71dbedaff60bd7c648f0192c7184b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * MD)</td>
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



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7bce8907b3cea3c34b9eeac6480bc955">isMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1f42f634cff46c0380f80cc600c19f3b">llvm::updateDbgValueForSpill</a>.</p>

</div>
</div>

### setOffset() {#aa233a8fe996a2045f5b02f5161e145c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setOffset (int64_t Offset)</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abed9003622087a5bbddb7c19b6d02ce6">isBlockAddress</a>, <a href="#a5b401e780c5eed0aca1cfbf44d36a545">isCPI</a>, <a href="#ab0d1155c8c38e84cbe387998fd2e517e">isGlobal</a>, <a href="#a143ff82a16da33c626da4949180e6b1f">isMCSymbol</a>, <a href="#a7c5f0ef161b5b4dedad2e9aac9fcfee7">isSymbol</a>, <a href="#ac0890848fb02b90b1f7956063bc61cb3">isTargetIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a8dcd3550374d734c49f2f09cfe59d92e">ChangeToBA</a>, <a href="#a80025569f9c67b220c8938482944bbda">ChangeToES</a>, <a href="#a83e996ed26eacbf3033314b3df58b133">ChangeToGA</a>, <a href="#a67cc3c894d3231db9636847712fa3171">ChangeToTargetIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#abdd08d782bfb8c6b53e27485a53a3477">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldOffset</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>.</p>

</div>
</div>

### setPredicate() {#ab1d6b6ca5842fa071bf1cb3510e1d0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setPredicate (unsigned Predicate)</td>
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



<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4039d2f36755814cb173552df270bddc">isPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a321f2dfbd709348cfd0e1ab66cf0b62c">llvm::CombinerHelper::applyNotCmp</a>.</p>

</div>
</div>

### setReg() {#a682ba82f42f7903d0000ffbb13ea3b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::setReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the register this operand corresponds to.</p>

<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a>, <a href="#ac0035d7c1c860501c877c20e6e93297b">getReg</a>, <a href="#ae42703e0d4c147a9765234011797f5dd">MachineRegisterInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6cdddfff71264f7e1e744fdea34085d3">llvm::ARMTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a83aa1663ebe23169979a76be989b1144">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::adjustTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a3fa089137317e93276cab5774d4bf11f">llvm::SwingSchedulerDAG::applyInstrChange</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afa907eb6ba127a5f4167f5a1671efed0">llvm::CombinerHelper::applyOptBrCondByInvertingCond</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aaa02ab5ab2c50cce96f4fec73c8186c3">llvm::LegalizerHelper::bitcastDst</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#aca2b6568c134ce283d74d23db8d6b665">llvm::R600InstrInfo::buildSlotOfVectorInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a9d84441ae7638d9c27873f5a3810cb88">castBufferRsrcArgToV4I32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a78249707a06ea5161d8c6bbb442ea46c">castBufferRsrcFromV4I32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6b1057a57ff0d013cd3a78bb69f43db2">cloneInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblydebugvaluemanager/#a93c989266fe445bd8d6466480699665e">llvm::WebAssemblyDebugValueManager::cloneSink</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/classes/regbankselecthelper/#ae56b2250d41c0820f12319e553d76084">RegBankSelectHelper::constrainRegBankUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a9acef535219004fa4c89f4f996343b6f">copySubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#acd7a7dc7a2d3ba79fe5ee12378638317">llvm::SIRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acd9a409ba62041c36090fe42bfdf16d7">llvm::M68kInstrInfo::ExpandCCR</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a090d5d72da6a965488b7e9ec04f04c33">llvm::M68kInstrInfo::ExpandMOVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0d585a5fdebc1deeffc750a2a3308d89">ExpandMOVImmSExti8</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#acf82a3fa2657200bf3068a0273939229">llvm::M68kInstrInfo::ExpandMOVSZX_RM</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a6388048852214c02aa209e16f10b588a">llvm::M68kInstrInfo::ExpandMOVX_RR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#acf2585460bbea1e2bac210c9588d4bc4">expandNOVLXLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a44f31fb5ea31b5062b22b05cb8fddee4">expandNOVLXStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a5ba48cabad5945f96c69984f907e4fa0">llvm::X86InstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/swingschedulerdag/#a51bda1806219d879123625c8d4ae3fbc">llvm::SwingSchedulerDAG::fixupRegisterOverlaps</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a2222b2a89839a157c1b2992743effe">llvm::insertAssignInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a23855b574f5790880e0cdfc2b6b39aad">llvm::SIInstrInfo::legalizeOperandsFLAT</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad5c2911f44ee301ccf57ae61b7915b5a">llvm::SIInstrInfo::legalizeOperandsSMRD</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#accc5aa5171b3bf3b455bbbac12dd405e">llvm::X86InstrInfo::loadStoreTileReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblypeephole-cpp/#a838442534a7db8c9a083268f8df2d342">maybeRewriteToDrop</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#acfa23971275a6efd8097dd91be42ee3b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergePairedInsns</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a25a4c14864c6f574bc99e19e15a8b4d2">llvm::LegalizerHelper::moreElementsVectorDst</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac465c012a999bcab06235573fcb0860f">llvm::LegalizerHelper::moreElementsVectorSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aae3719bc967fb84bbbd69ac597866ea1">llvm::SIInstrInfo::moveToVALUImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad7f8e31fdc4b07d287c52567a2d259f4">llvm::LegalizerHelper::narrowScalarDst</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a5cafcb9996d69b6f864daa6c7d00c48a">llvm::LegalizerHelper::narrowScalarSrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a4501178e61d2f154d7b9bc4fc519fe68">llvm::R600InstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a29513f18e551370b1b438f95403efc04">llvm::TargetInstrInfo::PredicateInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#a83cbf55cc29b8e364bc11d81165caaed">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::processBlock</a>, <a href="/web-llvm/docs/api/classes/regbankselecthelper/#a9c19f0d81ecc0282828c546f12bc5b36">RegBankSelectHelper::reAssignRegBankOnDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#aeae677889401c02a8def9a0508e858c7">reinsertVectorIndexAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a290f07593ec0820655db5efe88422c44">llvm::CombinerHelper::replaceRegOpWith</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a03c6876ed7ada0d971240509db503dc0">llvm::R600InstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/kernelrewriter/#a2e7a99d381fd8c317ade905833ae3138">anonymous{ModuloSchedule.cpp}::KernelRewriter::rewrite</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/copyrewriter/#a50cda2940b3e3a92753c912202296de4">anonymous{PeepholeOptimizer.cpp}::CopyRewriter::RewriteCurrentSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/insertsubregrewriter/#a448ffa9de937932dddc4d927c1554aab">anonymous{PeepholeOptimizer.cpp}::InsertSubregRewriter::RewriteCurrentSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/regsequencerewriter/#ad1e6780b2cde967f55f56868b46c01a1">anonymous{PeepholeOptimizer.cpp}::RegSequenceRewriter::RewriteCurrentSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600expandspecialinstrs-cpp-/r600expandspecialinstrspass/#a38dc359e925f1a8fd75ba272f45b4736">anonymous{R600ExpandSpecialInstrs.cpp}::R600ExpandSpecialInstrsPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad80050301ef9c1da322681da46fa097d">llvm::salvageDebugInfoForDbgValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#a933b079df28c77f3850ed1edf94c6ed8">selectCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a0f1b1f36c5069336e43ad70639b7f176">substituteSimpleCopyRegs</a>, <a href="#a9842e6805ce84262b6bbe7da2b26772c">substPhysReg</a>, <a href="#a13a5b2fd837189405f1b07a6c9249d4f">substVirtReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a17772fd1beeccd740ec6412abad098f9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldPhiAGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a7c842ead18aca7681bd1cd596a3c8ba3">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::tryMoveVGPRConstToSGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#af704613be9bed4ecd92e5aee263c2d5f">llvm::LegalizerHelper::widenScalarDst</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1675c68d181eacf6dde19dc7d0cdd20c">llvm::LegalizerHelper::widenScalarSrc</a>.</p>

</div>
</div>

### setRegMask() {#a34c5f27bf78b4d1ce93378885811bf54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setRegMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * RegMaskPtr)</td>
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

<p>Sets value of register mask operand referencing Mask.</p>


<p>The operand does not take ownership of the memory referenced by Mask, it must remain valid for the lifetime of the operand. See <a href="#a4c01d756ca363aef75429d61d21c0c14">CreateRegMask()</a>. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> physreg with a 0 bit in the mask is clobbered by the instruction.</p>


<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a55fdcb2a9df9a69067eed1bc17a0b927">isRegMask</a>.</p>

</div>
</div>

### setSubReg() {#a001d31fcea92be51d2999826b806606f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setSubReg (unsigned subReg)</td>
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



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf4d05c8ea2fc82ae12300ef5fb48951">llvm::TargetInstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sipeepholesdwa-cpp/#a31d97fa097f56caffd225e23495f005f">copyRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7a3901a88827b844402f5a9e484945a6">llvm::SIInstrInfo::foldImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a64505b70265bcadc4993631d532a5fd5">llvm::AArch64InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a8c0efd377a713687b369602245dbe9da">insertDivByZeroTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a76f877e67f5943b857f8976d4a289848">llvm::SIInstrInfo::legalizeOperandsVOP2</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af0bbac5dd9f698f2c73477c4e5f36b60">llvm::AArch64InstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#a83cbf55cc29b8e364bc11d81165caaed">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/copyrewriter/#a50cda2940b3e3a92753c912202296de4">anonymous{PeepholeOptimizer.cpp}::CopyRewriter::RewriteCurrentSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/insertsubregrewriter/#a448ffa9de937932dddc4d927c1554aab">anonymous{PeepholeOptimizer.cpp}::InsertSubregRewriter::RewriteCurrentSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/regsequencerewriter/#ad1e6780b2cde967f55f56868b46c01a1">anonymous{PeepholeOptimizer.cpp}::RegSequenceRewriter::RewriteCurrentSource</a>, <a href="#a9842e6805ce84262b6bbe7da2b26772c">substPhysReg</a>, <a href="#a13a5b2fd837189405f1b07a6c9249d4f">substVirtReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a17772fd1beeccd740ec6412abad098f9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldPhiAGPR</a>.</p>

</div>
</div>

### setTargetFlags() {#ad407b071bad6c9a435cade250ec8c8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineOperand::setTargetFlags (unsigned F)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a4c9594c955fec80c73ddd964b5efd554">isReg</a>.</p>


<p>Referenced by <a href="#a8dcd3550374d734c49f2f09cfe59d92e">ChangeToBA</a>, <a href="#a937dbc7794a81ea51dc91c03feb931bc">ChangeToDbgInstrRef</a>, <a href="#a80025569f9c67b220c8938482944bbda">ChangeToES</a>, <a href="#a4355c32a39876f8305ede47c1d7220ff">ChangeToFPImmediate</a>, <a href="#a13b9c3d91aaffb22e0119f3467694b69">ChangeToFrameIndex</a>, <a href="#a83e996ed26eacbf3033314b3df58b133">ChangeToGA</a>, <a href="#a7b39ecfd6793534206dbb095b0d464c7">ChangeToImmediate</a>, <a href="#a62f6582318ed3f4d326b0d115316f7f0">ChangeToMCSymbol</a>, <a href="#a67cc3c894d3231db9636847712fa3171">ChangeToTargetIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#acdf3f4cb6342e67c42191cf29984df97">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#ab55c74c151c09190ab2204e33e77b299">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerHardenedBRJumpTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#adf35a52665d3f70d22acefe2846cb50f">anonymous{MIParser.cpp}::MIParser::parseMachineOperandAndTargetFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a2f4e57397c15057e80f3edaeca9377f4">swapImmOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ab80360d244cbaf4d3aaa327f4d62038f">swapRegAndNonRegOperand</a>.</p>

</div>
</div>

### substPhysReg() {#a9842e6805ce84262b6bbe7da2b26772c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::substPhysReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>substPhysReg - Substitute the current register with the physical register Reg, taking any existing SubReg into account.</p>


<p>For instance, substPhysReg(eax) will change reg1024:sub_8bit to al.</p>


<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a028a8c5113d40d8c3f4427053bf36738">getSubReg</a>, <a href="#a75eb135014670ce946e78739cdc9b51b">isDef</a>, <a href="#ab979122f21b7fa46d3d2d9b21983068b">setIsUndef</a>, <a href="#a682ba82f42f7903d0000ffbb13ea3b57">setReg</a>, <a href="#a001d31fcea92be51d2999826b806606f">setSubReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9f59e1f6dd6677348ba082a10fc09061">llvm::MachineInstr::substituteRegister</a>.</p>

</div>
</div>

### substVirtReg() {#a13a5b2fd837189405f1b07a6c9249d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::substVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned SubIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>substVirtReg - Substitute the current register with the virtual subregister Reg:SubReg.</p>


<p>Take any existing SubReg index into account, using <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> to compose the subreg indices if necessary. Reg must be a virtual register, SubIdx can be 0.</p>


<p>Declaration at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a028a8c5113d40d8c3f4427053bf36738">getSubReg</a>, <a href="#a682ba82f42f7903d0000ffbb13ea3b57">setReg</a>, <a href="#a001d31fcea92be51d2999826b806606f">setSubReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9f59e1f6dd6677348ba082a10fc09061">llvm::MachineInstr::substituteRegister</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isOnRegUseList() {#a79f20db4cc2c9c940a70ce458fe8890a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::isOnRegUseList ()</td>
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

<p>isOnRegUseList - Return true if this operand is on a register use/def list or false if not.</p>


<p>This can only be called for register operands that are part of a machine instruction.</p>


<p>Definition at line 1014 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### removeRegFromUses() {#a65fa704e5b121d106599a9960707edf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::removeRegFromUses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### OffsetLo {#ad8ad6db209d25c087f43741d35624da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::OffsetLo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### RegNo {#aaf8435daf56f7cb3a39fdfc76a9f58ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::RegNo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Contents {#ac077ebcc4f9c6402953a003d041083cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::MachineOperand::ContentsUnion llvm::MachineOperand::Contents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### IsDeadOrKill {#a80877a58aaa58d3e92c40dd2b0573442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::IsDeadOrKill</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsDeadOrKill For uses: IsKill - Conservatively indicates the last use of a register on this path through the function.</p>


<p>A register operand with true value of this flag must be the last use of the register, a register operand with false value may or may not be the last use of the register. After regalloc we can use recomputeLivenessFlags to get precise kill flags. For defs: IsDead - True if this register is never used by a subsequent instruction. This is only valid on register operands.</p>


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### IsDebug {#a360a7ff322871610ec595a28ad3e42f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::IsDebug</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsDebug - True if this MO_Register 'use' operand is in a debug pseudo, not a real instruction.</p>


<p>Such uses should be ignored during codegen.</p>


<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### IsDef {#aecfd30fa29d989489c5a50a5e9aab397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::IsDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsDef - True if this is a def, false if this is a use of the register.</p>


<p>This is only valid on register operands.</p>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### IsEarlyClobber {#a900f9d28f7f2f45cdcfd85203b5061c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::IsEarlyClobber</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsEarlyClobber - True if this MO_Register 'def' operand is written to by the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> before all input registers are read.</p>


<p>This is used to model the GCC inline asm '&amp;' constraint modifier.</p>


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### IsImp {#a4958e654888d9088cff368f6413ff602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::IsImp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsImp - True if this is an implicit def or use, false if it is explicit.</p>


<p>This is only valid on register opderands.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### IsInternalRead {#a9adece572aa84b7c3eaa96d784f21b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::IsInternalRead</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsInternalRead - True if this operand reads a value that was defined inside the same instruction or bundle.</p>


<p>This flag can be set on both use and def operands. On a sub-register def operand, it refers to the part of the register that isn't written. On a full-register def operand, it is a noop.</p>


<p>When this flag is set, the instruction bundle must contain at least one other def of the register. If multiple instructions in the bundle define the register, the meaning is target-defined.</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### IsRenamable {#a4bc30536b123c1473f15916bec3f1946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::IsRenamable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable()</a>.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### IsUndef {#a4cda16cd0cf564882565648b77ad8669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::IsUndef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsUndef - True if this register operand reads an "undef" value, i.e.</p>


<p>the read value doesn't matter. This flag can be set on both use and def operands. On a sub-register def operand, it refers to the part of the register that isn't written. On a full-register def operand, it is a noop. See <a href="#a3be9857a09c82046b77a71918b5e214f">readsReg()</a>.</p>


<p>This is only valid on registers.</p>


<p>Note that an instruction may have multiple &lt;undef&gt; operands referring to the same register. In that case, the instruction may depend on those operands reading the same dont-care value. For example:</p>


<p>%1 = XOR undef %2, undef %2</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> register can be used for %2, and its value doesn't matter, but the two operands must be the same register.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### OpKind {#a17b57b956f719162c8705ae7eea7aa3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::OpKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OpKind - Specify what kind of operand this is.</p>


<p>This discriminates the union.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### ParentMI {#ae6174e85d459bd1e9329d42e15dcffc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::MachineOperand::ParentMI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParentMI - This is the instruction that this operand is embedded into.</p>


<p>This is valid for all operand types, when the operand is in an instr.</p>


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### SmallContents {#a03a6af3f4880fdb7cd89dc8e7d8b32d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::MachineOperand llvm::MachineOperand::SmallContents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SmallContents - This really should be part of the Contents union, but lives out here so we can get a better packed struct.</p>


<p>MO_Register: <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> number. OffsetedInfo: Low bits of offset.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### SubReg\_TargetFlags {#a32671810a5f107fb242fc6abfc4b0a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::SubReg_TargetFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subregister number for MO_Register.</p>


<p>A value of 0 indicates the MO_Register has no subReg.</p>


<p>For all other kinds of operands, this field holds target-specific flags.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

### TiedTo {#a1fce8abfb67dd7904f0a3444cdf9bb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::TiedTo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TiedTo - Non-zero when this register operand is tied to another register operand.</p>


<p>The encoding of this field is described in the block comment before <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa37e31e5df481d2f8a6f9f022886cf5e">MachineInstr::tieOperands()</a>.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### clobbersPhysReg() {#ae4ecf5483b94e2bb72967b80cc2008d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineOperand::clobbersPhysReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * RegMask, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clobbersPhysReg - Returns true if this RegMask clobbers PhysReg.</p>


<p>It is sometimes necessary to detach the register mask pointer from its machine operand. This static method can be used for such detached bit mask pointers.</p>


<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#adab6a6e130a565c2cb11ef465fac90e7">llvm::MCRegister::isPhysical</a> and <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a127e2906913fb89109f3e86397a559ad">llvm::MCRegister::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#a4798468cafe0ab51df84370b1f0e288e">llvm::LiveRegUnits::addRegsInMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a6a91ff524836d3fca6cabe37c8fb7dc5">canClobberPhysRegDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a533e8228c87838f5c738d087a8512fa1">canClobberReachingPhysRegUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#affd5619a70ecc254d62f604150468f1d">CheckForLiveRegDefMasked</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86vzeroupper-cpp/#a5d17e2c1c88234e9fa6eabc2dce7b925">clobbersAllYmmAndZmmRegs</a>, <a href="#a7c45ed93ec219927c08e0a8fb77c94d3">clobbersPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aeeed341d0f3c7220d070d766e3a0f584">llvm::MachineInstr::findRegisterDefOperandIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecopypropagation-cpp-/copytracker/#aba7fb21a2d5ab45963fa25629ad883aa">anonymous{MachineCopyPropagation.cpp}::CopyTracker::getPreservedRegUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#affb039caf886de8fc67678e1dfd83b83">llvm::M68kRegisterInfo::getReservedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a90cb28ef245dd02827b432caed30f710">handleRegMaskClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ab7cbed44cf5366935e93c0a0182dfd5f">llvm::CallLowering::parametersInCSRMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/physicalregisterusageinfo/#aaa2c354cf7353f24dac62741d54bc98b">llvm::PhysicalRegisterUsageInfo::print</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#adfee5cf71110ecb406e359e538fc3cf9">llvm::LivePhysRegs::removeRegsInMask</a>, <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#aef64448ecc992aafc1321df93a30a824">llvm::LiveRegUnits::removeRegsNotPreserved</a>, <a href="/web-llvm/docs/api/classes/anonymous-peepholeoptimizer-cpp-/peepholeoptimizer/#ae6c94cc4b29dfbcc1cc39b73e871ec2a">anonymous{PeepholeOptimizer.cpp}::PeepholeOptimizer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#a3f06df57fdd66d54f952c1c60e5048c3">llvm::LivePhysRegs::stepForward</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a91a98a9dff1a64d1c6ba9a9dc801cf72">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineBundleAfter</a> and <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a73d25ebef02d1312bd901c694d7321ee">LiveDebugValues::MLocTracker::writeRegMask</a>.</p>

</div>
</div>

### CreateBA() {#ad3ad3b0e833c44eb432854df8e3bff6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateBA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> * BA, int64_t Offset, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="#af269b990800f72c7cf535c407e8e639ba7e48d34b4b9e7e8dd77301779ff77013">MO_BlockAddress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6eb17a3fc032cb29dbc1908f1d4ba046">llvm::MachineInstrBuilder::addBlockAddress</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a58e9647502521e6042d3e074f3bcaab2">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::LDIWRdK &gt;</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a77f5672641188aaed10066f78ebb24af">anonymous{MIParser.cpp}::MIParser::parseBlockAddressOperand</a>.</p>

</div>
</div>

### CreateCFIIndex() {#a3cf19eb005905508319869685dda19ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateCFIIndex (unsigned CFIIndex)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba0270d8f468e7b92dafb486293ecf137d">MO_CFIIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ac0b8e1a3e4961f36e5acd8259ccceeab">anonymous{MIParser.cpp}::MIParser::parseCFIOperand</a>.</p>

</div>
</div>

### CreateCImm() {#a5e7a07b4efeaec2afcb83a6551b38441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateCImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * CI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba5cc9e17457a92caa963ed784d83f6233">MO_CImmediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3348f4e81264ccfe03832f141fdf44a3">llvm::MachineInstrBuilder::addCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#af20c06f6ef57cddf624f531efbaf69e7">llvm::CSEMIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp/#a6a69b6a63e9d670d0ce33ab39363ca07">GetMOForConstDbgOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a96f48f9a5690ef01b9d2574472e1f7e2">anonymous{MIParser.cpp}::MIParser::parseTypedImmediateOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a61326cd6384971e828511e500b3367c6">processSwitchesConstants</a>.</p>

</div>
</div>

### CreateCPI() {#aebe6fe7948d0ae093aba94381c73ed67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateCPI (unsigned Idx, int Offset, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="#af269b990800f72c7cf535c407e8e639ba0d4fd3b1a2d5d46d77b66d5a35783580">MO_ConstantPoolIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a88177c2ee5d3e579e50128cf83de5ba6">llvm::MachineInstrBuilder::addConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aa736beb031d297f0eade73ddf496a663">anonymous{MIParser.cpp}::MIParser::parseConstantPoolIndexOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a657c17735f988deb12c8067e40be44d4">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::prescanForConstants</a>.</p>

</div>
</div>

### CreateDbgInstrRef() {#ab5cfdca0e0de9a0c79714b57b290e8a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateDbgInstrRef (unsigned InstrIdx, unsigned OpIdx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 960 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba87cf4128c65c3799c2189ceb3fb62bd3">MO_DbgInstrRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a1c86a488cc8a95190bc351fac90405e2">anonymous{MIParser.cpp}::MIParser::parseDbgInstrRefOperand</a>.</p>

</div>
</div>

### CreateES() {#a2871c33d3a1264270d23ec72b71f1399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateES (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * SymName, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">MO_ExternalSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a30a1feca92679c24a46b0b824a6de269">llvm::MachineInstrBuilder::addExternalSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aeab6958e2224c86557e4ae4a338bf07d">anonymous{MIParser.cpp}::MIParser::parseExternalSymbolOperand</a>.</p>

</div>
</div>

### CreateFI() {#afda3f1971b3e44709267be818ffd3035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateFI (int Idx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba97561985119c4a774e3ec6439240fa80">MO_FrameIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a7cfc0ecfec922ebf19bd023f3b675604">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#a593e839307453b63de7b7021e8cc059a">llvm::X86AddressMode::getFullAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7eb536540d37a55860c52b81778b013e">llvm::FastISel::lowerDbgValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a509beb4628e05fbfe24e7bc562aa6d48">anonymous{MIParser.cpp}::MIParser::parseFixedStackObjectOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a6f18959fe1cc20cb62b5a169b61c0bb8">anonymous{MIParser.cpp}::MIParser::parseStackObjectOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aa3921084f5ef700564dcb83801124551">anonymous{LiveDebugVariables.cpp}::UserValue::rewriteLocations</a>.</p>

</div>
</div>

### CreateFPImm() {#a2cd605d7476194cf38e7ef6d2c57391a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateFPImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> * CFP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639bac4edc21072344f5aafa2a8f307c78b81">MO_FPImmediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a95c7b5ed23471212aeaba1eee6501261">llvm::MachineInstrBuilder::addFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#ae1fe7f5085d203a5984b2450f907b239">llvm::CSEMIRBuilder::buildFConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a7b104b582108e25271c32924224a20fb">convertImplicitDefToConstZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp/#a6a69b6a63e9d670d0ce33ab39363ca07">GetMOForConstDbgOp</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvinlineasmlowering/#ad76d409865bd147da020b46aa7525013">llvm::SPIRVInlineAsmLowering::lowerAsmOperandForConstraint</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4175071c6efe1557747e226a1e8fe2e2">anonymous{MIParser.cpp}::MIParser::parseFPImmediateOperand</a>.</p>

</div>
</div>

### CreateGA() {#ace112d8a86396bd55e99738cd41005b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateGA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, int64_t Offset, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">MO_GlobalAddress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a9117be19af857a7bdcee7bdf0279024c">llvm::MachineInstrBuilder::addGlobalAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#a593e839307453b63de7b7021e8cc059a">llvm::X86AddressMode::getFullAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a90a141a0a4ccdd0ff757cac3d29f0ee6">llvm::AMDGPUCallLowering::lowerChainCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a88ed2f870a01ae1fa7343375ab87dfb3">anonymous{MIParser.cpp}::MIParser::parseGlobalAddressOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>.</p>

</div>
</div>

### CreateImm() {#ab09679b541a6ba1219b3602569847364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateImm (int64_t Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">MO_Immediate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6cdddfff71264f7e1e744fdea34085d3">llvm::ARMTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a9c27deca75181d5b0986eb74bc38a1b1">llvm::ARMBaseInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a844dfba8ffcebffad1f2f43287740c96">llvm::AVRInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a36c56da02f10d527ab7084e5d172d1d4">llvm::HexagonInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a492be44ddc8ccbf85c4ef650b6111868">llvm::LanaiInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#aa62ebce075bb748470a41fdfeffe7532">llvm::MSP430InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aedb2f85719d229f0c9bc62ab1d17e918">llvm::PPCInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afa68867e0d5d04298782e0548047244d">llvm::SystemZInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#ad267470275e53101aed250a06554fdac">llvm::WebAssemblyInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a092553d9bd8edd039d855fb411c6d887">llvm::XCoreInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#ac205677cbd92cecf1a6fcddb4798a12d">llvm::XtensaInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a5fbf08fc2002106c8e39caa9c2c84cd8">llvm::M68kInstrInfo::AnalyzeBranchImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a96da06741a80bacedc0da0469394eff3">llvm::SIInstrInfo::analyzeBranchImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a51f54f2b0fd916f4c01b600905180782">llvm::AArch64InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad304b10479d6791deee8ad1b157fb37f">llvm::X86InstrInfo::analyzeBranchPredicate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abe2e17618e19433e64677bce53b46370">llvm::SIInstrInfo::buildExtractSubRegOrImm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a7b104b582108e25271c32924224a20fb">convertImplicitDefToConstZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instrinfo-cpp-/aarch64pipelinerloopinfo/#a3225760dca7855181b535133948ea278">anonymous{AArch64InstrInfo.cpp}::AArch64PipelinerLoopInfo::createRemainingIterationsGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-armbaseinstrinfo-cpp-/armpipelinerloopinfo/#a2afe54a3f381a7c3f67db172f886d734">anonymous{ARMBaseInstrInfo.cpp}::ARMPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a08073cedfc0efeff220a6af9b84d2cb6">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstrinfo-cpp-/ppcpipelinerloopinfo/#a849593db21c6c97b0f31b2e29e33483d">anonymous{PPCInstrInfo.cpp}::PPCPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a7a1bb4352b705901de9836f44ad326f4">llvm::AArch64InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab0a615cb68b545ea3a9c88243a0ab4d9">emitVFROUND_NOEXCEPT_MASK</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a222d82bcc0b1cb30a36ed1bf3bbeac63">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::fixupConditionalBr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#ade8ad153c39e5550054c7873486dd21d">foldConstantsIntoIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#a593e839307453b63de7b7021e8cc059a">llvm::X86AddressMode::getFullAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp/#a6a69b6a63e9d670d0ce33ab39363ca07">GetMOForConstDbgOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvlegalizerinfo/#a1ddebf0db857b4b9fd7004511b7eb393">llvm::RISCVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#adaff9002688c9185afc9e8b0e2a46f88">llvm::InlineAsmLowering::lowerAsmOperandForConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a9d7f3f2b0dc486075d4d462b7d744174">anonymous{MIParser.cpp}::MIParser::parse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aeb1310110d7dbaccfa5d0973446dc718">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7d7396e09a5fcf968a2536b1375c356f">anonymous{MIParser.cpp}::MIParser::parseImmediateOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a0c8d28ec07b076990dfad603aa041f9b">anonymous{MIParser.cpp}::MIParser::parseSubRegisterIndexOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#af77884023f62584e3a1c2daad3d643c1">anonymous{MIParser.cpp}::MIParser::parseTargetImmMnemonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a657c17735f988deb12c8067e40be44d4">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::prescanForConstants</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupinsttuning-cpp-/x86fixupinsttuningpass/#af4fc51360b5ca432e573316e0609d182">anonymous{X86FixupInstTuning.cpp}::X86FixupInstTuningPass::processInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a11f1861a002da0c49856c526542fc51e">llvm::XtensaInstrInfo::removeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyinstrinfo/#a241d1fcf9b25f0d0783bb5d08235bcbc">llvm::WebAssemblyInstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a285142054aed60907906550e49ed07e2">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a0f9992c5e3a519e4128db320ba2d2e18">llvm::FastISel::selectStackmap</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a983032106624c6c737b6d07bc4dcb3be">llvm::HexagonInstrInfo::setBundleNoShuf</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a1f87ab4ea0d4b9807d9a5318edcb205b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryAddToFoldList</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a0c7d1732461b6f0d88e719eebadf9f2a">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::updateOperand</a>.</p>

</div>
</div>

### CreateIntrinsicID() {#af7cf8fdf7e933b17b3fdf1d49b67e195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateIntrinsicID (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> ID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba9f104d16987b5384042276466fc2e003">MO_IntrinsicID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7ac6e2ee4b04561d22ba0bdc2d32897f">llvm::MachineInstrBuilder::addIntrinsicID</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a02ce808485bec6d45ce163e0d50bb061">anonymous{MIParser.cpp}::MIParser::parseIntrinsicOperand</a>.</p>

</div>
</div>

### CreateJTI() {#ab3700e1a41d8d584dc6e1720b803b2f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateJTI (unsigned Idx, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639baa1741ad7465d81fb3020b84c390ee49d">MO_JumpTableIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#aaa7ad3e87d858a3ed3b3dc8b05b70078">llvm::MachineInstrBuilder::addJumpTableIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#a7308d52d83c46ab568f48acffee1fd68">getMovOperand</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a0688b95ba758f0bdee953833ccbd7a4d">anonymous{MIParser.cpp}::MIParser::parseJumpTableIndexOperand</a>.</p>

</div>
</div>

### CreateMBB() {#af38d24646cd711efc334aee49919cdf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">MO_MachineBasicBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-webassemblyfixbrtabledefaults-cpp-/#a909d1ae12bd80d2dd78cef64f540a728">anonymous{WebAssemblyFixBrTableDefaults.cpp}::fixBrTableDefault</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#aa5f0e43ec22230708870040ca6a9bc2e">anonymous{MIParser.cpp}::MIParser::parseMBBOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#adc90ef1bf034dfb4446b910d3795d218">llvm::PeelingModuloScheduleExpander::peelPrologAndEpilogs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a>.</p>

</div>
</div>

### CreateMCSymbol() {#a081ab7d53b85dfd7a2f8609689147393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateMCSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba17c8e891dacb2adc4a2d0ee5b10d6e9f">MO_MCSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7ffeb5b3940506a54e69e72e26e2a6cd">llvm::MachineInstrBuilder::addSym</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a8c0a6f5ad327c20349f2a2e0a5845b3e">llvm::MipsTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#adaf899f496f2ac717a79e58b4e439058">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerLOADauthptrstatic</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7eba052b8ea2a231281c651c53ef10b5">anonymous{MIParser.cpp}::MIParser::parseMCSymbolOperand</a>.</p>

</div>
</div>

### CreateMetadata() {#a903091abda5acf43af8ade829181b9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Meta)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639babf35c1c1ff9daae15b2dff8efa224623">MO_Metadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7f54f5772ba80cc1f7c4a92203f14e57">llvm::MachineInstrBuilder::addMetadata</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a0ba2f5ae9cb5a6e84640d02c50e52a09">anonymous{MIParser.cpp}::MIParser::parseMetadataOperand</a>.</p>

</div>
</div>

### CreatePredicate() {#a985d3c6d580d9dad7efe3129606150ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreatePredicate (unsigned Pred)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 979 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba3ab395cc24292a5e8e499e48f1553d94">MO_Predicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6d40d83c14042582354b5d875ed7f2d8">llvm::MachineInstrBuilder::addPredicate</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4590f4e05f484028f3b4bf3387955427">anonymous{MIParser.cpp}::MIParser::parsePredicateOperand</a>.</p>

</div>
</div>

### CreateReg() {#af2c351dad09a71aa08e1d85c67ae6e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, bool isDef, bool isImp=false, bool isKill=false, bool isDead=false, bool isUndef=false, bool isEarlyClobber=false, unsigned SubReg=0, bool isDebug=false, bool isInternalRead=false, bool isRenamable=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaee820701392c55ad54235d3d7201206">isDead</a>, <a href="#aa2d3a60e597b4a6cf24ee4ac12d2cdbf">isDebug</a>, <a href="#a75eb135014670ce946e78739cdc9b51b">isDef</a>, <a href="#abd6aa9da048ef7a4faeaac6484d5c9a6">isEarlyClobber</a>, <a href="#ad3008c73231cdb4922d197fe56525364">isInternalRead</a>, <a href="#a4046212ebc647b17e811837ae4ea3afd">isKill</a>, <a href="#a8be49bc86b5d01b52b90baf1b4477667">isRenamable</a>, <a href="#a1255befbcd6e034394681b1bcd3529ff">isUndef</a>, <a href="#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">MO_Register</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2be4041e5133aa22135fa2890cc7aeae">llvm::MachineInstr::addImplicitDefUseOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a52716532c3562bbe9c3fc343761c3c8a">llvm::SITargetLowering::AddMemOpInit</a>, <a href="/web-llvm/docs/api/classes/llvm/giselinstprofilebuilder/#a91d96d0c46203c7f3f08e8d0619d9226">llvm::GISelInstProfileBuilder::addNodeIDRegType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad0a79b68db2b8f84f92b1ee24352b3ce">llvm::MachineInstr::addRegisterDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6cdddfff71264f7e1e744fdea34085d3">llvm::ARMTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aa9b79124bd53c05103a4c771b1b6a510">llvm::RISCVTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aedb2f85719d229f0c9bc62ab1d17e918">llvm::PPCInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a086f43049b2d52208b7727be22f5e604">llvm::R600InstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abe2e17618e19433e64677bce53b46370">llvm::SIInstrInfo::buildExtractSubRegOrImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad2c3e98260a6eb6daa3ba1da72a45e05">llvm::condCodeOp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#abe83de329645327b1d40bee0d304aff8">createCallWithOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-armbaseinstrinfo-cpp-/armpipelinerloopinfo/#a2afe54a3f381a7c3f67db172f886d734">anonymous{ARMBaseInstrInfo.cpp}::ARMPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstrinfo-cpp-/ppcpipelinerloopinfo/#a849593db21c6c97b0f31b2e29e33483d">anonymous{PPCInstrInfo.cpp}::PPCPipelinerLoopInfo::createTripCountGreaterCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#ac9fa612919367a702574336b92a242d2">llvm::MipsInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a6885e40448874565521daac98e11f50d">llvm::TargetInstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a0275d59e3ed329286ba88b96120d280e">describeMOVrrLoadedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a562f6e6e1f13537b17f177e13161a1b6">describeORRLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#add09df38070887ea74972930f1c9ce83">llvm::AArch64TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a1a47bf5e934d1f1a3b4b0d9e4495e586">llvm::RISCVTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a88fd52c520cef6a03af97c37c308ae78">LiveDebugValues::MLocTracker::emitLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a851a237b27ce366221fcb1daf2f0d119">llvm::HexagonFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab0a615cb68b545ea3a9c88243a0ab4d9">emitVFROUND_NOEXCEPT_MASK</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ae0196eca3002f5fd8c339ea859ddd12f">llvm::SIInstrInfo::enforceOperandRCAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a0cf3c7ba2564fa10526e70ecd607db74">expandSGPRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#a593e839307453b63de7b7021e8cc059a">llvm::X86AddressMode::getFullAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp/#a6a69b6a63e9d670d0ce33ab39363ca07">GetMOForConstDbgOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a9999cb33dafa808ba440465867d26ac0">imposeStackOrdering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertreadwritecsr-cpp/#a93ca2859094e3f43227290d2f88472c9">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a90a141a0a4ccdd0ff757cac3d29f0ee6">llvm::AMDGPUCallLowering::lowerChainCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a352ccfab7392a21f5253bca1791022d5">llvm::FastISel::lowerDbgDeclare</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a7eb536540d37a55860c52b81778b013e">llvm::FastISel::lowerDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aeaeffb171ae383d18f217fbd278c8717">llvm::RISCVInstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a1ac412f2e4cc981d3b9d3f6cf6d5988a">anonymous{MachineOutliner.cpp}::MachineOutliner::outline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcinstrinfo-cpp/#aae34e9ed9446266fe2dcc421cc67093f">parseCondBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ad4d22d791beba2d17644bc14544e3877">anonymous{MIParser.cpp}::MIParser::parseRegisterOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#adc90ef1bf034dfb4446b910d3795d218">llvm::PeelingModuloScheduleExpander::peelPrologAndEpilogs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ad97514ca5a771f28d31ee16af616f8">llvm::predOps</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppctocregdeps-cpp-/ppctocregdeps/#a176ecfb7ebeac654d5064720a6620307">anonymous{PPCTOCRegDeps.cpp}::PPCTOCRegDeps::processBlock</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#ac441348b2e73e12e1d8657de17b76568">TransferTracker::recoverAsEntryValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixvgprcopies-cpp-/sifixvgprcopies/#a09c2c01c550356b7377cdd8a2cd619a4">anonymous{SIFixVGPRCopies.cpp}::SIFixVGPRCopies::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstructionselector-cpp-/ppcinstructionselector/#a051c8a2638fc5f95b9ccd5e82a7a8559">anonymous{PPCInstructionSelector.cpp}::PPCInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a0f9992c5e3a519e4128db320ba2d2e18">llvm::FastISel::selectStackmap</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284276bdba816c71f6c16ee08e842b41">llvm::FastISel::selectXRayCustomEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a8c80b7d55789b6712c22642d4f94b90d">llvm::FastISel::selectXRayTypedEvent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac185ac23ce865ff964fd0999a1bc346d">llvm::t1CondCodeOp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>.</p>

</div>
</div>

### CreateRegLiveOut() {#ac5416f0631d02c0c4404b906af9e3be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateRegLiveOut (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af269b990800f72c7cf535c407e8e639bac72cbca4074e0bc4a26afc03db602da5">MO_RegisterLiveOut</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ae35da4f6e23c51b04dc46d9fcfc7c066">anonymous{MIParser.cpp}::MIParser::parseLiveoutRegisterMaskOperand</a>.</p>

</div>
</div>

### CreateRegMask() {#a4c01d756ca363aef75429d61d21c0c14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateRegMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CreateRegMask - Creates a register mask operand referencing Mask.</p>


<p>The operand does not take ownership of the memory referenced by Mask, it must remain valid for the lifetime of the operand.</p>


<p>A RegMask operand represents a set of non-clobbered physical registers on an instruction that clobbers many registers, typically a call. The bit mask has a bit set for each physreg that is preserved by this instruction, as described in the documentation for <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a51887ac7b6af3703f0a8d37b3ba6b478">TargetRegisterInfo::getCallPreservedMask()</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> physreg with a 0 bit in the mask is clobbered by the instruction.</p>


<p>Definition at line 933 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af269b990800f72c7cf535c407e8e639ba48257b48932e88a230caff68469fd9f6">MO_RegisterMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a8880ccaea51a4ee9b48c3c8d7fbfebf4">llvm::MachineInstrBuilder::addRegMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a115cf2109c3a6f662603ef7879242c59">anonymous{MIParser.cpp}::MIParser::parseCustomRegisterMaskOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#af7b186f0f87ad315cbd814abed5dab72">anonymous{MIParser.cpp}::MIParser::parseMachineOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>.</p>

</div>
</div>

### CreateShuffleMask() {#ab261a066a6f63f72c705a1d7a40e56de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Reference <a href="#af269b990800f72c7cf535c407e8e639ba512cc7de4a9ee26228ed614f8447d760">MO_ShuffleMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a846993bea18636f4fd47bbe401fece04">llvm::MachineInstrBuilder::addShuffleMask</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a70c970df35e9a1ebde9a6371fb8a6bc6">anonymous{MIParser.cpp}::MIParser::parseShuffleMaskOperand</a>.</p>

</div>
</div>

### CreateTargetIndex() {#af3137f95a28140bba664c03c2f350870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand llvm::MachineOperand::CreateTargetIndex (unsigned Idx, int64_t Offset, unsigned TargetFlags=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>References <a href="#af269b990800f72c7cf535c407e8e639babb48fd8c9fa828e23f5d33f46cb0cbbb">MO_TargetIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a0bc7ed8aefe042984bce6ea95ad5f1ec">llvm::MachineInstrBuilder::addTargetIndex</a> and <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a6273fafa595d2e1f8940595b5dccc8dc">anonymous{MIParser.cpp}::MIParser::parseTargetIndexOperand</a>.</p>

</div>
</div>

### getRegMaskSize() {#a9fd1f4d5c1460886c4aa983a2027d944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineOperand::getRegMaskSize (unsigned NumRegs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns number of elements needed for a regmask array.</p>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a6cba8c24b1495a6caff37e5e6df77aa2">llvm::MachineFunction::allocateRegMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affcc57979d2a520e5b02b09f2cd12ae8">llvm::hash_value</a>, <a href="#ad7f2dc64214551418f486026ffc95fa4">isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#a0d7ae72cbefa48b3c446bbe0a0347010">regMaskFromTemplate</a>, <a href="/web-llvm/docs/api/classes/anonymous-regusageinfocollector-cpp-/regusageinfocollector/#a20589df6cd2c2e12e77a1741a0e4223e">anonymous{RegUsageInfoCollector.cpp}::RegUsageInfoCollector::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#ae0d8a95e0be5b8b7c9e31abc8ead009d">llvm::AArch64RegisterInfo::UpdateCustomCallPreservedMask</a>.</p>

</div>
</div>

### printIRSlotNumber() {#aaf41c1517148f1b067536a43623d6a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::printIRSlotNumber (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int Slot)</td>
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

<p>Print an IRSlotNumber.</p>

<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a39e0c396e9ae881eddc29a02ebc40956">printIRBlockReference</a> and <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#afe314b6a6d04121d7d8bf9f8ad80605b">llvm::MIRFormatter::printIRValue</a>.</p>

</div>
</div>

### printOperandOffset() {#a91a415f70087b68402bb454cc1b8fa18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::printOperandOffset (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, int64_t Offset)</td>
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

<p>Print the offset with explicit +/- signs.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a4706e639e364501f6000985df1222c58">llvm::MachineMemOperand::print</a> and <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>.</p>

</div>
</div>

### printStackObjectReference() {#a2c42d0e762a9efb66e50b7f349ee4207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::printStackObjectReference (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned FrameIndex, bool IsFixed, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Print a stack object reference.</p>

<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-ad322848578d151a36fcda7ed451f767/#a73280526e3e17258a89d574dd090560b">llvm::yaml::ScalarTraits&lt; FrameIndex &gt;::output</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a294946bd7b49d5ef31f4f42120f75b92">printFrameIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/miprinter/#aa7c297367c0cce1855e484d15703b759">llvm::MIPrinter::printStackObjectReference</a>.</p>

</div>
</div>

### printSubRegIdx() {#a2c59687e1086bf24ffa307eaee13c3d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::printSubRegIdx (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
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

<p>Print a subreg index operand.</p>


<p>MO_Immediate operands can also be subreg idices. If it's the case, the subreg index name will be printed. <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a894f447628559f53d2279c9f9fae0780">MachineInstr::isOperandSubregIdx</a> can be called to check this.</p>


<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a> and <a href="/web-llvm/docs/api/classes/llvm/miprinter/#a0dec8c3931e753255d1e88ab0216e629">llvm::MIPrinter::print</a>.</p>

</div>
</div>

### printSymbol() {#af04079051720988fb6801f962d034e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::printSymbol (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym)</td>
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

<p>Print a <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> as an operand.</p>

<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a48e904486c2be7b98450bc2306c10648">llvm::MachineInstr::print</a>, <a href="#a76123bb0e0b41f5dbae594726160db22">print</a>, <a href="/web-llvm/docs/api/classes/llvm/miprinter/#ac9a4f7f4a86744121b96bfb651c60567">llvm::MIPrinter::print</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#aba7721fa19b2ff3f14b96aaf2ba413c5">printCFI</a>.</p>

</div>
</div>

### printTargetFlags() {#a3bdc6bcbf7eec4329ba1b6c91ff776d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineOperand::printTargetFlags (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
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

<p>Print operand target flags.</p>

<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a>, definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#adfffc4f9fb8a41711b60e03fa51476ec">getMFIfAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a451e8cfa89994a66fbc9d47ce9c3bca8">getTargetFlagName</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#a76123bb0e0b41f5dbae594726160db22">print</a> and <a href="/web-llvm/docs/api/classes/llvm/miprinter/#a0dec8c3931e753255d1e88ab0216e629">llvm::MIPrinter::print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">MachineOperand.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp">MachineOperand.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
