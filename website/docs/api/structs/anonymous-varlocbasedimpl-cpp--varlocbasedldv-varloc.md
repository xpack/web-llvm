---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VarLoc` Struct Reference

<p>A pair of debug variable and value location. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MachineLocKind { <a href="#ae75263bf3f950bac95a9acd39f867a5b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EntryValueLocKind { <a href="#afcce817845f93bd7111bbb9d49976b91">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31208a966620aad4fe4475125d44eb2">VarLoc</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1925514d81a3665fa2a2f998a834142">operator==</a> (const VarLoc &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9153aa3f165630696640780cc5539a09">operator&lt;</a> (const VarLoc &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This operator guarantees that VarLocs are sorted by Variable first. <a href="#a9153aa3f165630696640780cc5539a09">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73907236c1efb52f7e21bc2103bed865">BuildDbgValue</a> (MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a DBG_VALUE representing this VarLoc in the given function. <a href="#a73907236c1efb52f7e21bc2103bed865">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6fcc0ddd63abe3b2b7a7cd8a53d265">isConstant</a> (MachineLocKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is the <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a> field a constant or constant object? <a href="#acb6fcc0ddd63abe3b2b7a7cd8a53d265">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543d6df060ea38c89e3ce25df620de03">isEntryBackupLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a> field is an entry backup location. <a href="#a543d6df060ea38c89e3ce25df620de03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642ed2607a09bf03f4326ab9a47cb537">isEntryValueBackupReg</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this variable is described by register <span class="doxyComputerOutput">Reg</span> holding the entry value, return true. <a href="#a642ed2607a09bf03f4326ab9a47cb537">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6ed26398983379a9bb70a74dc6f35ba">isEntryValueCopyBackupReg</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this variable is described by register <span class="doxyComputerOutput">Reg</span> holding a copy of the entry value, return true. <a href="#ae6ed26398983379a9bb70a74dc6f35ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b31dd60884b154464a066d3abcb2e5d">usesReg</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this variable is described in whole or part by <span class="doxyComputerOutput">Reg</span>, return true. <a href="#a1b31dd60884b154464a066d3abcb2e5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af508c85c8a057a4c3820ab54efb509c0">getRegIdx</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this variable is described in whole or part by <span class="doxyComputerOutput">Reg</span>, return true. <a href="#af508c85c8a057a4c3820ab54efb509c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e4c046889069e28b09b1f8b8c07c166">getDescribingRegs</a> (SmallVectorImpl&lt; uint32_t &gt; &amp;Regs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this variable is described in whole or part by 1 or more registers, add each of them to <span class="doxyComputerOutput">Regs</span> and return true. <a href="#a4e4c046889069e28b09b1f8b8c07c166">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60bd10f9e230ddaaeb85f220767c730">containsSpillLocs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac282f98aefd3f48ea8cf8988d0c719b5">usesSpillLoc</a> (SpillLoc SpillLocation) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this variable is described in whole or part by <span class="doxyComputerOutput">SpillLocation</span>, return true. <a href="#ac282f98aefd3f48ea8cf8988d0c719b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c05bc2fbd53efc111f1b3e3bc93bfdd">getSpillLocIdx</a> (SpillLoc SpillLocation) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this variable is described in whole or part by <span class="doxyComputerOutput">SpillLocation</span>, return the index . <a href="#a6c05bc2fbd53efc111f1b3e3bc93bfdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58e3e2929f779fd99cf121a4780fa51">containsWasmLocs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fa557ad157a1edf6e3ee63e7866808">usesWasmLoc</a> (WasmLoc WasmLocation) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this variable is described in whole or part by <span class="doxyComputerOutput">WasmLocation</span>, return true. <a href="#a72fa557ad157a1edf6e3ee63e7866808">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d530a5e9702fabe607a5671d75a3b5d">dominates</a> (LexicalScopes &amp;LS, MachineBasicBlock &amp;MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the lexical scope of this value's debug location dominates MBB. <a href="#a3d530a5e9702fabe607a5671d75a3b5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a546a8afbb0006b2024243dad1b096abd">dump</a> (const TargetRegisterInfo *TRI, const TargetInstrInfo *TII, raw_ostream &amp;Out=dbgs()) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45fe37d9ede56258ffe90160a343bbda">Var</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identity of the variable at this location. <a href="#a45fe37d9ede56258ffe90160a343bbda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77fc7a4808c0e2128c5a4dd77bdb84e6">Expr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The expression applied to this location. <a href="#a77fc7a4808c0e2128c5a4dd77bdb84e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11572d4e58c002164c702168812e3ef">MI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DBG_VALUE to clone var/expr information from if this location is moved. <a href="#af11572d4e58c002164c702168812e3ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum anonymous_namespace{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::EntryValueLocKind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41dd5916d6e3bb962c052b576d3f00f6">EVKind</a> = EntryValueLocKind::NonEntryValueKind</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/machineloc">MachineLoc</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a291548a2c6c2115c6979833debacd38c">Locs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of machine locations used to determine the variable's value, in conjunction with Expr. <a href="#a291548a2c6c2115c6979833debacd38c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1e7dce64d92f4cb2dd37c45881d745f">OrigLocMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to map the index of each location in Locs back to the index of its original debug operand in MI. <a href="#ae1e7dce64d92f4cb2dd37c45881d745f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/machineloc">MachineLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4758fe52de70289bf8a83ca331e45346">GetLocForOp</a> (const MachineOperand &amp;Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static VarLoc</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6ef2e1f904f5ae37130e01e1a9e7f2">CreateEntryLoc</a> (const MachineInstr &amp;MI, const DIExpression *EntryExpr, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take the variable and machine-location in DBG_VALUE MI, and build an entry location using the given expression. <a href="#abc6ef2e1f904f5ae37130e01e1a9e7f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static VarLoc</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4231fc51fb908514d263c62a494a5794">CreateEntryBackupLoc</a> (const MachineInstr &amp;MI, const DIExpression *EntryExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take the variable and machine-location from the DBG_VALUE (from the function entry), and build an entry value backup location. <a href="#a4231fc51fb908514d263c62a494a5794">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static VarLoc</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67d1cd7a645ab88ba531d39b6f1399a5">CreateEntryCopyBackupLoc</a> (const MachineInstr &amp;MI, const DIExpression *EntryExpr, Register NewReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take the variable and machine-location from the DBG_VALUE (from the function entry), and build a copy of an entry value backup location by setting the register location to NewReg. <a href="#a67d1cd7a645ab88ba531d39b6f1399a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static VarLoc</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f76d36eb2fec3691668e118955bb06">CreateCopyLoc</a> (const VarLoc &amp;OldVL, const MachineLoc &amp;OldML, Register NewReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy the register location in DBG_VALUE MI, updating the register to be NewReg. <a href="#ab2f76d36eb2fec3691668e118955bb06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static VarLoc</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83430be1a086d5f807e950afc110f7ae">CreateSpillLoc</a> (const VarLoc &amp;OldVL, const MachineLoc &amp;OldML, unsigned SpillBase, StackOffset SpillOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take the variable described by DBG_VALUE* MI, and create a VarLoc locating it in the specified spill location. <a href="#a83430be1a086d5f807e950afc110f7ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A pair of debug variable and value location.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### EntryValueLocKind {#afcce817845f93bd7111bbb9d49976b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::EntryValueLocKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">NonEntryValueKind<a id="afcce817845f93bd7111bbb9d49976b91a0008d60ea1bc694bae045af8a8ee4483"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EntryValueKind<a id="afcce817845f93bd7111bbb9d49976b91ae3dc1cfde1820e56380bf669d4dbde5f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EntryValueBackupKind<a id="afcce817845f93bd7111bbb9d49976b91a65780694c4feb556da97373cae65e486"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EntryValueCopyBackupKind<a id="afcce817845f93bd7111bbb9d49976b91a4ae0765d2887ca4c8408450562b954d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### MachineLocKind {#ae75263bf3f950bac95a9acd39f867a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::MachineLocKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">InvalidKind<a id="ae75263bf3f950bac95a9acd39f867a5ba1aa8bfe6c8b095aede66da8191fdaafd"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegisterKind<a id="ae75263bf3f950bac95a9acd39f867a5baad580edf0586eab3a55e21a79cba29aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SpillLocKind<a id="ae75263bf3f950bac95a9acd39f867a5babc392e09bba313d989df36b6bc236d80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmediateKind<a id="ae75263bf3f950bac95a9acd39f867a5ba35be436487452ed6bd004c8f0fae1cb3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WasmLocKind<a id="ae75263bf3f950bac95a9acd39f867a5ba080f89c468524ae2cae5fd4242e6e7c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VarLoc() {#ae31208a966620aad4fe4475125d44eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::VarLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a9153aa3f165630696640780cc5539a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; Other)</td>
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

<p>This operator guarantees that VarLocs are sorted by Variable first.</p>

<p>Definition at line 776 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### operator==() {#ac1925514d81a3665fa2a2f998a834142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; Other)</td>
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



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### BuildDbgValue() {#a73907236c1efb52f7e21bc2103bed865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::BuildDbgValue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Create a DBG_VALUE representing this VarLoc in the given function.</p>


<p>Copies variable-specific information such as <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> and inlining information from the original DBG_VALUE instruction, which may have been several transfers ago.</p>


<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### containsSpillLocs() {#ae60bd10f9e230ddaaeb85f220767c730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::containsSpillLocs ()</td>
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



<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### containsWasmLocs() {#ab58e3e2929f779fd99cf121a4780fa51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::containsWasmLocs ()</td>
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



<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### dominates() {#a3d530a5e9702fabe607a5671d75a3b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::dominates (<a href="/web-llvm/docs/api/classes/llvm/lexicalscopes">LexicalScopes</a> &amp; LS, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p>Determine whether the lexical scope of this value's debug location dominates MBB.</p>

<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### dump() {#a546a8afbb0006b2024243dad1b096abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out=dbgs())</td>
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



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getDescribingRegs() {#a4e4c046889069e28b09b1f8b8c07c166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::getDescribingRegs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint32_t &gt; &amp; Regs)</td>
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

<p>If this variable is described in whole or part by 1 or more registers, add each of them to <span class="doxyComputerOutput">Regs</span> and return true.</p>

<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getRegIdx() {#af508c85c8a057a4c3820ab54efb509c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::getRegIdx (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>If this variable is described in whole or part by <span class="doxyComputerOutput">Reg</span>, return true.</p>

<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### getSpillLocIdx() {#a6c05bc2fbd53efc111f1b3e3bc93bfdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::getSpillLocIdx (<a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/spillloc">SpillLoc</a> SpillLocation)</td>
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

<p>If this variable is described in whole or part by <span class="doxyComputerOutput">SpillLocation</span>, return the index .</p>

<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### isConstant() {#acb6fcc0ddd63abe3b2b7a7cd8a53d265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::isConstant (MachineLocKind Kind)</td>
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

<p>Is the <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a> field a constant or constant object?</p>

<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### isEntryBackupLoc() {#a543d6df060ea38c89e3ce25df620de03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::isEntryBackupLoc ()</td>
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

<p>Check if the <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a> field is an entry backup location.</p>

<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### isEntryValueBackupReg() {#a642ed2607a09bf03f4326ab9a47cb537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::isEntryValueBackupReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>If this variable is described by register <span class="doxyComputerOutput">Reg</span> holding the entry value, return true.</p>

<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### isEntryValueCopyBackupReg() {#ae6ed26398983379a9bb70a74dc6f35ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::isEntryValueCopyBackupReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>If this variable is described by register <span class="doxyComputerOutput">Reg</span> holding a copy of the entry value, return true.</p>

<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### usesReg() {#a1b31dd60884b154464a066d3abcb2e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::usesReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>If this variable is described in whole or part by <span class="doxyComputerOutput">Reg</span>, return true.</p>

<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### usesSpillLoc() {#ac282f98aefd3f48ea8cf8988d0c719b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::usesSpillLoc (<a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/spillloc">SpillLoc</a> SpillLocation)</td>
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

<p>If this variable is described in whole or part by <span class="doxyComputerOutput">SpillLocation</span>, return true.</p>

<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### usesWasmLoc() {#a72fa557ad157a1edf6e3ee63e7866808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::usesWasmLoc (<a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/wasmloc">WasmLoc</a> WasmLocation)</td>
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

<p>If this variable is described in whole or part by <span class="doxyComputerOutput">WasmLocation</span>, return true.</p>

<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EVKind {#a41dd5916d6e3bb962c052b576d3f00f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::EntryValueLocKind anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::EVKind = EntryValueLocKind::NonEntryValueKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### Expr {#a77fc7a4808c0e2128c5a4dd77bdb84e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIExpression* anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::Expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The expression applied to this location.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### Locs {#a291548a2c6c2115c6979833debacd38c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineLoc, 8&gt; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::Locs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of machine locations used to determine the variable's value, in conjunction with Expr.</p>


<p>Initially populated with MI's debug operands, but may be transformed independently afterwards.</p>


<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### MI {#af11572d4e58c002164c702168812e3ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr&amp; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::MI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DBG_VALUE to clone var/expr information from if this location is moved.</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### OrigLocMap {#ae1e7dce64d92f4cb2dd37c45881d745f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 8&gt; anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::OrigLocMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to map the index of each location in Locs back to the index of its original debug operand in MI.</p>


<p>Used when multiple location operands are coalesced and the original MI's operands need to be accessed while emitting a debug value.</p>


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### Var {#a45fe37d9ede56258ffe90160a343bbda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugVariable anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::Var</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identity of the variable at this location.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CreateCopyLoc() {#ab2f76d36eb2fec3691668e118955bb06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLoc anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::CreateCopyLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; OldVL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/machineloc">MachineLoc</a> &amp; OldML, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg)</td>
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

<p>Copy the register location in DBG_VALUE MI, updating the register to be NewReg.</p>

<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### CreateEntryBackupLoc() {#a4231fc51fb908514d263c62a494a5794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLoc anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::CreateEntryBackupLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * EntryExpr)</td>
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

<p>Take the variable and machine-location from the DBG_VALUE (from the function entry), and build an entry value backup location.</p>


<p>The backup location will turn into the normal location if the backup is valid at the time of the primary location clobbering.</p>


<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### CreateEntryCopyBackupLoc() {#a67d1cd7a645ab88ba531d39b6f1399a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLoc anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::CreateEntryCopyBackupLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * EntryExpr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg)</td>
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

<p>Take the variable and machine-location from the DBG_VALUE (from the function entry), and build a copy of an entry value backup location by setting the register location to NewReg.</p>

<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### CreateEntryLoc() {#abc6ef2e1f904f5ae37130e01e1a9e7f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLoc anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::CreateEntryLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * EntryExpr, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Take the variable and machine-location in DBG_VALUE MI, and build an entry location using the given expression.</p>

<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### CreateSpillLoc() {#a83430be1a086d5f807e950afc110f7ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarLoc anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::CreateSpillLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> VarLoc &amp; OldVL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-varlocbasedimpl-cpp-/varlocbasedldv/varloc/machineloc">MachineLoc</a> &amp; OldML, unsigned SpillBase, <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> SpillOffset)</td>
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

<p>Take the variable described by DBG_VALUE* MI, and create a VarLoc locating it in the specified spill location.</p>

<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

### GetLocForOp() {#a4758fe52de70289bf8a83ca331e45346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoc anonymous{VarLocBasedImpl.cpp}::VarLocBasedLDV::VarLoc::GetLocForOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/varlocbasedimpl-cpp">VarLocBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
