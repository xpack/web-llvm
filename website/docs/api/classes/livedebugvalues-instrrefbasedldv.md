---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/livedebugvalues/instrrefbasedldv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstrRefBasedLDV` Class



## Declaration

<div class="doxyDeclaration">
class LiveDebugValues::InstrRefBasedLDV { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">CodeGen/LiveDebugValues/InstrRefBasedImpl.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/ldvimpl">LDVImpl</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8126e881577442cc33511b29b08a0d32">FragmentInfo</a> = <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab334acbb393549bc7c6e65c0d1c08842">OptFragmentInfo</a> = std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c6ff6a4c2ab1a469d229a327ed07222">VarToFragments</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="#a8126e881577442cc33511b29b08a0d32">FragmentInfo</a>, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc9d9007b0d77bc0954612b88df15142">MLocTransferMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Machine location/value transfer function, a mapping of which locations are assigned which new values. <a href="#abc9d9007b0d77bc0954612b88df15142">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abba7c6095e3e9ebb63a516620332773c">LiveIdxT</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> *, 16 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Live in/out structure for the variable values: a per-block map of variables to their values. <a href="#abba7c6095e3e9ebb63a516620332773c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f040800f20929318533875154927e1">VarAndLoc</a> = std::pair&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c96cc2839fdb5fe0010e73712a6ff61">InValueT</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> for a live-in value: the predecessor block, and its value. <a href="#a3c96cc2839fdb5fe0010e73712a6ff61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcc5fc74d98f09bd495e93cec779cbc">LiveInsT</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a45f040800f20929318533875154927e1">VarAndLoc</a>, 8 &gt;, 8 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector (per block) of a collection (inner smallvector) of live-ins. <a href="#a4fcc5fc74d98f09bd495e93cec779cbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2233b318fa41cb9167e82f952f4b6df6">ScopeToDILocT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from lexical scopes to a <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> in that scope. <a href="#a2233b318fa41cb9167e82f952f4b6df6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55b289a4e7786074f4f3372425763cd">ScopeToVarsT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a>, 4 &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from lexical scopes to variables in that scope. <a href="#aa55b289a4e7786074f4f3372425763cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68274d2602df99b0792e3474e37b3775">ScopeToAssignBlocksT</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lexicalscope">LexicalScope</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping from lexical scopes to blocks where variables in that scope are assigned. <a href="#a68274d2602df99b0792e3474e37b3775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93f315c2ce86d06ab7a212a3019c8965">InstAndNum</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pair of <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, and its 1-based offset into the containing block. <a href="#a93f315c2ce86d06ab7a212a3019c8965">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65dd2d19f26744f60c65d3164cfb5076">::InstrRefLDVTest</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625f1469290a1b9bb1bc071a5392d3cb">InstrRefBasedLDV</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default construct and initialize the pass. <a href="#a625f1469290a1b9bb1bc071a5392d3cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae270bdce77ec139bf18564e50664dab8">dump_mloc_transfer</a> (const MLocTransferMap &amp;mloc_transfer) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e3a7e9be90841c721e738db731abbf">isCalleeSaved</a> (LocIdx L) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad778dafd8a5d853569fe78079b6960b7">isCalleeSavedReg</a> (Register R) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3764a9e5e3a3929c0cef3d6dceaedf">hasFoldedStackStore</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1165eb09769fbc90612ff41c1830b3">findLocationForMemOperand</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/debugvariablemap">DebugVariableMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40164b47ac9386a03fb7acf930eca83a">getDVMap</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno">SpillLocationNo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b4b803e9f62d4926a8d662c3d2786b6">isSpillInstruction</a> (const MachineInstr &amp;MI, MachineFunction *MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests whether this instruction is a spill to a stack slot. <a href="#a5b4b803e9f62d4926a8d662c3d2786b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706f17a46553480f1ee4ad63e6af83d9">isLocationSpill</a> (const MachineInstr &amp;MI, MachineFunction *MF, unsigned &amp;Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decide if @MI is a spill instruction and return true if it is. <a href="#a706f17a46553480f1ee4ad63e6af83d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno">SpillLocationNo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07570f4999d0dd6b8eda2e51a0ed12c4">isRestoreInstruction</a> (const MachineInstr &amp;MI, MachineFunction *MF, unsigned &amp;Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a given instruction is identified as a spill, return the spill slot and set <span class="doxyComputerOutput">Reg</span> to the spilled register. <a href="#a07570f4999d0dd6b8eda2e51a0ed12c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno">SpillLocationNo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f55a37e37cf727fd53d40a58687cd7">extractSpillBaseRegAndOffset</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a spill instruction, extract the spill slot information, ensure it's tracked, and return the spill number. <a href="#a81f55a37e37cf727fd53d40a58687cd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8b21a5dac1f16592b6568015385f7a">getValueForInstrRef</a> (unsigned InstNo, unsigned OpNo, MachineInstr &amp;MI, const FuncValueTable *MLiveOuts, const FuncValueTable *MLiveIns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For an instruction reference given by <span class="doxyComputerOutput">InstNo</span> and <span class="doxyComputerOutput">OpNo</span> in instruction <span class="doxyComputerOutput">MI</span> returns the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> pointed to by that instruction reference if any exists, otherwise returns std::nullopt. <a href="#a6c8b21a5dac1f16592b6568015385f7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d8c07b9cedf432f5d345544688d960">process</a> (MachineInstr &amp;MI, const FuncValueTable *MLiveOuts, const FuncValueTable *MLiveIns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Observe a single instruction while stepping through a block. <a href="#a06d8c07b9cedf432f5d345544688d960">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a04f10b667dc5b481a6edeaa1888b0">transferDebugValue</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examines whether <span class="doxyComputerOutput">MI</span> is a DBG_VALUE and notifies trackers. <a href="#a07a04f10b667dc5b481a6edeaa1888b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d5c7cc1b11a8d0455b3461cb6ea121">transferDebugInstrRef</a> (MachineInstr &amp;MI, const FuncValueTable *MLiveOuts, const FuncValueTable *MLiveIns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examines whether <span class="doxyComputerOutput">MI</span> is a DBG_INSTR_REF and notifies trackers. <a href="#aa1d5c7cc1b11a8d0455b3461cb6ea121">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6962b166d41a26c23c4ff1aeee4b0ac5">transferDebugPHI</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores value-information about where this PHI occurred, and what instruction number is associated with it. <a href="#a6962b166d41a26c23c4ff1aeee4b0ac5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a734b8343dd36a859e887d6e048a9a37a">transferRegisterCopy</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examines whether <span class="doxyComputerOutput">MI</span> is copy instruction, and notifies trackers. <a href="#a734b8343dd36a859e887d6e048a9a37a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d3b0bc989755d5befa2762363922866">transferSpillOrRestoreInst</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examines whether <span class="doxyComputerOutput">MI</span> is stack spill or restore instruction, and notifies trackers. <a href="#a9d3b0bc989755d5befa2762363922866">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf7e8f68978d333ba4eb817370952e8f">transferRegisterDef</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examines <span class="doxyComputerOutput">MI</span> for any registers that it defines, and notifies trackers. <a href="#abf7e8f68978d333ba4eb817370952e8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb6b27cdf1b0325978594464835075e">performCopy</a> (Register Src, Register Dst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy one location to the other, accounting for movement of subregisters too. <a href="#aacb6b27cdf1b0325978594464835075e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f5726e576f9a2190f07ad047841f9d">accumulateFragmentMap</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accumulate a mapping between each <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> fragment and other fragments of that <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> which overlap. <a href="#a10f5726e576f9a2190f07ad047841f9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6bfbe8902542495bf8b1e1867c94150">resolveDbgPHIs</a> (MachineFunction &amp;MF, const FuncValueTable &amp;MLiveOuts, const FuncValueTable &amp;MLiveIns, MachineInstr &amp;Here, uint64_t InstrNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the machine value number referred to by (potentially several) DBG_PHI instructions. <a href="#ac6bfbe8902542495bf8b1e1867c94150">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0d554b2cb3525ca83c4a36b50f4f33">resolveDbgPHIsImpl</a> (MachineFunction &amp;MF, const FuncValueTable &amp;MLiveOuts, const FuncValueTable &amp;MLiveIns, MachineInstr &amp;Here, uint64_t InstrNum)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5f0bf451a6c1870f6d8c2828e11737">produceMLocTransferFunction</a> (MachineFunction &amp;MF, SmallVectorImpl&lt; MLocTransferMap &gt; &amp;MLocTransfer, unsigned MaxNumBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Step through the function, recording register definitions and movements in an <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a>. <a href="#a5f5f0bf451a6c1870f6d8c2828e11737">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b86c42097dd294307437291bbc8b2f">buildMLocValueMap</a> (MachineFunction &amp;MF, FuncValueTable &amp;MInLocs, FuncValueTable &amp;MOutLocs, SmallVectorImpl&lt; MLocTransferMap &gt; &amp;MLocTransfer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Solve the machine value location dataflow problem. <a href="#ab6b86c42097dd294307437291bbc8b2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa53b1db8d8910ccd6f9d350a17fab4">findStackIndexInterference</a> (SmallVectorImpl&lt; unsigned &gt; &amp;Slots)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examine the stack indexes (i.e. <a href="#a4fa53b1db8d8910ccd6f9d350a17fab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3cab548a55c94d96852f07fb16ea98">placeMLocPHIs</a> (MachineFunction &amp;MF, SmallPtrSetImpl&lt; MachineBasicBlock * &gt; &amp;AllBlocks, FuncValueTable &amp;MInLocs, SmallVectorImpl&lt; MLocTransferMap &gt; &amp;MLocTransfer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Install PHI values into the live-in array for each block, according to the IDF of each register. <a href="#a0e3cab548a55c94d96852f07fb16ea98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90f1c48d64696e5e60b4b34d53e07a3e">placePHIsForSingleVarDefinition</a> (const SmallPtrSetImpl&lt; MachineBasicBlock * &gt; &amp;InScopeBlocks, MachineBasicBlock *MBB, SmallVectorImpl&lt; VLocTracker &gt; &amp;AllTheVLocs, DebugVariableID Var, LiveInsT &amp;Output)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Propagate variable values to blocks in the common case where there's only one value assigned to the variable. <a href="#a90f1c48d64696e5e60b4b34d53e07a3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6111524681758e1000aaffa8df3d89e">BlockPHIPlacement</a> (const SmallPtrSetImpl&lt; MachineBasicBlock * &gt; &amp;AllBlocks, const SmallPtrSetImpl&lt; MachineBasicBlock * &gt; &amp;DefBlocks, SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;PHIBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the iterated-dominance-frontier for a set of defs, using the existing LLVM facilities for this. <a href="#aa6111524681758e1000aaffa8df3d89e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07b52c00979721f3aef3e806f640fa7">mlocJoin</a> (MachineBasicBlock &amp;MBB, SmallPtrSet&lt; const MachineBasicBlock *, 16 &gt; &amp;Visited, FuncValueTable &amp;OutLocs, ValueTable &amp;InLocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a control flow join (lattice value meet) of the values in machine locations at <span class="doxyComputerOutput">MBB</span>. <a href="#ad07b52c00979721f3aef3e806f640fa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ce7b03957b1093525b17050a957f24f">getBlocksForScope</a> (const DILocation *DILoc, SmallPtrSetImpl&lt; const MachineBasicBlock * &gt; &amp;Output, const SmallPtrSetImpl&lt; MachineBasicBlock * &gt; &amp;AssignBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce a set of blocks that are in the current lexical scope. <a href="#a4ce7b03957b1093525b17050a957f24f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59a737b5062cc6b00ced87df09c9a353">buildVLocValueMap</a> (const DILocation *DILoc, const SmallSet&lt; DebugVariableID, 4 &gt; &amp;VarsWeCareAbout, SmallPtrSetImpl&lt; MachineBasicBlock * &gt; &amp;AssignBlocks, LiveInsT &amp;Output, FuncValueTable &amp;MOutLocs, FuncValueTable &amp;MInLocs, SmallVectorImpl&lt; VLocTracker &gt; &amp;AllTheVLocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Solve the variable value dataflow problem, for a single lexical scope. <a href="#a59a737b5062cc6b00ced87df09c9a353">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4674e0625f729563d44ba5cab429ef8a">vlocJoin</a> (MachineBasicBlock &amp;MBB, LiveIdxT &amp;VLOCOutLocs, SmallPtrSet&lt; const MachineBasicBlock *, 8 &gt; &amp;BlocksToExplore, DbgValue &amp;LiveIn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to eliminate un-necessary PHIs on entry to a block. <a href="#a4674e0625f729563d44ba5cab429ef8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a97be3b9a83608262c594ea71ca8364">pickVPHILoc</a> (SmallVectorImpl&lt; DbgOpID &gt; &amp;OutValues, const MachineBasicBlock &amp;MBB, const LiveIdxT &amp;LiveOuts, FuncValueTable &amp;MOutLocs, const SmallVectorImpl&lt; const MachineBasicBlock * &gt; &amp;BlockOrders)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For the given block and live-outs feeding into it, try to find machine locations for each debug operand where all the values feeding into that operand join together. <a href="#a5a97be3b9a83608262c594ea71ca8364">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8acdd8867ac44190e388a08af059250a">pickOperandPHILoc</a> (unsigned DbgOpIdx, const MachineBasicBlock &amp;MBB, const LiveIdxT &amp;LiveOuts, FuncValueTable &amp;MOutLocs, const SmallVectorImpl&lt; const MachineBasicBlock * &gt; &amp;BlockOrders)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204464a5e130feff38120d8989e427ef">emitTransfers</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take collections of DBG_VALUE instructions stored in TTracker, and install them into their output blocks. <a href="#a204464a5e130feff38120d8989e427ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2393c70c72c7638d47f319a87783e830">initialSetup</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Boilerplate computation of some initial sets, artifical blocks and RPOT block ordering. <a href="#a2393c70c72c7638d47f319a87783e830">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ade9f757d736b13b669d71b06ef2d1e">makeDepthFirstEjectionMap</a> (SmallVectorImpl&lt; unsigned &gt; &amp;EjectionMap, const ScopeToDILocT &amp;ScopeToDILocation, ScopeToAssignBlocksT &amp;AssignBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce a map of the last lexical scope that uses a block, using the scopes DFSOut number. <a href="#a6ade9f757d736b13b669d71b06ef2d1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6304d2a737f712448762178dd1f4404">depthFirstVLocAndEmit</a> (unsigned MaxNumBlocks, const ScopeToDILocT &amp;ScopeToDILocation, const ScopeToVarsT &amp;ScopeToVars, ScopeToAssignBlocksT &amp;ScopeToBlocks, LiveInsT &amp;Output, FuncValueTable &amp;MOutLocs, FuncValueTable &amp;MInLocs, SmallVectorImpl&lt; VLocTracker &gt; &amp;AllTheVLocs, MachineFunction &amp;MF, const TargetPassConfig &amp;TPC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When determining per-block variable values and emitting to DBG_VALUEs, this function explores by lexical scope depth. <a href="#af6304d2a737f712448762178dd1f4404">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a326f546ac1f97d0d5d6fe81187d095d5">ExtendRanges</a> (MachineFunction &amp;MF, MachineDominatorTree *DomTree, TargetPassConfig *TPC, unsigned InputBBLimit, unsigned InputDbgValLimit) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the liveness information for the given machine function and extend ranges across basic blocks. <a href="#a326f546ac1f97d0d5d6fe81187d095d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd6fca22445bf3062b6a35fba5137d6">DomTree</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aab1ae1f3779d4d46a12fcefe0903bb">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a487646e28e68aed1416ec95d3fe3e4e1">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a10bf9bccc71697dea7be468c2f5746">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetframelowering">TargetFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07d89949403222c9a50d48803c004bf7">TFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa351a7c3e07b4006d0f43afe08f6d812">MFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9cd59bfbdd3378a02426ebfd8411a86">CalleeSavedRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lexicalscopes">LexicalScopes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40865c48645bd3916eaf08a5c0d4960d">LS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45db428547286759eab78d45192001f3">TPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc888a5d7bdc06ad0f9734dddc9cb463">EmptyExpr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78400f292849e9960cef9172f1fc1fba">MTracker</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Object to track machine locations as we step through a block. <a href="#a78400f292849e9960cef9172f1fc1fba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dffa1e1ffeb5a451136b837a07ef23f">CurBB</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of the current block <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a> is stepping through. <a href="#a2dffa1e1ffeb5a451136b837a07ef23f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb320903dbb7f9bb43982ac351c5c2b">CurInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of the current instruction <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a> is evaluating. <a href="#aecb320903dbb7f9bb43982ac351c5c2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/vloctracker">VLocTracker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3969ac5b6d12166ef9e6ac00ab4ae7c9">VTracker</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Variable tracker – listens to DBG_VALUEs occurring as InstrRefBasedImpl steps through a block. <a href="#a3969ac5b6d12166ef9e6ac00ab4ae7c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/transfertracker">TransferTracker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61028875188a8b16510dac222a472b04">TTracker</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracker for transfers, listens to DBG_VALUEs and transfers of values between locations during stepping, creates new DBG_VALUEs when values move location. <a href="#a61028875188a8b16510dac222a472b04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac62138fdd885d11b3eb5bf8bba63c4">ArtificialBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Blocks which are artificial, i.e. <a href="#aeac62138fdd885d11b3eb5bf8bba63c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a09b6200c1332310da5d23445fef6ab">OrderToBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, unsigned int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44c580a6d08875e2765aa3d5e47a6c1a">BBToOrder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71629590cc6d688bdfa05f76613fcc5e">BBNumToRPO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; uint64_t, InstAndNum &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db40a2a1b51a222eb02ba0ff7f05f73">DebugInstrNumToInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from debug instruction number to the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> labelled with that number, and its location within the function. <a href="#a0db40a2a1b51a222eb02ba0ff7f05f73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; DebugPHIRecord, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2704806d9344f84133d9dd4a8fc4b6f7">DebugPHINumToValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from instruction numbers defined by DBG_PHIs to a record of what that DBG_PHI read and where. <a href="#a2704806d9344f84133d9dd4a8fc4b6f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2fd2da038a0079e35e2d22f37984d4ee">OverlapMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1ccefe1bfa1c318776ec1c00ac2528">OverlapFragments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2c6ff6a4c2ab1a469d229a327ed07222">VarToFragments</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c55db6d427ce7a739fbf81108f03fef">SeenFragments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned &gt;, std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0888177522a9aec5b22527f0a9b981">SeenDbgPHIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of DBG_INSTR_REF instructions to their values, for those DBG_INSTR_REFs that call resolveDbgPHIs. <a href="#a8c0888177522a9aec5b22527f0a9b981">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap">DbgOpIDMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e6911b3ba5b15b5a136a7d49580a09">DbgOpStore</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/debugvariablemap">DebugVariableMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02017d9f0608b38aba5e98e209328b16">DVMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping between DebugVariables and unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> numbers. <a href="#a02017d9f0608b38aba5e98e209328b16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a868405ab5f3dd0880f364a1e8abac5e4">AdjustsStackInCalls</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if we need to examine call instructions for stack clobbers. <a href="#a868405ab5f3dd0880f364a1e8abac5e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093bc749657288862cfe97564bf7a6e7">StackProbeSymbolName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If AdjustsStackInCalls is true, this holds the name of the target's stack probe function, which is the function we expect will alter the stack pointer. <a href="#a093bc749657288862cfe97564bf7a6e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 1113 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FragmentInfo {#a8126e881577442cc33511b29b08a0d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::FragmentInfo =  DIExpression::FragmentInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### InValueT {#a3c96cc2839fdb5fe0010e73712a6ff61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::InValueT =  std::pair&lt;MachineBasicBlock *, DbgValue *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> for a live-in value: the predecessor block, and its value.</p>

<p>Definition at line 1136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### LiveIdxT {#abba7c6095e3e9ebb63a516620332773c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::LiveIdxT =  SmallDenseMap&lt;const MachineBasicBlock *, DbgValue *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Live in/out structure for the variable values: a per-block map of variables to their values.</p>

<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### LiveInsT {#a4fcc5fc74d98f09bd495e93cec779cbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::LiveInsT =  SmallVector&lt;SmallVector&lt;VarAndLoc, 8&gt;, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector (per block) of a collection (inner smallvector) of live-ins.</p>


<p>Used as the result type for the variable value dataflow problem.</p>


<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### MLocTransferMap {#abc9d9007b0d77bc0954612b88df15142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::MLocTransferMap =  SmallDenseMap&lt;LocIdx, ValueIDNum&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Machine location/value transfer function, a mapping of which locations are assigned which new values.</p>

<p>Definition at line 1127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### OptFragmentInfo {#ab334acbb393549bc7c6e65c0d1c08842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::OptFragmentInfo =  std::optional&lt;DIExpression::FragmentInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### ScopeToAssignBlocksT {#a68274d2602df99b0792e3474e37b3775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::ScopeToAssignBlocksT =  DenseMap&lt;const LexicalScope *, SmallPtrSet&lt;MachineBasicBlock *, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping from lexical scopes to blocks where variables in that scope are assigned.</p>


<p>Such blocks aren't necessarily "in" the lexical scope, it's just a block where an assignment happens.</p>


<p>Definition at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### ScopeToDILocT {#a2233b318fa41cb9167e82f952f4b6df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::ScopeToDILocT =  DenseMap&lt;const LexicalScope *, const DILocation *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping from lexical scopes to a <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> in that scope.</p>

<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### ScopeToVarsT {#aa55b289a4e7786074f4f3372425763cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::ScopeToVarsT = 
      DenseMap&lt;const LexicalScope *, SmallSet&lt;DebugVariableID, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping from lexical scopes to variables in that scope.</p>

<p>Definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### VarAndLoc {#a45f040800f20929318533875154927e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::VarAndLoc =  std::pair&lt;DebugVariableID, DbgValue&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### VarToFragments {#a2c6ff6a4c2ab1a469d229a327ed07222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::VarToFragments = 
      DenseMap&lt;const DILocalVariable *, SmallSet&lt;FragmentInfo, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### InstAndNum {#a93f315c2ce86d06ab7a212a3019c8965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::InstrRefBasedLDV::InstAndNum =  std::pair&lt;const MachineInstr *, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pair of <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, and its 1-based offset into the containing block.</p>

<p>Definition at line 1199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ::InstrRefLDVTest {#a65dd2d19f26744f60c65d3164cfb5076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class ::InstrRefLDVTest</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstrRefBasedLDV() {#a625f1469290a1b9bb1bc071a5392d3cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrRefBasedLDV::InstrRefBasedLDV ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default construct and initialize the pass.</p>

<p>Definition at line 1496 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump\_mloc\_transfer() {#ae270bdce77ec139bf18564e50664dab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::dump_mloc_transfer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abc9d9007b0d77bc0954612b88df15142">MLocTransferMap</a> &amp; mloc_transfer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1499 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 3429 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### findLocationForMemOperand() {#a3c1165eb09769fbc90612ff41c1830b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LocIdx &gt; InstrRefBasedLDV::findLocationForMemOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1517 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1399 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a0b0401973fc9567440717a5d32a8eb8d">llvm::LocationSize::hasValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getDVMap() {#a40164b47ac9386a03fb7acf930eca83a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugVariableMap &amp; LiveDebugValues::InstrRefBasedLDV::getDVMap ()</td>
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



<p>Definition at line 1520 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### hasFoldedStackStore() {#abe3764a9e5e3a3929c0cef3d6dceaedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::InstrRefBasedLDV::hasFoldedStackStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 1504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue/#a9959ffdc41bc31cf2211b8824f79259eaf38d1857511c3f0404c95f65664b36ab">llvm::PseudoSourceValue::FixedStack</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isCalleeSaved() {#ac8e3a7e9be90841c721e738db731abbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::isCalleeSaved (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1501 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1363 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="#ad778dafd8a5d853569fe78079b6960b7">isCalleeSavedReg</a>.</p>

</div>
</div>

### isCalleeSavedReg() {#ad778dafd8a5d853569fe78079b6960b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::isCalleeSavedReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1367 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>.</p>


<p>Referenced by <a href="#ac8e3a7e9be90841c721e738db731abbf">isCalleeSaved</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### accumulateFragmentMap() {#a10f5726e576f9a2190f07ad047841f9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::accumulateFragmentMap (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accumulate a mapping between each <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> fragment and other fragments of that <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> which overlap.</p>


<p>This reduces work during the data-flow stage from "Find any overlapping fragments" to "Check if the
known-to-overlap fragments are present".</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MI</td>
<td class="doxyParamItemDescription"><p>A previously unprocessed debug instruction to analyze for fragment usage.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### BlockPHIPlacement() {#aa6111524681758e1000aaffa8df3d89e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::BlockPHIPlacement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; AllBlocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; DefBlocks, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; PHIBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the iterated-dominance-frontier for a set of defs, using the existing LLVM facilities for this.</p>


<p>Works for a single "value" or machine/variable location. <span class="doxyComputerOutput">AllBlocks</span> Set of blocks where we might consume the value. <span class="doxyComputerOutput">DefBlocks</span> Set of blocks where the value/location is defined. <span class="doxyComputerOutput">PHIBlocks</span> Output set of blocks where PHIs must be placed.</p>


<p>Declaration at line 1386 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2799 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### buildMLocValueMap() {#ab6b86c42097dd294307437291bbc8b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::buildMLocValueMap (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MInLocs, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MOutLocs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#abc9d9007b0d77bc0954612b88df15142">MLocTransferMap</a> &gt; &amp; MLocTransfer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Solve the machine value location dataflow problem.</p>


<p>Takes as input the transfer functions in <span class="doxyComputerOutput">MLocTransfer</span>. Writes the output live-in and live-out arrays to the (initialized to zero) multidimensional arrays in <span class="doxyComputerOutput">MInLocs</span> and <span class="doxyComputerOutput">MOutLocs</span>. The outer dimension is indexed by block number, the inner by <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a>.</p>


<p>Declaration at line 1356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2671 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### buildVLocValueMap() {#a59a737b5062cc6b00ced87df09c9a353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::buildVLocValueMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DILoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a>, 4 &gt; &amp; VarsWeCareAbout, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; AssignBlocks, <a href="#a4fcc5fc74d98f09bd495e93cec779cbc">LiveInsT</a> &amp; Output, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MOutLocs, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MInLocs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/vloctracker">VLocTracker</a> &gt; &amp; AllTheVLocs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Solve the variable value dataflow problem, for a single lexical scope.</p>


<p>Uses the algorithm from the file comment to resolve control flow joins using PHI placement and value propagation. Reads the locations of machine values from the <span class="doxyComputerOutput">MInLocs</span> and <span class="doxyComputerOutput">MOutLocs</span> arrays (see buildMLocValueMap) and reads the variable values transfer function from <span class="doxyComputerOutput">AllTheVlocs</span>. Live-in and Live-out variable values are stored locally, with the live-ins permanently stored to <span class="doxyComputerOutput">Output</span> once a fixedpoint is reached. <span class="doxyComputerOutput">VarsWeCareAbout</span> contains a collection of the variables in <span class="doxyComputerOutput">Scope</span> that we should be tracking. <span class="doxyComputerOutput">AssignBlocks</span> contains the set of blocks that aren't in <span class="doxyComputerOutput">DILoc's</span> scope, but which do contain DBG_VALUEs, which VarLocBasedImpl tracks locations through.</p>


<p>Declaration at line 1426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 3143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### depthFirstVLocAndEmit() {#af6304d2a737f712448762178dd1f4404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::depthFirstVLocAndEmit (unsigned MaxNumBlocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2233b318fa41cb9167e82f952f4b6df6">ScopeToDILocT</a> &amp; ScopeToDILocation, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa55b289a4e7786074f4f3372425763cd">ScopeToVarsT</a> &amp; ScopeToVars, <a href="#a68274d2602df99b0792e3474e37b3775">ScopeToAssignBlocksT</a> &amp; ScopeToBlocks, <a href="#a4fcc5fc74d98f09bd495e93cec779cbc">LiveInsT</a> &amp; Output, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MOutLocs, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MInLocs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/vloctracker">VLocTracker</a> &gt; &amp; AllTheVLocs, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> &amp; TPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When determining per-block variable values and emitting to DBG_VALUEs, this function explores by lexical scope depth.</p>


<p>Doing so means that per block information can be fully computed before exploration finishes, allowing us to emit it and free data structures earlier than otherwise. It's also good for locality.</p>


<p>Declaration at line 1481 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 3543 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### emitTransfers() {#a204464a5e130feff38120d8989e427ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::emitTransfers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Take collections of DBG_VALUE instructions stored in TTracker, and install them into their output blocks.</p>

<p>Declaration at line 1461 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 3658 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### ExtendRanges() {#a326f546ac1f97d0d5d6fe81187d095d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::ExtendRanges (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * DomTree, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> * TPC, unsigned InputBBLimit, unsigned InputDbgValLimit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the liveness information for the given machine function and extend ranges across basic blocks.</p>

<p>Declaration at line 1490 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 3691 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### extractSpillBaseRegAndOffset() {#a81f55a37e37cf727fd53d40a58687cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SpillLocationNo &gt; InstrRefBasedLDV::extractSpillBaseRegAndOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a spill instruction, extract the spill slot information, ensure it's tracked, and return the spill number.</p>

<p>Declaration at line 1278 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### findStackIndexInterference() {#a4fa53b1db8d8910ccd6f9d350a17fab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::findStackIndexInterference (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Slots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examine the stack indexes (i.e.</p>


<p>offsets within the stack) to find the basic units of interference – like reg units, but for the stack.</p>


<p>Declaration at line 1362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2515 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### getBlocksForScope() {#a4ce7b03957b1093525b17050a957f24f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::getBlocksForScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DILoc, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Output, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; AssignBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produce a set of blocks that are in the current lexical scope.</p>


<p>This means those blocks that contain instructions "in" the scope, blocks where assignments to variables in scope occur, and artificial blocks that are successors to any of the earlier blocks. See <a href="https://llvm.org/PR48091">https://llvm.org/PR48091</a> for more commentry on what "in scope" means. <span class="doxyComputerOutput">DILoc</span> A location in the scope that we're fetching blocks for. <span class="doxyComputerOutput">Output</span> Set to put in-scope-blocks into. <span class="doxyComputerOutput">AssignBlocks</span> Blocks known to contain assignments of variables in scope.</p>


<p>Declaration at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 3080 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### getValueForInstrRef() {#a6c8b21a5dac1f16592b6568015385f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ValueIDNum &gt; InstrRefBasedLDV::getValueForInstrRef (unsigned InstNo, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> * MLiveOuts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> * MLiveIns)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For an instruction reference given by <span class="doxyComputerOutput">InstNo</span> and <span class="doxyComputerOutput">OpNo</span> in instruction <span class="doxyComputerOutput">MI</span> returns the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> pointed to by that instruction reference if any exists, otherwise returns std::nullopt.</p>

<p>Declaration at line 1283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1474 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### initialSetup() {#a2393c70c72c7638d47f319a87783e830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::initialSetup (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Boilerplate computation of some initial sets, artifical blocks and RPOT block ordering.</p>

<p>Declaration at line 1465 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 3439 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### isLocationSpill() {#a706f17a46553480f1ee4ad63e6af83d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::isLocationSpill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, unsigned &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decide if @MI is a spill instruction and return true if it is.</p>


<p>We use 2 criteria to make this decision:</p>


<ul class="doxyList ">
<li>Is this instruction a store to a spill slot?</li>
<li>Is there a register operand that is both used and killed? TODO: Store optimization can fold spills into other stores (including other spills). We do not handle this yet (more than one memory operand).</li>
</ul>

<p>Declaration at line 1266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2025 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### isRestoreInstruction() {#a07570f4999d0dd6b8eda2e51a0ed12c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SpillLocationNo &gt; InstrRefBasedLDV::isRestoreInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, unsigned &amp; Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a given instruction is identified as a spill, return the spill slot and set <span class="doxyComputerOutput">Reg</span> to the spilled register.</p>

<p>Declaration at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2036 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### isSpillInstruction() {#a5b4b803e9f62d4926a8d662c3d2786b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SpillLocationNo &gt; InstrRefBasedLDV::isSpillInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tests whether this instruction is a spill to a stack slot.</p>

<p>Declaration at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2006 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### makeDepthFirstEjectionMap() {#a6ade9f757d736b13b669d71b06ef2d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::makeDepthFirstEjectionMap (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; EjectionMap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2233b318fa41cb9167e82f952f4b6df6">ScopeToDILocT</a> &amp; ScopeToDILocation, <a href="#a68274d2602df99b0792e3474e37b3775">ScopeToAssignBlocksT</a> &amp; AssignBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Produce a map of the last lexical scope that uses a block, using the scopes DFSOut number.</p>


<p>Mapping is block-number to DFSOut. <span class="doxyComputerOutput">EjectionMap</span> Pre-allocated vector in which to install the built ma. <span class="doxyComputerOutput">ScopeToDILocation</span> Mapping of <a href="/web-llvm/docs/api/classes/llvm/lexicalscopes">LexicalScopes</a> to their DILocations. <span class="doxyComputerOutput">AssignBlocks</span> Map of blocks where assignments happen for a scope.</p>


<p>Declaration at line 1472 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 3497 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### mlocJoin() {#ad07b52c00979721f3aef3e806f640fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::mlocJoin (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 16 &gt; &amp; Visited, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; OutLocs, <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a7697a3c717033a44ba7f9b272c1d5331">ValueTable</a> &amp; InLocs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a control flow join (lattice value meet) of the values in machine locations at <span class="doxyComputerOutput">MBB</span>.</p>


<p>Follows the algorithm described in the file-comment, reading live-outs of predecessors from <span class="doxyComputerOutput">OutLocs</span>, the current live ins from <span class="doxyComputerOutput">InLocs</span>, and assigning the newly computed live ins back into <span class="doxyComputerOutput">InLocs</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>two bools – the first indicates whether a change was made, the second whether a lattice downgrade occurred. If the latter is true, revisiting this block is necessary.</p></dd>
</dl>


<p>Declaration at line 1397 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2436 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### performCopy() {#aacb6b27cdf1b0325978594464835075e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::performCopy (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy one location to the other, accounting for movement of subregisters too.</p>

<p>Declaration at line 1319 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1974 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### pickOperandPHILoc() {#a8acdd8867ac44190e388a08af059250a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ValueIDNum &gt; InstrRefBasedLDV::pickOperandPHILoc (unsigned DbgOpIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abba7c6095e3e9ebb63a516620332773c">LiveIdxT</a> &amp; LiveOuts, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MOutLocs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; BlockOrders)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1454 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2893 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### pickVPHILoc() {#a5a97be3b9a83608262c594ea71ca8364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::pickVPHILoc (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a> &gt; &amp; OutValues, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abba7c6095e3e9ebb63a516620332773c">LiveIdxT</a> &amp; LiveOuts, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MOutLocs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; BlockOrders)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For the given block and live-outs feeding into it, try to find machine locations for each debug operand where all the values feeding into that operand join together.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if a joined location was found for every value that needed to be joined.</p></dd>
</dl>


<p>Declaration at line 1450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2813 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### placeMLocPHIs() {#a0e3cab548a55c94d96852f07fb16ea98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::placeMLocPHIs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; AllBlocks, <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MInLocs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#abc9d9007b0d77bc0954612b88df15142">MLocTransferMap</a> &gt; &amp; MLocTransfer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Install PHI values into the live-in array for each block, according to the IDF of each register.</p>

<p>Declaration at line 1366 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2541 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### placePHIsForSingleVarDefinition() {#a90f1c48d64696e5e60b4b34d53e07a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::placePHIsForSingleVarDefinition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; InScopeBlocks, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/vloctracker">VLocTracker</a> &gt; &amp; AllTheVLocs, <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a> Var, <a href="#a4fcc5fc74d98f09bd495e93cec779cbc">LiveInsT</a> &amp; Output)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Propagate variable values to blocks in the common case where there's only one value assigned to the variable.</p>


<p>This function has better performance as it doesn't have to find the dominance frontier between different assignments.</p>


<p>Declaration at line 1375 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 3390 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### process() {#a06d8c07b9cedf432f5d345544688d960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::process (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> * MLiveOuts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> * MLiveIns)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Observe a single instruction while stepping through a block.</p>

<p>Declaration at line 1289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### produceMLocTransferFunction() {#a5f5f0bf451a6c1870f6d8c2828e11737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::produceMLocTransferFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#abc9d9007b0d77bc0954612b88df15142">MLocTransferMap</a> &gt; &amp; MLocTransfer, unsigned MaxNumBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Step through the function, recording register definitions and movements in an <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a>.</p>


<p>Convert the observations into a per-block transfer function in <span class="doxyComputerOutput">MLocTransfer</span>, suitable for using with the machine value location dataflow problem.</p>


<p>Declaration at line 1347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### resolveDbgPHIs() {#ac6bfbe8902542495bf8b1e1867c94150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ValueIDNum &gt; InstrRefBasedLDV::resolveDbgPHIs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MLiveOuts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MLiveIns, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Here, uint64_t InstrNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the machine value number referred to by (potentially several) DBG_PHI instructions.</p>


<p>Block duplication and tail folding can duplicate DBG_PHIs, shifting the position where values in registers merge, and forming another mini-ssa problem to solve. <span class="doxyComputerOutput">Here</span> the position of a DBG_INSTR_REF seeking a machine value number <span class="doxyComputerOutput">InstrNum</span> Debug instruction number defined by DBG_PHI instructions.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The machine value number at position Here, or std::nullopt.</p></dd>
</dl>


<p>Declaration at line 1330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 4118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### resolveDbgPHIsImpl() {#a5c0d554b2cb3525ca83c4a36b50f4f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ValueIDNum &gt; InstrRefBasedLDV::resolveDbgPHIsImpl (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MLiveOuts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> &amp; MLiveIns, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Here, uint64_t InstrNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 4133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### transferDebugInstrRef() {#aa1d5c7cc1b11a8d0455b3461cb6ea121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::transferDebugInstrRef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> * MLiveOuts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/livedebugvalues/funcvaluetable">FuncValueTable</a> * MLiveIns)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examines whether <span class="doxyComputerOutput">MI</span> is a DBG_INSTR_REF and notifies trackers.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI was recognized and processed.</p></dd>
</dl>


<p>Declaration at line 1298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1621 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### transferDebugPHI() {#a6962b166d41a26c23c4ff1aeee4b0ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::transferDebugPHI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores value-information about where this PHI occurred, and what instruction number is associated with it.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI was recognized and processed.</p></dd>
</dl>


<p>Declaration at line 1304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1778 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### transferDebugValue() {#a07a04f10b667dc5b481a6edeaa1888b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::transferDebugValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examines whether <span class="doxyComputerOutput">MI</span> is a DBG_VALUE and notifies trackers.</p>


<p>End all previous ranges related to @MI and start a new range from @MI if it is a DBG_VALUE instr.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI was recognized and processed.</p></dd>
</dl>


<p>Declaration at line 1294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### transferRegisterCopy() {#a734b8343dd36a859e887d6e048a9a37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::transferRegisterCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examines whether <span class="doxyComputerOutput">MI</span> is copy instruction, and notifies trackers.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI was recognized and processed.</p></dd>
</dl>


<p>Declaration at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### transferRegisterDef() {#abf7e8f68978d333ba4eb817370952e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstrRefBasedLDV::transferRegisterDef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examines <span class="doxyComputerOutput">MI</span> for any registers that it defines, and notifies trackers.</p>

<p>Declaration at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1857 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### transferSpillOrRestoreInst() {#a9d3b0bc989755d5befa2762363922866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::transferSpillOrRestoreInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examines whether <span class="doxyComputerOutput">MI</span> is stack spill or restore instruction, and notifies trackers.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if MI was recognized and processed.</p></dd>
</dl>


<p>Declaration at line 1312 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2050 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

### vlocJoin() {#a4674e0625f729563d44ba5cab429ef8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstrRefBasedLDV::vlocJoin (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="#abba7c6095e3e9ebb63a516620332773c">LiveIdxT</a> &amp; VLOCOutLocs, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 8 &gt; &amp; BlocksToExplore, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> &amp; LiveIn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempt to eliminate un-necessary PHIs on entry to a block.</p>


<p>Examines the live-in values coming from predecessors live-outs, and replaces any PHIs already present in this blocks live-ins with a live-through value if the PHI isn't needed. <span class="doxyComputerOutput">LiveIn</span> Old live-in value, overwritten with new one if live-in changes.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any live-ins change value, either from value propagation or PHI elimination.</p></dd>
</dl>


<p>Declaration at line 1440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 2966 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AdjustsStackInCalls {#a868405ab5f3dd0880f364a1e8abac5e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::InstrRefBasedLDV::AdjustsStackInCalls = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if we need to examine call instructions for stack clobbers.</p>


<p>We normally assume that they don't clobber SP, but stack probes on Windows do.</p>


<p>Definition at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### ArtificialBlocks {#aeac62138fdd885d11b3eb5bf8bba63c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineBasicBlock *, 16&gt; LiveDebugValues::InstrRefBasedLDV::ArtificialBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Blocks which are artificial, i.e.</p>


<p>blocks which exclusively contain instructions without DebugLocs, or with line 0 locations.</p>


<p>Definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### BBNumToRPO {#a71629590cc6d688bdfa05f76613fcc5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, unsigned&gt; LiveDebugValues::InstrRefBasedLDV::BBNumToRPO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### BBToOrder {#a44c580a6d08875e2765aa3d5e47a6c1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineBasicBlock *, unsigned int&gt; LiveDebugValues::InstrRefBasedLDV::BBToOrder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### CalleeSavedRegs {#aa9cd59bfbdd3378a02426ebfd8411a86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector LiveDebugValues::InstrRefBasedLDV::CalleeSavedRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### CurBB {#a2dffa1e1ffeb5a451136b837a07ef23f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::InstrRefBasedLDV::CurBB = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of the current block <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a> is stepping through.</p>

<p>Definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### CurInst {#aecb320903dbb7f9bb43982ac351c5c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::InstrRefBasedLDV::CurInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of the current instruction <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a> is evaluating.</p>

<p>Definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### DbgOpStore {#a21e6911b3ba5b15b5a136a7d49580a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgOpIDMap LiveDebugValues::InstrRefBasedLDV::DbgOpStore</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1239 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### DebugInstrNumToInstr {#a0db40a2a1b51a222eb02ba0ff7f05f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;uint64_t, InstAndNum&gt; LiveDebugValues::InstrRefBasedLDV::DebugInstrNumToInstr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from debug instruction number to the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> labelled with that number, and its location within the function.</p>


<p>Used to transform instruction numbers in DBG_INSTR_REFs into machine value numbers.</p>


<p>Definition at line 1203 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### DebugPHINumToValue {#a2704806d9344f84133d9dd4a8fc4b6f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DebugPHIRecord, 32&gt; LiveDebugValues::InstrRefBasedLDV::DebugPHINumToValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from instruction numbers defined by DBG_PHIs to a record of what that DBG_PHI read and where.</p>


<p>Populated and edited during the machine value location problem – we use LLVMs SSA Updater to fix changes by optimizations that destroy PHI instructions.</p>


<p>Definition at line 1226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### DomTree {#a0cd6fca22445bf3062b6a35fba5137d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* LiveDebugValues::InstrRefBasedLDV::DomTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### DVMap {#a02017d9f0608b38aba5e98e209328b16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugVariableMap LiveDebugValues::InstrRefBasedLDV::DVMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping between DebugVariables and unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> numbers.</p>


<p>This is a more efficient way to represent the identity of a variable, versus a plain <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a>.</p>


<p>Definition at line 1244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### EmptyExpr {#abc888a5d7bdc06ad0f9734dddc9cb463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DIExpression* LiveDebugValues::InstrRefBasedLDV::EmptyExpr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### LS {#a40865c48645bd3916eaf08a5c0d4960d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexicalScopes LiveDebugValues::InstrRefBasedLDV::LS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### MFI {#aa351a7c3e07b4006d0f43afe08f6d812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFrameInfo* LiveDebugValues::InstrRefBasedLDV::MFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### MRI {#a487646e28e68aed1416ec95d3fe3e4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo* LiveDebugValues::InstrRefBasedLDV::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### MTracker {#a78400f292849e9960cef9172f1fc1fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MLocTracker* LiveDebugValues::InstrRefBasedLDV::MTracker = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Object to track machine locations as we step through a block.</p>


<p>Could probably be a field rather than a pointer, as it's always used.</p>


<p>Definition at line 1171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### OrderToBB {#a6a09b6200c1332310da5d23445fef6ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *&gt; LiveDebugValues::InstrRefBasedLDV::OrderToBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### OverlapFragments {#a4a1ccefe1bfa1c318776ec1c00ac2528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverlapMap LiveDebugValues::InstrRefBasedLDV::OverlapFragments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### SeenDbgPHIs {#a8c0888177522a9aec5b22527f0a9b981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;MachineInstr *, unsigned&gt;, std::optional&lt;ValueIDNum&gt; &gt; LiveDebugValues::InstrRefBasedLDV::SeenDbgPHIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping of DBG_INSTR_REF instructions to their values, for those DBG_INSTR_REFs that call resolveDbgPHIs.</p>


<p>These variable references solve a mini SSA problem caused by DBG_PHIs being cloned, this collection caches the result.</p>


<p>Definition at line 1237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### SeenFragments {#a3c55db6d427ce7a739fbf81108f03fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VarToFragments LiveDebugValues::InstrRefBasedLDV::SeenFragments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### StackProbeSymbolName {#a093bc749657288862cfe97564bf7a6e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef LiveDebugValues::InstrRefBasedLDV::StackProbeSymbolName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If AdjustsStackInCalls is true, this holds the name of the target's stack probe function, which is the function we expect will alter the stack pointer.</p>

<p>Definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### TFI {#a07d89949403222c9a50d48803c004bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetFrameLowering* LiveDebugValues::InstrRefBasedLDV::TFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### TII {#a5a10bf9bccc71697dea7be468c2f5746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* LiveDebugValues::InstrRefBasedLDV::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### TPC {#a45db428547286759eab78d45192001f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetPassConfig* LiveDebugValues::InstrRefBasedLDV::TPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### TRI {#a1aab1ae1f3779d4d46a12fcefe0903bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* LiveDebugValues::InstrRefBasedLDV::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### TTracker {#a61028875188a8b16510dac222a472b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TransferTracker* LiveDebugValues::InstrRefBasedLDV::TTracker = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tracker for transfers, listens to DBG_VALUEs and transfers of values between locations during stepping, creates new DBG_VALUEs when values move location.</p>

<p>Definition at line 1187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### VTracker {#a3969ac5b6d12166ef9e6ac00ab4ae7c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VLocTracker* LiveDebugValues::InstrRefBasedLDV::VTracker = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Variable tracker – listens to DBG_VALUEs occurring as InstrRefBasedImpl steps through a block.</p>


<p>Reads the values at each location from the <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> object.</p>


<p>Definition at line 1182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
