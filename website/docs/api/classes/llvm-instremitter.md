---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instremitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstrEmitter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::InstrEmitter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">CodeGen/SelectionDAG/InstrEmitter.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 16 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add888de4c361e3791a2aba0cb578aa53">InstrEmitter</a> (const TargetMachine &amp;TM, MachineBasicBlock *mbb, MachineBasicBlock::iterator insertpos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instremitter">InstrEmitter</a> - Construct an <a href="/web-llvm/docs/api/classes/llvm/instremitter">InstrEmitter</a> and set it to start inserting at the given position in the given block. <a href="#add888de4c361e3791a2aba0cb578aa53">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade27a165903cbaaf156adfd59a7c684b">AddDbgValueLocationOps</a> (MachineInstrBuilder &amp;MIB, const MCInstrDesc &amp;DbgValDesc, ArrayRef&lt; SDDbgOperand &gt; Locations, VRBaseMapType &amp;VRBaseMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10bb6b0cc9a25c709e0009358b859d69">EmitDbgValue</a> (SDDbgValue *SD, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitDbgValue - Generate machine instruction for a dbg_value node. <a href="#a10bb6b0cc9a25c709e0009358b859d69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1157b5306838143f5553c67c1c8489c5">EmitDbgInstrRef</a> (SDDbgValue *SD, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a dbg_value as a DBG_INSTR_REF. <a href="#a1157b5306838143f5553c67c1c8489c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63e197923d820bd6b000a5344adc92ea">EmitDbgNoLocation</a> (SDDbgValue *SD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a DBG_VALUE $noreg, indicating a variable has no location. <a href="#a63e197923d820bd6b000a5344adc92ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71936ccaaca62faa835ddf1887cb2626">EmitDbgValueList</a> (SDDbgValue *SD, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a DBG_VALUE_LIST from the operands to <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a>. <a href="#a71936ccaaca62faa835ddf1887cb2626">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0fecac8378f609fa3740fe1fd51465e">EmitDbgValueFromSingleOp</a> (SDDbgValue *SD, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a DBG_VALUE from the operands to <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a>. <a href="#ae0fecac8378f609fa3740fe1fd51465e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec97d2a9d814aa73cc7ede2fd0d617f">EmitDbgLabel</a> (SDDbgLabel *SD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate machine instruction for a dbg_label node. <a href="#a3ec97d2a9d814aa73cc7ede2fd0d617f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461913029999dc961dbc0aff26365413">EmitNode</a> (SDNode *Node, bool IsClone, bool IsCloned, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitNode - Generate machine code for a node and needed dependencies. <a href="#a461913029999dc961dbc0aff26365413">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb3d3bae06ab41b4da7ebbcd2dfc2ee">getBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getBlock - Return the current basic block. <a href="#a0fb3d3bae06ab41b4da7ebbcd2dfc2ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6445e994c1787842504c3f6cab2a8e1">getInsertPos</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getInsertPos - Return the current insertion position. <a href="#ae6445e994c1787842504c3f6cab2a8e1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b746ea9f24626a502c5eaa833f8725">EmitCopyFromReg</a> (SDNode *Node, unsigned ResNo, bool IsClone, Register SrcReg, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitCopyFromReg - Generate machine code for an CopyFromReg node or an implicit physical register output. <a href="#af0b746ea9f24626a502c5eaa833f8725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7679d3a15a3605085d1996878f6db58d">CreateVirtualRegisters</a> (SDNode *Node, MachineInstrBuilder &amp;MIB, const MCInstrDesc &amp;II, bool IsClone, bool IsCloned, VRBaseMapType &amp;VRBaseMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef6482872ab71ab91e5a52e877b48a08">getVR</a> (SDValue Op, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getVR - Return the virtual register corresponding to the specified result of the specified node. <a href="#aef6482872ab71ab91e5a52e877b48a08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2245c61bad1e84803a28a4c53f884ac7">AddRegisterOperand</a> (MachineInstrBuilder &amp;MIB, SDValue Op, unsigned IIOpNum, const MCInstrDesc *II, VRBaseMapType &amp;VRBaseMap, bool IsDebug, bool IsClone, bool IsCloned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddRegisterOperand - Add the specified register as an operand to the specified machine instr. <a href="#a2245c61bad1e84803a28a4c53f884ac7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae315cb47b79eea2f22bf985f74525420">AddOperand</a> (MachineInstrBuilder &amp;MIB, SDValue Op, unsigned IIOpNum, const MCInstrDesc *II, VRBaseMapType &amp;VRBaseMap, bool IsDebug, bool IsClone, bool IsCloned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddOperand - Add the specified operand to the specified machine instr. <a href="#ae315cb47b79eea2f22bf985f74525420">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af396a4cb47427505b9e4399c5bb360dc">ConstrainForSubReg</a> (Register VReg, unsigned SubIdx, MVT VT, bool isDivergent, const DebugLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ConstrainForSubReg - Try to constrain VReg to a register class that supports SubIdx sub-registers. <a href="#af396a4cb47427505b9e4399c5bb360dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cab15df803b40139736b9a573229b4f">EmitSubregNode</a> (SDNode *Node, VRBaseMapType &amp;VRBaseMap, bool IsClone, bool IsCloned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitSubregNode - Generate machine code for subreg nodes. <a href="#a5cab15df803b40139736b9a573229b4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa94b554c580cd7ecdef4e79d86ee60d">EmitCopyToRegClassNode</a> (SDNode *Node, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitCopyToRegClassNode - Generate machine code for COPY_TO_REGCLASS nodes. <a href="#afa94b554c580cd7ecdef4e79d86ee60d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330c1314b252c4cc92900ebb77367291">EmitRegSequence</a> (SDNode *Node, VRBaseMapType &amp;VRBaseMap, bool IsClone, bool IsCloned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitRegSequence - Generate machine code for REG_SEQUENCE nodes. <a href="#a330c1314b252c4cc92900ebb77367291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4b1a68135fdc9dd7fefa140e7d1919">EmitMachineNode</a> (SDNode *Node, bool IsClone, bool IsCloned, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitMachineNode - Generate machine code for a target-specific node and needed dependencies. <a href="#a9d4b1a68135fdc9dd7fefa140e7d1919">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b134de1aca52e26b0ef55c47ba4f41">EmitSpecialNode</a> (SDNode *Node, bool IsClone, bool IsCloned, VRBaseMapType &amp;VRBaseMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EmitSpecialNode - Generate machine code for a target-independent node and needed dependencies. <a href="#a66b134de1aca52e26b0ef55c47ba4f41">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadac083e7e3a330d09adefdc9cf1acc3">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220419e7ebc6ae765ea90a8314effeab">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab63848b8e5c60adbfcfb6a061055ffcf">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e48cf9b8e666c9e183d8790cca0565">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4113c91e0104b838cf9c80e9d9b1e01d">TLI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8acac2462bbebbbea324bfce6c0e26e">MBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc30d11e046df72272dd0aaa299174c1">InsertPos</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a884c46d90985bf4a787fb7aa8eb94d47">EmitDebugInstrRefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should we try to produce DBG_INSTR_REF instructions? <a href="#a884c46d90985bf4a787fb7aa8eb94d47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a91d391f3b91e549c1514468966f4e6">CountResults</a> (SDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CountResults - The results of target nodes have register or immediate operands first, then an optional chain, and optional flag operands (which do not go into the machine instrs.) <a href="#a6a91d391f3b91e549c1514468966f4e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### VRBaseMapType {#a1c0d5a36d3c86bc8252351ddea11efc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstrEmitter::VRBaseMapType =  SmallDenseMap&lt;SDValue, Register, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstrEmitter() {#add888de4c361e3791a2aba0cb578aa53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrEmitter::InstrEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> insertpos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instremitter">InstrEmitter</a> - Construct an <a href="/web-llvm/docs/api/classes/llvm/instremitter">InstrEmitter</a> and set it to start inserting at the given position in the given block.</p>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 1451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddDbgValueLocationOps() {#ade27a165903cbaaf156adfd59a7c684b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::AddDbgValueLocationOps (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; DbgValDesc, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand">SDDbgOperand</a> &gt; Locations, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a86a93dd8ddbce120d8c3101c16bc3cc6">llvm::MachineInstrBuilder::addFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709aae386012326afbc26eeecc3701f36134">llvm::SDDbgOperand::CONST</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709a8c6e740c1259b720ed9f87a05baf593b">llvm::SDDbgOperand::FRAMEIX</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp/#a6a69b6a63e9d670d0ce33ab39363ca07">GetMOForConstDbgOp</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709aa35847085c9bc57f525640fa8ae5a15c">llvm::SDDbgOperand::SDNODE</a> and <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709a18402f81e9528c3cc41c781786e533b8">llvm::SDDbgOperand::VREG</a>.</p>


<p>Referenced by <a href="#ae0fecac8378f609fa3740fe1fd51465e">EmitDbgValueFromSingleOp</a> and <a href="#a71936ccaaca62faa835ddf1887cb2626">EmitDbgValueList</a>.</p>

</div>
</div>

### EmitDbgInstrRef() {#a1157b5306838143f5553c67c1c8489c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * InstrEmitter::EmitDbgInstrRef (<a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> * SD, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a dbg_value as a DBG_INSTR_REF.</p>


<p>May produce DBG_VALUE $noreg instead if there is no variable location; alternately a half-formed DBG_INSTR_REF that refers to a virtual register and is corrected later in isel.</p>


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a15f4de7989cc83855e8f65792ae94bc4">llvm::DIExpression::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709aae386012326afbc26eeecc3701f36134">llvm::SDDbgOperand::CONST</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a99560dec7123cee3a3e6bbc0d70befdd">llvm::DIExpression::convertToVariadicExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab5cfdca0e0de9a0c79714b57b290e8a5">llvm::MachineOperand::CreateDbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a63e197923d820bd6b000a5344adc92ea">EmitDbgNoLocation</a>, <a href="#ae0fecac8378f609fa3740fe1fd51465e">EmitDbgValueFromSingleOp</a>, <a href="#a71936ccaaca62faa835ddf1887cb2626">EmitDbgValueList</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709a8c6e740c1259b720ed9f87a05baf593b">llvm::SDDbgOperand::FRAMEIX</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a1d23f6c5a21c459b913fa6e63cf75dc9">llvm::SDDbgValue::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#ac08d83b680a533ba07f644648545ab9c">llvm::SDDbgValue::getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#af7673427faa10f98864b7e7b9b008ec8">llvm::SDDbgOperand::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#aa6c31464e5393b719458fcb337369bdb">llvm::SDDbgValue::getLocationOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp/#a6a69b6a63e9d670d0ce33ab39363ca07">GetMOForConstDbgOp</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#a343fd12fb0de39a8f7bdfe6acbb9a1bb">llvm::SDDbgOperand::getResNo</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#a94d6e361d3359e291427734fcc364582">llvm::SDDbgOperand::getSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a3b54645b0192a0ed2af213eb528b2f80">llvm::SDDbgValue::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#a4639cbb2d8bdbb307d236cb2fc165011">llvm::SDDbgOperand::getVReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#ae238ef844b7d208238cd654383931699">llvm::SDDbgValue::isIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#af439591059d973f85e23d248f63f3529">llvm::SDDbgValue::isVariadic</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709aa35847085c9bc57f525640fa8ae5a15c">llvm::SDDbgOperand::SDNODE</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709a18402f81e9528c3cc41c781786e533b8">llvm::SDDbgOperand::VREG</a>.</p>


<p>Referenced by <a href="#a10bb6b0cc9a25c709e0009358b859d69">EmitDbgValue</a>.</p>

</div>
</div>

### EmitDbgLabel() {#a3ec97d2a9d814aa73cc7ede2fd0d617f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * InstrEmitter::EmitDbgLabel (<a href="/web-llvm/docs/api/classes/llvm/sddbglabel">SDDbgLabel</a> * SD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate machine instruction for a dbg_label node.</p>

<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 976 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7f54f5772ba80cc1f7c4a92203f14e57">llvm::MachineInstrBuilder::addMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbglabel/#ab77a4c656d331c23dec5ef4ab74a03cf">llvm::SDDbgLabel::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbglabel/#a8659da19e958bf1163d1983066287378">llvm::SDDbgLabel::getLabel</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### EmitDbgNoLocation() {#a63e197923d820bd6b000a5344adc92ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * InstrEmitter::EmitDbgNoLocation (<a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> * SD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a DBG_VALUE $noreg, indicating a variable has no location.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 912 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab420b672954fd0fc80a22da36dd9cc52">llvm::DIExpression::convertToUndefExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a1d23f6c5a21c459b913fa6e63cf75dc9">llvm::SDDbgValue::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#ac08d83b680a533ba07f644648545ab9c">llvm::SDDbgValue::getExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a3b54645b0192a0ed2af213eb528b2f80">llvm::SDDbgValue::getVariable</a>.</p>


<p>Referenced by <a href="#a1157b5306838143f5553c67c1c8489c5">EmitDbgInstrRef</a> and <a href="#a10bb6b0cc9a25c709e0009358b859d69">EmitDbgValue</a>.</p>

</div>
</div>

### EmitDbgValue() {#a10bb6b0cc9a25c709e0009358b859d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * InstrEmitter::EmitDbgValue (<a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> * SD, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitDbgValue - Generate machine instruction for a dbg_value node.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a1157b5306838143f5553c67c1c8489c5">EmitDbgInstrRef</a>, <a href="#a63e197923d820bd6b000a5344adc92ea">EmitDbgNoLocation</a>, <a href="#ae0fecac8378f609fa3740fe1fd51465e">EmitDbgValueFromSingleOp</a>, <a href="#a71936ccaaca62faa835ddf1887cb2626">EmitDbgValueList</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a1d23f6c5a21c459b913fa6e63cf75dc9">llvm::SDDbgValue::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#aa6c31464e5393b719458fcb337369bdb">llvm::SDDbgValue::getLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a3b54645b0192a0ed2af213eb528b2f80">llvm::SDDbgValue::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#aa041c9375782c6ab2d0b6c24fd986630">llvm::SDDbgValue::isInvalidated</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#af439591059d973f85e23d248f63f3529">llvm::SDDbgValue::isVariadic</a> and <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#ae77e165206b5171c2e43a90014006669">llvm::SDDbgValue::setIsEmitted</a>.</p>

</div>
</div>

### EmitDbgValueFromSingleOp() {#ae0fecac8378f609fa3740fe1fd51465e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * InstrEmitter::EmitDbgValueFromSingleOp (<a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> * SD, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a DBG_VALUE from the operands to <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a>.</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>


<p>References <a href="#ade27a165903cbaaf156adfd59a7c684b">AddDbgValueLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7f54f5772ba80cc1f7c4a92203f14e57">llvm::MachineInstrBuilder::addMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#aaca42b5103c6b7f2cb9a050b61fed709aae386012326afbc26eeecc3701f36134">llvm::SDDbgOperand::CONST</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a8e4ee2a70091fe36640fda28c69580c6">llvm::DIExpression::constantFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgoperand/#a839c3f734c6a978e745998e5d7904beb">llvm::SDDbgOperand::fromConst</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a1d23f6c5a21c459b913fa6e63cf75dc9">llvm::SDDbgValue::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#ac08d83b680a533ba07f644648545ab9c">llvm::SDDbgValue::getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#aa6c31464e5393b719458fcb337369bdb">llvm::SDDbgValue::getLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a3b54645b0192a0ed2af213eb528b2f80">llvm::SDDbgValue::getVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#ae238ef844b7d208238cd654383931699">llvm::SDDbgValue::isIndirect</a>.</p>


<p>Referenced by <a href="#a1157b5306838143f5553c67c1c8489c5">EmitDbgInstrRef</a> and <a href="#a10bb6b0cc9a25c709e0009358b859d69">EmitDbgValue</a>.</p>

</div>
</div>

### EmitDbgValueList() {#a71936ccaaca62faa835ddf1887cb2626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * InstrEmitter::EmitDbgValueList (<a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a> * SD, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a DBG_VALUE_LIST from the operands to <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue">SDDbgValue</a>.</p>

<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 925 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>


<p>References <a href="#ade27a165903cbaaf156adfd59a7c684b">AddDbgValueLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a7f54f5772ba80cc1f7c4a92203f14e57">llvm::MachineInstrBuilder::addMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a1d23f6c5a21c459b913fa6e63cf75dc9">llvm::SDDbgValue::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#ac08d83b680a533ba07f644648545ab9c">llvm::SDDbgValue::getExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#aa6c31464e5393b719458fcb337369bdb">llvm::SDDbgValue::getLocationOps</a> and <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a3b54645b0192a0ed2af213eb528b2f80">llvm::SDDbgValue::getVariable</a>.</p>


<p>Referenced by <a href="#a1157b5306838143f5553c67c1c8489c5">EmitDbgInstrRef</a> and <a href="#a10bb6b0cc9a25c709e0009358b859d69">EmitDbgValue</a>.</p>

</div>
</div>

### EmitNode() {#a461913029999dc961dbc0aff26365413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrEmitter::EmitNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, bool IsClone, bool IsCloned, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
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

<p>EmitNode - Generate machine code for a node and needed dependencies.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

### getBlock() {#a0fb3d3bae06ab41b4da7ebbcd2dfc2ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::InstrEmitter::getBlock ()</td>
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

<p>getBlock - Return the current basic block.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

### getInsertPos() {#ae6445e994c1787842504c3f6cab2a8e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::InstrEmitter::getInsertPos ()</td>
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

<p>getInsertPos - Return the current insertion position.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AddOperand() {#ae315cb47b79eea2f22bf985f74525420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::AddOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, unsigned IIOpNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> * II, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap, bool IsDebug, bool IsClone, bool IsCloned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddOperand - Add the specified operand to the specified machine instr.</p>


<p>II specifies the instruction information for the node, and IIOpNum is the operand number (in the II) that we are adding. IIOpNum and II are used for assertions only.</p>


<p>II specifies the instruction information for the node, and IIOpNum is the operand number (in the II) that we are adding.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### AddRegisterOperand() {#a2245c61bad1e84803a28a4c53f884ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::AddRegisterOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, unsigned IIOpNum, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> * II, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap, bool IsDebug, bool IsClone, bool IsCloned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddRegisterOperand - Add the specified register as an operand to the specified machine instr.</p>


<p>Insert register copies if the register is not in the required register class.</p>


<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### ConstrainForSubReg() {#af396a4cb47427505b9e4399c5bb360dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register InstrEmitter::ConstrainForSubReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, unsigned SubIdx, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, bool isDivergent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ConstrainForSubReg - Try to constrain VReg to a register class that supports SubIdx sub-registers.</p>


<p>Emit a copy if that isn't possible. Return the virtual register to use.</p>


<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### CreateVirtualRegisters() {#a7679d3a15a3605085d1996878f6db58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::CreateVirtualRegisters (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp; MIB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; II, bool IsClone, bool IsCloned, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### EmitCopyFromReg() {#af0b746ea9f24626a502c5eaa833f8725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::EmitCopyFromReg (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, unsigned ResNo, bool IsClone, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitCopyFromReg - Generate machine code for an CopyFromReg node or an implicit physical register output.</p>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### EmitCopyToRegClassNode() {#afa94b554c580cd7ecdef4e79d86ee60d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::EmitCopyToRegClassNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitCopyToRegClassNode - Generate machine code for COPY_TO_REGCLASS nodes.</p>


<p>COPY_TO_REGCLASS is just a normal copy, except that the destination register is constrained to be in a particular register class.</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### EmitMachineNode() {#a9d4b1a68135fdc9dd7fefa140e7d1919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::EmitMachineNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, bool IsClone, bool IsCloned, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitMachineNode - Generate machine code for a target-specific node and needed dependencies.</p>

<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### EmitRegSequence() {#a330c1314b252c4cc92900ebb77367291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::EmitRegSequence (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap, bool IsClone, bool IsCloned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitRegSequence - Generate machine code for REG_SEQUENCE nodes.</p>

<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### EmitSpecialNode() {#a66b134de1aca52e26b0ef55c47ba4f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::EmitSpecialNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, bool IsClone, bool IsCloned, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitSpecialNode - Generate machine code for a target-independent node and needed dependencies.</p>

<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### EmitSubregNode() {#a5cab15df803b40139736b9a573229b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrEmitter::EmitSubregNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap, bool IsClone, bool IsCloned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EmitSubregNode - Generate machine code for subreg nodes.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

### getVR() {#aef6482872ab71ab91e5a52e877b48a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register InstrEmitter::getVR (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="#a1c0d5a36d3c86bc8252351ddea11efc2">VRBaseMapType</a> &amp; VRBaseMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getVR - Return the virtual register corresponding to the specified result of the specified node.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EmitDebugInstrRefs {#a884c46d90985bf4a787fb7aa8eb94d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstrEmitter::EmitDebugInstrRefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Should we try to produce DBG_INSTR_REF instructions?</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

### InsertPos {#acc30d11e046df72272dd0aaa299174c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::InstrEmitter::InsertPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

### MBB {#ae8acac2462bbebbbea324bfce6c0e26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::InstrEmitter::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

### MF {#aadac083e7e3a330d09adefdc9cf1acc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::InstrEmitter::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

### MRI {#a220419e7ebc6ae765ea90a8314effeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::InstrEmitter::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

### TII {#ab63848b8e5c60adbfcfb6a061055ffcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::InstrEmitter::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

### TLI {#a4113c91e0104b838cf9c80e9d9b1e01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering* llvm::InstrEmitter::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

### TRI {#a30e48cf9b8e666c9e183d8790cca0565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::InstrEmitter::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CountResults() {#a6a91d391f3b91e549c1514468966f4e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned InstrEmitter::CountResults (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
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

<p>CountResults - The results of target nodes have register or immediate operands first, then an optional chain, and optional flag operands (which do not go into the machine instrs.)</p>


<p>CountResults - The results of target nodes have register or immediate operands first, then an optional chain, and optional glue operands (which do not go into the resulting <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>).</p>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp">InstrEmitter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-h">InstrEmitter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
